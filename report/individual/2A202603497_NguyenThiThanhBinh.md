# Báo cáo cá nhân — MSSV_HoTen

## 1. Thông tin học viên

- Họ tên: Nguyễn Thị Thanh Bình
- MSSV: 2A202603497
- Tên nhóm: 7a
- Link repo nhóm: https://github.com/ThanhBinh101/K5-L3-Day02-NguyenThiThanhBinh-2A202603497-DiscoveryProblemFraming

**Đề tài đề xuất:** VinWonders Companion — Trợ lý hành trình cá nhân hóa theo tình hình thực tế.

> Quy ước: Các số phút, số người và số lần trong bảng CP1 là giả định để thiết kế kiểm chứng, chưa phải kết quả quan sát hay khảo sát. Mỗi ước lượng gắn với một tình huống và cách quy đổi/đo cụ thể; cần thay bằng số liệu thực sau khi kiểm chứng. Các số thời gian ở phần sau cũng là baseline giả định. Target là mục tiêu thử nghiệm, không phải kết quả đã đạt. Các đóng góp nhóm chưa thực hiện hoặc chưa xác nhận cần được cập nhật trước khi nộp.

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

|   # | Lăng kính                         | Job Story: Khi… tôi muốn… để…                                                                                                       | Ai chịu ảnh hưởng?                           | Dấu hiệu (giả định cần kiểm chứng)                                                                                                                            |
| --: | --------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   1 | Cần đọc, tổng hợp nhiều thông tin | Khi có nhiều trò chơi để lựa chọn, tôi muốn tìm các trò phù hợp sở thích và điều kiện tham gia để tránh mất thời gian xem từng trò. | Khách tham quan, người lập kế hoạch cho nhóm | Giả định: nhóm so sánh 3 trò, mất khoảng 6 phút (2 phút/trò); kiểm tra bằng cách bấm giờ từ lúc mở danh sách đến khi thống nhất, chưa đo thực tế.               |
|   2 | Tốn thời gian                     | Khi chọn điểm đến tiếp theo, tôi muốn biết thời gian chờ và thời gian đi bộ để quyết định hợp lý trước khi di chuyển.               | Khách có thời gian tham quan giới hạn        | Giả định: mỗi lần chọn trò mất khoảng 2 phút để tra 2 thông tin (1 phút xem thời gian chờ, 1 phút xem thời gian đi bộ); bấm giờ đến khi quyết định.            |
|   3 | Pain từ người khác                | Khi trò chơi đông bất ngờ hoặc tạm ngừng, tôi muốn có phương án thay thế để không phải tự làm lại toàn bộ lịch trình.               | Khách đi theo lịch, gia đình                 | Giả định: mỗi lần trò tạm ngừng, nhóm mất khoảng 5 phút (2 phút tìm lựa chọn khác, 3 phút so sánh và thống nhất); ghi số lần phát sinh và bấm giờ từng lần.   |
|   4 | Lặp lại                           | Khi cần nhà vệ sinh, tôi muốn tìm điểm gần và có đường tiếp cận phù hợp để giải quyết nhu cầu nhanh.                                | Khách đang di chuyển, gia đình có trẻ nhỏ    | Giả định: mỗi lần cần tìm nhà vệ sinh mất khoảng 3 phút (1 phút tìm vị trí, 2 phút kiểm tra đường đi/khả năng tiếp cận); bấm giờ đến khi chọn được điểm.     |
|   5 | Tốn thời gian                     | Khi cần mua nước, tôi muốn tìm điểm đang mở và thuận đường để không phải đi vòng.                                                   | Khách tham quan                              | Giả định: mỗi lần cần mua nước mất khoảng 3 phút (2 phút tìm điểm đang mở, 1 phút chọn điểm thuận tuyến); ghi số lần phải hỏi/đi vòng trong một ngày tham quan. |
|   6 | Cần đọc, tổng hợp nhiều thông tin | Khi muốn ăn, tôi muốn so sánh nhà hàng theo vị trí, giá, thời gian phục vụ và lịch tiếp theo để chọn điểm thuận tiện.               | Nhóm khách, người tổ chức chuyến đi          | Giả định: nhóm so sánh 3 nhà hàng, mất khoảng 6 phút (2 phút/điểm); bấm giờ đến khi chọn xong, đồng thời ghi số lựa chọn phải loại vì không khớp lịch.          |
|   7 | Pain từ người khác                | Khi nhóm có sở thích khác nhau hoặc bắt đầu mệt, tôi muốn điều chỉnh nhịp độ và hoạt động để cả nhóm vẫn có trải nghiệm phù hợp.    | Gia đình, nhóm bạn                           | Giả định: nhóm 4 người cần khoảng 5 phút (1 phút/người nêu nhu cầu, 1 phút thống nhất) khi bất đồng hoặc cần nghỉ; kiểm tra bằng quan sát, chưa khảo sát khách. |
|   8 | Lặp lại                           | Khi muốn xem show, tôi muốn biết còn đủ thời gian chơi và di chuyển hay không để tránh bỏ lỡ chương trình.                          | Khách có hoạt động ưu tiên                   | Giả định: nhóm kiểm tra trước 1 show/ngày; mỗi lần mất khoảng 3 phút (1 phút xem lịch, 2 phút đối chiếu thời gian đi bộ); cần ghi số lần thực tế trong ngày.   |

**Nếu có dùng AI để gợi ý thêm:**

- Tôi giữ lại ý tưởng tìm tiện ích thuận tuyến vì gắn trực tiếp với nhu cầu tôi đã nêu.
- Tôi giữ lại việc xét lịch show, thời gian nghỉ và hoạt động ghim vì chỉ giảm hàng chờ chưa chắc tạo trải nghiệm tốt.
- Tôi bỏ khỏi MVP các chức năng tự đặt phòng, thanh toán và triển khai toàn hệ thống vì làm tăng phạm vi và rủi ro.
- Tôi không chấp nhận số liệu tổn thất do AI ước tính như dữ liệu thực tế.
- Tôi điều chỉnh cách định vị: cần kiểm tra và nâng cấp tính năng hiện hữu của ứng dụng, tránh mặc định đây là chức năng hoàn toàn mới.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem                                                                   | Vì sao chọn                                                                     | Điều còn chưa chắc                                                         |
| ---: | ------------------------------------------------------------------------- | ------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
|    1 | Khó chọn và điều chỉnh tuyến theo sở thích, hàng chờ và thời gian còn lại | Gắn với trải nghiệm xuyên suốt ngày tham quan; kết hợp các nhu cầu tôi quan tâm | Baseline, nguồn dữ liệu chờ, tính năng hiện có và mức cải thiện có thể đạt |
|    2 | Khó tìm tiện ích thuận tiện trong lúc di chuyển                           | Nhu cầu cụ thể, dễ giới hạn phạm vi và kiểm tra kết quả                         | Mức độ thường xuyên; liệu bản đồ hiện tại đã giải quyết đủ tốt chưa        |
|    3 | Khó chọn nhà hàng phù hợp với hành trình                                  | Kết hợp nhu cầu ăn uống với lịch vui chơi; có thể kiểm chứng giá trị dịch vụ    | Nguồn dữ liệu nhà hàng, tình trạng chờ và hiệu quả tăng thêm               |

### Problem Card #1

| Trường                  | Nội dung                                                                                                                                                                 |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Job Story               | Khi cần chọn hoặc đổi hoạt động trong khu vui chơi, tôi muốn có phương án phù hợp với sở thích, hàng chờ và thời gian còn lại để hoàn thành nhiều hoạt động ưu tiên hơn. |
| Actor                   | Người đại diện nhóm khách và các thành viên đi cùng.                                                                                                                     |
| Thời điểm / bối cảnh    | Khi bắt đầu tham quan, kết thúc một hoạt động hoặc tình hình thay đổi.                                                                                                   |
| Quy trình hiện tại      | 1. Xác định nhu cầu → 2. Tra bản đồ/lịch → 3. So sánh hoạt động → 4. Kiểm tra hàng chờ → 5. Ghép lại tuyến → 6. Thống nhất lựa chọn.                                     |
| Bottleneck              | Giả định bước 3–4 tổng 6 phút; bước 5 là 4 phút. Tổng bottleneck 10 phút trong lượt quyết định 15 phút.                                                                  |
| Impact                  | Khách mất công quyết định, có thể đi vòng hoặc bỏ lỡ hoạt động ưu tiên. Chưa định lượng tác động tài chính.                                                              |
| Success metric          | Baseline cần đo; giả định ban đầu 15 phút/lượt. Target: p90 quyết định ≤3 phút; giảm chờ thực tế ≥15% so với đối chứng mà không giảm số hoạt động ưu tiên hoàn thành.    |
| Phương án không dùng AI | Form sở thích + bộ lọc điều kiện + bản đồ + thuật toán tối ưu tuyến.                                                                                                     |
| Giả thuyết về AI        | LLM giúp diễn đạt nhiều nhu cầu bằng hội thoại, hỏi thông tin thiếu và giải thích phương án dễ hơn bộ lọc.                                                               |
| Cảm nhận nhanh          | **Workflow**: LLM Feature kết hợp rule và optimizer; chưa cần Agent tự trị.                                                                                              |

Quy trình nháp hiện tại:

1. Khách xác định nhu cầu.
2. 🔄 Khách tra bản đồ và lịch trên ứng dụng.
3. Khách đối chiếu hoạt động với sở thích. 🔴
4. 🔄 Khách hỏi nhân viên hoặc xem bảng hàng chờ. 🔴
5. Khách ghép lại tuyến. 🔴
6. Nhóm thống nhất lựa chọn.

**Tổng giả định: 15 phút/lượt; không gồm đi bộ, chơi và xếp hàng.**

### Problem Card #2

| Trường                  | Nội dung                                                                                                                             |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| Job Story               | Khi cần nhà vệ sinh, nước hoặc chỗ nghỉ, tôi muốn tìm điểm phù hợp gần mình hoặc thuận tuyến để giải quyết nhu cầu mà không đi vòng. |
| Actor                   | Khách đang di chuyển, đặc biệt gia đình có trẻ nhỏ hoặc người cần đường tiếp cận phù hợp.                                            |
| Thời điểm / bối cảnh    | Khi phát sinh nhu cầu trong ngày tham quan.                                                                                          |
| Quy trình hiện tại      | 1. Phát sinh nhu cầu → 2. Mở bản đồ/hỏi nhân viên → 3. Kiểm tra vị trí, giờ mở → 4. Chọn điểm → 5. Bắt đầu di chuyển.                |
| Bottleneck              | Giả định bước 2–3 mất 4 phút; tổng quyết định 6 phút, chưa tính đi bộ.                                                               |
| Impact                  | Khách có thể mất thời gian, đi vòng hoặc đến điểm không phù hợp.                                                                     |
| Success metric          | Baseline cần đo. Target: p90 phản hồi có kết quả ≤10 giây; ≥95% gợi ý đúng vị trí và trạng thái theo nguồn kiểm chứng.               |
| Phương án không dùng AI | Bản đồ với nút NVS/Nước/Nghỉ và tìm kiếm theo khoảng cách đường đi.                                                                  |
| Giả thuyết về AI        | Có ích khi yêu cầu chứa ngữ cảnh như “mua nước tiện đường đến show”; không cần thiết cho mọi câu hỏi gần nhất.                       |
| Cảm nhận nhanh          | **Rule** cho tìm kiếm đơn giản; **Workflow** khi cần hội thoại nhiều điều kiện.                                                      |

Quy trình nháp hiện tại:

1. Khách phát sinh nhu cầu.
2. 🔄 Tra bản đồ hoặc hỏi nhân viên.
3. Kiểm tra vị trí và khả năng sử dụng. 🔴
4. Chọn tiện ích.
5. Di chuyển đến điểm đã chọn.

### Problem Card #3

| Trường                  | Nội dung                                                                                                                                                  |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story               | Khi muốn ăn nhưng vẫn có lịch vui chơi, tôi muốn chọn nhà hàng phù hợp ngân sách và thuận đường để không mất nhiều thời gian hoặc lỡ hoạt động tiếp theo. |
| Actor                   | Nhóm khách cần ăn trong khung giờ giới hạn.                                                                                                               |
| Thời điểm / bối cảnh    | Trước giờ ăn hoặc khi cần thay đổi kế hoạch.                                                                                                              |
| Quy trình hiện tại      | 1. Tìm nhà hàng → 2. Xem thực đơn/giá → 3. Kiểm tra chờ → 4. Đối chiếu lịch và đường đi → 5. Chọn phương án.                                              |
| Bottleneck              | Giả định bước 3–4 mất 6 phút trong tổng quyết định 10 phút.                                                                                               |
| Impact                  | Có thể chọn điểm bất tiện, chờ lâu hoặc không đủ thời gian đến hoạt động đã định.                                                                         |
| Success metric          | Baseline cần đo. Target: p90 chọn phương án ≤3 phút; 100% phương án hiển thị vượt kiểm tra mốc cố định đã biết.                                           |
| Phương án không dùng AI | Danh sách nhà hàng có bộ lọc giá, vị trí, giờ mở và tính thời gian di chuyển.                                                                             |
| Giả thuyết về AI        | Hiểu yêu cầu nhiều điều kiện và giải thích đánh đổi giữa các phương án.                                                                                   |
| Cảm nhận nhanh          | **Workflow**, với điều kiện dữ liệu đủ tin cậy.                                                                                                           |

Quy trình nháp hiện tại:

1. Tìm nhà hàng.
2. Xem thực đơn và giá.
3. 🔄 Hỏi hoặc kiểm tra tình trạng chờ. 🔴
4. So sánh với tuyến và giờ hoạt động tiếp theo. 🔴
5. Thống nhất điểm ăn.

### Card muốn pitch nhất

- **Card số:** 1.
- **Vì sao:** Đây là quyết định trung tâm của hành trình; hai card còn lại có thể trở thành nhu cầu hỗ trợ trong cùng trải nghiệm.
- **Câu hỏi muốn nhóm phản biện:** Dữ liệu chờ có đủ tin cậy không? App hiện tại đã giải quyết đến đâu? Lớp hội thoại có tốt hơn form và bộ lọc đủ để bù chi phí không?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra                                  | Đồng ý? | Đã sửa gì                                                    |
| --------------------------------------------------- | ------- | ------------------------------------------------------------ |
| Thời gian 15 phút chưa có baseline thực tế          | Có      | Đánh dấu giả định, đề xuất quan sát trước khi đưa ra cam kết |
| App có thể đã có chức năng lịch trình               | Có      | Chuyển định vị sang xác minh và nâng cấp khoảng trống        |
| Thuật toán thông thường có thể tạo phần lớn giá trị | Có      | Tách LLM khỏi rule/optimizer và đề xuất so sánh có/không LLM |
| Dữ liệu chờ có thể thiếu hoặc cũ                    | Có      | Thêm dấu thời gian, ngưỡng hết hạn và fallback               |
| Giảm chờ chưa chắc làm khách hài lòng hơn           | Có      | Bổ sung số hoạt động ưu tiên hoàn thành và mức hài lòng      |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

> Nội dung “đã làm” chỉ ghi việc xác nhận được từ quá trình chuẩn bị cá nhân. Hoạt động với nhóm cần cập nhật đúng thực tế.

| Hoạt động                  | Tôi đã làm gì?                                                                               | Kết quả / ảnh hưởng tới bài nhóm                                                    |
| -------------------------- | -------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| Pitch Problem Card         | Đã chuẩn bị cách giới thiệu vấn đề từ góc nhìn khách và các câu trả lời phản biện            | Có nội dung để pitch; [điền kết quả trình bày thực tế]                              |
| Phản biện bài của bạn khác | Đã chuẩn bị câu hỏi về nguồn số liệu, baseline, vai trò AI và ROI của case chống gian lận    | [Điền câu đã thực sự hỏi và phản hồi nhận được]                                     |
| Nhận phản biện             | Trong trao đổi với AI, nhận câu hỏi về dữ liệu chờ, tính năng hiện hữu và phương án không AI | Đã thu hẹp phạm vi, bổ sung giả định và fallback; [bổ sung phản biện từ người thật] |
| Gom cluster / cây OST      | Đề xuất ba cụm: chọn hoạt động, điều chỉnh tuyến, tìm tiện ích                               | [Chưa xác nhận nhóm đã lập OST; cập nhật kết quả thật]                              |
| Chọn candidate problem     | Cá nhân ưu tiên Card #1                                                                      | [Cập nhật quyết định chính thức của nhóm]                                           |
| Kiểm chứng / research      | Dùng AI hỗ trợ tìm và đối chiếu nguồn công khai; phân biệt review với khảo sát               | Nhận ra cần kiểm tra chức năng app hiện có; chưa có phỏng vấn/survey                |
| Quy trình nhóm             | Đã chuẩn bị mô hình current-state 4 làn, 6 bước và handoff                                   | Có sơ đồ nháp; thời gian cần xác minh và nhóm review                                |
| Problem Statement          | Đã chuẩn bị 6 trường, metric và operational boundary                                         | Tách được mục tiêu trải nghiệm, dữ liệu và quyền thao tác                           |
| Mức can thiệp AI           | Đề xuất LLM Feature + rule + optimizer                                                       | Chưa cần Agent tự trị; cần so sánh với phương án không LLM                          |
| Quyết định                 | Đề xuất GO cho prototype hẹp, NOT YET cho pilot thực địa                                     | [Cập nhật quyết định được nhóm thống nhất]                                          |

---

## 5. Dùng AI

| Checkpoint                     | Tôi dùng AI để làm gì?                         | AI hữu ích ở đâu?                               | AI sai hoặc hời hợt ở đâu?                                          | Tôi sửa gì bằng nhận định của mình?                                             |
| ------------------------------ | ---------------------------------------------- | ----------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| CP1 Scan                       | Mở rộng các vấn đề quanh hành trình VinWonders | Phân tách sở thích, hàng chờ, tuyến và tiện ích | Có thể mở rộng thành quá nhiều tính năng                            | Giữ nhu cầu tôi đã nêu, bỏ đặt phòng và thanh toán khỏi MVP                     |
| CP2 Problem Card               | Viết card và stress-test như CFO/vận hành      | Đặt câu hỏi về actor, bottleneck và metric      | Số liệu ước tính dễ bị hiểu là số thật                              | Gắn nhãn giả định và yêu cầu đo baseline                                        |
| CP4 Research                   | Tìm nguồn công khai về app và tiền lệ ngành    | Giúp nhận diện chức năng đã được giới thiệu     | Review riêng lẻ không chứng minh mức phổ biến hoặc ROI              | Chỉ dùng làm tín hiệu định tính; cần khảo sát thêm                              |
| CP5 Quy trình                  | Mô hình hóa swimlane, bước và handoff          | Làm rõ trách nhiệm và đầu vào/đầu ra            | Sơ đồ có thể khiến quy trình giả định trông như thực tế đã xác minh | Ghi rõ phạm vi lượt quyết định và không bắt quản lý duyệt từng tuyến            |
| CP5–6 Problem Statement        | Viết 6-field, metric và boundary               | Tách nhu cầu khỏi giải pháp                     | Dễ trộn thời gian khách, giờ nhân viên và tiền tiết kiệm            | Không quy thời gian khách thành tiền; tách trung bình khỏi p90                  |
| CP6 Mức can thiệp / quyết định | So sánh Rule, LLM và Agent; kiểm tra ROI       | Giúp xây điều kiện GO/NOT YET                   | Không thể chứng minh AI bắt buộc hay lợi nhuận chắc chắn            | Giữ baseline không LLM, GO theo phạm vi và không cam kết hòa vốn dưới một tháng |

### Trạng thái kiểm chứng

- Đã có thiết kế prompt, JSON và adversarial test cases.
- Tôi đã cho biết có API Gemini.
- Báo cáo này chưa có log thực thi để xác nhận prototype chạy thành công.
- Không coi output minh họa là kết quả quan sát.
- Cần lưu log thật và review cả nội dung, không chỉ định dạng JSON.

---

## 6. Reflection (CP7)

> **Phần này tôi tự viết bằng trải nghiệm thật, tối thiểu 200 từ tổng cho 6.1–6.6. Những câu hỏi gợi nhớ bên dưới không phải nội dung trả lời để nộp.**

### 6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?

[Viết tên hoặc nội dung một problem bạn thực sự đã nghe. Điều gì trong cách bạn đó xác định actor, bằng chứng hoặc impact khiến bạn học được? Nếu chưa nghe, chưa ghi là đã tham gia.]

### 6.2. Nhóm có lúc nào bị “solution-first” không? Nhóm nhận ra và xử lý thế nào?

[Nhớ lại lúc nhóm nói về chatbot, Agent hoặc công nghệ trước khi thống nhất vấn đề. Ai đặt câu hỏi kéo nhóm về pain point? Nếu chưa xảy ra trong nhóm, nói rõ và phân biệt với trao đổi cá nhân cùng AI.]

### 6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.

[Chọn một lần thật: nhận ra app đã có lịch trình; không cần AI cho mọi câu hỏi; hoặc chưa đủ dữ liệu để cam kết realtime. Ghi ý kiến ban đầu, phản biện nhận được và thay đổi của bạn.]

### 6.4. Kết quả kiểm chứng có làm tôi bất ngờ không? Điều gì?

[Chỉ kể nghiên cứu, phỏng vấn hoặc survey thực sự đã làm. Nếu mới research nguồn công khai, nêu đúng điều đó; không viết rằng đã phỏng vấn khách.]

### 6.5. Điều khó nhất khi viết Problem Statement là gì?

[Chọn khó khăn bạn thực sự gặp: tách problem khỏi solution; chọn actor; xác định phạm vi một lượt; tìm baseline; hoặc tránh quy thời gian khách thành tiền.]

### 6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?

[Nêu hành động cụ thể: kiểm tra app trước brainstorm, thu baseline sớm, yêu cầu nguồn cho mọi con số, hoặc so sánh với bản không LLM.]

### 6.7. Hiểu bài

[Đóng tài liệu và tự viết 5–8 câu. Lần lượt giải thích: vấn đề của khách → quy trình hiện tại → metric → boundary → mức can thiệp AI → quyết định. Không sao chép đoạn giải thích do AI viết.]

---

## 7. Tài liệu tham khảo

- VinWonders — Trang ứng dụng trên Google Play:  
  https://play.google.com/store/apps/details?hl=vi&id=com.vinwonders.app  
  Dùng để tham khảo chức năng được công bố và phản hồi định tính; không suy rộng review thành tỷ lệ khách gặp vấn đề.

- Walt Disney World — My Disney Experience:  
  https://disneyworld.disney.go.com/guest-services/mobile-apps/  
  Dùng làm tiền lệ sản phẩm trong ngành, không làm bằng chứng ROI tại VinWonders.

- Worksheet và rubric Lab 02 do giảng viên cung cấp.

- ChatGPT — Đối tác hỗ trợ brainstorm, phản biện và soạn cấu trúc. Nội dung AI không được xem là nguồn độc lập chứng minh số liệu.

```

```
