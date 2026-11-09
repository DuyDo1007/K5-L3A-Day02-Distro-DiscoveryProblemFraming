# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:Distro
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
OUTCOME: Giảm thời gian và công sức đièu phối công việc của nhóm,đồng thời hạn chế bỏ sót deadline và việc quan trọng.
├── Opportunity A: Khó tìm được khung giờ làm việc chung
├── Opportunity B: Khó nắm bắt và tổng hợp thông tin từ nhiều nguồn
└── Opportunity C: Dễ bỏ sót các yêu cầu từ nhiều kênh
└── Opportunity D: Khó nhận biết tiến độ thực tế từ nhiều kênh.
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

× AI tổng hợp thông báo
× AI lập lịch họp

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #12 Theo dõi tiến độ và phần còn thiếu của thành viên trước milestone | 5 | 4 | 3 | 4 | 4 | 4 | 4 | **28** |
| #3 Gom deadline được thông báo rải rác về một chỗ | 4 | 4 | 3 | 3 | 5 | 5 | 4 | **28** |
| #4 Tổng hợp thông báo, yêu cầu và deadline từ nhiều kênh mỗi ngày | 4 | 4 | 3 | 4 | 3 | 4 | 3 | **25** |

**Candidate được chọn (đề xuất theo hướng OST hiện có):**  
Khi gần đến hạn milestone/báo cáo đồ án, trưởng nhóm muốn nắm được tiến độ thực tế và phần còn thiếu của từng thành viên để điều phối việc hoàn thành đúng hạn.

**Vì sao chọn:**  
Candidate #12 khớp trực tiếp với outcome về điều phối công việc nhóm và opportunity “khó nhận biết tiến độ thực tế”. Actor, thời điểm và bottleneck đã được mô tả tương đối rõ; báo cáo cá nhân có ước tính khoảng 110 phút/đợt deadline cho việc hỏi, chờ phản hồi và kiểm tra bản nháp. Quy trình cũng có thể so sánh với các cách đơn giản hơn như quy ước cập nhật tiến độ, checklist hoặc bảng theo dõi.

**Vì sao loại các candidate còn lại:**  
- **#3 — Gom deadline:** có phương án Rule đơn giản (một lịch chung và nhắc hạn), nên phù hợp làm phương án đối chứng; tần suất pain được ghi nhận còn thấp và chưa đủ căn cứ để ưu tiên hơn bài toán tiến độ nhóm.  
- **#4 — Tổng hợp thông tin nhiều kênh:** pain có phạm vi rộng nhưng gộp nhiều loại thông tin và nguồn dữ liệu; baseline khoảng 45 phút/ngày còn sơ bộ, có nguy cơ trùng thời gian giữa các hoạt động. Cần thu hẹp phạm vi trước khi chọn.  
- Các candidate khác có bối cảnh hoặc actor riêng, nhưng ít khớp hơn với outcome điều phối công việc nhóm đã ghi trong OST; một số có phương án No AI/Rule rõ hoặc số liệu chưa được xác nhận.

**Xử lý bất đồng (nếu có):**  

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

Bài của nhóm nằm ở ô:độ mơ hồ trung bình–cao và độ phức tạp trung bình.

Vì sao:Candidate #12 là: “Khi gần đến hạn milestone/báo cáo đồ án, trưởng nhóm muốn nắm được tiến độ thực tế và phần còn thiếu của từng thành viên để điều phối việc hoàn thiện kịp thời”.
Khía cạnh “tiến độ thực tế” không có một định nghĩa duy nhất: mỗi thành viên có cách cập nhật, mức độ phản hồi, và mức độ “đã hoàn thành” khác nhau; do đó, AI cần phải suy luận từ nhiều nguồn chứ không chỉ đọc một bảng duy nhất.
Tuy nhiên, quy trình vẫn có cấu trúc rõ: task, deadline, trạng thái, blocker, phần còn thiếu. Điều này đủ để xây một workflow có input cố định, thay vì để AI tự hành động như một agent.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Một template cập nhật tiến độ theo nhóm: mỗi người điền status, blocker, task còn lại và deadline; trưởng nhóm tổng hợp bằng hội nghị/check-in định kỳ.|Khi toàn bộ nhóm đã đồng nhất cách cập nhật và không cần suy luận từ nhiều nguồn. |Vẫn mất thời gian tổng hợp thủ công; dễ bỏ sót phần “thực tế” không được ghi rõ. | Không chọn|
| **Rule** |Tạo form chuẩn hoặc công thức tính trạng thái từ dữ liệu có sẵn: task đã xong / đang làm / chậm / chưa bắt đầu; hiển thị phần thiếu sót theo từng thành viên. |Khi tiến độ đã được ghi rõ và chuẩn hóa, không cần AI giải thích ngữ nghĩa. | Không đánh giá được tình huống mơ hồ như “đang làm nhưng chưa chắc hoàn thành”; thiếu khả năng phân tích blocker.|Không chọn |
| **Workflow** | Thu thập cập nhật từ task board / chat / file / check-in → AI tóm tắt tiến độ, task còn thiếu, rủi ro và gợi ý điều phối → trưởng nhóm review và quyết định hành động.| Khi cần tổng hợp nhiều nguồn, nhưng vẫn giữ người ra quyết định cuối cùng.|AI có thể diễn giải sai trạng thái, bỏ sót blocker hoặc gán “hoàn thành” nhầm. | Chọn|
| **Agent** | AI tự quét toàn bộ kênh thông tin, tự đánh giá tiến độ, nhắn nhủ thành viên và đề xuất phân công lại.| Khi hệ thống cần tự thực hiện nhiều bước và chịu trách nhiệm quyết định liên tục.| Quá rộng, dễ sai, khó kiểm soát, tiềm ẩn rủi ro về quyền truy cập và sự tin cậy.| Không chọn|

**Mức chọn:** Workflow

**Vì sao không chọn mức đơn giản hơn:**
Candidate #12 không chỉ là “ghi lại tiến độ”, mà là “nắm được tiến độ thực tế và phần còn thiếu” khi thông tin nằm rải rác trong nhiều nguồn: tasks, chat, file, review, milestone.
Nếu chỉ dùng No AI hoặc Rule, nhóm vẫn phải dành thời gian đọc lại nhiều kênh và quyết định xem “đã thực sự tiến bộ hay chưa”. Đây là nơi AI có giá trị rõ nhất: tóm tắt, so sánh, và phát hiện thiếu sót.
Tuy nhiên, vì khía cạnh “tiến độ thực tế” có tính chủ quan và dễ sai lệch, AI không nên tự ra quyết định cuối cùng. Vậy Workflow là mức phù hợp để giữ con người ở vị trí kiểm soát và điều phối.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Một bản tóm tắt tiến độ theo từng thành viên: task đã hoàn thành, đang làm, chậm, blocker, phần còn thiếu, nguy cơ trễ trước milestone. |
| **Judgment** — con người cân nhắc, quyết định gì? | Trưởng nhóm quyết định ai đang chậm, blocker nào thật sự quan trọng, liệu cần phân công lại hoặc điều chỉnh mốc thời gian không. |
| **Action** — hành động cuối cùng là gì, ai làm? | Trưởng nhóm gửi nhắc, phân công bổ sung, sắp xếp lại công việc hoặc điều hành họp khắc phục chậm tiến độ. |
| **Outcome** — đo kết quả bằng gì? | Thời gian cần để rà soát tiến độ trước milestone; số task bị phát hiện quá muộn; tỉ lệ milestone đúng hạn; số lần cần điều phối đột xuất. |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Task list, deadline, trạng thái cập nhật, file / comment / chat, milestone, lịch họp. Dữ liệu có sẵn nhưng rải rác. |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Phản hồi từ trưởng nhóm sau từng milestone: task nào bị đánh giá sai, blocker nào bị bỏ sót, cập nhật nào cần chuẩn hóa hơn. |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:Nhóm muốn AI tóm tắt tiến độ và phát hiện rủi ro, nhưng không muốn AI tự quyết định ai chậm, ai cần được giao việc, hay ai đã hoàn thành thật sự. Điều này cho thấy dạng hỗ trợ (augment), không phải tự động hóa hoàn toàn.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:
Bỏ sót blocker là tệ hơn. Nếu AI không phát hiện được phần đang chậm, nhóm sẽ không kịp điều phối trước milestone. Vì vậy, thiết kế giữ “con người kiểm tra” ở cuối và ưu tiên cảnh báo rủi ro cao thay vì xem AI đã “đánh dấu chắc chắn”.
---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Trưởng nhóm / PM nhóm phụ trách điều phối tiến độ và milestone của đồ án |
| **Quy trình** | Mỗi khi sắp đến deadline milestone/báo cáo: nhóm cập nhật task, deadline và blocker từ task board, file, Discord, chat và meeting; trưởng nhóm rà soát và tổng hợp tiến độ để điều phối tiếp theo |
| **Bottleneck** | Thông tin tiến độ nằm rải rác và cập nhật không đều; trưởng nhóm mất thời gian để đối chiếu dữ liệu và xác định phần còn thiếu thực tế |
| **Impact** | Nhiều task chỉ được phát hiện chậm khi gần deadline; nhóm dễ bỏ sót phần còn thiếu, làm tăng công sức gấp rút và nguy cơ trễ milestone |
| **Success Metric** (baseline → target, cách đo) | Baseline: 45–60 phút/check-in để rà soát tiến độ và xác định ai đang chậm; target: dưới 15 phút/check-in; đo bằng thời gian trưởng nhóm dùng để tổng hợp tiến độ trước mỗi milestone; đồng thời theo dõi số task bị phát hiện quá muộn |
| **Boundary** | AI không tự cập nhật trạng thái cho thành viên, không tự phân công lại việc, không suy luận dựa trên thông tin không có trong input |
| **AI intervention point** | Sau khi có dữ liệu tiến độ từ task/ file / chat / meeting, trước khi trưởng nhóm quyết định điều phối lại |
| **Mức chọn** | Workflow |
| **Rủi ro & người kiểm tra** | AI có thể gộp trạng thái sai, bỏ sót blocker hoặc nhầm lẫn deadline; trưởng nhóm phải xác nhận danh sách blocker và phần còn thiếu trước khi gửi cho cả nhóm |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Actor | Trưởng nhóm muốn biết tiến độ thực tế | Trưởng nhóm / PM nhóm phụ trách điều phối milestone | Làm rõ vai trò người dùng và bối cảnh quyết định |
| Quy trình | Tổng hợp tiến độ từ nhiều nguồn | Cụ thể hơn: task board + chat + file + meeting + milestone | Đảm bảo AI có input rõ ràng và báo cáo sát với tình huống thực |
| Success Metric | Chỉ tập trung vào thời gian tổng hợp | Thêm số task phát hiện quá muộn và độ chính xác của tóm tắt | Nhiều người phản biện rằng “nhanh nhưng sai” không phải là giải pháp tốt |
| Boundary | AI tóm tắt tiến độ | AI không tự quyết định / cập nhật / phân công | Giữ người kiểm tra ở vị trí quan trọng, giảm rủi ro AI sai |


**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Đúng trạng thái task | Mọi task được AI mô tả đúng với dữ liệu đã có; không gán “hoàn thành” cho task chưa xong | Có task đánh dấu sai trạng thái hoặc bỏ sót task đang thực hiện |
| 2 | Không bỏ sót blocker | Tất cả blocker quan trọng xuất hiện trong input đều được liệt kê | Có blocker rõ ràng nhưng không được nhắc đến |
| 3 | Phân biệt rõ phần còn thiếu | AI nêu được ai đang chậm, thiếu gì và cần làm gì tiếp | Tóm tắt chung chung, không xác định người chịu trách nhiệm |
| 4 | Dễ đọc trong 2 phút | Bản tóm tắt ngắn, rõ, có nhấn mạnh rủi ro và mốc quan trọng | Dài dòng, mơ hồ, khó rà soát ngay |

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
