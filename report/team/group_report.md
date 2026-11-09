# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Tổng hợp desk-based từ hai file cá nhân hiện có. Candidate được đề xuất, chưa có biên bản pitch/đồng thuận nhóm, phỏng vấn, survey hoặc số liệu bấm giờ. Các quy trình/metric tương lai là kế hoạch pilot, không phải kết quả đã đạt. Phân công trong `TEAM.md` là đề xuất.
> Worksheet: [docs/01-worksheet.md](../../docs/01-worksheet.md) · Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md) · Nhân sự/phân công: [TEAM.md](../../TEAM.md)

## 1. Thông tin nhóm

- Tên nhóm: Monday
- Hai hồ sơ đã đối chiếu: Bùi Thị Huyền Tâm (2A202603917), Lương Đức Anh (2A202603931).
- Candidate đề xuất: Khi tổng kết chi tiêu tháng, người dùng muốn gom khoản từ app/ngân hàng, tiền mặt và điểm trả trước vào một bảng dễ hiểu, để thấy chi tiêu thực mà không bỏ sót hoặc tính trùng.
- Quyết định hiện tại: **Not Yet** cho sản phẩm/AI; xác minh và pilot thủ công trước.

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Candidate pool từ hai báo cáo cá nhân

Các candidate dưới đây được rút từ scan/top 3 của hai file; chưa khẳng định thành viên đã pitch hoặc phản biện trong buổi nhóm.

| # | Người / nguồn | Candidate (Job Story ngắn) | Actor | Bottleneck giả thuyết | Câu hỏi phản biện cần hỏi |
|---:|---|---|---|---|---|
| 1 | Lương Đức Anh — CP1/2 | Khi muốn biết tháng này tiền đi đâu, tôi muốn gom tiền ngân hàng/app trả trước và tiền mặt, để thấy chi tiêu gần với thực tế | Cá nhân dùng nhiều nguồn tiền | Dựng lại khoản cash và điểm trả trước; nguy cơ tính cả lúc nạp lẫn lúc dùng | App/điểm nào đang dùng? Nạp và tiêu được ghi thế nào? |
| 2 | Huyền Tâm — CP1/2 | Khi rà soát chi tiêu, tôi muốn xem giao dịch ngân hàng/ví ở một chỗ, để biết tiền đã đi đâu và còn bao nhiêu | Cá nhân dùng nhiều app | Mở nhiều app, dò và phân loại giao dịch | Có thực sự cần nhiều nguồn hay một app đã đủ? |
| 3 | Lương Đức Anh — CP1 | Khi lịch học/lịch cá nhân kín, tôi muốn biết việc nào có thể dời/bỏ, để không làm vỡ lịch | Cá nhân có lịch học và lịch riêng | Ước lượng tác động dây chuyền khi đổi lịch | Có lần gần nhất và thời gian xử lý không? |
| 4 | Lương Đức Anh — CP2 | Khi gặp truyện/tin chưa đọc ngay, tôi muốn lưu thành hàng đợi riêng, để tìm lại và theo dõi tiến độ | Người đọc nhiều nội dung trên web | Tìm giữa nhiều tab, không nhớ đang đọc đến đâu | Bao nhiêu tab/nội dung thực sự bị quên? |
| 5 | Lương Đức Anh — CP2 | Khi có việc/ý tưởng bất chợt, tôi muốn lưu thật nhanh, để không quên khi chuyển hoạt động | Cá nhân | Không có bước ghi ổn định lúc ý nghĩ xuất hiện | Tuần gần nhất có bao nhiêu lần quên? |
| 6 | Huyền Tâm — CP1/2 | Khi nhóm chuẩn bị chuyến đi, tôi muốn tổng hợp ngày rảnh, ngân sách và phương án di chuyển, để chốt kế hoạch phù hợp | Người điều phối và bạn đi cùng | Gom phản hồi và so sánh phương án | Số người, vòng chat, thời gian chốt? |
| 7 | Huyền Tâm — CP1 | Khi tìm phương án đi lại, tôi muốn so sánh tổng chi phí và thời gian, để chọn phương án trong ngân sách | Người điều phối/nhóm đi cùng | Tra cứu nhiều lựa chọn | Lần gần nhất mất bao lâu, có mấy lựa chọn? |
| 8 | Huyền Tâm — CP1/2 | Khi lời nhắc định kỳ xuất hiện, tôi muốn nhớ lý do và bước tiếp theo, để biết cần làm gì | Cá nhân | Tìm lại chat/ghi chú để khôi phục ngữ cảnh | Trong hai tuần phải tra lại bao nhiêu lần? |
| 9 | Huyền Tâm — CP1 | Khi nhắc bạn về việc chung, tôi muốn kèm bối cảnh và hạn chót, để họ không phải hỏi lại | Người nhắc và bạn bè | Người nhận thiếu thông tin ban đầu | Có ví dụ tin nhắn hỏi lại nào? |
| 10 | Lương Đức Anh — CP1 | Khi muốn xem lại chi tiêu, tôi muốn đổi điểm trả trước và giao dịch thành khoản tiền dễ hiểu, để so với tiền mặt | Cá nhân | Quy đổi điểm và tách nạp khỏi tiêu | Có tỷ lệ quy đổi/lịch sử điểm chính xác không? |
| 11 | Lương Đức Anh — CP1 | Khi có ý tưởng giữa lúc làm việc khác, tôi muốn lưu nó trong vài giây, để tìm lại sau | Cá nhân | Chuyển ngữ cảnh trước khi ghi | Ý tưởng nào đã mất, ảnh hưởng ra sao? |
| 12 | Huyền Tâm — CP1 | Khi lên lịch nhóm, tôi muốn thấy giờ, điểm đón và phương án dự phòng cùng chỗ, để không tìm lại trong nhiều đoạn chat | Cả nhóm | Thông tin phân tán nhiều nguồn | Lần gần nhất phải hỏi lại là khi nào? |

### 2.2. Cluster

| Cluster | Candidate | Pattern chung |
|---|---|---|
| A — Tổng hợp tiền cá nhân | #1, #2, #10 | Giao dịch nằm ở nhiều dạng/nguồn; dễ thiếu khoản, khó quy đổi hoặc tính trùng |
| B — Lập kế hoạch và điều phối | #3, #6, #7, #9, #12 | Cần so sánh lịch/chi phí hoặc truyền bối cảnh để phối hợp |
| C — Lưu và tìm lại thông tin | #4, #5, #8, #11 | Ý nghĩ, nội dung đọc hoặc lời nhắc tách khỏi ngữ cảnh |

### 2.3. Opportunity Solution Tree rút gọn

```text
OUTCOME: Tăng độ đầy đủ của tổng kết chi tiêu tháng mà không tăng lỗi tính tiền
├── Opportunity A: Một phần chi tiêu không xuất hiện trong lịch sử ngân hàng
├── Opportunity B: Tiền mặt và điểm trả trước khó đối chiếu với khoản đã dùng
└── Opportunity C: Nạp điểm và sử dụng điểm có thể bị tính trùng khi tổng kết
```

Đã loại khỏi tầng opportunity vì là solution: “kết nối mọi app”, “AI tự quản lý tài chính”, “tự động quy đổi mọi điểm”.

### 2.4. Chấm điểm shortlist (1–5)

Điểm sơ bộ từ hai báo cáo; chưa phải chấm điểm nhóm. “Pain có bằng chứng” phản ánh độ cụ thể của scan, không thay cho log/phỏng vấn độc lập.

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh 4 mức | Hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Tiền cá nhân qua app, cash, điểm trả trước | 5 | 4 | 3 | 4 | 4 | 5 | 4 | **29** |
| Kế hoạch đi lại nhóm | 4 | 3 | 1 | 3 | 4 | 4 | 3 | 22 |
| Ghi nhanh việc/ý tưởng | 4 | 3 | 1 | 2 | 5 | 4 | 3 | 22 |

**Candidate đề xuất:** Tổng hợp chi tiêu nhiều nguồn, tập trung vào cash và điểm trả trước.

**Lý do:** Hai scan đều nhắc tổng quan chi tiêu nhiều nguồn. Báo cáo Lương Đức Anh cụ thể hơn: ít nhất 4 app, tiền mặt, điểm trả trước cho di chuyển và hóa đơn điện thoại; bottleneck là dựng lại cash/điểm và phân biệt nạp với tiêu. Các bước/metric có thể kiểm tra bằng pilot nhỏ. Đây là hội tụ của hai scan, chưa phải phỏng vấn hay đồng thuận nhóm.

**Các candidate còn lại:** Chưa loại bỏ; đi lại nhóm và lưu thông tin cần được pitch và so bằng bằng chứng thực tế.

**Bất đồng:** Chưa có biên bản để xác định bất đồng/đồng thuận.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại | Quan trọng | Bằng chứng hiện có | Kiểm trước? |
|---:|---|---|---:|---:|---|
| 1 | Người dùng phải mở nhiều app và nguồn tiền để rà soát định kỳ | Value | 5 | 2 | Có |
| 2 | Dựng lại cash/điểm trả trước gây thiếu hoặc sai tổng | Value | 5 | 2 | Có |
| 3 | Người dùng ghi cash ngay sau khi mua đủ đều để dữ liệu hữu ích | Usability | 4 | 1 | Có |
| 4 | Các app liên quan xuất được lịch sử hoặc có số dư đối chiếu | Feasibility | 4 | 1 | Có |
| 5 | Tách nạp điểm và điểm đã dùng ngăn được tính trùng | Feasibility | 4 | 2 | Có |
| 6 | Người dùng chấp nhận giữ dữ liệu trong bảng do mình kiểm soát | Viability | 4 | 1 | Có |

Điểm bằng chứng thấp vì chưa có diary, bấm giờ, phỏng vấn hay dữ liệu đã ẩn danh trong repo.

### 3.2. Kiểm chứng

**Đã có:** Hai báo cáo scan cùng đề cập tổng hợp tiền nhiều nguồn. Một nêu ít nhất 4 app, cash, điểm trả trước và hóa đơn; đây là tự báo cáo, chưa có đối chiếu độc lập.

**Chưa có:** Interview, survey, log thời gian, số giao dịch thiếu/sai, xác nhận app nào xuất được dữ liệu. Không có interview snapshot để trích dẫn.

| Nguồn | Số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác/giới hạn |
|---|---:|---|---|
| Hai báo cáo cá nhân | 2 | Cùng nhắc khó thấy tổng tiền từ nhiều nguồn | Chưa có baseline hoặc kiểm chứng độc lập; một báo cáo ghi rõ chưa bấm giờ |
| Phỏng vấn/survey/diary | 0 | Chưa có | Chưa có |

**Kế hoạch:** Phỏng vấn 2–3 người từng tổng kết tiền nhiều nguồn; hỏi lần gần nhất, từng nguồn, quy trình, thời gian, khoản bị bỏ sót/tính trùng và workaround. Một người tự nguyện ghi diary 2 tuần: phút mỗi phiên, nguồn, khoản cash, điểm nạp/tiêu và sai lệch khi đối chiếu. Không hỏi họ có muốn app AI.

**Problem cần xác minh:** Thu hẹp vào dựng lại cash/điểm trả trước và tránh tính cả top-up lẫn usage. Nếu pain không lặp lại hoặc khó đo, xem lại candidate.

### 3.3. Research giải pháp đã có

| Công cụ/pattern | Link | Giải bước nào? | Điểm mạnh | Khoảng trống/rủi ro | Bài học |
|---|---|---|---|---|---|
| Google Sheets nhập CSV | [Google Sheets Help](https://support.google.com/docs/answer/12236443?hl=en) | Import file giao dịch vào bảng | Người dùng kiểm soát dữ liệu/công thức; có thể lọc và cộng | Chỉ dùng được nếu app xuất file; cash/điểm vẫn phải ghi; schema có thể khác | Thử CSV và bảng chuẩn hóa trước tích hợp |
| Splitwise cho chi phí nhóm | [Splitwise Help](https://kb.splitwise.com/getting-started/how-do-i-use-splitwise) | Ghi khoản nhóm/trip, ai trả và chia số dư | Có sẵn cho chi phí chung | Không thay ledger cá nhân; import thẻ chỉ ở phạm vi hỗ trợ theo [Splitwise Pro](https://www.splitwise.com/pro) | Dùng nếu pain chính là chia tiền chuyến đi, không phải tổng kết mọi chi tiêu cá nhân |
| Bảng tính + quy tắc cash/điểm | Pattern thủ công cần thử | Ghi cash; top-up tăng số dư điểm; usage mới là chi tiêu | Minh bạch, dễ sửa, không cần gửi dữ liệu AI | Cần ghi đều; quy tắc phải được người dùng duy trì | Làm baseline No AI/Rule |

**Kết luận research:** CSV/bảng tính hỗ trợ nguồn có thể xuất; Splitwise giải chi phí nhóm. Chưa có bằng chứng các công cụ này tự ghép cash + điểm trả trước + giao dịch app mà tránh tính trùng. Pilot tách hai khái niệm: top-up là dòng tiền nạp vào số dư; usage là khoản tiêu dùng. Khi tính **tiêu dùng theo danh mục**, chỉ cộng usage; khi xem **dòng tiền**, chỉ cộng khoản nạp, không cộng cả hai vào cùng một tổng. Không tự xây agent.

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại (cần quan sát/bấm giờ)

```text
Trả qua cash/ngân hàng/app → lịch sử ở nhiều nơi hoặc không có
→ nạp điểm trả trước → sử dụng điểm sau đó
→ cuối kỳ mở lại nguồn, nhớ cash, cộng/phân loại
→ tổng có thể thiếu hoặc tính trùng nạp điểm với lúc sử dụng
```

| Bước | Actor | Input | Output | Thời gian/tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Người dùng | Khoản mua/di chuyển | Giao dịch app/ngân hàng hoặc cash | Hàng ngày; chưa đo | Ghi nguồn thanh toán |
| 2 | Người dùng | Điểm trả trước | Số điểm nạp và đã dùng | Khi nạp/dùng; chưa đo | Tách nạp khỏi chi tiêu cuối cùng |
| 3 | Người dùng | Hóa đơn/nguồn khác | Khoản định kỳ | Theo kỳ; chưa đo | Kiểm tra trùng với top-up nếu có |
| 4 | Người dùng | Lịch sử rải rác | Bảng tổng hợp | Cuối kỳ; chưa đo | Mở từng app và nhập lại |
| 5 | Người dùng | Bảng tổng hợp | Tổng chi theo nhóm | Chưa đo | Kiểm cash thiếu, quy đổi và trùng |

**Bottleneck:** Dựng lại cash và điểm đã dùng là giả thuyết từ Problem Card của Lương Đức Anh; duration cần đo.

### 4.2. Quy trình tương lai đề xuất (pilot No AI/Rule)

```text
[1 Nhập giao dịch từ file app nào xuất được]          ← CON NGƯỜI
→ [2 Ghi cash; top-up vào số dư điểm/dòng tiền]        ← RULE + CON NGƯỜI
→ [3 Ghi usage là tiêu dùng, không cộng trùng top-up]  ← RULE
→ [4 Phân loại khoản quen thuộc và tính tổng]          ← RULE
→ [5 Người dùng đối chiếu số dư, khoản lạ và trùng]    ← CON NGƯỜI (HITL)

BOUNDARY: Không kết nối tài khoản/đưa file cho AI; không tự quy đổi điểm nếu thiếu tỷ lệ.
FALLBACK: File không import được hoặc số liệu lệch → rà từng nguồn như quy trình cũ.
```

### 4.3. Before / after

| Chỉ số | Trước | Sau (mục tiêu pilot) | Ghi chú |
|---|---|---|---|
| Số bước | 5 bước mô tả, chưa quan sát | 5 bước có phân vai/rule rõ | Đếm lại sau diary |
| Tổng thời gian | Chưa đo | Giảm ≥30% so với baseline sau 2 tuần | Bấm giờ từng phiên |
| Bước thủ công | Chưa đếm; phần lớn dự kiến thủ công | 2–3 bước nhập/duyệt thủ công | Không tự động hóa cash/ngoại lệ |
| Bottleneck | Dựng lại cash/điểm, giả thuyết | Nhập cash và đối chiếu ngoại lệ | Pilot xác định bottleneck còn lại |
| Rủi ro mới | Thiếu khoản/tính trùng | Rule sai, quên ghi cash hoặc lệch số dư | Đối chiếu số dòng/tổng/số dư |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Cá nhân dùng nhiều app thanh toán, tiền mặt và điểm trả trước cho di chuyển |
| **Quy trình** | Chi tiêu qua nhiều nguồn → lịch sử rải rác/không có → cuối kỳ mở từng nguồn và dựng lại tổng chi |
| **Bottleneck** | Ghi nhớ cash và tách dòng tiền top-up khỏi tiêu dùng lúc dùng điểm; chưa đo thời gian |
| **Impact** | Báo cáo tiêu dùng có thể thiếu khoản hoặc cộng trùng top-up/usage; sai lệch chưa đo |
| **Success Metric** | Trong 2 tuần ghi ngày theo dõi và khoản thiếu; mục tiêu ban đầu 5/7 ngày mỗi tuần, đối chiếu số dư điểm và không tính trùng |
| **Boundary** | Không kết nối tài khoản/đưa dữ liệu cho AI; không tự quy đổi điểm khi thiếu tỷ lệ; người dùng xác nhận tổng |

**Phản biện:** 5/7 ngày đo thói quen ghi, chưa đo tiết kiệm thời gian/độ chính xác. Đồng ý bổ sung baseline thời gian và đối chiếu ở v1.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Đề xuất: độ mơ hồ thấp–trung bình nếu danh mục cố định; độ phức tạp trung bình do nhiều nguồn, cash không có lịch sử số và quy tắc điểm khác nhau. Chưa rõ app nào xuất được dữ liệu.

### 6.2. So sánh bốn mức

| Mức | Phương án | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** | Bảng ghi cash/app/hóa đơn và checklist cuối kỳ | Ít giao dịch, người dùng ghi đều | Nhập thủ công, dễ quên cash | Baseline |
| **Rule** | Import CSV, chuẩn hóa cột, mapping merchant, tách top-up/usage | Nguồn xuất được, quy tắc lặp ổn định | File khác format, mapping sai | **Chọn pilot đầu** |
| **Workflow** | Import → rule → AI gợi ý khoản lạ → người dùng duyệt | Ngoại lệ ngôn ngữ vẫn tốn thời gian sau khi thử rule | Sai phân loại, dữ liệu nhạy cảm | Chưa chọn |
| **Agent** | Tự kết nối nguồn, phân loại và cập nhật tổng | Không cần cho quy trình có bước cố định | Quyền truy cập rộng, sai lệch khó phát hiện | Không chọn |

**Mức chọn:** Rule/no-AI. Chưa chọn AI.

**Vì sao không chọn mức phức tạp hơn:** Nút khó có vẻ là cash không có log và cách tính điểm, không phải hiểu ngôn ngữ. Quy tắc minh bạch giải trực tiếp vấn đề với ít rủi ro dữ liệu hơn.

### 6.3. AI Canvas (chỉ là phương án dự phòng, không thuộc pilot)

| Thành phần | Nội dung nếu sau này thử AI |
|---|---|
| **Prediction** | Gợi ý danh mục cho mô tả giao dịch lạ; không dự đoán số dư/quy đổi điểm |
| **Judgment** | Người dùng xác nhận khoản chi và cách xử lý top-up/usage |
| **Action** | Người dùng lưu hoặc sửa bảng tổng |
| **Outcome** | Thời gian, độ đầy đủ, phân loại sai và số lần tính trùng |
| **Input** | Mô tả đã ẩn thông tin nhạy cảm, merchant, danh mục; chỉ sau khi đánh giá quyền riêng tư |
| **Feedback** | Người dùng sửa nhãn; không mặc định dùng dữ liệu cá nhân để huấn luyện |

### 6.4. Google PAIR

- **Augment hay automate?** Nếu sau này thử AI, chỉ gợi ý danh mục; người dùng xác nhận và sửa. Chưa có phỏng vấn để xác nhận nhu cầu.
- **Báo nhầm hay bỏ sót?** Cả hai làm tổng sai. Bỏ cash làm thiếu; tính top-up lẫn usage làm trùng. Pilot tách số dư điểm khỏi chi tiêu và đối chiếu từng nguồn.

---

## 7. Problem Statement v1 + tiêu chí đánh giá

| Trường | Nội dung |
|---|---|
| **Actor** | Cá nhân dùng nhiều app, cash và điểm trả trước; trường hợp scan cụ thể nêu ít nhất 4 app |
| **Quy trình** | Ghi cash, nhập lịch sử có thể xuất; ghi top-up là dòng tiền vào số dư và usage là tiêu dùng; đối chiếu riêng từng tổng |
| **Bottleneck** | Dựng lại cash/điểm đã dùng và tách hai cách nhìn tổng tiền; duration chưa đo |
| **Impact** | Tổng tiêu dùng tháng có thể thiếu hoặc cộng trùng top-up/usage; chưa lượng hóa |
| **Success Metric** | Diary 2 tuần; theo dõi ≥5/7 ngày mỗi tuần, giảm ≥30% thời gian so với baseline, không tăng khoản thiếu/sai |
| **Boundary** | Dữ liệu giữ cục bộ; không kết nối tài khoản/đưa cho AI; không tự quy đổi điểm; người dùng duyệt tổng |
| **AI intervention point** | Không có trong pilot; nếu cân nhắc sau này, chỉ gợi ý danh mục khoản không khớp |
| **Mức chọn** | Rule/no-AI |
| **Rủi ro & người kiểm tra** | Người dùng đối chiếu số dư điểm, giao dịch và tổng bảng; người phụ trách pilot ghi sai lệch |

**Thay đổi so với v0:** Thu hẹp vào cash chưa có lịch sử và điểm trả trước có thể bị tính trùng; thêm thời gian/độ chính xác vào metric; bỏ AI khỏi pilot.

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Phạm vi | Tổng hợp app, cash, điểm, hóa đơn | Cash + điểm trả trước; nhập giao dịch xuất được | Nút cụ thể nhất trong scan của Lương Đức Anh |
| Metric | Ghi 5/7 ngày, tránh tính trùng | Thêm baseline thời gian và không tăng lỗi | Tần suất ghi chép chưa đo hiệu quả/độ chính xác |
| Can thiệp | Có thể AI phân loại | Rule/no-AI | CSV/rule đơn giản hơn; chưa có bằng chứng AI cần thiết |

**Tiêu chí đánh giá:**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Độ bao phủ | Ghi ≥5/7 ngày và đối chiếu các nguồn đã chọn | Cash/app bị bỏ khỏi tổng |
| 2 | Nhất quán cách tính điểm | Báo cáo tiêu dùng chỉ cộng usage; báo cáo dòng tiền chỉ cộng top-up; không cộng cả hai vào cùng tổng | Cộng top-up và usage thành hai khoản chi trong cùng một tổng |
| 3 | Đối chiếu | Tổng khớp giao dịch nguồn/số dư điểm trong phạm vi đã định | Có sai lệch không giải thích được |
| 4 | Thời gian | Giảm ≥30% sau 2 tuần so với baseline | Giảm <20% hoặc thao tác tăng |
| 5 | Quyền kiểm soát | Người dùng sửa được ngoại lệ; dữ liệu không rời nơi kiểm soát | Tự xác nhận khoản lạ hoặc gửi dữ liệu ra ngoài không được phép |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Mức độ | Lý do/bằng chứng |
|---|---|---|
| **Value** | Trung bình–cao | Hai scan cùng nhắc tiền nhiều nguồn; chưa có interview/diary/impact đo |
| **Usability** | Trung bình | Bảng tính dễ tiếp cận nhưng cần ghi cash đều và hiểu quy tắc điểm; chưa thử |
| **Feasibility** | Trung bình | Sheets hỗ trợ nhập CSV; chưa kiểm tra từng app và cash vẫn nhập tay |
| **Viability** | Cao với AI ngoài; thấp–trung bình với bảng cục bộ | Dữ liệu tài chính nhạy cảm; chưa đánh giá dịch vụ ngoài; bảng cục bộ không cần chi phí mới |

### 8.2. Kết luận

**Quyết định:** **Not Yet** cho sản phẩm/AI; tiếp tục diary và pilot bảng cục bộ để kiểm tra problem.

**Lý do:** Hai scan hội tụ trên tiền nhiều nguồn; một scan mô tả rõ cash và điểm trả trước. Nhưng chưa xác nhận thời gian, tần suất, khoản sai hay khả năng xuất file. CSV/bảng tính là baseline phù hợp.

**Pilot nhỏ nhất:** Một người tình nguyện ghi 2 tuần, tối thiểu 4 phiên; chỉ lưu file cục bộ, không chia sẻ dữ liệu giao dịch. Ghi phút, nguồn, cash, điểm nạp/điểm dùng, khoản thiếu/trùng và kết quả đối chiếu. Không xây phần mềm.

**Cần kiểm chứng trước khi Go:** 2/3 người được hỏi thực sự tổng kết từ nhiều nguồn định kỳ; kể được lần gần nhất; dữ liệu có thể đối chiếu; pilot giảm thời gian mà không tăng lỗi.

**Ngưỡng dừng:** Sau 4 phiên, nếu thời gian giảm dưới 20%, không thể đối chiếu cash/điểm, hoặc có khoản thiếu/trùng không được phát hiện, dừng tự động hóa và quay lại rà từng nguồn. Chỉ xem Workflow AI sau khi rule được thử và có chấp thuận về dữ liệu.

---

## 9. Hạn chế và hướng tiếp theo

- Candidate/điểm số là tổng hợp từ hai hồ sơ, chưa phải quyết định nhóm đã họp và thống nhất.
- Chưa có phỏng vấn, survey, diary, baseline hay tín hiệu phản bác trực tiếp.
- Nhóm cần pitch/ghi câu hỏi phản biện, xác nhận phân công trong `TEAM.md`, phỏng vấn 2–3 người và chạy diary trước khi chốt.
- Nếu pitch thật chọn kế hoạch đi lại hoặc vấn đề khác, phải cập nhật OST, process, research và Problem Statement theo lựa chọn đó.

## 10. Tài liệu tham khảo

- [Google Sheets Help — nhập dữ liệu](https://support.google.com/docs/answer/12236443?hl=en)
- [Splitwise Help — cách sử dụng](https://kb.splitwise.com/getting-started/how-do-i-use-splitwise)
- [Splitwise Pro — transaction import và tính năng](https://www.splitwise.com/pro)
- [Báo cáo cá nhân — Bùi Thị Huyền Tâm](../individual/2A202603917_Bùi%20Thị%20Huyền%20Tâm.md)
- [Báo cáo cá nhân — Lương Đức Anh](../individual/2A202603931_Luong%20Duc%20Anh.md)
- [docs/01-worksheet.md](../../docs/01-worksheet.md)
- [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md)
