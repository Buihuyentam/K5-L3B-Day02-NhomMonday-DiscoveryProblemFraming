# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản nháp làm từ tài liệu hiện có trong repo. Repo chưa có ghi chép pitch, phỏng vấn/survey, log thời gian hay research riêng của nhóm; vì vậy số liệu và quy trình dưới đây là giả thuyết để kiểm chứng, không phải kết quả thực địa. Không dùng nội dung này làm bằng chứng phỏng vấn. Cập nhật sau khi nhóm xác nhận.
> Worksheet: [docs/01-worksheet.md](../../docs/01-worksheet.md) · Hướng dẫn framework: [docs/03-international-frameworks.md](../../docs/03-international-frameworks.md)

## 1. Thông tin nhóm

- Tên nhóm: Monday
- Thành viên đã biết trong `TEAM.md`: Lương Đức Anh (2A202603931), Bùi Thị Huyền Tâm (2A202603917); danh sách còn thiếu.
- Candidate problem tạm chọn: Khi làm bài nhóm theo nhiều checkpoint, thành viên muốn xác định nhanh cần tạo/cập nhật nội dung ở đâu và còn thiếu gì, để hoàn tất deliverable đúng yêu cầu.
- Quyết định cuối: **Not Yet** — cần xác nhận pain và baseline với thành viên thật trước khi chọn giải pháp.

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

Chưa có biên bản pitch hoặc Problem Card cá nhân trong repo. Không thể quy candidate cho thành viên hay ghi câu hỏi phản biện như thể đã xảy ra. Dưới đây là các candidate desk-research suy ra từ loại công việc được mô tả trong worksheet; cần từng thành viên xác nhận bằng trải nghiệm thật.

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck giả thuyết | Câu hỏi phản biện cần hỏi |
|---:|---|---|---|---|---|
| 1 | Chưa ghi nhận | Khi bắt đầu checkpoint, tôi muốn biết deliverable và file đích, để không bỏ sót đầu việc | Thành viên nhóm | Tìm yêu cầu giữa worksheet, checkpoints và templates | Lần gần nhất bạn phải tìm yêu cầu này là khi nào? |
| 2 | Chưa ghi nhận | Khi nhóm chọn một vấn đề, tôi muốn so sánh các candidate theo cùng tiêu chí, để quyết định có lý do | Nhóm Monday | Gom pitch và đối chiếu tiêu chí | Nhóm hiện có bao nhiêu candidate và ghi ở đâu? |
| 3 | Chưa ghi nhận | Khi chuẩn bị báo cáo, tôi muốn biết phần nào cần dữ liệu thật, để không trình bày giả định như kết quả | Người tổng hợp báo cáo | Phân biệt ví dụ, giả thuyết và bằng chứng | Có mục nào nhóm chưa có dữ liệu để điền không? |
| 4 | Chưa ghi nhận | Khi nhiều người cùng làm, tôi muốn biết ai phụ trách phần nào, để tránh trùng hoặc bỏ trống việc | Nhóm Monday | Chưa có phân công điền trong TEAM.md | Có việc nào bị chờ vì chưa rõ người phụ trách? |
| 5 | Chưa ghi nhận | Khi viết reflection, tôi muốn dựa vào ghi chép hoạt động của mình, để phản ánh đúng trải nghiệm | Từng thành viên | Chưa có nhật ký cá nhân | Bạn đã ghi lại phản biện/đổi ý ở đâu? |

### 2.2. Cluster

| Cluster | Candidate | Pattern chung |
|---|---|---|
| A — Tìm yêu cầu và file đích | #1, #3 | Thông tin bài nằm ở nhiều tài liệu, cần tìm đúng hướng dẫn và trạng thái |
| B — Phối hợp | #2, #4 | Cần thống nhất tiêu chí, người làm và quyết định |
| C — Ghi nhận trải nghiệm | #5 | Cần ghi sự kiện khi nó vừa xảy ra để báo cáo cá nhân chính xác |

### 2.3. Opportunity Solution Tree rút gọn

```text
OUTCOME: Thành viên hoàn tất deliverable đúng yêu cầu với ít thời gian tìm kiếm và làm lại hơn
├── Opportunity A: Thành viên chưa chắc yêu cầu nào áp dụng cho checkpoint hiện tại
├── Opportunity B: Nhóm chưa có một chỗ ghi quyết định, người phụ trách và trạng thái
└── Opportunity C: Thành viên có thể quên chi tiết phản biện và thay đổi ý kiến đã xảy ra
```

Ý loại khỏi tầng opportunity vì là giải pháp: “chatbot hỏi đáp”, “dashboard tiến độ”, “tự động điền báo cáo”. Chưa có bằng chứng những giải pháp này cần thiết.

### 2.4. Chấm điểm shortlist (1–5)

Điểm dưới đây là đánh giá sơ bộ từ cấu trúc repo, không phải đồng thuận hay bằng chứng nhóm.

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được 4 mức | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Tìm yêu cầu/file đích | 4 | 3 | 1 | 2 | 5 | 4 | 4 | 23 |
| Ghi quyết định/phân công | 4 | 3 | 1 | 2 | 5 | 4 | 3 | 22 |
| Ghi nhật ký để reflection | 3 | 3 | 1 | 2 | 5 | 3 | 4 | 21 |

**Candidate tạm chọn:** Tìm yêu cầu và file đích cho checkpoint.

**Lý do:** Phạm vi nhỏ, actor xác định được và có thể đo thời gian tìm yêu cầu trên một nhiệm vụ cụ thể. Tài liệu hiện tại có worksheet, checkpoints, template nhóm và template cá nhân, nhưng sự tồn tại của nhiều file không tự chứng minh người học gặp khó.

**Lý do chưa loại các candidate khác:** Chưa có pitch thật để so sánh; cần để nhóm xác nhận trước khi chốt.

**Bất đồng:** Chưa có biên bản; không ghi nhận bất đồng chưa được xác nhận.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại | Quan trọng | Bằng chứng hiện có | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Thành viên mất thời gian tìm yêu cầu/file đích trong lúc làm checkpoint | Value | 5 | 1 | Có |
| 2 | Việc tìm kiếm xảy ra lặp lại, không chỉ một lần lúc mới đọc repo | Value | 4 | 1 | Có |
| 3 | Một trang chỉ mục/checklist đủ giảm thời gian tìm | Usability | 4 | 1 | Có |
| 4 | Các yêu cầu trong tài liệu đủ nhất quán để lập chỉ mục bằng quy tắc | Feasibility | 3 | 2 | Sau khi xác nhận pain |
| 5 | Thành viên sẽ dùng trang chỉ mục trong các checkpoint tiếp theo | Viability | 3 | 1 | Có |

Điểm bằng chứng thấp phản ánh repo không có quan sát người dùng; tài liệu chỉ chứng minh nội dung đang nằm ở các file, không chứng minh mức độ khó tìm.

**Giả định ưu tiên:** #1 và #2. Phỏng vấn 2–3 thành viên/nhóm khác đã làm qua checkpoint, hỏi về lần gần nhất, thời gian tìm, đường dẫn họ đã mở và cách xử lý. Không hỏi họ có thích chatbot hay không.

### 3.2. Kiểm chứng

**Trạng thái:** Chưa thực hiện. Không có interview snapshot, survey, log hoặc ghi chép quan sát nào trong repo.

| Nguồn | Số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Tài liệu trong repo | 5+ tệp liên quan | Hướng dẫn, checklist và các template nằm ở các file khác nhau | Cấu trúc có tên file và liên kết chéo; người đọc có thể tìm được dễ dàng |
| Phỏng vấn/survey | 0 | Chưa có | Chưa có |

**Câu hỏi kiểm chứng đề xuất:** “Kể lần gần nhất bạn cần biết checkpoint yêu cầu gì. Bạn mở những file nào, mất bao lâu, và cuối cùng làm gì?” Ghi lại vai trò, diễn biến, thời gian ước lượng của người tham gia, workaround và cả trường hợp họ tìm được ngay. Không ghi tên thật.

**Thay đổi problem sau kiểm chứng:** Chưa có kết quả để kết luận. Candidate hiện vẫn là giả thuyết.

### 3.3. Research giải pháp đã có

Research desk-based đã kiểm tra tài liệu chính thức GitHub về README, relative links và Projects. Đây là các pattern liên quan tới điều hướng/phối hợp công việc, không phải bằng chứng người học của nhóm đang gặp pain. Giải pháp nền tảng hiện có trong project là README/checkpoints, liên kết chéo tới worksheet và các template báo cáo.

| Giải pháp/pattern hiện có | Nguồn | Giải phần nào | Điểm mạnh | Khoảng trống/rủi ro | Bài học |
|---|---|---|---|---|---|
| README + mục lục và relative links | [GitHub Docs: About README](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes), [Markdown links](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) | Định hướng điểm bắt đầu, dẫn tới file/heading liên quan | README là điểm vào; GitHub hỗ trợ mục lục và link tương đối | Không tự chứng minh người đọc tìm được nội dung; mục lục cần tổ chức tốt | Cải thiện README/link trước khi thêm AI |
| GitHub Projects board | [GitHub Docs: Projects quickstart](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/quickstart-for-projects) | Theo dõi đầu việc và trạng thái | Có view theo status, có thể nhìn việc đang làm | Cần thiết lập, cập nhật; có thể quá mức cho nhóm nhỏ | Bảng TEAM.md đơn giản có thể đủ; chỉ dùng board nếu phối hợp là pain đã xác nhận |
| Checklist/template hiện có trong repo | [CHECKPOINTS.md](../../CHECKPOINTS.md), [group_report.md](group_report.md), [báo cáo cá nhân](../individual/2A202603917_Bùi%20Thị%20Huyền%20Tâm.md) | Liệt kê đầu ra và cấu trúc cần điền | Không cần mua hay xây công cụ mới | Người học vẫn phải nối yêu cầu với file; chưa đo mức độ khó | Thử chỉ mục có link và đo tác vụ trước |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại (giả thuyết, cần bấm giờ)

```text
Đọc checkpoint → mở worksheet → tìm template/file đích → dò thông tin cần điền
→ làm nhiệm vụ → tự kiểm tra lại với rubric
```

| Bước | Actor | Input | Output | Thời gian/tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Thành viên | Tên checkpoint | Mục tiêu và đầu việc | Chưa đo / checkpoint | Xem CHECKPOINTS.md |
| 2 | Thành viên | Yêu cầu | Cách thực hiện chi tiết | Chưa đo | Mở worksheet và tài liệu tham chiếu |
| 3 | Thành viên | Yêu cầu đã hiểu | File đích | Chưa đo | Tìm template cá nhân/nhóm |
| 4 | Thành viên | Nội dung đã làm | Deliverable | Phụ thuộc nhiệm vụ | Điền báo cáo |
| 5 | Thành viên/nhóm | Deliverable | Bản tự kiểm | Chưa đo | So với rubric và submission checklist |

**Bottleneck giả thuyết:** Bước 2–3, định vị nội dung và file đích. Chưa có số phút quan sát được.

### 4.2. Quy trình tương lai (thử cải tiến không AI trước)

```text
[1 Mở một trang chỉ mục theo checkpoint: link + deliverable + tiêu chí] ← RULE / nội dung biên tập
→ [2 Làm bài theo template hiện có] ← CON NGƯỜI
→ [3 Đối chiếu checklist] ← RULE / CON NGƯỜI

Boundary: không tự tạo nội dung cá nhân, không đánh dấu hoàn thành thay người học.
Fallback: quay lại CHECKPOINTS.md, worksheet và template hiện có.
```

### 4.3. Before / after (mục tiêu thử nghiệm, chưa phải kết quả)

| Chỉ số | Trước | Sau (mục tiêu pilot) | Ghi chú |
|---|---:|---:|---|
| Số bước | 5 (ước tính) | 3 | Cần xác nhận bằng quan sát |
| Thời gian tìm yêu cầu/file | Chưa đo | Giảm ít nhất 30% so với baseline | Bấm giờ 3 tác vụ tương đương trước/sau |
| Bước thủ công | Chưa đo | Vẫn do người học thực hiện | Chỉ gom link/checklist |
| Bottleneck | Định vị hướng dẫn | Đối chiếu checklist | Giả thuyết |
| Rủi ro mới | Yêu cầu bị bỏ sót | Chỉ mục lỗi thời hoặc bỏ sót | Gán người cập nhật, dẫn link nguồn |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Thành viên nhóm Monday đang làm các checkpoint của Day 02 |
| **Quy trình** | Đọc checkpoint, tra worksheet, tìm file đích, hoàn thành nội dung, tự đối chiếu rubric |
| **Bottleneck** | Giả thuyết: phải chuyển qua nhiều tài liệu để ghép yêu cầu với file cần điền; chưa đo thời gian |
| **Impact** | Có nguy cơ tốn thời gian tìm kiếm hoặc bỏ sót mục; chưa có dữ liệu về tần suất/tác động |
| **Success Metric** | Baseline chưa có. Đo thời gian tìm đúng hướng dẫn và file cho 3 tác vụ; mục tiêu pilot giảm ≥30%, đồng thời không tăng số mục bị bỏ sót |
| **Boundary** | Không tự viết reflection cá nhân, không bịa bằng chứng, không đánh dấu task hoàn tất; thành viên đối chiếu yêu cầu nguồn trước khi nộp |

**Phản biện:** “Nhiều tài liệu” chưa chứng minh là bottleneck; có thể các liên kết hiện tại đã đủ. Đồng ý. Cần quan sát người học trước khi chốt vấn đề hoặc đầu tư giải pháp.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

**Đánh giá sơ bộ:** độ mơ hồ thấp, độ phức tạp thấp. Tác vụ tra file và checklist có đích đến xác định, dữ liệu đóng trong repo. Cả hai đánh giá này vẫn cần xác nhận qua quan sát.

### 6.2. So sánh 4 mức

| Mức | Phương án | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** | Sắp xếp chỉ mục/checklist có liên kết | Người học cần tìm đúng yêu cầu | Cần cập nhật thủ công | **Ưu tiên thử trước** |
| **Rule** | Điều hướng theo checkpoint/tên deliverable | Cấu trúc và tên file ổn định | Link cũ hoặc mapping sai | Có thể dùng như chỉ mục |
| **Workflow** | Người học chọn checkpoint → trả danh sách link và checklist | Có nhiều bước điều hướng lặp lại đã được chứng minh | Có thể thêm độ phức tạp không cần thiết | Chưa chọn |
| **Agent** | Hỏi đáp tự do trên tài liệu và tự đề xuất nội dung | Nguồn lớn, câu hỏi khó dự đoán, có nhu cầu đã xác nhận | Trả lời sai/không truy nguồn; làm thay phần cá nhân | Không chọn |

**Mức chọn:** No AI cho pilot đầu tiên; Rule chỉ ở dạng chỉ mục tĩnh nếu quan sát xác nhận có vấn đề tìm kiếm.

**Vì sao không chọn mức phức tạp hơn:** Chưa có bằng chứng pain hay lợi ích AI; cách sắp xếp link/checklist rẻ, minh bạch và dễ sửa. Không có cơ sở biện minh cho Workflow hoặc Agent.

### 6.3. AI Canvas rút gọn

Vì chưa chọn AI, canvas này ghi điều kiện nếu sau pilot cân nhắc công cụ hỗ trợ.

| Thành phần | Nội dung giả thuyết |
|---|---|
| **Prediction** | Trả về file/hướng dẫn phù hợp với checkpoint được hỏi |
| **Judgment** | Người học xác nhận đúng checkpoint và kiểm tra câu trả lời với nguồn gốc |
| **Action** | Người học mở tài liệu và tự hoàn thành bài |
| **Outcome** | Thời gian tìm đúng nguồn và tỷ lệ bỏ sót yêu cầu |
| **Input** | Tài liệu markdown trong repo, trạng thái phiên bản và câu hỏi |
| **Feedback** | Câu trả lời sai/thiếu được ghi nhận và sửa trong chỉ mục; chỉ cân nhắc AI sau khi có lỗi lặp lại |

### 6.4. Hai câu hỏi của Google PAIR

- **Augment hay automate?** Nếu có nhu cầu, chỉ hỗ trợ điều hướng; người học vẫn đọc, suy nghĩ và viết nội dung cá nhân. Chưa có phỏng vấn để coi đây là nhu cầu đã xác nhận.
- **Báo nhầm hay bỏ sót?** Bỏ sót yêu cầu có thể khiến deliverable thiếu; trả lời sai có thể dẫn tới thao tác sai. Biện pháp tối thiểu là hiển thị link nguồn cạnh từng hướng dẫn và yêu cầu người học tự kiểm checklist. Pilot hiện tại không dùng AI.

---

## 7. Problem Statement v1 + tiêu chí đánh giá

| Trường | Nội dung |
|---|---|
| **Actor** | Thành viên nhóm Monday; cần xác nhận có pain lặp lại |
| **Quy trình** | Xác định checkpoint → mở hướng dẫn và file liên quan → làm bài → tự kiểm theo rubric |
| **Bottleneck** | Chưa xác nhận; cần đo thời gian định vị nguồn |
| **Impact** | Chưa lượng hóa; giả thuyết là thời gian tìm kiếm và nguy cơ bỏ sót |
| **Success Metric** | Trong thử nghiệm 3 tác vụ, thời gian tìm giảm ≥30% so với baseline và không phát sinh mục yêu cầu bị bỏ sót; ghi số liệu từng tác vụ |
| **Boundary** | Chỉ mục không thay thế tài liệu nguồn, không viết thay nội dung cá nhân và không khẳng định trạng thái hoàn thành |
| **AI intervention point** | Không có ở pilot đầu; cân nhắc hỗ trợ tìm nguồn chỉ khi có nhu cầu và dữ liệu lỗi lặp lại |
| **Mức chọn** | No AI (pilot), Rule tĩnh nếu cần điều hướng |
| **Rủi ro & người kiểm tra** | Link sai/lỗi thời: người duy trì repo kiểm tra; người học đối chiếu tài liệu gốc |

**Thay đổi so với v0:** Thu hẹp giải pháp thử nghiệm về chỉ mục/checklist, tạm bỏ giả định cần AI; problem vẫn chưa được xác thực.

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Mức can thiệp | Chưa xác định | No AI trước, Rule tĩnh nếu cần | Chưa có evidence rằng AI cần thiết |
| Metric | Đo tìm nguồn và mục bỏ sót | Cùng metric, đặt ngưỡng pilot 30% | Cần ngưỡng đo được; 30% là mục tiêu thử, không phải kết quả |
| Bằng chứng pain | Chưa có | Vẫn chưa có | Cần giữ nguyên trạng thái trung thực, không coi giả thuyết là xác nhận |

**Tiêu chí đánh giá nếu sau này có câu trả lời tự động:**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Truy nguồn | Mỗi chỉ dẫn có đường dẫn tới file nguồn đúng | Không có nguồn hoặc dẫn sai |
| 2 | Bao phủ yêu cầu | Không bỏ sót mục bắt buộc trong tác vụ đã chọn | Thiếu mục trong checklist nguồn |
| 3 | Đúng phạm vi | Không tự viết reflection/bằng chứng cá nhân | Tạo nội dung giả định như trải nghiệm thật |
| 4 | Tính cập nhật | Link và tên file còn hiệu lực ở phiên bản repo hiện tại | Hướng dẫn lỗi thời hoặc file không tồn tại |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Mức độ | Lý do/bằng chứng |
|---|---|---|
| **Value** | Cao | Chưa có phỏng vấn/log chứng minh vấn đề xảy ra; chỉ suy ra từ cấu trúc tài liệu |
| **Usability** | Trung bình | Chỉ mục có thể dễ dùng, nhưng chưa thử với thành viên khác |
| **Feasibility** | Thấp | Sắp xếp Markdown/link trong repo khả thi; chưa có triển khai cần kiểm tra |
| **Viability** | Thấp | Không phát sinh công cụ trả phí nếu pilot bằng chỉ mục/checklist; cần người duy trì link |

### 8.2. Kết luận

**Quyết định:** **Not Yet** cho việc xây hoặc dùng AI; cho phép làm kiểm chứng/pilot chỉ mục thủ công.

**Lý do:** Thiếu bằng chứng về pain, baseline và tần suất. Phương án đơn giản nhất là kiểm thử khả năng tìm kiếm hiện tại và thử chỉ mục gắn link.

**Pilot nhỏ nhất:** Nhờ 3 thành viên làm 3 tác vụ tra cứu checkpoint tương đương; ghi thời gian tìm đúng file, số lần mở nhầm và số yêu cầu bỏ sót. Thử lại với một trang chỉ mục có link, so sánh kết quả. Đây là kế hoạch, chưa được thực hiện.

**Cần kiểm chứng trước:** Có ít nhất 2/3 người gặp khó trong tác vụ thực tế và baseline đủ lớn để cải thiện có ý nghĩa. Nếu đa số tìm được ngay, đóng problem này và không thêm giải pháp.

**Ngưỡng dừng:** Nếu chỉ mục không giảm trung vị thời gian tìm ít nhất 30% hoặc làm tăng mục bỏ sót trong 3 tác vụ, quay lại CHECKPOINTS.md và sửa cấu trúc tài liệu; không nâng lên AI/Agent.

---

## 9. Hạn chế và hướng tiếp theo

- Chưa có CP1/CP2 cá nhân, pitch nhóm, phản biện thật, interview, survey hay baseline thời gian trong repo.
- Điểm chấm, quy trình và ngưỡng pilot là giả thuyết/thiết kế kiểm chứng, không phải kết quả nhóm đã quan sát.
- Cần các thành viên xác nhận candidate, bổ sung thành viên/vai trò trong `TEAM.md`, thực hiện kiểm chứng và cập nhật kết luận.
- Báo cáo cá nhân để nguyên template vì phần reflection phải là trải nghiệm thật của người viết; không thể suy ra từ tài liệu chung.

## 10. Tài liệu tham khảo

- [CHECKPOINTS.md](../../CHECKPOINTS.md) — yêu cầu và đầu ra từng checkpoint.
- [README.md](../../README.md) — hướng dẫn bắt đầu trong repo.
- [docs/01-worksheet.md](../../docs/01-worksheet.md) — hướng dẫn chi tiết và phương pháp.
- [docs/03-international-frameworks.md](../../docs/03-international-frameworks.md) — framework tham khảo.
- [TEAM.md](../../TEAM.md) — thành viên đã đăng ký và phân công hiện có.
