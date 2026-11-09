# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Kiều Đình Văn | Khi bắt đầu lab và nhận repo có nhiều file hướng dẫn, tôi muốn nắm nhanh việc cần nộp, cách đặt tên và tiêu chí bị trừ điểm để bắt tay làm đúng. | Học viên K5; coach chấm bài bị ảnh hưởng khi nộp sai | Đối chiếu RUBRIC với CHECKPOINTS để ghép checkpoint – sản phẩm cần nộp – điều kiện bị trừ điểm; khoảng 8 phút trong quy trình tổng 15–30 phút. | Liệu checklist mẫu dùng lại có được không không, hay các lab khác nhau đáng kể trong docs? (Đỗ Đắc Duy) |
| 2 | Kiều Đình Văn | Khi nhóm cần hẹn giờ làm phần chung, tôi muốn chốt được khung giờ mọi người đều rảnh để bắt đầu sớm trước deadline. | Thành viên nhóm Distro (3–4 người), thường là người điều phối hỏi lịch | Chờ phản hồi từng người khoảng 3 giờ; câu hỏi mở khiến câu trả lời khó so sánh, có thể kéo dài thêm khoảng 1 giờ để chốt. | Tình trạng này xảy ra gần nhất khi nào,có liên tục mỗi lần không,mỗi lần đầu tầm 3-4 giờ trong khi nhóm 3 - 4 thành viên không? (Đỗ Đắc Duy)|
| 3 | Kiều Đình Văn | Khi deadline được thông báo rải rác ở nhiều nơi, tôi muốn thấy các deadline sắp tới ở một chỗ để không bị lỡ hạn. | Học viên | Dò lại LMS, email và group chat; khoảng 10 phút/lần, thông tin trong chat dễ bị trôi. | Vấn đề là,deadlines ở nhiều nền tảng khác nhau,hay do bạn chưa có công cụ để lưu các deadlines khi nhận?(Đỗ Đắc Duy) |
| 4 | Đỗ Đắc Duy | Khi bắt đầu ngày làm việc, tôi muốn tổng hợp thông báo, yêu cầu và deadline quan trọng từ email, Discord và lịch để không bỏ sót việc cần làm. | Dev, PM | Chuyển qua lại giữa nhiều nguồn, tìm lại nội dung liên quan rồi tự tổng hợp; baseline sơ bộ khoảng 45 phút/ngày, còn cần xác nhận trùng lặp. | Trong thực tế, tin nhắn công việc hay bị viết tắt hoặc trao đổi phân tán trong nhiều box chat. Nếu AI tóm tắt hoặc quét sót một thông báo khẩn cấp từ PM/khách hàng làm mình sót việc, thì ai sẽ chịu trách nhiệm cho sai sót này? (Đào Kiên Cường)|
| 5 | Đỗ Đắc Duy | Khi bắt đầu một task, tôi muốn xác định nhanh quy trình, quy định và tài liệu liên quan để không phải đọc nhiều tài liệu không cần thiết hoặc bỏ sót yêu cầu. | Dev, PM và thành viên trong team | Tìm đúng tài liệu liên quan trong các thư mục/công cụ rồi đọc, lọc và đối chiếu; ước tính khoảng 45 phút mỗi lần bắt đầu task (cần xác minh). | Nút thắt ở đây là do dev 'không thể tìm thấy tài liệu', hay thực chất là do người giao task (PM/Tech Lead) viết docs quá sơ sài (Đào Kiên Cường)|
| 6 | Đỗ Đắc Duy | Khi bắt đầu project dùng AI Coding Agent, tôi muốn xác định skills, rules và coding convention phù hợp để giảm thời gian setup và hạn chế code không đúng quy ước. | Dev, Tech Lead, Reviewer | Tìm hiểu convention, kiểm tra rules/skills, chọn hoặc viết cấu hình và chạy thử; setup ước tính hơn 30 phút/project. | Setup rules cho project chỉ làm 1 lần lúc khởi tạo dự án (tần suất rất thấp). Tại sao nhóm không dùng một file template rules mẫu dùng chung mà lại cần build 1 solution riêng cho problem này(Đào Kiên Cường)|
| 7 | Nguyễn Thùy Dương | Khi nhận hợp đồng thuê trọ trước khi ký, tôi muốn hiểu rõ nghĩa vụ về tiền cọc, chi phí và chấm dứt thuê để biết điều gì cần hỏi lại hoặc đề nghị sửa. | Sinh viên mới tốt nghiệp đang tìm phòng trọ | Đọc và hiểu các điều khoản cần hỏi lại; thời gian bottleneck chưa được đo riêng (thời gian đọc ban đầu 20–30 phút theo mô tả, cần xác nhận). | Một năm bạn ký mấy hợp đồng thuê trọ? Nếu chỉ 1–2 lần thì giảm 30% thời gian đọc hợp đồng là tiết kiệm được bao nhiêu phút mỗi năm? Hay pain thật là số tiền cọc bị mất, và nếu vậy thì bạn đã mất bao nhiêu, vì điều khoản nào? (Kiều Đình Văn)|
| 8 | Nguyễn Thùy Dương | Khi tự học qua video bài giảng dài sau giờ làm, tôi muốn lưu ý chính và tìm lại đúng đoạn hướng dẫn để thực hành mà không phải ghi chép thủ công quá lâu. | Người tự học kỹ năng online, đặc biệt sinh viên mới tốt nghiệp | Dừng video để gõ và tổ chức ghi chú; tổng thời gian nêu khoảng 70–90 phút cho video 30 phút nhưng chưa xác nhận, thời gian riêng của bottleneck chưa đo. | Bạn đã thử tính năng transcript có sẵn của YouTube hoặc công cụ tóm tắt video nào chưa? Nếu thử rồi thì chúng còn thiếu bước nào khiến bạn vẫn mất 60–90 phút? Còn bảng scan ghi là ghi chú xong ‘khó tra cứu lại’, vậy pain thật nằm ở lúc ghi chép hay ở lúc tìm lại đoạn cần xem? (Kiều Đình Văn)|
| 9 | Nguyễn Thùy Dương | Khi tổng hợp chi phí chung cuối tháng, tôi muốn xác định đúng phần tiền mỗi người theo thỏa thuận để thanh toán minh bạch và đúng hạn. | Sinh viên ở ghép, đặc biệt người phụ trách tổng hợp chi phí | Nhập/kiểm tra hóa đơn và tính phần tiền từng người theo quy tắc chia; baseline toàn quy trình 45–60 phút/tháng chưa xác nhận, riêng thời gian tính chưa đo. | Bạn đã tự kết luận dùng Rule, Google Sheets là đủ. Vậy cuối tháng 30–45 phút đó mất vào bước nào: tính toán, hay đi nhắc từng người đóng tiền? Nếu là tính toán thì sao phòng bạn chưa dùng Splitwise hay một bảng công thức cố định?(Kiều Đình Văn) |
| 10 | Đào Kiên Cường | Khi chuẩn bị ứng tuyển vị trí intern/fresher, tôi muốn biết độ tương thích giữa hồ sơ và JD, đồng thời xác định phần cần chỉnh để chuẩn bị CV nhanh hơn. | Sinh viên năm cuối ứng tuyển intern/fresher | Viết lại bullet dự án và summary cho khớp từ khóa, khoảng 20–25 phút/lần; tổng quy trình khoảng 45 phút/vị trí. |  Điểm “% phù hợp với JD” dựa trên tiêu chí nào? CV có nhiều từ khóa hơn liệu có thực sự giúp ứng viên được gọi phỏng vấn?(Nguyễn Thùy Dương) |
| 11 | Đào Kiên Cường | Khi chuẩn bị hồ sơ xét tốt nghiệp, tôi muốn xác định quy chế áp dụng đúng khóa và đối chiếu điều kiện với bảng điểm để biết mình còn thiếu gì. | Sinh viên năm cuối chuẩn bị xét công nhận tốt nghiệp | Đọc lọc quy chế đúng khóa và đối chiếu thủ công từng môn/nhóm tự chọn; ước tính toàn quy trình khoảng 150 phút/đợt. | Nút thắt là khó hiểu quy chế hay chưa xác định được quy chế nào áp dụng cho khóa mình? Nếu chọn sai văn bản ngay từ đầu thì AI đối chiếu có còn đáng tin không?(Nguyễn Thùy Dương)|
| 12 | Đào Kiên Cường | Khi gần đến hạn milestone/báo cáo đồ án, tôi muốn nắm tiến độ thực tế và phần còn thiếu của từng thành viên để điều phối kịp thời. | Trưởng nhóm đồ án môn học hoặc đồ án tốt nghiệp | Chờ phản hồi thành viên (ước tính 45 phút) và mở từng bản nháp để kiểm tra nội dung (khoảng 30 phút) mỗi đợt deadline. |  Pain chính là thành viên không báo cáo hay thực sự chưa hoàn thành việc? Nếu họ không đưa bản nháp lên thư mục chung thì quét file có giải quyết được tình trạng thiếu thông tin không?(Nguyễn Thùy Dương)|

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — Tìm và hiểu hướng dẫn / kiến thức |#1 Nắm yêu cầu, cách nộp và tiêu chí chấm trong repo; #5 Tìm quy trình, quy định và tài liệu liên quan đến task; #6 Xác định skills, rules và coding convention cho AI Coding Agent; #8 Ghi chú và tìm lại đoạn hướng dẫn trong video bài giảng |Thông tin hướng dẫn nằm trong nhiều tài liệu hoặc định dạng; người dùng cần tìm đúng phần liên quan để bắt đầu hoặc thực hiện công việc.|
| B — Điều phối công việc và deadline | #2 Chốt giờ làm chung; #3 Tổng hợp deadline rải rác; #4 Gom thông báo, yêu cầu và deadline từ nhiều kênh; #12 Theo dõi tiến độ milestone và phần còn thiếu của từng thành viên|Thông tin về thời gian, trạng thái và việc cần làm phân tán; người dùng cần nắm tình hình để phối hợp và tránh trễ hạn. |
| C — Đối chiếu thông tin |#7 Hiểu nghĩa vụ trong hợp đồng thuê trọ; #9 Xác định phần chi phí mỗi người; #10 Đối chiếu hồ sơ với JD; #11 Đối chiếu bảng điểm với quy chế tốt nghiệp |Người dùng cần hiểu các điều kiện hoặc thỏa thuận rồi đối chiếu với hoàn cảnh của mình để xác định nghĩa vụ, mức độ phù hợp hoặc kết quả cần đạt. |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: 
├── Opportunity A: 
├── Opportunity B: 
└── Opportunity C: 
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
