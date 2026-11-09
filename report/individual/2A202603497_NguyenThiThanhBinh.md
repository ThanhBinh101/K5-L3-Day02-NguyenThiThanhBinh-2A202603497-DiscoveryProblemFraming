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

Các actor cụ thể dưới đây là phân khúc mục tiêu giả định để định hướng kiểm chứng, chưa được xác nhận qua phỏng vấn hoặc quan sát khách thực tế.

**Kiểm tra ứng dụng hiện tại:** App VinWonders đã có khả năng lập kế hoạch phù hợp. Qua lần kiểm tra của tôi, khoảng trống cần tìm hiểu thêm là điều chỉnh kế hoạch linh hoạt theo tình trạng hoạt động và thời gian chờ thực tế; tôi cũng chưa tìm thấy chỗ xem WC và menu nhà hàng thuận tiện trong cùng luồng, phải chuyển qua nhiều mục của app. Đây là ghi nhận từ lần kiểm tra app, chưa phải nghiên cứu khả dụng có người dùng; cần kiểm chứng thêm xem thông tin có nằm ở mục khác hoặc khác theo phiên bản/địa điểm không.

|   # | Lăng kính                    | Job Story: Khi… tôi muốn… để…                                                                                                                                                                                                             | Ai chịu ảnh hưởng?                           | Dấu hiệu (giả định cần kiểm chứng)                                                                                                                                                            |
| --: | ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   1 | Cần tổng hợp nhiều thông tin | Khi cùng gia đình tham quan và cần chọn trò tiếp theo, tôi muốn xem kế hoạch đã lập và điều chỉnh theo tình trạng hiện tại để không mất thời gian chuyển qua nhiều mục hoặc lỡ show đã chọn.                                          | Phụ huynh đang cùng con chọn hoạt động cho gia đình | App VinWonders hiện đã có khả năng lập kế hoạch phù hợp. Qua kiểm tra app, chưa thấy kế hoạch tự điều chỉnh theo tình trạng thay đổi; giả định so sánh 3 trò mất khoảng 6 phút cần bấm giờ xác minh. |
|   2 | Tốn thời gian                | Khi phụ huynh đang cùng con chọn điểm đến tiếp theo, tôi muốn biết thời gian chờ thực tế và thời gian đi bộ của từng trò trong kế hoạch để quyết định hợp lý trước khi di chuyển.                                                  | Phụ huynh đi cùng trẻ trong chuyến tham quan có giờ show/giờ kết thúc cố định | Qua kiểm tra app, chưa tìm thấy thông tin thời gian chờ thực tế để điều chỉnh kế hoạch; nhận định có trò phải chờ đến 2 giờ là giả định cần xác minh, không phải số đo.                           |
|   3 | Pain từ người khác           | Khi trò gia đình định chơi đông bất ngờ hoặc tạm ngừng, tôi muốn có phương án thay thế để không phải tự làm lại toàn bộ lịch trình cho các thành viên đi cùng.                                                                          | Người đang điều phối lịch vui chơi cho gia đình có trẻ nhỏ | Giả định: mỗi lần trò tạm ngừng, nhóm mất khoảng 5 phút (2 phút tìm lựa chọn khác, 3 phút so sánh và thống nhất).                                                                             |
|   4 | Lặp lại                      | Khi đi cùng trẻ nhỏ hoặc người cần lối đi thuận tiện và họ cần dùng nhà vệ sinh, tôi muốn tìm nhanh vị trí, đường tiếp cận và tình trạng đông để giảm thời gian dò tìm và chờ.                                                         | Người chăm sóc/người đi cùng trẻ nhỏ hoặc người hạn chế khả năng di chuyển | Qua kiểm tra app, chưa tìm thấy chỗ xem WC thuận tiện trong cùng luồng lập kế hoạch; cần chuyển qua nhiều mục để tìm thông tin liên quan. Mốc chờ 15–30 phút là giả định cần xác minh.        |
|   5 | Tốn thời gian                | Khi đang đi cùng gia đình và cần mua nước, tôi muốn tìm điểm đang mở, thuận tuyến và có loại nước phù hợp (nước đóng chai hoặc quầy pha chế) để không phải đi vòng.                                                               | Người lớn trong nhóm gia đình đang chọn điểm mua nước | Giả định: mỗi lần cần mua nước mất khoảng 3 phút (2 phút tìm điểm đang mở, 1 phút chọn điểm thuận tuyến); ghi số lần phải hỏi/đi vòng trong một ngày tham quan.                               |
|   6 | Cần tổng hợp nhiều thông tin | Khi cần chọn bữa ăn cho gia đình trong ngày tham quan, tôi muốn xem menu và so sánh nhà hàng theo vị trí, giá, thời gian phục vụ và lịch tiếp theo để chọn điểm thuận tiện mà không phải dò nhiều mục.                                  | Người lớn đang tổ chức bữa ăn cho gia đình có trẻ nhỏ/người lớn tuổi | Qua kiểm tra app, chưa tìm thấy menu nhà hàng ở một chỗ thuận tiện trong luồng lập kế hoạch; cần chuyển qua nhiều mục. Giả định so sánh 3 nhà hàng mất khoảng 6 phút; mốc chờ order 30 phút cần xác minh. |
|   7 | Pain từ người khác           | Khi một thành viên trong gia đình muốn nghỉ hoặc có sở thích khác với các thành viên còn lại, tôi muốn điều chỉnh nhịp độ và hoạt động để cả nhóm vẫn có trải nghiệm phù hợp.                                                       | Người lớn đang điều phối hoạt động cho gia đình đi cùng trẻ em/người lớn tuổi | Giả định: nhóm 4 người cần khoảng 5 phút (1 phút/người nêu nhu cầu, 1 phút thống nhất) khi bất đồng hoặc cần nghỉ; kiểm tra bằng quan sát, chưa khảo sát khách.                               |
|   8 | Lặp lại                      | Khi đã chọn một show muốn xem, tôi muốn kiểm tra liệu còn đủ thời gian chơi và di chuyển đến địa điểm biểu diễn hay không để tránh bỏ lỡ show.                                                                                       | Phụ huynh đi cùng trẻ, đã ghim/ưu tiên một show trong lịch tham quan | Giả định: nhóm kiểm tra trước 1 show/ngày; mỗi lần mất khoảng 3 phút (1 phút xem lịch, 2 phút đối chiếu thời gian đi bộ); cần ghi số lần thực tế trong ngày.                                  |

**Nếu có dùng AI để gợi ý thêm:**

- Tôi giữ lại ý tưởng tìm tiện ích thuận tuyến vì gắn trực tiếp với nhu cầu tôi đã nêu.
- Tôi giữ lại việc xét lịch show, thời gian nghỉ và hoạt động ghim vì chỉ giảm hàng chờ chưa chắc tạo trải nghiệm tốt.
- Tôi bỏ khỏi MVP các chức năng tự đặt phòng, thanh toán và triển khai toàn hệ thống vì làm tăng phạm vi và rủi ro.
- Tôi không chấp nhận số liệu tổn thất do AI ước tính như dữ liệu thực tế.
- Tôi điều chỉnh cách định vị: cần kiểm tra và nâng cấp tính năng hiện hữu của ứng dụng, tránh mặc định đây là chức năng hoàn toàn mới.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem                                                                | Vì sao chọn                                                                      | Điều còn chưa chắc                                                                                |
| ---: | ---------------------------------------------------------------------- | -------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
|    1 | Khó cập nhật kế hoạch đã lập theo thời gian chờ/tình trạng thực tế và lịch show | App đã lập được kế hoạch; khoảng trống là cập nhật kế hoạch theo tình hình và truy cập thông tin liên quan thuận tiện | Cần xác minh nguồn/cập nhật thời gian chờ; đo số lần chuyển mục và thời gian điều chỉnh kế hoạch |
|    2 | Khó tìm nhanh WC, nước và thông tin tiếp cận/trạng thái đông trong app | Nhu cầu phát sinh cụ thể; lần kiểm tra app cho thấy phải chuyển qua nhiều mục để tìm thông tin liên quan | Cần xác minh vị trí thông tin theo phiên bản/địa điểm; tần suất phát sinh và mốc chờ 15–30 phút chưa kiểm chứng |
|    3 | Khó xem menu nhà hàng thuận tiện khi chọn bữa ăn theo nhu cầu gia đình | Bám sát scan #6; kết hợp menu, thành phần gia đình và lịch vui chơi | Cần xác minh menu có ở mục khác không; thời gian order 30 phút và lợi ích so với danh sách lọc thông thường |

### Problem Card #1

| Trường                  | Nội dung                                                                                                                                                                                                                                                  |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story               | Khi kế hoạch vui chơi đã lập cần thay đổi vì hàng chờ hoặc tình trạng trò chơi, tôi muốn xem thông tin liên quan và cập nhật lựa chọn ngay trong luồng kế hoạch, đồng thời đối chiếu giờ show để không phải tự chuyển qua nhiều mục và vẫn kịp hoạt động ưu tiên. |
| Actor                   | Phụ huynh đang điều phối chuyến đi cho gia đình có trẻ nhỏ, chịu trách nhiệm chọn trò tiếp theo cùng các thành viên. Đây là actor mục tiêu giả định, cần xác nhận qua phỏng vấn/quan sát.                              |
| Thời điểm / bối cảnh    | Khi phụ huynh lập kế hoạch đầu ngày, chọn trò tiếp theo sau một hoạt động, hoặc phải đổi kế hoạch vì hàng chờ/tình trạng trò chơi thay đổi; gia đình có một show ưu tiên cần đến đúng giờ.                              |
| Quy trình hiện tại      | 1. Xem kế hoạch phù hợp đã lập trong app → 2. Khi tình trạng thay đổi, tìm thông tin chờ/hoạt động → 3. Chuyển mục để xem lịch show, đường đi hoặc tiện ích liên quan → 4. Tự so sánh lựa chọn thay thế → 5. Cập nhật kế hoạch và thống nhất với gia đình. |
| Bottleneck              | App đã hỗ trợ lập kế hoạch; khoảng trống quan sát được là phải chuyển qua nhiều mục để tra thông tin và chưa thấy kế hoạch tự cập nhật theo thời gian chờ/tình trạng thực tế. Thời lượng tìm/điều chỉnh chưa đo; các mốc ở scan chỉ là giả định để kiểm chứng. |
| Impact                  | Có thể mất thời gian quyết định, gặp thời gian chờ dài (scan nêu có thể đến 2 tiếng; cần xác minh), hoặc bỏ lỡ show yêu thích. Thời gian xếp hàng là thời gian trải nghiệm, không cộng vào thời gian tìm/chọn phương án.                                  |
| Success metric          | Đo thời gian và số lần chuyển mục để cập nhật một kế hoạch sau khi tình trạng thay đổi; theo dõi tỷ lệ hoàn thành trò/show ưu tiên. Chỉ đo độ chính xác thời gian chờ nếu có nguồn chờ thực tế để đối chiếu. Mục tiêu p90 ≤3 phút vẫn là target giả định, cần thiết lập baseline trước. |
| Phương án không dùng AI | Giữ bộ lập kế hoạch hiện có; thêm liên kết thông tin WC/menu/lịch/chờ vào cùng luồng, và quy tắc thông báo/cập nhật kế hoạch từ dữ liệu có sẵn, có dấu thời gian.                                                |
| Giả thuyết về AI        | LLM có thể giúp diễn đạt yêu cầu thay đổi và giải thích lựa chọn, nhưng chỉ khi dữ liệu thời chờ/tình trạng có nguồn tin cậy; so sánh với quy tắc và giao diện nối các mục trước khi kết luận cần AI.               |
| Cảm nhận nhanh          | **Workflow**: LLM Feature tùy chọn kết hợp rule và optimizer; chưa cần Agent tự trị.                                                                                                                                                                      |

Quy trình nháp hiện tại:

1. Phụ huynh mở kế hoạch phù hợp đã lập trong app.
2. Khi tình trạng trò chơi thay đổi, tìm thông tin chờ/tình trạng; hiện chưa thấy số chờ thực tế trong app theo lần kiểm tra.
3. Chuyển qua các mục để tra lịch show, đường đi, WC hoặc menu nếu cần.
4. Tự so sánh phương án thay thế với giờ show và nhu cầu gia đình.
5. Quay lại kế hoạch để sửa và thống nhất với gia đình.

Đây là quy trình rút ra từ lần kiểm tra app và cần kiểm chứng bằng task walkthrough với người dùng. Bấm giờ toàn bộ thao tác, số lần chuyển mục và số lần phải hỏi nhân viên; không dùng mốc 2 tiếng làm baseline khi chưa xác minh.

### Problem Card #2

| Trường                  | Nội dung                                                                                                                                                                                        |
| ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story               | Khi cần nhà vệ sinh hoặc mua nước, tôi muốn tìm điểm đang mở, thuận đường và phù hợp nhu cầu (như loại nước hoặc khả năng tiếp cận) để không đi vòng hay phải chờ lâu ở điểm quá đông.          |
| Actor                   | Người lớn đang chăm sóc trẻ nhỏ hoặc hỗ trợ thành viên hạn chế khả năng di chuyển, cần tìm nhà vệ sinh/điểm mua nước phù hợp cho người đi cùng. Actor đại diện chính cần kiểm chứng; hai tình huống tiện ích có thể cần tách khi nghiên cứu. |
| Thời điểm / bối cảnh    | Khi phát sinh nhu cầu trong ngày tham quan.                                                                                                                                                     |
| Quy trình hiện tại      | 1. Phát sinh nhu cầu → 2. Chuyển mục/tìm WC hoặc điểm mua nước trong app → 3. Tra vị trí, đường đi và khả năng tiếp cận → 4. Hỏi nhân viên hoặc chọn điểm → 5. Di chuyển và sử dụng.             |
| Bottleneck              | Qua lần kiểm tra app, chưa tìm thấy điểm xem WC thuận tiện trong cùng luồng kế hoạch và phải chuyển nhiều mục để tìm thông tin liên quan. Thời gian tìm/chọn và mốc chờ 15–30 phút đều cần đo/xác minh. |
| Impact                  | Có thể đi vòng, chọn nhầm điểm không phù hợp hoặc phải chờ ở điểm đông; tác động rõ hơn với gia đình có trẻ nhỏ/người cần tiếp cận thuận tiện.                                                  |
| Success metric          | Đo riêng thời gian tìm/chọn, quãng đường đi vòng và thời gian chờ thực tế. Mục tiêu thử nghiệm: p90 tìm được điểm phù hợp ≤10 giây; ≥95% gợi ý đúng vị trí/trạng thái từ nguồn kiểm chứng.      |
| Phương án không dùng AI | Bản đồ phân loại nhà vệ sinh/nước, lọc trạng thái và khả năng tiếp cận, sắp xếp theo đường đi.                                                                                                  |
| Giả thuyết về AI        | Hội thoại có thể hiểu yêu cầu kết hợp như loại nước và điểm thuận đường; tìm điểm gần nhất đơn giản có thể giải quyết bằng bộ lọc thông thường.                                                 |
| Cảm nhận nhanh          | **Rule** cho tìm kiếm cơ bản; **Workflow** khi cần kết hợp nhiều điều kiện và giải thích lựa chọn.                                                                                              |

Quy trình nháp hiện tại:

1. Khách phát sinh nhu cầu (nhà vệ sinh hoặc mua nước).
2. 🔄 Tìm tiện ích trên bản đồ hoặc hỏi nhân viên (scan ước tính tìm/chọn khoảng 3 phút). 🔴
3. Kiểm tra điểm đang mở, đường đi và khả năng tiếp cận.
4. Chọn điểm; nếu là nhà vệ sinh, ghi riêng thời gian chờ sử dụng (scan nêu 15–30 phút, cần kiểm chứng).
5. Di chuyển đến điểm đã chọn.

### Problem Card #3

| Trường                  | Nội dung                                                                                                                                                                                                                                                          |
| ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Job Story               | Khi cần ăn trong ngày tham quan, tôi muốn xem trước menu và chọn nơi phù hợp với ngân sách, lịch trình, số lượng người và nhu cầu của gia đình (người lớn tuổi/trẻ nhỏ) để cả nhóm ăn phù hợp mà không lỡ hoạt động tiếp theo.                                    |
| Actor                   | Phụ huynh/người lớn chịu trách nhiệm chọn bữa ăn cho gia đình có trẻ nhỏ hoặc người lớn tuổi, trong khung giờ giữa hai hoạt động đã lên lịch. Đây là actor mục tiêu giả định, cần xác nhận với khách thực tế.                                                                                  |
| Thời điểm / bối cảnh    | Trước giờ ăn hoặc khi lịch trình thay đổi; cần cân nhắc cả thời gian order và hoạt động tiếp theo.                                                                                                                                                                |
| Quy trình hiện tại      | 1. Nêu nhu cầu bữa ăn và thành phần nhóm → 2. Chuyển mục tìm nhà hàng/menu → 3. Tra giá và thời gian chờ nếu có → 4. Đối chiếu vị trí, đường đi, lịch vui chơi → 5. Quay lại kế hoạch và thống nhất lựa chọn.                                                                                                                          |
| Bottleneck              | Qua lần kiểm tra app, chưa tìm thấy menu nhà hàng ở một chỗ thuận tiện trong luồng kế hoạch; phải chuyển nhiều mục. Mốc so sánh 3 nhà hàng/6 phút và chờ order 30 phút đều là giả định cần xác minh riêng.                                                                                                                        |
| Impact                  | Có thể chọn nơi không phù hợp với thành viên, chờ lâu hoặc không kịp hoạt động tiếp theo.                                                                                                                                                                         |
| Success metric          | Đo thời gian chọn, độ chính xác/cập nhật của menu và sai lệch thời gian chờ hiển thị so với thực tế. Mục tiêu thử nghiệm: p90 chọn nhà hàng ≤3 phút và thông tin menu được xác minh trước khi hiển thị; không cam kết giảm thời gian phục vụ khi chưa có dữ liệu. |
| Phương án không dùng AI | Danh sách nhà hàng có menu, giá, thông tin tiếp cận và bộ lọc theo vị trí, giờ mở, nhu cầu nhóm; hiển thị thời gian chờ nếu có nguồn đáng tin cậy.                                                                                                                |
| Giả thuyết về AI        | AI có thể diễn giải yêu cầu nhóm nhiều điều kiện và tóm tắt điểm phù hợp/đánh đổi; cần so sánh với bộ lọc menu và tiêu chí có cấu trúc.                                                                                                                           |
| Cảm nhận nhanh          | **Workflow** nếu menu/trạng thái có nguồn đủ tin cậy; nếu không, bắt đầu bằng danh sách/bộ lọc với dữ liệu đã xác minh.                                                                                                                                           |

Quy trình nháp hiện tại:

1. Nêu nhu cầu bữa ăn và thành phần nhóm.
2. 🔄 Tìm nhà hàng, so sánh menu/giá của khoảng 3 lựa chọn (giả định khoảng 6 phút). 🔴
3. 🔄 Hỏi hoặc kiểm tra thời gian chờ order (scan nêu 30 phút, cần xác minh). 🔴
4. Đối chiếu vị trí, đường đi và lịch hoạt động tiếp theo.
5. Nhóm thống nhất điểm ăn.

### Card muốn pitch nhất

- **Card số:** 1.
- **Vì sao:** Card #1 không giả định app thiếu chức năng lập kế hoạch; tập trung vào việc cập nhật kế hoạch đã lập khi tình trạng thay đổi và giảm việc phải chuyển nhiều mục để tìm dữ liệu liên quan.
- **Câu hỏi muốn nhóm phản biện:** App có cung cấp thời gian chờ thực tế từ nguồn nào và cập nhật với tần suất ra sao? Có cách đưa thông tin chờ, WC và menu vào luồng kế hoạch mà không cần LLM không? Dữ liệu nào khả thi cho prototype?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra                                                    | Đồng ý? | Đã sửa gì                                                                                                     |
| --------------------------------------------------------------------- | ------- | ------------------------------------------------------------------------------------------------------------- |
| Các mốc 2 tiếng, 15–30 phút và 30 phút chưa có nguồn/đo lường rõ ràng | Có      | Ghi là số cần kiểm chứng; tách thời gian tìm/chọn khỏi thời gian xếp hàng hoặc sử dụng                        |
| App đã có chức năng lập kế hoạch; giả định làm mới toàn bộ là không đúng | Có      | Giữ chức năng lập kế hoạch hiện có; tập trung vào cập nhật theo tình trạng/chờ thực tế và giảm chuyển mục để xem dữ liệu liên quan |
| Chưa rõ cách khách tìm WC/menu hoặc cập nhật kế hoạch khi tình trạng đổi | Có      | Ghi nhận từ lần kiểm tra app phải chuyển nhiều mục; cần task walkthrough để xác minh bước, thời gian và vị trí tính năng theo phiên bản/địa điểm |
| Thuật toán/bộ lọc thông thường có thể tạo phần lớn giá trị            | Có      | Tách LLM khỏi rule/optimizer và đề xuất so sánh có/không LLM                                                  |
| Dữ liệu chờ, menu hoặc trạng thái tiện ích có thể thiếu/cũ            | Có      | Chỉ hiển thị thông tin có nguồn và dấu thời gian; đặt ngưỡng hết hạn, fallback khi không có dữ liệu           |
| Giảm thời gian chờ không hoàn toàn nằm trong quyền kiểm soát sản phẩm | Có      | Đo riêng thời gian quyết định, sai lệch dự báo và tỷ lệ hoàn thành hoạt động ưu tiên; không hứa giảm hàng chờ |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

> Nội dung “đã làm” chỉ ghi việc xác nhận được từ quá trình chuẩn bị cá nhân. Hoạt động với nhóm cần cập nhật đúng thực tế.

| Hoạt động                  | Tôi đã làm gì?                                                                               | Kết quả / ảnh hưởng tới bài nhóm                                                    |
| -------------------------- | -------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| Pitch Problem Card         | Đã chuẩn bị cách giới thiệu vấn đề từ góc nhìn khách và các câu trả lời phản biện            | Có nội dung để pitch; [điền kết quả trình bày thực tế]                              |
| Phản biện bài của bạn khác | Đã chuẩn bị câu hỏi về nguồn số liệu, baseline, vai trò AI và ROI của case chống gian lận    | [Điền câu đã thực sự hỏi và phản hồi nhận được]                                     |
| Nhận phản biện             | Trong trao đổi với AI, nhận câu hỏi về dữ liệu chờ, tính năng hiện hữu và phương án không AI | Đã thu hẹp phạm vi, bổ sung giả định và fallback; [bổ sung phản biện từ người thật] |
| Gom cluster / cây OST      | Đề xuất các cụm: chọn/đổi trò và canh giờ show; tìm tiện ích; chọn bữa ăn theo nhu cầu nhóm  | [Chưa xác nhận nhóm đã lập OST; cập nhật kết quả thật]                              |
| Chọn candidate problem     | Cá nhân ưu tiên Card #1                                                                      | [Cập nhật quyết định chính thức của nhóm]                                           |
| Kiểm chứng / research      | Kiểm tra app VinWonders và dùng AI hỗ trợ tìm/đối chiếu nguồn công khai                     | Xác nhận app có lập kế hoạch; ghi nhận khoảng trống về điều chỉnh theo tình trạng/chờ thực tế và việc phải chuyển nhiều mục để tìm WC/menu; chưa phỏng vấn/survey |
| Quy trình nhóm             | Đã chuẩn bị mô hình current-state 4 làn, 6 bước và handoff                                   | Có sơ đồ nháp; thời gian cần xác minh và nhóm review                                |
| Problem Statement          | Đã chuẩn bị 6 trường, metric và operational boundary                                         | Tách được mục tiêu trải nghiệm, dữ liệu và quyền thao tác                           |
| Mức can thiệp AI           | Đề xuất LLM Feature + rule + optimizer                                                       | Chưa cần Agent tự trị; cần so sánh với phương án không LLM                          |
| Quyết định                 | Đề xuất GO cho prototype hẹp, NOT YET cho pilot thực địa                                     | [Cập nhật quyết định được nhóm thống nhất]                                          |

---

## 5. Dùng AI

| Checkpoint                     | Tôi dùng AI để làm gì?                         | AI hữu ích ở đâu?                                                               | AI sai hoặc hời hợt ở đâu?                                          | Tôi sửa gì bằng nhận định của mình?                                             |
| ------------------------------ | ---------------------------------------------- | ------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| CP1 Scan                       | Mở rộng các vấn đề quanh hành trình VinWonders | Phân tách sở thích, hàng chờ, tuyến, show, tiện ích và nhu cầu ăn uống của nhóm | Có thể mở rộng thành quá nhiều tính năng                            | Giữ các nhu cầu đã nêu, bỏ đặt phòng và thanh toán khỏi MVP                     |
| CP2 Problem Card               | Viết card và stress-test như CFO/vận hành      | Đặt câu hỏi về actor, bottleneck và metric                                      | Số liệu ước tính dễ bị hiểu là số thật                              | Ghi rõ giả định; tách thời gian tìm/chọn khỏi thời gian xếp hàng và đo baseline |
| CP4 Research                   | Tìm nguồn công khai về app và tiền lệ ngành    | Giúp nhận diện chức năng đã được giới thiệu                                     | Review riêng lẻ không chứng minh mức phổ biến hoặc ROI              | Chỉ dùng làm tín hiệu định tính; cần khảo sát thêm                              |
| CP5 Quy trình                  | Mô hình hóa swimlane, bước và handoff          | Làm rõ trách nhiệm và đầu vào/đầu ra                                            | Sơ đồ có thể khiến quy trình giả định trông như thực tế đã xác minh | Ghi rõ phạm vi lượt quyết định và không bắt quản lý duyệt từng tuyến            |
| CP5–6 Problem Statement        | Viết 6-field, metric và boundary               | Tách nhu cầu khỏi giải pháp                                                     | Dễ trộn thời gian khách, giờ nhân viên và tiền tiết kiệm            | Không quy thời gian khách thành tiền; tách trung bình khỏi p90                  |
| CP6 Mức can thiệp / quyết định | So sánh Rule, LLM và Agent; kiểm tra ROI       | Giúp xây điều kiện GO/NOT YET                                                   | Không thể chứng minh AI bắt buộc hay lợi nhuận chắc chắn            | Giữ baseline không LLM, GO theo phạm vi và không cam kết hòa vốn dưới một tháng |

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
