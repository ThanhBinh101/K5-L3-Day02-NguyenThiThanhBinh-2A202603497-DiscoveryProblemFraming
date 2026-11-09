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

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Bỏ dở khóa học ngoại ngữ trực tuyến | Có thể hỏi người học quanh mình về một khóa học đã bỏ dở và lý do cụ thể; tiến độ có thể kiểm tra khi họ đồng ý | Chưa rõ nguyên nhân chính là nội dung, thời gian, độ khó hay thiếu tương tác; cần tìm người học đã từng bỏ dở |
| 2 | Lãng phí điện trong gia đình/tòa nhà | Có thể quan sát thiết bị và thói quen sử dụng, ghi nhận mức tiêu thụ nếu có dữ liệu | Chưa rõ mức tiêu thụ bất thường đến từ thiết bị nào và có dữ liệu đo đủ chi tiết không |
| 3 | Khó xác minh tin giả/deepfake | Có thể khảo sát cách người dùng kiểm tra một nội dung công khai, không cần thu dữ liệu nhạy cảm | Chưa rõ người dùng có thường gặp nội dung khó xác minh và mức độ chính xác của các dấu hiệu họ đang dùng |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi học ngoại ngữ trực tuyến và bắt đầu tụt tiến độ, tôi muốn biết bước học tiếp theo phù hợp với thời gian và trình độ của mình, để tiếp tục học và đạt mục tiêu |
| Actor | Người học ngoại ngữ trực tuyến đã từng chậm tiến độ hoặc bỏ dở khóa học |
| Thời điểm / bối cảnh | Sau vài buổi học đầu hoặc khi người học bỏ lỡ lịch học |
| Quy trình hiện tại (3–7 bước) | 1. Chọn khóa học 2. Bắt đầu học theo nội dung có sẵn 3. Gặp khó khăn hoặc bỏ lỡ buổi học 4. Tự quyết định có học tiếp không 5. Tiếp tục hoặc bỏ khóa học |
| Bottleneck (bước nào, mất bao nhiêu phút) | Giả thuyết: sau khi chậm tiến độ, người học không biết nên tiếp tục từ đâu; chưa đo được thời gian/tần suất. Xác minh qua phỏng vấn người từng bỏ dở |
| Impact (nếu không giải thì sao) | Người học có thể không hoàn thành khóa học hoặc mục tiêu học tập; cần xác minh lý do bỏ dở thay vì giả định thiếu động lực |
| Success metric (baseline → target) | Baseline: tỷ lệ hoàn thành/tuần học của nhóm thử nghiệm, chưa có. Target chốt sau baseline; theo dõi số buổi hoàn thành trong 2 tuần và hỏi lý do nghỉ học |
| Phương án không dùng AI | Chia mục tiêu thành các buổi ngắn, lịch học cố định và nhắc học theo lịch do người học tự chọn |
| Giả thuyết về AI (nếu có) | Chưa có căn cứ cần AI; trước tiên kiểm tra liệu lịch học và nội dung chia nhỏ có giúp duy trì tiến độ không |
| Cảm nhận nhanh | Chưa biết; thử No AI/Rule trước |

Quy trình nháp hiện tại:

```text
[Chọn khóa học: ___ phút, ghi thời gian thực tế]
→ [Học theo nội dung có sẵn: ___ phút/buổi]
→ [Bỏ lỡ buổi học hoặc gặp khó: ghi sự kiện]
→ [Tìm lại tiến độ/bước tiếp theo: ___ phút; bottleneck giả thuyết]
→ [Tiếp tục học hoặc dừng: ghi kết quả]
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi phát hiện điện trong nhà tiêu thụ nhiều hơn dự kiến, tôi muốn biết thiết bị hoặc thời điểm nào góp phần đáng kể, để cân nhắc cách giảm lãng phí |
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

### Problem Card #3

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
- Vì sao: người học có thể kể lại một khóa học đã bỏ dở và tiến trình có thể kiểm tra khi họ đồng ý. Đây là lựa chọn sơ bộ, cần xác nhận có thể tiếp cận người học phù hợp.
- Câu hỏi muốn nhóm phản biện: “Bằng chứng nào cho thấy người học bỏ dở vì không biết bước tiếp theo, thay vì thiếu thời gian hoặc không còn nhu cầu?”

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Các chủ đề theo ngành rộng hơn một bài toán kiểm chứng được | Đồng ý | Thu hẹp thành hành vi cụ thể: tiếp tục học sau khi chậm tiến độ |
| Chưa có dữ liệu thực tế để khẳng định nguyên nhân bỏ dở | Đồng ý | Ghi nguyên nhân là giả thuyết và xác minh qua phỏng vấn người từng bỏ khóa |
| Chưa chứng minh AI cần thiết | Đồng ý | Đề xuất thử lịch học cố định/chia nhỏ nội dung trước và để mức can thiệp là “Chưa biết” |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Tôi pitch card “kiểm tra thiếu mục/tài liệu trước deadline” cho nhóm, giải thích actor, quy trình, bottleneck và impact rõ ràng. | Card này được nhóm đánh giá là dễ hiểu và có thể đo được. Nó trở thành card mạnh nhất để đi tiếp. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: “Bottleneck đặt ở bước nào, không phải là cả quy trình? Nếu không dùng AI, cách làm đơn giản nhất là gì?” | Câu hỏi này giúp các bạn khác thu hẹp lại vấn đề và tránh viết quá rộng hoặc nhảy sang giải pháp sớm. |
| Nhận phản biện | Câu hỏi tôi nhận được: “Bạn có chắc đây là problem thật của sinh viên, hay chỉ là thói quen cá nhân?”; “Gần đây bạn có mất 30–60 phút không?” | Tôi đã sửa lại cách mô tả bằng cách cụ thể hóa thời điểm, tần suất và bước bottleneck để card chặt hơn. |
| Gom cluster / cây OST | Tôi hỗ trợ nhóm gộp các candidate tương tự như “tìm thông tin cũ”, “tổng hợp feedback”, “kiểm tra rubric trước deadline” thành cùng một nhóm pain. | Giúp nhóm nhìn thấy pattern và chọn problem đúng chứ không chỉ chọn bài toán riêng lẻ. |
| Chọn candidate problem | Tôi góp ý rằng nên chọn problem có actor rõ, quy trình thực tế và bottleneck đo được. | Nhóm cuối cùng ưu tiên card kiểm tra thiếu mục/tài liệu trước deadline. |
| Kiểm chứng / research | Tôi tham gia xem lại bằng chứng về tần suất và thời gian, đồng thời kiểm tra rằng problem không quá “cá nhân”. | Tạo nền tảng cho việc xác định bài toán có thực sự đáng giải quyết không. |
| Quy trình nhóm | Tôi theo dõi cách nhóm mô tả quy trình hiện tại và tương lai, nhấn vào các bước nào cần rule, workflow hay người kiểm tra. | Điều này giúp nhóm không lẫn lộn problem với solution. |
| Problem Statement | Tôi đóng góp vào việc viết v0: actor, quy trình, bottleneck, impact, success metric, boundary. | Bản mô tả bài toán trở nên rõ hơn và có thể so sánh với các giải pháp khác nhau. |
| Mức can thiệp AI | Tôi góp ý rằng nên bắt đầu bằng Rule/Workflow thay vì nghĩ đến Agent. | Giúp nhóm bỏ đi suy nghĩ “AI tự làm tất cả” và chuyển về mức can thiệp phù hợp. |
| Quyết định | Tôi đồng thuận với quyết định chọn Rule/Workflow cho vấn đề này nếu cần, với người kiểm tra ở cuối. | Kết quả là nhóm không quá lạc sang AI sớm và giữ được mức độ thực tế. |

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
