# Báo cáo cá nhân — 2A202603495_HoangMinhHuy

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Hoàng Minh Huy
- MSSV: 2A202603495
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: 7A
- Link repo nhóm: https://github.com/ThanhBinh101/K5-L3-Day02-NguyenThiThanhBinh-2A202603497-DiscoveryProblemFraming/tree/HoangMinhHuy-2A202603495

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

Danh sách dưới đây được viết lại từ 10 chủ đề và số liệu/đích mục tiêu bạn cung cấp. Các số liệu ngành và mục tiêu này chưa kèm nguồn để kiểm tra, nên chỉ ghi nhận là thông tin tham khảo chưa xác minh; chúng không chứng minh trải nghiệm cá nhân hay người dùng mục tiêu gặp vấn đề. Cần kiểm chứng pain, actor và baseline riêng trước khi pitch.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại / Pain từ người khác | Khi phát sinh giao dịch thẻ mà tôi không thực hiện, tôi muốn được cảnh báo và biết cách xử lý kịp thời, để hạn chế thiệt hại tài chính | Chủ thẻ tín dụng và đơn vị phát hành thẻ | Thiệt hại ngành >30 tỷ USD/năm, tỷ lệ gian lận 0.05%–0.1%; mục tiêu tham khảo: false positive <10%, chặn >90%. Chưa có nguồn đi kèm/xác minh; cần tìm hiểu hành trình báo giao dịch lạ, không thu thập thông tin thẻ. |
| 2 | Pain từ người khác | Khi có dấu hiệu sức khỏe đáng lo ngại, tôi muốn biết khi nào cần tìm hỗ trợ y tế, để không bỏ qua nguy cơ nghiêm trọng | Người có nguy cơ sức khỏe và nhân viên y tế | Số liệu bạn cung cấp: 15 triệu ca đột quỵ/năm; mục tiêu tham khảo: độ chính xác dự đoán 85%–90%. Chưa có nguồn/định nghĩa metric; cần chuyên gia y tế, không tự chẩn đoán hoặc khuyến nghị điều trị. |
| 3 | Lặp lại / Tốn thời gian | Khi cần hỗ trợ về sản phẩm hoặc dịch vụ, tôi muốn nhận được câu trả lời chính xác mà không phải chờ lâu hoặc lặp lại thông tin, để giải quyết được yêu cầu | Khách hàng và nhân viên chăm sóc khách hàng | Số liệu bạn cung cấp: >3 triệu truy vấn, >500.000 người dùng, phản hồi <0.4 giây; mục tiêu là giảm tải/chi phí. Chưa có nguồn/xác minh và chưa rõ ngữ cảnh; cần đo thời gian chờ và tỷ lệ liên hệ lại ở đối tượng cụ thể. |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi tìm sản phẩm trong cửa hàng trực tuyến, tôi muốn nhanh chóng thấy các lựa chọn phù hợp với nhu cầu của mình, để không mất thời gian lọc quá nhiều kết quả | Người mua sắm trực tuyến | Số liệu bạn cung cấp: recommendation đóng góp 35% doanh thu Amazon/Netflix, mục tiêu tăng conversion 20%–30%. Chưa có nguồn/xác minh và mẫu số cho mức tăng; cần quan sát phiên tìm kiếm thực tế. |
| 5 | Lặp lại / Tốn thời gian | Khi chăm sóc cây trồng trên ruộng, tôi muốn phát hiện khu vực có cỏ dại hoặc cây trồng gặp vấn đề, để sử dụng nguồn lực đúng nơi và bảo vệ cây trồng | Nông dân và người vận hành trang trại | Mô tả bạn cung cấp nêu nhận diện cỏ dại bằng thị giác máy tính và mục tiêu giảm thuốc tới 90%; chưa có nguồn/xác minh điều kiện áp dụng. Cần phỏng vấn người làm nông, xem quy trình và tuân thủ an toàn thuốc. |
| 6 | Lặp lại / Pain từ người khác | Khi học ngoại ngữ trực tuyến, tôi muốn nội dung và nhịp học phù hợp với trình độ và tiến độ của mình, để tiếp tục học và hoàn thành mục tiêu | Người học ngoại ngữ trực tuyến | Mục tiêu bạn cung cấp: tăng tỷ lệ hoàn thành 1.5–2 lần; chưa có nguồn, baseline hay định nghĩa “hoàn thành”. Hỏi người học về khóa gần nhất đã bỏ dở và kiểm tra tiến độ nếu họ đồng ý. |
| 7 | Pain từ người khác / Cần đọc, tổng hợp nhiều thông tin | Khi thấy nội dung có dấu hiệu thù ghét, quấy rối hoặc khuyến khích bạo lực, tôi muốn biết cách báo cáo và được bảo vệ khỏi nội dung đó, để sử dụng nền tảng an toàn hơn | Người dùng và người kiểm duyệt nền tảng | Mục tiêu bạn cung cấp: tự động xử lý >95% vi phạm trước khi user report; chưa có nguồn/định nghĩa vi phạm và độ chính xác. Cần xem quy trình báo cáo và rủi ro gắn nhãn sai; không tự động kết luận về người dùng. |
| 8 | Tốn thời gian / Lặp lại | Khi cần giao hoặc nhận hàng trong giờ cao điểm, tôi muốn biết thời gian đến dự kiến đáng tin cậy, để sắp xếp giao nhận và giảm trễ hẹn | Người gửi, người nhận và đơn vị giao hàng | Mục tiêu bạn cung cấp: giảm nhiên liệu 15%–20%, thời gian giao 25%; chưa có nguồn, baseline hay điều kiện đo. Cần ghi thời gian dự kiến so với thực tế trên nhiều chuyến. |
| 9 | Lặp lại / Tốn thời gian | Khi sử dụng điện trong nhà hoặc tòa nhà, tôi muốn nhận biết mức tiêu thụ bất thường và thiết bị có thể đang hoạt động không cần thiết, để giảm lãng phí và tránh gián đoạn | Hộ gia đình hoặc đơn vị vận hành tòa nhà | Mục tiêu bạn cung cấp: giảm dừng máy ngoài kế hoạch 30%–50%, chi phí điện 10%–15%; chưa có nguồn, baseline hay phạm vi đo. Cần ghi dữ liệu tiêu thụ và xác minh tình trạng cảm biến. |
| 10 | Cần đọc, tổng hợp nhiều thông tin / Pain từ người khác | Khi tiếp nhận một tin tức hoặc video gây tranh cãi, tôi muốn kiểm tra nguồn và dấu hiệu chỉnh sửa, để quyết định có nên tin hoặc chia sẻ hay không | Người đọc tin tức và người dùng mạng xã hội | Mục tiêu bạn cung cấp: độ chính xác nhận diện 88%–96%; chưa có nguồn, bộ dữ liệu hay định nghĩa accuracy. Cần kiểm tra cách người dùng xác minh nội dung; công cụ phát hiện không phải kết luận chắc chắn. |

**Nếu có dùng AI để gợi ý thêm:** danh sách 10 chủ đề và số liệu do tôi cung cấp; số liệu ngành/mục tiêu chưa được kiểm chứng nên không dùng thay cho bằng chứng người dùng. Tôi chưa loại candidate nào ở CP1; cần xác nhận actor, trải nghiệm và baseline trước khi chốt.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

Đây là shortlist tạm để chuẩn bị pitch, chưa phải kết luận dựa trên nghiên cứu. Thời lượng trong các sơ đồ cần được đo thực tế; không nên để dấu `___` trong bản nộp cuối.

| Rank | Ý tưởng CP1 được chọn | Problem thu hẹp thành card | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|---|
| 1 | CP1 #6 — Học ngoại ngữ trực tuyến | Khó duy trì việc học khi nội dung hoặc nhịp học chưa phù hợp với trình độ và tiến độ | Có thể hỏi người học về một khóa học cụ thể và các sự kiện đã xảy ra; tiến độ có thể kiểm tra nếu họ đồng ý | Chưa rõ nguyên nhân chậm/bỏ học có liên quan đến nội dung, thời gian, độ khó hay yếu tố khác; chưa có bằng chứng về nguyên nhân |
| 2 | CP1 #9 — Tiêu thụ điện trong nhà/tòa nhà | Khó xác định thiết bị hoặc thời điểm góp phần vào mức tiêu thụ bất thường | Có thể ghi chỉ số công tơ và quan sát thiết bị nếu có quyền tiếp cận dữ liệu | Chưa rõ có dữ liệu đủ chi tiết để liên hệ mức tiêu thụ với thiết bị cụ thể |
| 3 | CP1 #10 — Xác minh tin tức/video | Khó kiểm tra nguồn và ngữ cảnh của tin tức/video trước khi quyết định tin hoặc chia sẻ | Có thể quan sát một tác vụ kiểm chứng nội dung công khai mà không cần thu dữ liệu nhạy cảm | Chưa rõ tần suất gặp vấn đề và cách người dùng hiện xác minh nội dung |

Ba Problem Card bên dưới được chọn và thu hẹp trực tiếp từ các ý CP1 #6, #9 và #10. Các câu hỏi phản biện đặt cho card của thành viên khác thuộc CP3, không phải đầu vào hay nội dung của CP2.

### Problem Card #1 — từ CP1 #6: Học ngoại ngữ trực tuyến

| Trường | Nội dung |
|---|---|
| Job Story | Khi học ngoại ngữ trực tuyến và thấy nội dung hoặc nhịp học không còn phù hợp với trình độ/tiến độ của mình, tôi muốn xác định phần học tiếp theo phù hợp, để tiếp tục hướng tới mục tiêu học tập |
| Actor | Người học ngoại ngữ trực tuyến |
| Thời điểm / bối cảnh | Khi đang theo một khóa học nhưng nhận thấy tiến độ hoặc độ khó không phù hợp; cần hỏi người học về một lần cụ thể |
| Quy trình hiện tại (3–7 bước) | 1. Chọn khóa học 2. Học theo nội dung và nhịp có sẵn 3. Gặp nội dung quá dễ/khó hoặc chậm tiến độ (cần kiểm chứng) 4. Tự tìm phần học phù hợp tiếp theo 5. Tiếp tục, đổi nhịp học hoặc tạm dừng |
| Bottleneck (bước nào, mất bao nhiêu phút) | Giả thuyết: khó chọn nội dung/nhịp học phù hợp sau khi tiến độ thay đổi; chưa có số đo thời gian hay tần suất |
| Impact (nếu không giải thì sao) | Người học có thể khó duy trì tiến độ hoặc đạt mục tiêu; chưa khẳng định đây là nguyên nhân khiến họ bỏ học |
| Success metric (baseline → target) | Baseline chưa có. Có thể đo số buổi hoàn thành và số lần người học phải tự tìm/đổi nội dung trong một khoảng theo dõi thống nhất; chốt target sau khi có baseline |
| Phương án không dùng AI | Cho phép chọn mục tiêu, mức độ và nhịp học; chia nội dung thành phần nhỏ và để người học tự điều chỉnh lịch |
| Giả thuyết về AI (nếu có) | Chưa có căn cứ cần AI; trước tiên cần xác minh nhu cầu và xem điều chỉnh nội dung/nhịp học bằng lựa chọn có sẵn có đủ không |
| Cảm nhận nhanh | Chưa biết; so sánh No AI/Rule trước |

Quy trình nháp hiện tại:

```text
[Chọn khóa học và mục tiêu: ghi theo tác vụ thực tế]
→ [Học theo nội dung/nhịp hiện có]
→ [Ghi nhận khi nội dung hoặc tiến độ không phù hợp (cần hỏi/quan sát)]
→ [Tìm/chọn phần học tiếp theo: bấm giờ khi kiểm chứng; bottleneck giả thuyết]
→ [Tiếp tục, điều chỉnh nhịp hoặc tạm dừng: ghi kết quả]
```

### Problem Card #2 — từ CP1 #9: Tiêu thụ điện trong nhà/tòa nhà

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận thấy mức tiêu thụ điện trong nhà/tòa nhà bất thường, tôi muốn xác định thiết bị hoặc thời điểm có liên quan, để cân nhắc cách giảm lãng phí |
| Actor | Người trong hộ gia đình hoặc người vận hành tòa nhà có thể xem dữ liệu điện |
| Thời điểm / bối cảnh | Khi hóa đơn tăng hoặc khi rà soát mức tiêu thụ định kỳ |
| Quy trình hiện tại (3–7 bước) | 1. Nhận hóa đơn/xem công tơ 2. So sánh mức dùng với kỳ trước 3. Kiểm tra các thiết bị đang hoạt động 4. Đoán nguyên nhân 5. Thay đổi cách sử dụng 6. So sánh mức tiêu thụ kỳ sau |
| Bottleneck (bước nào, mất bao nhiêu phút) | Giả thuyết: khó quy mức tiêu thụ tổng về thiết bị/thời điểm cụ thể; dữ liệu hiện có và thời gian phân tích cần xác minh |
| Impact (nếu không giải thì sao) | Có thể tiếp tục lãng phí điện hoặc không phát hiện sự cố; cần đo mức tiêu thụ thực tế trước khi khẳng định ảnh hưởng |
| Success metric (baseline → target) | Baseline: kWh theo kỳ và thời gian kiểm tra, chưa thu thập. Target xác định sau khi có baseline; theo dõi kWh ở cùng kỳ và các thay đổi đã thực hiện |
| Phương án không dùng AI | Ghi chỉ số công tơ định kỳ, kiểm tra thiết bị và dùng bảng tính so sánh kỳ |
| Giả thuyết về AI (nếu có) | Có thể cần phân tích chuỗi dữ liệu nếu dữ liệu đủ chi tiết, nhưng trước tiên cần xác minh dữ liệu và xem so sánh thủ công có đủ không |
| Cảm nhận nhanh | Chưa biết; No AI/Rule có thể đủ |

Quy trình nháp hiện tại:

```text
[Nhận hóa đơn/xem công tơ: ___ phút]
→ [So sánh kỳ tiêu thụ: ___ phút]
→ [Kiểm tra thiết bị đang dùng: ___ phút]
→ [Tìm nguyên nhân mức tăng: ___ phút; bottleneck giả thuyết]
→ [Thử thay đổi cách sử dụng]
→ [So sánh chỉ số kỳ tiếp theo]
```

### Problem Card #3 — từ CP1 #10: Xác minh tin tức/video

| Trường | Nội dung |
|---|---|
| Job Story | Khi thấy một tin hoặc video chưa rõ nguồn gốc, tôi muốn kiểm tra các dấu hiệu và đối chiếu nguồn đáng tin, để quyết định có nên tin hoặc chia sẻ hay không |
| Actor | Người đọc tin tức hoặc người dùng mạng xã hội |
| Thời điểm / bối cảnh | Khi tiếp xúc với nội dung gây tranh cãi, đáng ngờ hoặc lan truyền nhanh |
| Quy trình hiện tại (3–7 bước) | 1. Nhận/xem nội dung 2. Xem nguồn đăng và ngữ cảnh 3. Tìm nguồn độc lập để đối chiếu 4. Cân nhắc độ tin cậy 5. Quyết định không chia sẻ, chia sẻ có cảnh báo hoặc báo cáo |
| Bottleneck (bước nào, mất bao nhiêu phút) | Giả thuyết: khó tìm nguồn độc lập và xác định ngữ cảnh; thời gian và tần suất cần đo bằng quan sát một tác vụ kiểm chứng |
| Impact (nếu không giải thì sao) | Có thể tin hoặc lan truyền nội dung sai; mức ảnh hưởng tùy nội dung, cần tránh kết luận chỉ dựa trên một công cụ phát hiện |
| Success metric (baseline → target) | Baseline: thời gian kiểm chứng và số bước hoàn tất, chưa đo. Target đặt sau baseline; đo tác vụ kiểm chứng mẫu công khai và ghi nguồn người tham gia sử dụng |
| Phương án không dùng AI | Kiểm tra nguồn gốc, ngày đăng, ngữ cảnh và đối chiếu với nhiều nguồn đáng tin cậy |
| Giả thuyết về AI (nếu có) | Công cụ phân tích có thể hỗ trợ chỉ ra dấu hiệu cần kiểm tra, nhưng không nên tự kết luận nội dung là thật/giả |
| Cảm nhận nhanh | Chưa biết; ưu tiên quy trình kiểm chứng có người quyết định |

Quy trình nháp hiện tại:

```text
[Nhận/xem nội dung: ___ phút]
→ [Kiểm tra nguồn đăng và ngữ cảnh: ___ phút]
→ [Tìm nguồn độc lập để đối chiếu: ___ phút; bottleneck giả thuyết]
→ [Đánh giá mức độ tin cậy: ___ phút]
→ [Quyết định có chia sẻ/báo cáo hay không]
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: phát triển trực tiếp từ CP1 #6 và có thể hỏi người học về một tình huống học cụ thể. Chưa có bằng chứng xác nhận nội dung/nhịp học là nguyên nhân khiến họ chậm tiến độ.
- Câu hỏi muốn nhóm phản biện: “Bằng chứng nào cho thấy nội dung hoặc nhịp học chưa phù hợp là trở ngại, thay vì thiếu thời gian, thay đổi mục tiêu hoặc nguyên nhân khác?”

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Ý tưởng CP1 về học ngoại ngữ còn rộng, chưa nêu tình huống cụ thể | Đồng ý | Thu hẹp thành tình huống người học nhận thấy nội dung/nhịp học không phù hợp và cần chọn bước học tiếp theo |
| Chưa có dữ liệu thực tế để khẳng định nội dung/nhịp học là trở ngại hoặc nguyên nhân tạm dừng | Đồng ý | Ghi đây là giả thuyết, cần hỏi người học về một trải nghiệm cụ thể; không kết luận họ bỏ học vì thiếu động lực |
| Chưa chứng minh AI cần thiết | Đồng ý | Đề xuất thử lịch học cố định/chia nhỏ nội dung trước và để mức can thiệp là “Chưa biết” |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

Đối chiếu với [báo cáo nhóm, mục 2–8](https://github.com/ThanhBinh101/K5-L3-Day02-NguyenThiThanhBinh-2A202603497-DiscoveryProblemFraming/blob/main/report/team/group_report.md). Bảng dưới đây chỉ ghi phần báo cáo nhóm có bằng chứng gắn với tôi; sản phẩm CP4–CP6 là đầu ra chung, không tự suy diễn thành phần việc cá nhân.

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| CP3 — Pitch candidate | Báo cáo nhóm ghi nhận tôi pitch ba candidate: hỗ trợ sản phẩm/dịch vụ, tìm sản phẩm trực tuyến và học ngoại ngữ trực tuyến. | Bảng pitch nhóm có các candidate #4–#6 mang tên tôi. **Cần đối chiếu lại với CP2 hiện tại:** top 3 cá nhân đã được sửa thành CP1 #6 (học ngoại ngữ), #9 (tiêu thụ điện), #10 (xác minh tin tức/video), nên candidate pitch trong báo cáo nhóm chưa khớp hoàn toàn với CP2 mới nhất. |
| CP3 — Câu hỏi phản biện tôi đặt | Tôi hỏi về an toàn khi đánh giá lỗi xe VinFast (#1), việc nên tách nhu cầu tìm WC và mua nước cùng độ tin cậy của dữ liệu tiện ích (#8), và khả năng xử lý lỗi thiếu thư viện Python bằng hướng dẫn/quy tắc trước khi dùng AI (#11). | Ba câu hỏi được ghi tên tôi trong bảng pitch nhóm; giúp làm rõ boundary an toàn, phạm vi problem và liệu giải pháp đơn giản hơn AI có đủ không. |
| CP3 — Phản biện tôi nhận | Với candidate hỗ trợ khách hàng, Thanh Bình hỏi loại yêu cầu/kênh cụ thể và căn cứ xác định giải quyết ngay lần đầu. Với candidate tìm sản phẩm, Long Nhật hỏi cách cân bằng giảm số lần lọc với việc vẫn tìm được sản phẩm đạt tiêu chí. | Hai câu hỏi phản biện này được ghi trong bảng pitch nhóm. Báo cáo cá nhân chưa ghi lại câu trả lời hay thay đổi nào sau phản biện; chỉ bổ sung nếu có thực tế. |
| CP3 — Shortlist và chấm điểm | Báo cáo nhóm có ghi candidate hỗ trợ khách hàng của tôi trong bảng chấm shortlist: 4 (actor rõ), 4 (quy trình rõ), 1 (pain có bằng chứng), 2 (impact đo được), 4 (vừa sức lab), 4 (so sánh mức can thiệp), 2 (hiểu domain), tổng 21. | Đây là điểm số đang có trong báo cáo nhóm; cần xác nhận đó là điểm tôi tự chấm hay điểm thảo luận chung. Chưa ghi nhận candidate cuối cùng được nhóm chọn. |
| CP4 — Kiểm chứng và research | Báo cáo nhóm chuyển candidate chính sang bài đối chiếu tình trạng 12 máy của Nhật. CP4 có rà soát 5 ca mô phỏng, nêu rõ chưa có phỏng vấn, survey hay baseline thực tế; research hai phương án Google Sheets và Snipe-IT. | Đây là nội dung sản phẩm nhóm. Báo cáo nhóm không ghi rõ tôi phụ trách thu thập dữ liệu, phỏng vấn hay research phần nào; vì vậy chưa ghi nhận đây là đóng góp cá nhân của tôi. |
| CP5 — Quy trình và Problem Statement v0 | Báo cáo nhóm mô tả quy trình 5 bước của ca kiểm 12 máy, nêu bước đối chiếu mã máy là bottleneck trong dữ liệu mô phỏng; đề xuất bảng bàn giao chuẩn và Rule lọc lỗi còn mở, có người trực xác minh ngoại lệ. | Đây là nội dung chung của báo cáo nhóm, baseline ca thật vẫn chưa đo. Chưa có phân công hoặc ghi nhận cụ thể cho thấy tôi là người lập quy trình hay viết Problem Statement v0. |
| CP6 — Mức can thiệp, v1 và quyết định | Báo cáo nhóm đề xuất mức Rule, giữ người trực xác minh và đặt điều kiện đánh giá tốc độ cùng chất lượng; quyết định/đề xuất còn chờ nhóm xác nhận. | Đây là nội dung chung. Báo cáo nhóm chưa ghi tôi phụ trách AI Canvas, tiêu chí đánh giá, phân tích rủi ro hay quyết định; không ghi các phần này là đóng góp cá nhân của tôi. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Gợi ý thêm vài problem và kiểm tra xem mỗi issue có đủ “đau” và có actor rõ không. | AI giúp tôi phát hiện các pattern mà mình chưa nghĩ tới, ví dụ “tìm thông tin cũ trong chat” hoặc “tổng hợp feedback”. | AI dễ đưa ra ý quá rộng, ví dụ “trợ lý AI cho sinh viên”, chưa đủ rõ bottleneck và thực tế. | Tôi loại những ý quá chung và giữ lại các cái có quy trình thật. |
| CP2 Problem Card | Gợi ý cách viết card rõ hơn, cập nhật bottleneck và success metric. | AI hữu ích trong việc chốt lại cách diễn đạt ngắn gọn nhưng đủ nội dung. | AI thường đưa ra câu văn mơ hồ hoặc nêu giải pháp sớm, không ép rõ actor/quy trình. | Tôi chỉnh lại thành câu rõ hơn, chắc chắn nhất là “bước xác minh rubric với file cũ” là bottleneck. |
| CP4 Research | Tìm hiểu cách hỏi kiểm chứng theo The Mom Test, và cách phân biệt problem thật với feedback xã hội. | Giúp tôi hình dung cách hỏi đúng kiểu, tránh hỏi “bạn có muốn dùng AI không?”. | AI không thể thay thế câu hỏi thực tế của người thật, nên chỉ là gợi ý cấu trúc. | Tôi vẫn cần dùng quy tắc: hỏi về đời sống và sự kiện thực tế đã xảy ra. |
| CP5 Quy trình | Dùng để kiểm tra xem quy trình tương lai có chia đủ bước rule / AI / người kiểm tra không. | Hữu ích khi mong muốn tránh “gom quá nhiều bước vào một” và làm đối tượng rõ ràng. | AI hay hợp nhất quá nhiều bước thành một, làm mất bottleneck ban đầu. | Tôi tách lại từng bước và giữ rõ ranh giới: AI không tự gửi, không tự sửa, không quyết định mà không có người xem xét. |
| CP5–6 Problem Statement | Gợi ý cách viết 6 trường và cách đối chiếu với success metric và boundary. | Giúp tôi đảm bảo không nhầm boundary với giải pháp. | AI dễ viết kiểu chung chung, không có sự cụ thể hóa theo bài toán nhóm. | Tôi bổ sung ví dụ thực tế và ràng buộc theo vấn đề mình đã chọn. |
| CP6 Mức can thiệp / quyết định | Tìm hiểu sự khác biệt giữa Rule, Workflow và Agent; kiểm tra mức nào phù hợp. | AI rất hữu ích để đặt câu hỏi đúng: “AI sai kiểu nào tệ hơn?” và “nếu AI sai, ai phát hiện?” | AI dễ khiến người dùng “đi thẳng tới Agent” mà không xem xét Rule trước. | Tôi giữ nguyên nguyên tắc: bắt đầu từ mức đơn giản nhất và chỉ lên cao khi cần. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Khi nghe các bài problem của bạn khác, tôi nhận ra điều quan trọng nhất là không phải ai cũng chọn được vấn đề tốt. Một card mạnh khi nó có actor rõ, quy trình thật, bottleneck cụ thể và impact có thể đo được. Tôi học được cách nhìn vào problem không chỉ từ “nó đáng làm” mà còn từ “nó lặp lại hàng tuần và người dùng thực sự đau vì nó”. Cách trình bày của bạn khác giúp tôi hiểu thêm rằng problem có thể xuất phát từ những việc rất nhỏ nhưng lại làm tốn thời gian nhiều hơn dự đoán. Điểm học lớn nhất là cảm giác “điều này rất bình thường” không đồng nghĩa với “điều này không đáng giải quyết”, vì trong thực tế những việc nhỏ lặp đi lặp lại có thể gây tổn thất rất lớn về thời gian và sức lực.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Có, nhóm có lúc bị solution-first khi ai cũng nghĩ ngay đến “phải dùng AI để gợi ý thiếu mục” mà chưa vạch rõ bottleneck. Lúc đầu, tôi và một số bạn dễ mắc vào kiểu suy nghĩ “AI sẽ đọc rubric và báo thiếu điểm thì xong”, nhưng chưa mô tả được quy trình hiện tại thực sự nào đang gây nhọc nhằn. Sau khi bị phản biện, nhóm nhận ra rằng phải xác định rõ actor, sự kiện trong đời sống, và bước nào mất thời gian nhất. Cách xử lý là dừng ngay, quay lại Job Story và Problem Card, và chỉ viết lại giải pháp sau khi đã biết rõ “bottleneck ở đâu, do ai chịu, và vì sao là pain thực”. Điều này giúp nhóm tránh lạc vào “AI cho mọi thứ”.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Có. Ban đầu tôi nghĩ vấn đề “kiểm tra thiếu mục trước deadline” là quá cá nhân và hơi nhỏ. Nhưng khi bị phản biện, tôi nhận ra đây là vấn đề rất thực vì nó xảy ra ở thời điểm deadline, có tác động trực tiếp đến điểm số, và thường là quy trình lặp lại nhiều lần. Tôi đã sửa lại card bằng cách bỏ câu nói quá mơ hồ như “tôi cần quản lý công việc tốt hơn” và thay bằng mô tả rõ: “đọc rubric, so sánh file cũ, tìm phần thiếu, sửa format trước khi nộp”. Sau khi chỉnh, tôi thấy problem rõ hơn rất nhiều, và cả nhóm cũng dễ hiểu hơn. Đó là lần tôi đổi ý vì nhận ra cái “rất nhỏ” vẫn là pain nếu nó xảy ra nhiều lần và có impact rõ.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Có, tôi bị bất ngờ vì cảm giác “đây là việc rất nhỏ” nhưng lại là việc mà nhiều người đều làm lặp lại và đều thấy mệt. Khi kiểm chứng, tôi nhận ra người khác cũng có cùng pattern: họ phải đọc lại rubric, tìm file cũ, lục trên nhiều nguồn, rồi mới biết mình thiếu gì. Điều này làm tôi thấy rõ rằng truyện “pain nhỏ” vẫn có tính hệ thống nếu lặp lại nhiều lần trong một quy trình. Cũng từ đó, tôi biết problem của mình không phải là “nên dùng AI ngay” mà là “cần có một quy trình gọn hơn để kiểm tra điều cơ bản”.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Điều khó nhất là làm cho Problem Statement vừa đủ rõ nhưng không lạc sang giải pháp. Rất dễ bị kéo vào “AI sẽ đọc file, so sánh rubric, báo thiếu mục” ngay trong phần problem. Tôi phải kiểm tra lại nhiều lần để đảm bảo không viết “cần AI”, mà chỉ mô tả: actor, quy trình, bottleneck, impact, boundary và success metric. Khó nhất là xác định boundary: ai làm gì, ai không làm gì, và với metric thì phải nói rõ baseline hiện tại và target muốn đạt. Nếu không đặt rõ boundary, cả bài giải thích sẽ bị mơ hồ và dễ rơi vào lời nói chung.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu làm lại, tôi sẽ tập trung hơn vào việc đo thời gian thật và xác định bottleneck một cách kỹ lưỡng. Tôi sẽ không chấp nhận những problem chỉ “nghe có vẻ đau” mà không có thời gian, tần suất và bằng chứng cụ thể. Tôi cũng sẽ phản biện mạnh hơn ở điểm “đây có phải là problem của cả nhóm hay chỉ của cá nhân tôi?” và “cách đơn giản nhất nếu không dùng AI là gì?” Nếu làm lại, tôi muốn nhóm quan tâm nhiều hơn đến việc thêm bằng chứng thực tế và không vội cài đặt AI. Bởi vì rất dễ bị lạc từ việc tìm đúng pain sang việc nghĩ nên dùng AI như thế nào.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Bài toán của nhóm là tìm cách giảm thời gian và sai sót khi kiểm tra lại bài nộp trước deadline. Quy trình hiện tại là đọc rubric, mở file cũ, so sánh từng phần và tìm thiếu mục, rồi sửa lại format. Metric cần đo là thời gian trung bình mỗi lần kiểm tra và mức độ sai sót trong bài nộp. Boundary là không để AI tự quyết định bài nộp thay người dùng; người dùng vẫn phải review và chỉnh sửa trước khi nộp. Mức can thiệp hợp lý không phải Agent, mà là Rule hoặc Workflow đơn giản: checklist + gợi ý điểm thiếu. Vì problem này có quy trình rõ, lặp lại và ít biên độ đầu ra, nên không cần AI tự hành động. Quyết định cuối cùng là nên dùng rule hoặc workflow, không cần agent, và nếu sau khi thử mà vẫn phải sửa quá nhiều thì quay lại checklist và template chuẩn.

---

## 7. Tài liệu tham khảo

- [README.md](../../README.md)
- [docs/01-worksheet.md](../../docs/01-worksheet.md)
- [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md)
- [RUBRIC.md](../../RUBRIC.md)
- [RULES.md](../../RULES.md)
- [SUBMISSION.md](../../SUBMISSION.md)
