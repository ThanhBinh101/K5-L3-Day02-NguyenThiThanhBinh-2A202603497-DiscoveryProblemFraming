# K5 · L3 · Day 02 — Bài làm cá nhân về Discovery & Problem Framing
**Bài mô phỏng**

> Tình huống, số liệu, quan sát và phản hồi AI trong bài đều là giả định để minh họa cách làm. Các mục tiêu là mốc đề xuất để kiểm chứng.

## 1. Bối cảnh cá nhân

Tôi là sinh viên CNTT trực một phòng thực hành có 12 máy. Tôi nhận ca 25 phút trước giờ học. Mỗi ca, tôi đăng nhập thử và chạy bài kiểm tra Python ngoại tuyến trên từng máy rồi báo cho giảng viên chỗ nào dùng được và chỗ nào cần đổi. Kết quả kiểm tra mới ghi theo mã dán trên máy, còn một số lỗi bàn giao chỉ ghi vị trí như “máy cuối dãy B”. Khi ghi chú thiếu mã hoặc thời điểm cập nhật, tôi phải quay lại đối chiếu trước khi chốt tình trạng máy.

## 2. Scan problem (CP1)

| # | Lăng kính | Job Story | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi thu bộ chuyển đổi màn hình cuối ca, tôi muốn biết bộ nào đã được trả, để bàn giao đủ thiết bị. | Sinh viên CNTT trực phòng thực hành, người mượn thiết bị | 3/5 ca phải đếm lại vì phiếu mượn ghi số lượng mà thiếu mã bộ chuyển đổi. |
| 2 | Lặp lại | Khi chuyển sang bài lab mới, tôi muốn các máy có đúng thư mục mã nguồn mẫu, để sinh viên bắt đầu cùng một phiên bản. | Sinh viên CNTT trực phòng thực hành, sinh viên làm lab | Trong 2 lần đổi bài, mỗi lần phải chép lại thư mục mẫu trên 3 máy. |
| 3 | Tốn thời gian | Khi một máy báo lỗi thiếu thư viện giữa ca, tôi muốn xác định Python đang chạy từ môi trường nào, để khôi phục bài đang làm. | Sinh viên CNTT trực phòng thực hành, sinh viên gặp lỗi | Trong 5 ca có 3 lượt xử lý, mất 12, 14 và 16 phút từ lúc nhận báo lỗi đến khi bài chạy lại. |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi kiểm tra máy trước ca lab, tôi muốn đối chiếu đúng kết quả kiểm tra và lỗi bàn giao theo mã máy, để báo chỗ dùng được và chỗ cần đổi trước giờ học. | Sinh viên CNTT trực phòng thực hành, giảng viên, sinh viên làm lab | 5 ca mất lần lượt 26, 30, 28, 32 và 24 phút từ lúc mở danh sách máy đến lúc báo tình trạng. Trung bình 28 phút/ca, riêng bước đối chiếu mất trung bình 12 phút/ca. 4/5 ca vượt mốc 25 phút. |
| 5 | Tốn thời gian | Khi laptop giảng viên không hiện hình lên máy chiếu, tôi muốn xác định kết nối nào đang lỗi, để giảng viên bắt đầu hướng dẫn đúng giờ. | Sinh viên CNTT trực phòng thực hành, giảng viên | 2 lần trong 5 ca phải thử lại cả cáp và cổng vào, mất 7 và 9 phút. |
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận thông báo đổi yêu cầu bài lab, tôi muốn xác định phiên bản tài liệu đang có hiệu lực, để mở đúng hướng dẫn cho lớp. | Sinh viên CNTT trực phòng thực hành, giảng viên | Trong 2 lần đổi yêu cầu, mỗi lần mất 6–9 phút để đối chiếu bài đăng trên LMS với thông báo của giảng viên. |
| 7 | Pain từ người khác | Khi bắt đầu nộp bài trên máy phòng lab, tôi muốn nhận ra thư mục nộp của lớp, để lưu đúng chỗ ngay lần đầu. | Sinh viên nộp bài trên máy phòng lab, giảng viên chấm bài | 2 lượt mở nhầm thư mục của lớp trước mất 7 và 9 phút từ lúc mở trình quản lý tệp đến khi lưu đúng chỗ. |
| 8 | Pain từ người khác | Khi bài lab cần tải dữ liệu qua Internet, tôi muốn biết sớm nếu phòng không tải được, để chuẩn bị bản dữ liệu ngoại tuyến. | Giảng viên, sinh viên làm lab | 2/5 ca giảng viên chỉ phát hiện không tải được dữ liệu sau khi giao bài, cả lớp chờ 5–7 phút. |
| 9 | Lặp lại | Khi đóng phòng sau ca cuối, tôi muốn biết máy nào còn bật, để hoàn tất kiểm tra mà không phải đi lại cả phòng. | Sinh viên CNTT trực phòng thực hành | 3/5 ca cuối ngày phải đi thêm một lượt vì danh sách đóng phòng chưa ghi trạng thái từng máy. |

**Gợi ý thêm của AI**

- **Scan #8.** AI gợi ý xem điều gì làm giảng viên phải đổi cách giao bài. Tôi thu hẹp ý đó thành việc phát hiện sớm lỗi tải dữ liệu để giảng viên có thời gian chuẩn bị bản ngoại tuyến.
- **Loại ý tự khóa mọi máy bị nghi lỗi.** Gợi ý đưa ra một giải pháp khi chưa xác định thế nào là máy cần ngừng sử dụng. Tôi giữ tình huống có thể quan sát ở #4 và để người trực xác nhận trạng thái máy.

## 3. Top 3 Problem Cards (CP2)

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Đối chiếu tình trạng máy trước ca (#4) | Xảy ra ở mọi ca trong bộ số liệu giả định. Bước đối chiếu mất trung bình 12 trong 28 phút/ca và 4/5 ca báo tình trạng sau mốc 25 phút. | Cần đo ở các ca thật để biết phần thời gian mất do thiếu mã máy, thiếu thời điểm cập nhật hay còn lý do khác. |
| 2 | Xử lý lỗi thiếu thư viện giữa ca (#3) | Ba lượt xử lý mất trung bình 14 phút/lượt và làm gián đoạn bài đang chạy. | Cần biết bao nhiêu lượt chỉ do chọn sai môi trường và bao nhiêu lượt cần cài lại thư viện. |
| 3 | Tìm đúng thư mục nộp bài (#7) | Hai lượt mở nhầm thư mục mất trung bình 8 phút/lượt và có thể bấm giờ ngay tại máy của sinh viên đến lúc tệp được lưu đúng. | Cần xác định sinh viên nhầm vì tên thư mục giống nhau hay vì hướng dẫn chưa ghi rõ đường dẫn. |

### Problem Card #1 — Đối chiếu tình trạng máy trước ca

| Trường | Nội dung |
|---|---|
| Job Story | Khi kiểm tra máy trước ca lab, tôi muốn đối chiếu đúng kết quả kiểm tra và lỗi bàn giao theo mã máy, để báo chỗ dùng được và chỗ cần đổi trước giờ học. |
| Actor | Sinh viên CNTT trực phòng thực hành. |
| Thời điểm / bối cảnh | Khi nhận ca, 25 phút trước giờ học. Kiểm tra 12 máy theo cùng một danh sách và báo tình trạng cho giảng viên. |
| Quy trình hiện tại | 1. Mở danh sách 12 máy, sổ bàn giao và phiếu kiểm tra ca hiện tại (2 phút).<br>2. Đăng nhập thử, chạy bài kiểm tra Python ngắn và ghi kết quả theo mã từng máy (8 phút).<br>3. **Bước nghẽn.** Ghép lỗi bàn giao với mã máy trên phiếu kiểm tra. Khi ghi chú thiếu mã hoặc thời điểm, dò sơ đồ chỗ ngồi và các dòng cập nhật trước đó (12 phút).<br>4. Chốt trạng thái từng máy. Máy đạt cả hai phép kiểm và không còn lỗi chặn được ghi **Dùng được**. Các máy còn lại được ghi **Cần đổi chỗ**, kèm lý do, kể cả trường hợp chưa xác minh được lỗi bàn giao (4 phút).<br>5. Gửi danh sách trạng thái 12 máy cho giảng viên (2 phút). |
| Bottleneck | Bước 3 mất trung bình 12 phút/ca vì phải tra lại máy nào ứng với ghi chú vị trí và lỗi nào còn hiệu lực. |
| Impact | Người trực mất trung bình 28 phút/ca. Ở 4/5 ca giả định, danh sách được gửi sau giờ bắt đầu từ 1 đến 7 phút, nên giảng viên phải sắp xếp đổi chỗ khi ca đã bắt đầu. |
| Success metric | **Mốc hiện tại (giả định)** là 28 phút/ca trung bình. **Mục tiêu** là trung bình ≤ 20 phút/ca. **Cách đo** là bấm giờ từ lúc mở danh sách máy đến lúc gửi danh sách trạng thái cho giảng viên. Dùng cùng phạm vi 12 máy và cùng hai phép kiểm để so sánh 5 ca trước và 5 ca sau khi thử phương án. Với mỗi ca, đối chiếu danh sách gửi với phiếu kiểm tra và sổ bàn giao. Yêu cầu ghi đủ trạng thái 12 máy, có kết quả cho từng phép kiểm hoặc ghi rõ lỗi chặn khiến phép kiểm chưa thể thực hiện. Số máy bị đánh dấu **Dùng được** khi thiếu kết quả đạt hoặc còn lỗi chặn chưa xử lý hay chưa xác minh phải bằng 0. |
| Phương án không dùng AI | Dùng một bảng có sẵn 12 mã máy và vị trí tương ứng. Mỗi lần cập nhật lỗi, ghi mã máy, thời điểm và trạng thái xử lý. Người trực nhập kết quả của ca hiện tại vào cùng bảng và lọc theo mã để xem lỗi còn mở. |
| Giả thuyết về AI | Nếu vẫn còn ghi chú bàn giao cũ viết tự do, AI có thể đề xuất mã máy từ mô tả vị trí và sơ đồ chỗ ngồi, đính kèm dòng ghi chú gốc và đánh dấu trường hợp có nhiều mã khả dĩ. Người trực xác nhận mã, xem kết quả kiểm tra và quyết định trạng thái trước khi gửi. Cần đo phần thời gian đối chiếu tiết kiệm được sau khi tính cả thời gian soát đề xuất. |
| Cảm nhận nhanh | Rule. Thử đối chiếu theo mã máy và lọc lỗi còn mở trước. |

*Các thời lượng ở quy trình là trung bình giả định. Năm bước cộng thành 2 + 8 + 12 + 4 + 2 = 28 phút/ca, cũng là (26 + 30 + 28 + 32 + 24) / 5.*

### Problem Card #2 và #3
| Card | Actor | Bottleneck | Metric | Cảm nhận nhanh |
|---|---|---|---|---|
| #2 — Xử lý lỗi thiếu thư viện giữa ca (Scan #3) | Sinh viên CNTT trực phòng thực hành | Dò đường dẫn Python và môi trường đang chạy trước khi biết cần đổi môi trường hay cài thư viện. | Trung bình giả định 14 phút/lượt, mục tiêu ≤ 7 phút/lượt. Bấm giờ từ lúc nhận báo lỗi đến khi chạy lại được bài đang làm. | Rule |
| #3 — Tìm đúng thư mục nộp bài (Scan #7) | Sinh viên nộp bài trên máy phòng lab | Phải dò lại đường dẫn sau khi mở nhầm thư mục của lớp trước. | Trung bình giả định 8 phút/lượt, mục tiêu ≤ 3 phút/lượt. Bấm giờ từ lúc mở trình quản lý tệp đến khi lưu được tệp vào đúng thư mục. | No AI |

### AI phản biện card #1

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Mốc 28 phút chưa rõ tính từ lúc bắt đầu kiểm máy hay từ lúc nhận ca, và có thể bỏ sót thời gian gửi danh sách. | Đồng ý | Chốt điểm đầu là lúc mở danh sách máy, điểm cuối là lúc gửi danh sách trạng thái. Tính lại trung bình trên 5 ca giả định và đối chiếu với tổng thời lượng 5 bước. |
| Chỉ đo tốc độ có thể dẫn đến bỏ một phép kiểm hoặc cho dùng máy còn lỗi chặn. | Đồng ý | Thêm điều kiện ghi đủ trạng thái 12 máy, ghi kết quả hoặc lý do chưa kiểm được ở từng phép kiểm và kiểm tra số máy bị đánh dấu **Dùng được** sai quy tắc. |
| Có thể để AI tự chọn mã máy từ ghi chú rồi tự chốt trạng thái. | Không đồng ý | Giới hạn đầu ra của AI ở mã đề xuất kèm dòng ghi chú gốc. Người trực xác nhận mã và chốt trạng thái dựa trên phép kiểm và lỗi còn mở. |

## 4. Công việc cá nhân

| Hoạt động | Tôi đã làm gì? | Kết quả |
|---|---|---|
| Ghi lại quy trình | Tách quy trình giả định thành 5 bước từ lúc mở danh sách đến lúc gửi trạng thái. | Xác định bước 3, đối chiếu lỗi bàn giao theo mã máy, là bước tốn thời gian nhất trong bộ số liệu minh họa. |
| Chọn vấn đề | So sánh 9 vấn đề theo thời gian, tần suất và ảnh hưởng tới giờ học. | Chọn Scan #4 làm Problem Card #1 vì có 4/5 ca giả định vượt mốc 25 phút. |
| Tính baseline | Tính trung bình từ thời lượng của 5 ca giả định và so lại với tổng thời lượng trung bình của 5 bước. | Hai phép tính đều cho 28 phút/ca. |
| Sửa Problem Card | Làm rõ hai mốc bấm giờ, thêm tiêu chí kiểm tra chất lượng trạng thái và xác định người chốt trạng thái. | Có mục tiêu trung bình ≤ 20 phút/ca và điều kiện để kiểm tra việc rút ngắn thời gian. |

## 5. Dùng AI

| Checkpoint | Dùng AI để làm gì? | Hữu ích ở đâu? | Sai/hời hợt ở đâu? | Tôi sửa gì |
|---|---|---|---|---|
| CP2 | Phản biện Problem Card #1, tập trung vào baseline, tiêu chí thành công và quyền chốt trạng thái. | Chỉ ra điểm đầu và cuối của phép đo còn mơ hồ, đồng thời phát hiện việc đo thời gian có thể che lấp thao tác bị bỏ sót. | Đề xuất AI tự chọn mã và tự chốt trạng thái dù ghi chú có thể thiếu mã máy hoặc thời điểm. | Tính đủ 5 bước vào baseline, thêm điều kiện kiểm tra đủ trạng thái và hai phép kiểm theo máy, giữ việc xác nhận mã và chốt trạng thái ở người trực. |

## 6. Reflection

Ban đầu tôi nghĩ đăng nhập và chạy Python trên từng máy sẽ chiếm nhiều thời gian nhất. Khi tách quy trình và tính trên bộ số liệu giả định, tôi thấy phần này trung bình mất 8 phút, còn đối chiếu lỗi bàn giao mất 12 phút. Việc 4/5 ca vượt mốc 25 phút khiến tôi ưu tiên tìm hiểu vì sao người trực phải dò lại ghi chú trước khi gửi danh sách.

Tôi sẽ bấm giờ từng bước ở 5 ca thật liên tiếp có cùng phạm vi 12 máy. Riêng ở bước 3, tôi sẽ ghi số lần phải tra lại vì thiếu mã máy và vì thiếu thời điểm cập nhật. Hai số đếm này cùng thời lượng thực tế sẽ giúp tôi quyết định có nên thử bảng bàn giao chuẩn hóa theo mã máy trước hay cần xem lại giả định về bước nghẽn.
