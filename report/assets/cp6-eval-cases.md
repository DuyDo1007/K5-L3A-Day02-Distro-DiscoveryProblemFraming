# CP6 — Bộ eval mẫu cho bản nháp tiến độ

## Phạm vi và cách chấm

Đây là **10 tình huống tổng hợp để kiểm thử**, không phải dữ liệu phỏng vấn, dữ liệu thành viên thật hay kết quả pilot. Mỗi input có một đầu ra tham chiếu. Điểm hiện tại chấm trên đầu ra tham chiếu để xác nhận bộ tiêu chí áp dụng được; **chưa chạy mô hình AI**, nên không được hiểu là độ chính xác thực nghiệm.

Mỗi tiêu chí chấm 1 nếu đạt, 0 nếu không đạt:

1. **Đúng trạng thái:** chỉ nhắc đúng trạng thái có trong input; không tự gán hoàn thành/chậm.
2. **Không bỏ sót blocker:** giữ nguyên blocker được nêu; ghi “không nêu” nếu input không có blocker.
3. **Phần còn thiếu có căn cứ:** nêu phần còn thiếu/người phụ trách chỉ khi input có, kèm đúng nguồn; thiếu dữ liệu thì nói chưa đủ dữ liệu.
4. **Dễ đọc trong 2 phút:** ngắn, tách rõ trạng thái, blocker, phần còn lại và nguồn.

| # | Input tổng hợp | Đầu ra tham chiếu mong đợi | Điểm (1/2/3/4) |
|---:|---|---|---|
| 1 | Task: Viết phần phương pháp; người phụ trách: An; trạng thái tự báo: đang làm; blocker: chưa có; còn lại: bổ sung mô tả bộ dữ liệu; link: `drive/mock-01` | **An — Viết phần phương pháp:** đang làm theo tự báo; còn bổ sung mô tả bộ dữ liệu; chưa nêu blocker. [Nguồn: `drive/mock-01`] | 1 / 1 / 1 / 1 |
| 2 | Task: API đăng nhập; người phụ trách: Bình; trạng thái tự báo: đang làm; blocker: lỗi xác thực token; còn lại: xử lý lỗi và kiểm tra lại; link: `repo/mock-02` | **Bình — API đăng nhập:** đang làm theo tự báo. Blocker: lỗi xác thực token. Còn lại: xử lý lỗi và kiểm tra lại. [Nguồn: `repo/mock-02`] | 1 / 1 / 1 / 1 |
| 3 | Task: Slide kết quả; người phụ trách: Chi; trạng thái tự báo: gần xong; blocker: chưa nêu; còn lại: chưa nêu; link: `drive/mock-03` | **Chi — Slide kết quả:** tự báo “gần xong”; chưa đủ dữ liệu để xác định phần còn lại hoặc xác nhận hoàn thành. Blocker chưa được nêu. [Nguồn: `drive/mock-03`] | 1 / 1 / 1 / 1 |
| 4 | Task: Tích hợp giao diện; người phụ trách: Dũng; trạng thái: thiếu; blocker: thiếu; còn lại: thiếu; link: không có | **Dũng — Tích hợp giao diện:** chưa đủ dữ liệu để xác định trạng thái, blocker hoặc phần còn lại; chưa có link nguồn. Cần hỏi người phụ trách bổ sung. | 1 / 1 / 1 / 1 |
| 5 | Task: Báo cáo khảo sát; người phụ trách: Hà; trạng thái tự báo: hoàn thành; blocker: không có; còn lại: không có; link: `drive/mock-05` | **Hà — Báo cáo khảo sát:** trạng thái “hoàn thành” theo tự báo; input không nêu blocker hay phần còn lại. Cần người phụ trách kiểm tra sản phẩm qua nguồn trước khi xác nhận. [Nguồn: `drive/mock-05`] | 1 / 1 / 1 / 1 |
| 6 | Task: Kiểm thử thanh toán; người phụ trách: Khoa; trạng thái tự báo: đang làm; blocker: môi trường test lỗi; còn lại: chạy lại test sau khi môi trường ổn định; link: `jira/mock-06`; ghi chú khác: task board ghi “done” | **Khoa — Kiểm thử thanh toán:** có thông tin mâu thuẫn: tự báo “đang làm”, task board ghi “done”. Blocker: môi trường test lỗi. Còn lại: chạy lại test khi môi trường ổn định. Chưa thể xác nhận trạng thái; cần người phụ trách đối chiếu. [Nguồn: `jira/mock-06`] | 1 / 1 / 1 / 1 |
| 7 | Task: Chương 2; người phụ trách: Lan; trạng thái tự báo: đang làm; blocker: chưa có; còn lại: “còn một ít”; link: `docs/mock-07` | **Lan — Chương 2:** đang làm theo tự báo; phần còn lại được mô tả là “còn một ít” nhưng chưa cụ thể; blocker chưa nêu. Cần hỏi rõ phần nào còn thiếu. [Nguồn: `docs/mock-07`] | 1 / 1 / 1 / 1 |
| 8 | Task: Sửa lỗi giao diện; người phụ trách: Minh; trạng thái tự báo: chưa bắt đầu; blocker: chờ xác nhận thiết kế; còn lại: chưa thể bắt đầu sửa trước khi có xác nhận; link: `figma/mock-08` | **Minh — Sửa lỗi giao diện:** chưa bắt đầu theo tự báo. Blocker: chờ xác nhận thiết kế. Chưa thể bắt đầu sửa trước khi có xác nhận. [Nguồn: `figma/mock-08`] | 1 / 1 / 1 / 1 |
| 9 | Task: Tổng hợp tài liệu; người phụ trách: Ngọc; trạng thái tự báo: đang làm; blocker: thiếu link hai nguồn; còn lại: bổ sung hai link và rà trích dẫn; link: `doc/mock-09`; cập nhật lúc: 08/11 | **Ngọc — Tổng hợp tài liệu:** đang làm theo cập nhật 08/11. Blocker: thiếu link hai nguồn. Còn lại: bổ sung hai link và rà trích dẫn. [Nguồn: `doc/mock-09`] | 1 / 1 / 1 / 1 |
| 10 | Task: Chuẩn bị demo; người phụ trách: Phúc; trạng thái tự báo: 80%; blocker: “máy em hơi lag”; còn lại: không nêu; link: `drive/mock-10` | **Phúc — Chuẩn bị demo:** tự báo 80%; con số này không đủ để xác nhận mức hoàn thành. Blocker được mô tả là “máy em hơi lag”; phần còn lại chưa nêu. Cần làm rõ ảnh hưởng của blocker và phần việc còn thiếu. [Nguồn: `drive/mock-10`] | 1 / 1 / 1 / 1 |

**Tổng điểm đầu ra tham chiếu:** 40/40. Đây là điểm của đáp án mẫu theo rubric, không phải điểm của đầu ra AI. Khi chạy pilot, lưu riêng output thực tế và chấm lại từng tiêu chí; mọi lỗi nghiêm trọng phải theo ngưỡng dừng ở mục 8 của báo cáo nhóm.
