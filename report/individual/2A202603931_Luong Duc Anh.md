# Báo cáo cá nhân

## 1. Thông tin học viên

- Họ tên: Luong Duc Anh
- MSSV: 2A202603931
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm:
- Link repo nhóm:

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi lịch học và lịch cá nhân đã kín, tôi muốn nhìn ra việc nào có thể dời hoặc bỏ, để xếp thêm việc mà không làm vỡ cả tuần. | Tôi | Lịch có các buổi học lệch giờ; chưa đo chính xác thời gian bị mất khi đổi lịch. |
| 2 | Lặp lại | Khi muốn biết tháng này tiền đi đâu, tôi muốn gom giao dịch từ các nguồn mình dùng, để thấy được khoản nào đang chi nhiều. | Tôi | Có ít nhất 4 ứng dụng thanh toán/ngân hàng; tiền mặt ăn trưa, điểm nạp trước trong app xe buýt/đi xe và hóa đơn điện thoại không nằm chung một chỗ. |
| 3 | Tốn thời gian | Khi vừa nghe nhiều việc cần nhớ hoặc đang trên đường ra khỏi nhà, tôi muốn ghi nhanh bằng giọng nói, để không quên mất việc sau vài phút. | Tôi | Ý định thường đến bất chợt; chưa có số lần quên được ghi lại. |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi mở trình duyệt và thấy nhiều tab truyện tranh hoặc tin tức muốn đọc, tôi muốn gom chúng thành từng hàng đợi, để theo dõi từng nhóm theo nhịp của mình. | Tôi | Có nhiều tab rời rạc; có thể bỏ quên nội dung nếu không mở lại ngay. |
| 5 | Lặp lại | Khi nảy ra một ý tưởng giữa lúc làm việc khác, tôi muốn lưu nó trong vài giây, để còn tìm lại được sau đó. | Tôi | Ý tưởng dễ biến mất khi chuyển sang việc khác; chưa có thói quen ghi đều. |
| 6 | Tốn thời gian | Khi có việc mới cần chen vào lịch, tôi muốn biết nó cần diễn ra lúc nào và kéo dài bao lâu, để quyết định dời việc nào thay vì chỉ cố nhét thêm. | Tôi và người hẹn cùng tôi | Lịch có nhiều khung giờ rời; tác động dây chuyền khi đổi lịch chưa được theo dõi. |
| 7 | Cần đọc, tổng hợp nhiều thông tin | Khi muốn xem lại chi tiêu, tôi muốn đổi điểm trả trước trong app và giao dịch ngân hàng thành khoản tiền dễ hiểu, để so được với tiền mặt đã tiêu. | Tôi | Điểm ứng dụng không hiện như giao dịch ngân hàng; tiền mặt không có lịch sử tự động. |
| 8 | Lặp lại | Khi có nhiều việc lặt vặt cần theo dõi, tôi muốn gom chúng theo nhóm và trạng thái, để không phải nhớ chúng đang nằm ở tab hay ứng dụng nào. | Tôi | Dùng nhiều tab và app; chưa có một nơi ghi danh sách thống nhất. |

**Nếu có dùng AI để gợi ý thêm:** Tôi giữ các ý về lịch bị xô lệch, gom dòng tiền từ nhiều nguồn, ghi nhanh bằng giọng nói, và chia hàng đợi đọc theo đúng những chuyện tôi gặp. Các ý này cần kiểm tra bằng cách ghi lại thời gian, số lần và khoản chi thực tế; hiện chưa có baseline.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Theo dõi tiền qua nhiều nguồn | Có ít nhất 4 app cộng với tiền mặt và hóa đơn; các khoản hiện nằm rải rác, có quy trình cuối kỳ để dựng lại. | App nào xuất được lịch sử, và tôi có duy trì ghi tiền mặt không? |
| 2 | Gom tab truyện và tin thành hàng đợi | Đây là nội dung tôi muốn theo dõi lâu dài; hàng đợi có ý nghĩa hơn là dọn tab cho sạch. | Bao nhiêu tab thực sự là nội dung muốn theo dõi, và queue nào hợp? |
| 3 | Ghi nhanh việc và ý tưởng trước khi quên | Tôi nêu rõ khoảnh khắc quên ngay sau khi rời nhà/chuyển việc; quy trình có thể thử bằng ghi âm hoặc ghi chú nhanh. | Việc cần ghi thường là task hay ý tưởng? Tần suất quên và cách tìm lại chưa rõ. |

### Problem Card #1 — Theo dõi tiền qua nhiều nguồn

| Trường | Nội dung |
|---|---|
| Job Story | Khi muốn biết tháng này tiền đi đâu, tôi muốn gom các khoản ngân hàng, app trả trước và tiền mặt, để nhìn được chi tiêu gần với thực tế hơn. |
| Actor | Tôi |
| Thời điểm / bối cảnh | Cuối ngày hoặc lúc muốn xem lại chi tiêu; tiền ăn trưa có thể trả cash, đi xe bằng app/điểm nạp trước, ngoài ra còn giao dịch ngân hàng và hóa đơn điện thoại. |
| Quy trình hiện tại (3–7 bước) | Trả tiền bằng nguồn tiện nhất → lịch sử nằm ở app riêng hoặc không có (cash) → nạp thêm điểm khi hết → trả hóa đơn điện thoại → muốn tổng kết thì phải nhớ/mở nhiều nguồn. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Dựng lại các khoản tiền mặt và điểm đã dùng; chưa bấm giờ nên cần ghi nhận trong một tuần. |
| Impact (nếu không giải thì sao) | Tổng chi thiếu khoản và khó biết tiền thực sự đi vào đâu. |
| Success metric (baseline → target) | Trong 2 tuần ghi số ngày có theo dõi và giao dịch bỏ sót; thử đạt ít nhất 5/7 ngày mỗi tuần, đồng thời đối chiếu tổng tiền nạp/chi ở từng nguồn. |
| Phương án không dùng AI | Một bảng ghi ngày, số tiền, nguồn và loại chi; nhập cash ngay sau khi mua, điểm nạp ghi riêng để tránh tính trùng với lúc tiêu. |
| Giả thuyết về AI (nếu có) | Có thể phân loại mô tả giao dịch và gợi ý khoản chưa rõ; không tự quy đổi điểm thành tiền nếu thiếu tỷ lệ hoặc tính nạp tiền hai lần. |
| Cảm nhận nhanh | Rule / Workflow |

Quy trình nháp hiện tại:

```text
Trả bằng cash/ngân hàng/app → lịch sử nằm rải rác hoặc không có → cuối kỳ nhớ/mở từng nguồn → cộng và phân loại thủ công → tổng bị thiếu khoản khó nhớ
```

### Problem Card #2 — Hàng đợi cho tab truyện và tin tức

| Trường | Nội dung |
|---|---|
| Job Story | Khi gặp truyện tranh hoặc tin muốn theo dõi nhưng chưa đọc ngay, tôi muốn lưu vào hàng đợi riêng, để có thể đọc một queue rồi nghỉ lâu mà vẫn biết queue khác còn gì. |
| Actor | Tôi |
| Thời điểm / bối cảnh | Đang lướt web, thấy bài/truyện đáng đọc nhưng phải quay lại việc khác. |
| Quy trình hiện tại (3–7 bước) | Mở trang muốn đọc → để thành tab → tiếp tục mở tab khác → tab truyện lẫn với tin và việc đang làm → tìm lại thủ công → đọc vài cái, phần còn lại nằm đó. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Tìm nội dung muốn đọc và nhớ mình đang theo dõi đến đâu; chưa đo thời gian hay số tab. |
| Impact (nếu không giải thì sao) | Nội dung mình chủ động muốn theo dõi bị lẫn vào đống tab và dễ quên; tab mở cũng làm rối lúc dùng máy. |
| Success metric (baseline → target) | Đếm số tab liên quan và thời gian tìm một bài trước khi thử; sau 2 tuần, tìm được bài cần đọc trong dưới 1 phút và biết queue nào đang đọc dở. |
| Phương án không dùng AI | Bookmark/đọc sau theo các queue “Truyện” và “Tin”, có trạng thái đang đọc/để sau. |
| Giả thuyết về AI (nếu có) | Có thể gợi ý phân loại theo loại trang hoặc tóm tắt để chọn bài; việc lưu và đánh dấu tiến độ nên vẫn đơn giản, tôi xác nhận phân loại. |
| Cảm nhận nhanh | Rule / Workflow |

Quy trình nháp hiện tại:

```text
Gặp nội dung muốn theo dõi → mở tab → tab dồn lên → tìm lại giữa tab → đọc một phần → quên các tab còn lại
```

### Problem Card #3 — Ghi nhanh việc và ý tưởng trước khi quên

| Trường | Nội dung |
|---|---|
| Job Story | Khi có việc cần nhớ hoặc ý tưởng bất chợt lúc đang làm việc khác/chuẩn bị ra khỏi nhà, tôi muốn lưu nó thật nhanh, để không quên ngay khi chuyển sang chuyện khác. |
| Actor | Tôi |
| Thời điểm / bối cảnh | Ý nghĩ xuất hiện giữa lúc đang đi hoặc đang tập trung vào việc khác; thường không tiện mở app rồi điền nhiều trường. |
| Quy trình hiện tại (3–7 bước) | Nghĩ ra việc/ý tưởng → tự nhủ sẽ nhớ → chuyển hoạt động hoặc ra khỏi nhà → quên mất → đôi khi nhớ lại muộn nhưng thiếu chi tiết. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bắt và lưu ý nghĩ ngay lúc nó xuất hiện; hiện chưa có bước ghi ổn định hay số lần quên được thống kê. |
| Impact (nếu không giải thì sao) | Việc nhỏ có thể bị lỡ; ý tưởng biến mất trước khi kịp xem lại. |
| Success metric (baseline → target) | Trong 1 tuần ghi số ý nghĩ cần lưu và số ý quên; thử nghiệm mục tiêu là lưu được 8/10 ý trong dưới 15 giây, rồi tìm lại cuối ngày. |
| Phương án không dùng AI | Widget ghi chú/voice memo một chạm, rồi dành 5 phút cuối ngày chuyển các ghi âm thành việc hoặc ý tưởng. |
| Giả thuyết về AI (nếu có) | Nhận giọng nói thành chữ và trích việc/tên/ngày có thể giảm bước lưu; phải hỏi lại khi câu nghe không rõ và không tự tạo deadline. |
| Cảm nhận nhanh | Workflow (ghi/phiên âm); có thể No AI nếu một chạm là đủ |

Quy trình nháp hiện tại:

```text
Nảy ra việc/ý tưởng → định nhớ trong đầu → chuyển sang việc khác/ra khỏi nhà → quên hoặc nhớ thiếu → không có gì để xem lại
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: Nhiều nguồn tiền và cash làm tổng chi khó thấy; muốn kiểm tra trước liệu việc ghi thủ công có bền hơn việc cố kéo dữ liệu từ mọi app không.
- Câu hỏi muốn nhóm phản biện: Điểm app nên tính lúc nạp hay lúc tiêu để không đếm hai lần?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Chưa có baseline về số giao dịch bị sót, thời gian tổng kết, số tab hay số lần quên. | Có | Để metric ở dạng thử nghiệm và ghi rõ cần lấy baseline trước khi khẳng định mức độ pain. |
| “Làm app/AI” là giải pháp sớm; bảng chi tiêu, bookmark queue hoặc voice memo một chạm có thể đủ. | Có | Thêm phương án không AI cho từng card; AI chỉ là giả thuyết cho phân loại/phiên âm, không phải mặc định. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
