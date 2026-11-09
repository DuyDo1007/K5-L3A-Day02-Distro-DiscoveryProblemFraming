# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

* Tên nhóm: Distro
* Candidate problem nhóm chọn: Theo dõi tiến độ và phần còn thiếu của thành viên trước milestone
* Quyết định cuối (Go / Not Yet / No-Go): Not Yet

## Thành viên

| STT | Họ và tên         | MSSV        | Vai trò trong nhóm                                                                                                | Tài khoản GitHub |
| --: | ----------------- | ----------- | ----------------------------------------------------------------------------------------------------------------- | ---------------- |
|   1 | Đỗ Đắc Duy        | 2A202603604 | Trưởng nhóm - ghi chép,viết Problem Statement                                                                     | DuyDo1007        |
|   2 | Đào Kiên Cường    | 2A202603396 | Kiểm chứng và research giải pháp đã có của candidate được chọn                                                    | daokiencuong     |
|   3 | Nguyễn Thùy Dương | 2A202603388 | Đánh giá rủi ro, đề xuất Go/Not Yet/No-Go; xác định điều kiện thử nghiệm, ngưỡng dừng, hạn chế và hướng tiếp theo | NTD\_DUONG       |
|   4 | Đình Văn Kiều     | 2A202603376 | Xác định quy trình trước/sau, đưa ra problem statement V0                                                         | vankd2307        |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint                                 | Người chính | Người hỗ trợ | Sản phẩm                                       |
| ------------------------------------------ | ----------- | ------------ | ---------------------------------------------- |
| CP3 — Hội tụ nhóm                          | Duy         |              | Cluster, cây OST, bảng chấm điểm               |
| CP4 — Kiểm chứng                           | Cường       |              | Assumption map, snapshot hoặc survey           |
| CP4 — Research                             | Cường       |              | Bảng research có link                          |
| CP5 — Quy trình trước/sau                  | Kiểu        |              | Quy trình + bảng before/after                  |
| CP5 — Problem Statement v0                 | Kiểu        |              | Problem Statement v0                           |
| CP6 — Mức can thiệp + Problem Statement v1 | Duy         | Dương        | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định                           | Duong       |              | 4 rủi ro + Go/Not Yet/No-Go                    |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### Đình Văn Kiều-2A202603376

**Phần việc phụ trách:**

* Xác định quy trình trước/sau, đưa ra problem statement V0

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

*

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

*

**Điều mình học được từ phần nhóm:**

*

### Đào Kiên Cường-2A202603396

**Phần việc phụ trách:**

* Kiểm chứng và research các giải pháp đã tồn tại của candidate được chọn

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

* Phân rã problem candidate và liệt kê assumptions
* Phỏng vấn để kiểm chứng lại các asssumptions, ghi lại các interview-snapshot
* Research các giải pháp đã có liên quan tới problem candidate

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

* Mục 3 trong group\_report.md
* File cp4-interview-snapshot-1.md, cp4-interview-snapshot-2.md, cp4-interview-snapshot-3.md
* Commit 6e12569

**Điều mình học được từ phần nhóm:**

* Cách để hình dung được giải pháp có thể giải quyết được vấn đề như thế nào
* Làm sao để tiếp cận và trao đổi được với những đối tượng liên quan tới giải pháp và vấn đề
* Cách research các công cụ có sẵn liên quan tới giải pháp mà mình định đưa ra, liệu có trùng hay không hay có thể cải thiện được hơn nữa không

### Nguyễn Thùy Dương - 2A202603388

**Phần việc phụ trách:**

* Đánh giá rủi ro và đề xuất quyết định; xác định hạn chế, hướng tiếp theo và tổng hợp tài liệu tham khảo.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

* Phân tích bốn rủi ro: Value, Usability, Feasibility và Viability cho bài toán hỗ trợ trưởng nhóm tổng hợp tiến độ trước milestone.
* Đề xuất Not Yet vì chưa đủ bằng chứng về chất lượng dữ liệu, độ chính xác và lợi ích tiết kiệm thời gian.
* Xác định các điều kiện cần kiểm chứng trước khi thử nghiệm; đề xuất pilot trong một nhóm, hai tuần và tối thiểu bốn lần check-in.
* Xây dựng ngưỡng dừng khi AI báo sai trạng thái, bỏ sót blocker, không tiết kiệm thời gian hoặc dữ liệu đầu vào không đầy đủ.
* Tổng hợp hạn chế, đề xuất các bước tiếp theo và ghi nguồn phương pháp tham khảo.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

* Mục 8.1: Bảng đánh giá bốn rủi ro.
* Mục 8.2: Quyết định Not Yet, điều kiện kiểm chứng, pilot và ngưỡng dừng.
* Mục 9: Hạn chế và hướng tiếp theo.
* Mục 10: Tài liệu tham khảo.

**Điều mình học được từ phần nhóm:**

* Một giải pháp AI có thể xây được chưa chắc đã mang lại giá trị; cần so sánh với cách làm đơn giản như bảng tiến độ chung.
* AI chỉ tổng hợp được dữ liệu đã cung cấp, không thể tự biết tiến độ thực tế khi thành viên cập nhật thiếu hoặc mâu thuẫn.
* Khi đánh giá hiệu quả, phải tính cả thời gian chuẩn bị dữ liệu, kiểm tra và sửa đầu ra.
* Quyết định Not Yet cần đi kèm điều kiện kiểm chứng và ngưỡng dừng rõ ràng; trưởng nhóm vẫn chịu trách nhiệm xác nhận và quyết định điều phối.

### Đỗ Đắc Duy-2A202603604

**Phần việc phụ trách:**

* Điều phối nhóm, ghi chép và xây dựng Problem Statement.
* Phụ trách CP3 — Hội tụ nhóm và CP6 — Mức can thiệp, Problem Statement v1.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

* Tổng hợp các ý tưởng của nhóm thành cluster, cây OST và bảng chấm điểm để thống nhất candidate problem.
* Ghi chép và điều phối các nội dung thảo luận của nhóm.
* Phối hợp với Dương xây dựng ma trận mức can thiệp, AI Canvas, phần đánh giá và Problem Statement v1.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

* Sản phẩm CP3: cluster, cây OST và bảng chấm điểm.
* Sản phẩm CP6: ma trận mức can thiệp, AI Canvas, phần eval và Problem Statement v1 trong `group_report.md`.

**Điều mình học được từ phần nhóm:**

* Cần hội tụ từ nhiều ý tưởng về một vấn đề cụ thể trước khi bàn sâu về giải pháp.
* Problem Statement cần dựa trên bằng chứng và được điều chỉnh khi nhóm hiểu rõ hơn về người dùng, quy trình và các giả định.
* Khi cân nhắc dùng AI, cần xác định rõ mức can thiệp phù hợp và so sánh với cách làm đơn giản hơn.
* Điều phối và ghi chép giúp nhóm thống nhất quyết định, nhưng cần ghi rõ bằng chứng và việc cần kiểm chứng tiếp theo.

