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

|   # | Lăng kính                         | Job Story: Khi… tôi muốn… để…                                                                                                                                                                                                             | Ai chịu ảnh hưởng?                           | Dấu hiệu (giả định cần kiểm chứng)                                                                                                                                                            |
| --: | --------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   1 | Cần đọc, tổng hợp nhiều thông tin | Khi có nhiều trò chơi để lựa chọn, tôi muốn tìm các trò phù hợp sở thích và điều kiện tham gia để tránh mất thời gian xem từng trò.                                                                                                       | Khách tham quan, người lập kế hoạch cho nhóm | Giả định: nhóm so sánh 3 trò, mất khoảng 6 phút (2 phút/trò). Khi sắp xếp dễ bỏ lỡ các show yêu thích.                                                                                        |
|   2 | Tốn thời gian                     | Khi chọn điểm đến tiếp theo, tôi muốn biết thời gian chờ và thời gian đi bộ của từng trờ chơi trong kế hoạch để quyết định hợp lý trước khi di chuyển.                                                                                    | Khách có thời gian tham quan giới hạn        | Khi đến nơi, trò chơi dài phải chờ đợi (có trò phải chờ đến 2 tiếng) -> mất thời gian, mệt, trải nghiệm không tốt                                                                             |
|   3 | Pain từ người khác                | Khi trò chơi đông bất ngờ hoặc tạm ngừng, tôi muốn có phương án thay thế để không phải tự làm lại toàn bộ lịch trình.                                                                                                                     | Khách đi theo lịch, gia đình                 | Giả định: mỗi lần trò tạm ngừng, nhóm mất khoảng 5 phút (2 phút tìm lựa chọn khác, 3 phút so sánh và thống nhất).                                                                             |
|   4 | Lặp lại                           | Khi cần nhà vệ sinh tôi muốn tìm điểm gần và có đường tiếp cận phù hợp để giải quyết nhu cầu nhanh và ít thời gian chờ đợi nhất có thể.                                                                                                   | Khách đang di chuyển, gia đình có trẻ nhỏ    | Giả định: mỗi lần cần tìm nhà vệ sinh mất khoảng 3 phút (1 phút tìm vị trí, 2 phút kiểm tra đường đi/khả năng tiếp cận); đôi khi phải chờ 15-30 phút do nơi gần nhất quá đông.                |
|   5 | Tốn thời gian                     | Khi cần mua nước, tôi muốn tìm điểm đang mở và thuận đường để không phải đi vòng. Tôi cũng muốn tìm nơi phù hợp với sở thích (nước đóng chai hoặc quầy pha chế)                                                                           | Khách tham quan                              | Giả định: mỗi lần cần mua nước mất khoảng 3 phút (2 phút tìm điểm đang mở, 1 phút chọn điểm thuận tuyến); ghi số lần phải hỏi/đi vòng trong một ngày tham quan.                               |
|   6 | Cần đọc, tổng hợp nhiều thông tin | Khi muốn ăn, tôi muốn so sánh nhà hàng theo vị trí, giá, thời gian phục vụ và lịch tiếp theo để chọn điểm thuận tiện. Ngoài ra tôi muốn được biết trước menu để lựa chọn phù hợp với tình hình gia đình (đi đông/ đi lẻ / người già/ trẻ) | Nhóm khách, người tổ chức chuyến đi          | Giả định: nhóm so sánh 3 nhà hàng, mất khoảng 6 phút (2 phút/điểm); bấm giờ đến khi chọn xong, đồng thời ghi số lựa chọn phải loại vì không khớp lịch. Thời gian chờ đợi xếp hàng order (30p) |
|   7 | Pain từ người khác                | Khi nhóm có sở thích khác nhau hoặc bắt đầu mệt, tôi muốn điều chỉnh nhịp độ và hoạt động để cả nhóm vẫn có trải nghiệm phù hợp.                                                                                                          | Gia đình, nhóm bạn                           | Giả định: nhóm 4 người cần khoảng 5 phút (1 phút/người nêu nhu cầu, 1 phút thống nhất) khi bất đồng hoặc cần nghỉ; kiểm tra bằng quan sát, chưa khảo sát khách.                               |
|   8 | Lặp lại                           | Khi muốn xem show, tôi muốn biết còn đủ thời gian chơi và di chuyển hay không để tránh bỏ lỡ chương trình.                                                                                                                                | Khách có hoạt động ưu tiên                   | Giả định: nhóm kiểm tra trước 1 show/ngày; mỗi lần mất khoảng 3 phút (1 phút xem lịch, 2 phút đối chiếu thời gian đi bộ); cần ghi số lần thực tế trong ngày.                                  |

**Nếu có dùng AI để gợi ý thêm:**

- Tôi giữ lại ý tưởng tìm tiện ích thuận tuyến vì gắn trực tiếp với nhu cầu tôi đã nêu.
- Tôi giữ lại việc xét lịch show, thời gian nghỉ và hoạt động ghim vì chỉ giảm hàng chờ chưa chắc tạo trải nghiệm tốt.
- Tôi bỏ khỏi MVP các chức năng tự đặt phòng, thanh toán và triển khai toàn hệ thống vì làm tăng phạm vi và rủi ro.
- Tôi không chấp nhận số liệu tổn thất do AI ước tính như dữ liệu thực tế.
- Tôi điều chỉnh cách định vị: cần kiểm tra và nâng cấp tính năng hiện hữu của ứng dụng, tránh mặc định đây là chức năng hoàn toàn mới.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem                                                                                          | Vì sao chọn                                                                      | Điều còn chưa chắc                                                                                  |
| ---: | ------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
|    1 | Khó chọn trò phù hợp sở thích, thời gian chờ và lịch show                                        | Kết nối scan #1–3, #8; có thể kiểm tra cả thời gian ra quyết định lẫn lịch trình | Thời gian chờ có chính xác/cập nhật không; con số chờ đến 2 tiếng và nguy cơ lỡ show cần xác minh   |
|    2 | Khó tìm tiện ích phù hợp và biết trước khả năng tiếp cận hoặc mức đông                           | Bám sát scan #4–5; nhu cầu phát sinh cụ thể trong lúc di chuyển                   | Tần suất phát sinh; mức chờ 15–30 phút và khả năng cung cấp trạng thái đông cần kiểm chứng          |
|    3 | Khó chọn nơi ăn phù hợp thực đơn, thành phần gia đình và lịch trình                              | Bám sát scan #6; kết hợp nhu cầu xem menu với thời gian phục vụ                   | Thời gian chờ order 30 phút, dữ liệu menu/trạng thái và lợi ích so với danh sách lọc thông thường   |

### Problem Card #1

| Trường                  | Nội dung                                                                                                                                                                                                           |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Job Story               | Khi lên lịch hoặc chọn/đổi trò tiếp theo, nhất là lúc trò đông hoặc tạm ngừng, tôi muốn so sánh lựa chọn theo sở thích, điều kiện tham gia, thời gian chờ và đường đi, đồng thời đối chiếu giờ show để ưu tiên hoạt động yêu thích mà không lỡ lịch. |
| Actor                   | Người đại diện nhóm khách và các thành viên đi cùng.                                                                                                                                                               |
| Thời điểm / bối cảnh    | Khi lập kế hoạch đầu ngày, sau khi kết thúc một trò hoặc khi hàng chờ/tình trạng hoạt động thay đổi.                                                                                                                |
| Quy trình hiện tại      | 1. Nêu sở thích/điều kiện → 2. Xem trò phù hợp → 3. Tra hàng chờ và đường đi → 4. Đối chiếu lịch show → 5. Nếu trò quá đông/tạm ngừng, tìm phương án khác → 6. Chọn và thống nhất hoạt động tiếp theo.                 |
| Bottleneck              | Theo giả định ở scan #1, so sánh 3 trò mất khoảng 6 phút; scan #2 ước tính tra chờ và đường đi mất 2 phút/lượt chọn; đối chiếu show khoảng 3 phút/lần (scan #8); tìm phương án khi trò tạm ngừng khoảng 5 phút/lần (scan #3). Các số này chưa đo thực tế. |
| Impact                  | Có thể mất thời gian quyết định, gặp thời gian chờ dài (scan nêu có thể đến 2 tiếng; cần xác minh), hoặc bỏ lỡ show yêu thích. Thời gian xếp hàng là thời gian trải nghiệm, không cộng vào thời gian tìm/chọn phương án. |
| Success metric          | Đo baseline thời gian chọn phương án và tỷ lệ hoàn thành trò/show đã ưu tiên. Mục tiêu thử nghiệm: p90 chọn phương án ≤3 phút và không giảm tỷ lệ hoàn thành hoạt động ưu tiên; theo dõi riêng sai lệch giữa thời gian chờ hiển thị và thực tế. |
| Phương án không dùng AI | Bộ lọc sở thích/điều kiện tham gia + lịch show + dữ liệu hàng chờ có dấu thời gian + quy tắc sắp xếp tuyến.                                                                                                        |
| Giả thuyết về AI        | LLM có thể nhận yêu cầu nhiều điều kiện bằng hội thoại và giải thích đánh đổi; cần kiểm tra xem có tốt hơn form/bộ lọc hay không.                                                                                   |
| Cảm nhận nhanh          | **Workflow**: LLM Feature tùy chọn kết hợp rule và optimizer; chưa cần Agent tự trị.                                                                                                                                 |

Quy trình nháp hiện tại:

1. Khách nêu sở thích và điều kiện tham gia.
2. 🔄 So sánh các trò phù hợp (giả định 3 trò, khoảng 6 phút). 🔴
3. 🔄 Tra thời gian chờ và đường đi (giả định khoảng 2 phút/lượt chọn). 🔴
4. Đối chiếu giờ show và thời gian di chuyển (giả định khoảng 3 phút/lần).
5. Nếu trò quá đông/tạm ngừng, tìm phương án thay thế (giả định khoảng 5 phút/lần).
6. Nhóm thống nhất trò tiếp theo.

Các mốc 6, 2, 3 và 5 phút là giả định từ scan #1–3, #8, cần bấm giờ để xác minh; không gồm thời gian chơi, đi bộ, hoặc xếp hàng. Thời gian chờ trò chơi (scan nêu có thể đến 2 tiếng) là một đại lượng riêng, chưa có nguồn đo xác nhận.

### Problem Card #2

| Trường                  | Nội dung                                                                                                                                                                                    |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story               | Khi cần nhà vệ sinh hoặc mua nước, tôi muốn tìm điểm đang mở, thuận đường và phù hợp nhu cầu (như loại nước hoặc khả năng tiếp cận) để không đi vòng hay phải chờ lâu ở điểm quá đông.      |
| Actor                   | Khách đang di chuyển, đặc biệt gia đình có trẻ nhỏ hoặc người cần đường tiếp cận phù hợp.                                                                                                    |
| Thời điểm / bối cảnh    | Khi phát sinh nhu cầu trong ngày tham quan.                                                                                                                                                 |
| Quy trình hiện tại      | 1. Phát sinh nhu cầu → 2. Tìm tiện ích/hỏi nhân viên → 3. Kiểm tra vị trí, trạng thái và đường đi → 4. Chọn điểm → 5. Di chuyển và sử dụng.                                               |
| Bottleneck              | Scan #4–5 ước tính tìm và chọn điểm mất khoảng 3 phút/lần. Scan #4 nêu có lúc chờ 15–30 phút ở nhà vệ sinh gần nhất; đây là thời gian chờ sử dụng, không phải thời gian tìm kiếm, cần xác minh. |
| Impact                  | Có thể đi vòng, chọn nhầm điểm không phù hợp hoặc phải chờ ở điểm đông; tác động rõ hơn với gia đình có trẻ nhỏ/người cần tiếp cận thuận tiện.                                               |
| Success metric          | Đo riêng thời gian tìm/chọn, quãng đường đi vòng và thời gian chờ thực tế. Mục tiêu thử nghiệm: p90 tìm được điểm phù hợp ≤10 giây; ≥95% gợi ý đúng vị trí/trạng thái từ nguồn kiểm chứng. |
| Phương án không dùng AI | Bản đồ phân loại nhà vệ sinh/nước, lọc trạng thái và khả năng tiếp cận, sắp xếp theo đường đi.                                                                                               |
| Giả thuyết về AI        | Hội thoại có thể hiểu yêu cầu kết hợp như loại nước và điểm thuận đường; tìm điểm gần nhất đơn giản có thể giải quyết bằng bộ lọc thông thường.                                               |
| Cảm nhận nhanh          | **Rule** cho tìm kiếm cơ bản; **Workflow** khi cần kết hợp nhiều điều kiện và giải thích lựa chọn.                                                                                            |

Quy trình nháp hiện tại:

1. Khách phát sinh nhu cầu (nhà vệ sinh hoặc mua nước).
2. 🔄 Tìm tiện ích trên bản đồ hoặc hỏi nhân viên (scan ước tính tìm/chọn khoảng 3 phút). 🔴
3. Kiểm tra điểm đang mở, đường đi và khả năng tiếp cận.
4. Chọn điểm; nếu là nhà vệ sinh, ghi riêng thời gian chờ sử dụng (scan nêu 15–30 phút, cần kiểm chứng).
5. Di chuyển đến điểm đã chọn.

### Problem Card #3

| Trường                  | Nội dung                                                                                                                                                                                                                                                                                       |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story               | Khi cần ăn trong ngày tham quan, tôi muốn xem trước menu và chọn nơi phù hợp với ngân sách, lịch trình, số lượng người và nhu cầu của gia đình (người lớn tuổi/trẻ nhỏ) để cả nhóm ăn phù hợp mà không lỡ hoạt động tiếp theo.                                                                 |
| Actor                   | Người đại diện nhóm và các thành viên cần lựa chọn bữa ăn phù hợp.                                                                                                                                                                                                                            |
| Thời điểm / bối cảnh    | Trước giờ ăn hoặc khi lịch trình thay đổi; cần cân nhắc cả thời gian order và hoạt động tiếp theo.                                                                                                                                                                                             |
| Quy trình hiện tại      | 1. Tìm nhà hàng → 2. Xem menu/giá và nhu cầu nhóm → 3. Kiểm tra thời gian chờ/order → 4. Đối chiếu vị trí, đường đi và lịch tiếp theo → 5. Nhóm thống nhất lựa chọn.                                                                                                                          |
| Bottleneck              | Scan #6 ước tính so sánh 3 nhà hàng mất khoảng 6 phút (2 phút/điểm); thời gian chờ order 30 phút là con số cần xác minh riêng, không cộng vào thời gian ra quyết định.                                                                                                                        |
| Impact                  | Có thể chọn nơi không phù hợp với thành viên, chờ lâu hoặc không kịp hoạt động tiếp theo.                                                                                                                                                                                                      |
| Success metric          | Đo thời gian chọn, độ chính xác/cập nhật của menu và sai lệch thời gian chờ hiển thị so với thực tế. Mục tiêu thử nghiệm: p90 chọn nhà hàng ≤3 phút và thông tin menu được xác minh trước khi hiển thị; không cam kết giảm thời gian phục vụ khi chưa có dữ liệu.                                  |
| Phương án không dùng AI | Danh sách nhà hàng có menu, giá, thông tin tiếp cận và bộ lọc theo vị trí, giờ mở, nhu cầu nhóm; hiển thị thời gian chờ nếu có nguồn đáng tin cậy.                                                                                                                                             |
| Giả thuyết về AI        | AI có thể diễn giải yêu cầu nhóm nhiều điều kiện và tóm tắt điểm phù hợp/đánh đổi; cần so sánh với bộ lọc menu và tiêu chí có cấu trúc.                                                                                                                                                        |
| Cảm nhận nhanh          | **Workflow** nếu menu/trạng thái có nguồn đủ tin cậy; nếu không, bắt đầu bằng danh sách/bộ lọc với dữ liệu đã xác minh.                                                                                                                                                                         |

Quy trình nháp hiện tại:

1. Nêu nhu cầu bữa ăn và thành phần nhóm.
2. 🔄 Tìm nhà hàng, so sánh menu/giá của khoảng 3 lựa chọn (giả định khoảng 6 phút). 🔴
3. 🔄 Hỏi hoặc kiểm tra thời gian chờ order (scan nêu 30 phút, cần xác minh). 🔴
4. Đối chiếu vị trí, đường đi và lịch hoạt động tiếp theo.
5. Nhóm thống nhất điểm ăn.

### Card muốn pitch nhất

- **Card số:** 1.
- **Vì sao:** Card #1 kết nối việc chọn trò theo sở thích/điều kiện với hàng chờ và nguy cơ lỡ show; đây là nhu cầu xuyên suốt chuyến đi.
- **Câu hỏi muốn nhóm phản biện:** Con số chờ đến 2 tiếng và nguy cơ lỡ show có bằng chứng nào? App hiện tại đã hiển thị lịch/chờ chưa? Dữ liệu có cập nhật đủ tin cậy, và hội thoại có tốt hơn bộ lọc không?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra                                                    | Đồng ý? | Đã sửa gì                                                                                              |
| --------------------------------------------------------------------- | ------- | ------------------------------------------------------------------------------------------------------ |
| Các mốc 2 tiếng, 15–30 phút và 30 phút chưa có nguồn/đo lường rõ ràng | Có      | Ghi là số cần kiểm chứng; tách thời gian tìm/chọn khỏi thời gian xếp hàng hoặc sử dụng                |
| App có thể đã có chức năng bản đồ, lịch show hoặc thông tin nhà hàng  | Có      | Chuyển định vị sang xác minh tính năng hiện hữu và tìm khoảng trống cụ thể                            |
| Thuật toán/bộ lọc thông thường có thể tạo phần lớn giá trị             | Có      | Tách LLM khỏi rule/optimizer và đề xuất so sánh có/không LLM                                           |
| Dữ liệu chờ, menu hoặc trạng thái tiện ích có thể thiếu/cũ             | Có      | Chỉ hiển thị thông tin có nguồn và dấu thời gian; đặt ngưỡng hết hạn, fallback khi không có dữ liệu   |
| Giảm thời gian chờ không hoàn toàn nằm trong quyền kiểm soát sản phẩm  | Có      | Đo riêng thời gian quyết định, sai lệch dự báo và tỷ lệ hoàn thành hoạt động ưu tiên; không hứa giảm hàng chờ |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

> Nội dung “đã làm” chỉ ghi việc xác nhận được từ quá trình chuẩn bị cá nhân. Hoạt động với nhóm cần cập nhật đúng thực tế.

| Hoạt động                  | Tôi đã làm gì?                                                                               | Kết quả / ảnh hưởng tới bài nhóm                                                    |
| -------------------------- | -------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| Pitch Problem Card         | Đã chuẩn bị cách giới thiệu vấn đề từ góc nhìn khách và các câu trả lời phản biện            | Có nội dung để pitch; [điền kết quả trình bày thực tế]                              |
| Phản biện bài của bạn khác | Đã chuẩn bị câu hỏi về nguồn số liệu, baseline, vai trò AI và ROI của case chống gian lận    | [Điền câu đã thực sự hỏi và phản hồi nhận được]                                     |
| Nhận phản biện             | Trong trao đổi với AI, nhận câu hỏi về dữ liệu chờ, tính năng hiện hữu và phương án không AI | Đã thu hẹp phạm vi, bổ sung giả định và fallback; [bổ sung phản biện từ người thật] |
| Gom cluster / cây OST      | Đề xuất các cụm: chọn/đổi trò và canh giờ show; tìm tiện ích; chọn bữa ăn theo nhu cầu nhóm   | [Chưa xác nhận nhóm đã lập OST; cập nhật kết quả thật]                              |
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
| CP1 Scan                       | Mở rộng các vấn đề quanh hành trình VinWonders | Phân tách sở thích, hàng chờ, tuyến, show, tiện ích và nhu cầu ăn uống của nhóm | Có thể mở rộng thành quá nhiều tính năng                  | Giữ các nhu cầu đã nêu, bỏ đặt phòng và thanh toán khỏi MVP                     |
| CP2 Problem Card               | Viết card và stress-test như CFO/vận hành      | Đặt câu hỏi về actor, bottleneck và metric      | Số liệu ước tính dễ bị hiểu là số thật                              | Ghi rõ giả định; tách thời gian tìm/chọn khỏi thời gian xếp hàng và đo baseline |
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
