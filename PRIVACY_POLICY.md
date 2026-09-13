# Chính sách quyền riêng tư LÂM MUSIC

**Cập nhật: 13/09/2026**

Chính sách này áp dụng cho ứng dụng LÂM MUSIC, các tính năng LÂM MAP trong ứng dụng và trang thông tin của ứng dụng. Đơn vị phát triển được giới thiệu trong ứng dụng là **Lâm Đại Ka**. Liên hệ về dữ liệu cá nhân và hỗ trợ: [lamdltb@gmail.com](mailto:lamdltb@gmail.com).

Ứng dụng kết hợp phát nhạc, YouTube, radio, TV, thư viện cá nhân, đồng bộ tài khoản và hỗ trợ bản đồ. Dữ liệu được xử lý phụ thuộc vào tính năng bạn sử dụng, quyền bạn cấp, gói dịch vụ và phiên bản ứng dụng. Không phải phiên bản hay thiết bị nào cũng có tất cả các tính năng dưới đây.

**Lưu ý về vị trí:** khi bạn bật tính năng hỗ trợ lái xe hoặc cảnh báo giao thông và cấp quyền phù hợp, ứng dụng có thể sử dụng vị trí ngay cả khi bạn chuyển sang ứng dụng khác hoặc tắt màn hình. Khi dùng bản đồ, tìm đường, tra cứu đường hoặc giao thông trực tuyến, vị trí hay khu vực bạn yêu cầu có thể được gửi tới máy chủ LÂM MUSIC và nhà cung cấp bản đồ để trả kết quả. Bạn có thể dừng tính năng hoặc thu hồi quyền vị trí trong cài đặt Android.

Bạn có thể [xem hướng dẫn xóa tài khoản và dữ liệu](https://dlthoibinh.github.io/lam-music-pro/account-deletion.html) mà không cần mở ứng dụng.

## 1. Tài khoản, thiết bị và quyền sử dụng

Khi đăng nhập bằng Google hoặc email, dịch vụ xác thực xử lý thông tin đăng nhập. LÂM MUSIC nhận thông tin hồ sơ cần thiết như mã tài khoản, email, tên hiển thị và ảnh đại diện nếu có, để nhận diện tài khoản, hiển thị hồ sơ và đồng bộ dữ liệu. Đăng nhập Google được xử lý qua Google; mật khẩu riêng của tài khoản email được xử lý bởi Firebase Authentication.

Khi đăng ký hoặc sử dụng thiết bị với tài khoản, ứng dụng gửi tên và loại thiết bị, hãng, model, phiên bản Android và ứng dụng, khả năng phát hoặc điều khiển nội dung, thời điểm hoạt động cùng mã nhận diện thiết bị. Mã nhận diện được tạo từ mã Android của thiết bị hoặc mã cài đặt thay thế. Chúng được dùng để quản lý thiết bị, đồng bộ, bảo vệ tài khoản và kiểm tra quyền sử dụng.

Để hạn chế tạo nhiều tài khoản nhằm nhận lại dùng thử miễn phí, dịch vụ lưu dấu xác nhận dùng thử gắn với tài khoản, email và thiết bị dưới dạng mã băm, tức mã đã được chuyển đổi để đối chiếu. Đây vẫn là dữ liệu có thể liên kết với tài khoản hoặc thiết bị; không phải dữ liệu hoàn toàn ẩn danh. Các dấu này có thể được giữ sau khi xóa tài khoản; xem mục 8.

Ứng dụng và dịch vụ xác minh ứng dụng cũng xử lý thông tin cần thiết để kiểm tra yêu cầu hợp lệ, hạn chế truy cập tự động và gian lận. Kết nối tới dịch vụ có thể để lại địa chỉ IP, thời gian yêu cầu, trạng thái và thông tin lỗi trong nhật ký vận hành.

## 2. Thư viện, đồng bộ và thiết bị liên kết

Khi bạn cấp quyền truy cập nhạc hoặc video, ứng dụng đọc thông tin tệp được phép truy cập như tên, nghệ sĩ, thời lượng, loại tệp, kích thước và vị trí tệp để lập thư viện và phát nội dung. Việc quét thư viện không tự gửi toàn bộ tệp nhạc hoặc video lên máy chủ LÂM MUSIC.

Khi sử dụng đồng bộ, các nội dung được hỗ trợ như cài đặt, thông tin thư viện, danh sách phát, lịch sử và mục yêu thích YouTube, radio hoặc TV, nguồn TV bạn thêm và liên kết Google Drive có thể được lưu với tài khoản trên dịch vụ đám mây. Đồng bộ thông tin thư viện không đồng nghĩa với sao lưu toàn bộ tệp nhạc hoặc video.

Khi dùng điều khiển hoặc chuyển nội dung giữa các thiết bị đã liên kết, thông tin thiết bị và nội dung đang phát, hàng đợi, trạng thái phát, thời điểm trong bài cùng lệnh điều khiển được trao đổi để thực hiện lựa chọn của bạn. Người có quyền truy cập thiết bị hoặc tài khoản liên kết có thể thấy những thông tin này.

Đăng xuất hoặc đổi tài khoản không tự xóa thư viện và dữ liệu đang có trên máy. Một số nội dung trên máy có thể tiếp tục xuất hiện và được kết hợp khi đồng bộ bằng tài khoản tiếp theo. Nếu dùng chung hoặc chuyển giao thiết bị, hãy xóa dữ liệu cá nhân trên máy trước khi người khác sử dụng.

## 3. YouTube, nghe nền và lưu để nghe ngoại tuyến

LÂM MUSIC sử dụng **YouTube Data API** cho một số chức năng tìm kiếm và cũng có đường tìm kiếm qua trang YouTube. Tùy cách tìm kiếm, nội dung bạn nhập và lựa chọn ngôn ngữ, khu vực được gửi tới dịch vụ tìm kiếm LÂM MUSIC hoặc trực tiếp tới Google/YouTube để trả kết quả. Khi tìm kiếm, mở video, ảnh hoặc phát nội dung, ứng dụng kết nối tới YouTube/Google; nhà cung cấp nhận thông tin yêu cầu và thông tin kết nối như địa chỉ IP.

Video có thể được xem bằng trình phát YouTube nhúng. Ở phiên bản hỗ trợ, khi bạn chọn **Nghe nền**, LÂM MUSIC dùng trình phát âm thanh của ứng dụng và kết nối tới nguồn phát YouTube để tiếp tục nghe khi chuyển ứng dụng hoặc khóa màn hình.

Quá trình phát có thể tạo dữ liệu đệm trên thiết bị. Nếu phiên bản và nội dung hỗ trợ lưu ngoại tuyến, lựa chọn tải hoặc lưu có thể lưu dữ liệu âm thanh cùng thông tin bài, nguồn, ảnh, kích thước và trạng thái tải. Bạn có thể xóa nội dung đã lưu trong phần quản lý tải hoặc ngoại tuyến. Cài đặt dung lượng và việc dọn bộ nhớ cũng có thể ảnh hưởng nội dung được giữ.

Lịch sử và yêu thích trong LÂM MUSIC có thể được lưu trên máy và đồng bộ khi bạn dùng tính năng tương ứng. Xóa chúng trong LÂM MUSIC không tự xóa lịch sử của tài khoản YouTube/Google hoặc mọi tệp đã tải. Trình duyệt YouTube trong ứng dụng có thể sử dụng cookie và dữ liệu trang web, kể cả cookie của bên thứ ba. Nút đặt lại trình phát không đồng nghĩa với xóa mọi cookie hoặc đăng xuất khỏi Google.

Bạn có thể tham khảo [Chính sách quyền riêng tư Google](https://policies.google.com/privacy) và [Điều khoản YouTube](https://www.youtube.com/t/terms) khi sử dụng những dịch vụ này.

## 4. Google Drive, radio, TV và tìm kiếm bằng giọng nói

Khi bạn mở liên kết, thư mục hoặc tệp Google Drive, ứng dụng và dịch vụ Google xử lý đường dẫn, mã tệp hoặc thư mục và thông tin cần thiết để liệt kê, xem hoặc tải nội dung bạn chọn. Bạn cũng có thể chọn tệp qua trình chọn tài liệu Android. Việc này không tự cấp cho LÂM MUSIC quyền đọc toàn bộ tài khoản Drive.

Trình duyệt Drive có thể lưu cookie hoặc phiên đăng nhập của Google. Tệp xem trước có thể nằm trong bộ nhớ đệm; tệp bạn tải để sử dụng tiếp được lưu trên thiết bị. Liên kết Drive bạn đưa vào thư viện có thể được đồng bộ theo mục 2. Hãy cân nhắc quyền chia sẻ của liên kết trước khi đưa vào thư viện dùng trên thiết bị chung.

Ứng dụng sử dụng danh mục **Radio Browser** để tìm đài radio. Từ khóa, quốc gia và thể loại bạn chọn được gửi tới dịch vụ danh mục để lọc kết quả. Khi bạn chọn phát đài từ danh mục, ứng dụng có thể gửi mã đài tới Radio Browser để ghi nhận lượt chọn. Dịch vụ nhận thông tin kết nối như địa chỉ IP và phiên bản ứng dụng trong yêu cầu.

Khi bạn phát radio, TV hoặc nguồn trực tuyến đã thêm, thiết bị kết nối tới nhà cung cấp nguồn đó. Nhà cung cấp có thể nhận địa chỉ IP và thông tin về nội dung được yêu cầu theo chính sách của họ.

Khi bạn chủ động tìm kiếm bằng giọng nói, dịch vụ nhận dạng giọng nói được chọn trên Android xử lý âm thanh và trả văn bản cho ứng dụng để tìm kiếm. Dịch vụ đó có thể xử lý âm thanh trên máy hoặc trực tuyến. Tính năng này không phải lời cam kết rằng mọi âm thanh chỉ được xử lý trên thiết bị.

## 5. Vị trí, bản đồ và báo cáo giao thông

Ứng dụng sử dụng tọa độ, độ chính xác, hướng di chuyển và tốc độ khi cần cho hiển thị vị trí, tìm đường, cảnh báo hoặc hỗ trợ lái xe. Việc xử lý vị trí trong nền phục vụ tính năng đang bật như đã nêu ở đầu chính sách; bạn có thể dừng trong ứng dụng hoặc thu hồi quyền Android.

Khi sử dụng dịch vụ trực tuyến:

- Tìm đường có thể gửi điểm xuất phát, đích đến, điểm dừng, lựa chọn di chuyển và mã phiên thiết bị tới dịch vụ LÂM MUSIC; dịch vụ tìm đường có thể gửi tọa độ và lựa chọn tuyến tới TomTom.
- Tìm địa điểm có thể gửi từ khóa, địa điểm đã chọn, ngôn ngữ và vị trí hoặc khu vực tìm kiếm tới Google Places hoặc dịch vụ tìm địa chỉ trên Android.
- Tra cứu giao thông hoặc cảnh báo gần bạn có thể gửi vị trí, tốc độ, hướng, độ chính xác và mã phiên thiết bị tới LÂM MUSIC. Các nhà cung cấp giao thông hoặc bản đồ nhận yêu cầu về khu vực cần tra cứu.
- Tra cứu thông tin đường và biển báo có thể gửi tọa độ, khu vực tìm kiếm tới các dịch vụ Overpass sử dụng dữ liệu OpenStreetMap. Lớp bản đồ trực tuyến có thể yêu cầu ô bản đồ từ OpenFreeMap hoặc nhà cung cấp được cấu hình.

Khi bạn gửi báo cáo sự cố giao thông hoặc xác nhận một báo cáo, dữ liệu có thể gồm loại sự cố, tọa độ, hướng, tốc độ, độ chính xác, đường liên quan và lựa chọn xác nhận. Máy chủ lưu thông tin này cùng mã đã chuyển đổi từ tài khoản để kiểm tra chất lượng, hạn chế báo cáo giả và tổng hợp sự cố. **Vị trí và nội dung sự cố tổng hợp có thể được hiển thị cho người dùng khác.** Thông tin công khai không chứa mã tài khoản người báo cáo, nhưng tọa độ và thời điểm vẫn có thể là thông tin nhạy cảm.

Báo cáo chưa gửi được có thể tạm lưu trên máy để gửi lại khi có kết nối. Dữ liệu cảnh báo và bản đồ tải về cũng có thể lưu trên máy để sử dụng ngoại tuyến. Gỡ ứng dụng không tự xóa báo cáo đã gửi lên máy chủ.

Nếu bạn chủ động xuất hoặc gửi bản chẩn đoán để hỗ trợ, tệp đó có thể chứa trạng thái lái xe và tọa độ. Hãy xem nội dung trước khi chia sẻ. Việc xuất tệp không tự đồng nghĩa với gửi tệp cho nhà phát triển.

## 6. Quảng cáo, giao dịch và thông báo

**Quảng cáo.** Ở màn hình hoặc phiên bản có quảng cáo, Google Mobile Ads có thể xử lý địa chỉ IP để suy ra vị trí gần đúng, mã quảng cáo hoặc mã nhận diện khác, tương tác với ứng dụng/quảng cáo và dữ liệu chẩn đoán để phân phối, đo lường và bảo vệ dịch vụ quảng cáo. Cách xử lý còn phụ thuộc thiết bị, khu vực và lựa chọn của bạn. Xem [thông tin dữ liệu của Google Mobile Ads](https://developers.google.com/admob/android/privacy/play-data-disclosure).

Ứng dụng sử dụng công cụ lựa chọn quyền riêng tư của Google. Khi có yêu cầu hoặc tùy chọn áp dụng, bạn có thể quản lý lựa chọn quảng cáo trong ứng dụng; bạn cũng có thể quản lý hoặc xóa mã quảng cáo trong cài đặt Android. Từ chối cá nhân hóa quảng cáo không nhất thiết loại bỏ mọi quảng cáo hoặc mọi xử lý cần thiết cho quảng cáo.

**Giao dịch Google Play.** Google Play xử lý thanh toán. LÂM MUSIC nhận dữ liệu cần để xác minh và khôi phục quyền lợi, như sản phẩm đã mua, mã xác minh giao dịch, thời điểm, trạng thái và thời hạn gói. Dữ liệu giao dịch được đối chiếu với tài khoản nhằm tránh dùng một giao dịch cho nhiều tài khoản. Ứng dụng không thu thập số thẻ hoặc thông tin đăng nhập ngân hàng qua màn hình mua gói của mình.

**Thông báo.** Khi bạn bật thông báo, Firebase Cloud Messaging xử lý mã nhận thông báo của thiết bị và chủ đề thông báo đã đăng ký để chuyển nội dung. Bạn có thể đổi lựa chọn thông báo trong ứng dụng hoặc cài đặt Android. Tắt thông báo không tự xóa tài khoản hay dữ liệu đã đồng bộ.

## 7. Quyền trên thiết bị và lựa chọn của bạn

Ứng dụng có thể yêu cầu các quyền sau khi cần cho tính năng tương ứng:

- **Vị trí chính xác hoặc gần đúng, kể cả trong nền:** bản đồ, tìm đường và cảnh báo giao thông khi được bật.
- **Nhạc, video hoặc tệp bạn chọn:** lập thư viện, phát và quản lý nội dung được phép truy cập.
- **Micro:** tìm kiếm bằng giọng nói do bạn khởi động.
- **Thiết bị ở gần/Bluetooth:** làm việc với thiết bị âm thanh hoặc thiết bị tương thích.
- **Thông báo:** thông báo dịch vụ, nội dung mới và trạng thái tính năng.
- **Hiển thị trên ứng dụng khác:** bảng cảnh báo nổi khi bạn bật tính năng này.

Bạn có thể kiểm tra hoặc thu hồi quyền tại **Cài đặt Android → Ứng dụng → LÂM MUSIC**. Một số quyền nằm trong mục quyền truy cập đặc biệt. Thu hồi quyền hoặc tắt tính năng sẽ giới hạn hoạt động tương ứng; dữ liệu đã gửi trước đó không tự được xóa.

## 8. Lưu trữ và thời gian giữ dữ liệu

- **Dữ liệu trên thiết bị:** cài đặt, lịch sử, thư viện, cookie, dữ liệu đệm và nội dung tải được giữ tùy loại cho đến khi bạn xóa, ứng dụng dọn theo giới hạn dung lượng hoặc dữ liệu ứng dụng bị xóa. Một số tệp đã lưu ở vị trí khác có thể vẫn còn sau khi gỡ ứng dụng; hãy kiểm tra bằng trình quản lý tệp.
- **Hồ sơ và dữ liệu đồng bộ trên máy chủ:** được giữ để vận hành tài khoản cho đến khi việc xóa tài khoản được hoàn tất, trừ các dữ liệu cần giữ được nêu dưới đây. Đăng xuất và gỡ ứng dụng không thay thế yêu cầu xóa tài khoản.
- **Dấu chống nhận lại dùng thử:** mã đối chiếu tài khoản, email, thiết bị và lịch sử đã nhận dùng thử được giữ sau khi xóa tài khoản để ngăn tạo lại tài khoản lấy thêm lượt thử. **Hiện các bản ghi này chưa có thời hạn tự động xóa.** Bạn có thể liên hệ để yêu cầu xem xét dữ liệu được giữ.
- **Dấu đối chiếu giao dịch đã xử lý:** sau khi xóa tài khoản đủ điều kiện, một số bản ghi chống sử dụng lại giao dịch được giữ bằng mã đối chiếu tài khoản và trạng thái đã xóa. Với các bản ghi giao dịch được xử lý trong quy trình này, mã tài khoản trực tiếp, mã xác minh mua hàng và mã đơn được loại bỏ. Các dấu đối chiếu còn lại hiện chưa có thời hạn tự động xóa. Lịch sử thanh toán do Google Play quản lý không bị xóa theo thao tác xóa tài khoản LÂM MUSIC.
- **Báo cáo giao thông:** có thời hạn hiệu lực theo loại sự cố, có thể được gia hạn khi có báo cáo hoặc xác nhận mới. Hết hiệu lực hiển thị không có nghĩa mọi bản sao đã bị xóa ngay. Dữ liệu sự cố đã tổng hợp có thể còn được giữ sau khi xử lý xóa liên kết người báo cáo.
- **Nhật ký vận hành và thư hỗ trợ:** có thể được giữ để xử lý lỗi, yêu cầu của bạn, bảo vệ dịch vụ và giải quyết tranh chấp. Hiện chúng tôi chưa công bố một thời hạn xóa chung cho mọi hệ thống nhật ký hoặc thư hỗ trợ; bạn có thể liên hệ để hỏi về dữ liệu cụ thể.

Các nhà cung cấp bên ngoài áp dụng chính sách lưu trữ riêng cho dữ liệu họ xử lý. Thời gian dữ liệu đệm còn được sử dụng để trả kết quả không đồng nghĩa với thời hạn xóa của máy chủ.

## 9. Xóa tài khoản, dữ liệu và quản lý gói mua

Bạn có thể mở **Cá nhân → Tài khoản & thiết bị → Xóa tài khoản & dữ liệu đám mây**, đọc thông báo và xác nhận. Bạn có thể được yêu cầu đăng nhập lại để bảo vệ tài khoản. Khi thành công, quy trình xóa tài khoản đăng nhập, hồ sơ và dữ liệu đồng bộ của tài khoản trên máy chủ; các ngoại lệ tại mục 8 vẫn áp dụng.

Nếu còn quyền mua đang hoạt động, có giao dịch cần xác minh hoặc không thể dùng thao tác trong ứng dụng, hãy dùng **Yêu cầu hỗ trợ xóa tài khoản** hoặc gửi email tới [lamdltb@gmail.com](mailto:lamdltb@gmail.com). Bạn cũng có thể gửi yêu cầu từ [trang xóa tài khoản](https://dlthoibinh.github.io/lam-music-pro/account-deletion.html) mà không cần cài ứng dụng. Việc hỗ trợ cần xác minh quyền sở hữu và làm rõ cách xử lý quyền mua; không yêu cầu mật khẩu hoặc mã dùng một lần.

**Xóa tài khoản không tự hủy thuê bao Google Play.** Bạn có thể quản lý thuê bao trong Google Play. Với quyền mua một lần, bạn không cần chờ quyền hết hạn để yêu cầu hỗ trợ xóa tài khoản. Mở trình soạn email hoặc gửi yêu cầu không có nghĩa việc xóa đã hoàn tất.

Tệp nhạc, video và dữ liệu còn trên thiết bị không tự bị xóa bởi thao tác xóa tài khoản đám mây. Bạn cần xóa lịch sử, nội dung tải hoặc dữ liệu ứng dụng riêng nếu muốn dọn thiết bị. Dữ liệu của tài khoản Google, YouTube, Drive và lịch sử mua trên Google Play được quản lý tại các dịch vụ đó.

Bạn cũng có thể liên hệ để hỏi dữ liệu nào đang được xử lý, yêu cầu chỉnh sửa thông tin hoặc yêu cầu xem xét xóa dữ liệu cụ thể mà không xóa toàn bộ tài khoản. Yêu cầu cần xác minh phù hợp để tránh tiết lộ dữ liệu cho người khác.

## 10. Bên nhận dữ liệu và xử lý ngoài Việt Nam

Dữ liệu được chuyển tới các dịch vụ cần cho tính năng bạn dùng: Google/Firebase cho tài khoản, dữ liệu đám mây, xác minh và thông báo; Google Play cho giao dịch; Google Mobile Ads cho quảng cáo; YouTube và nhà cung cấp nhạc/TV/radio cho nội dung; Radio Browser cho tìm đài và ghi nhận lượt chọn; Google Drive cho tệp bạn mở; Google Places, TomTom, dịch vụ địa chỉ Android, Overpass và nhà cung cấp ô bản đồ cho các chức năng bản đồ tương ứng. Các thiết bị đã liên kết và người dùng xem báo cáo giao thông nhận dữ liệu theo mục 2 và 5.

Những nhà cung cấp này có thể xử lý dữ liệu tại hạ tầng ngoài Việt Nam. Chính sách này không cam kết mọi dữ liệu chỉ nằm tại Việt Nam. Bạn có thể đọc [Chính sách Google](https://policies.google.com/privacy), [thông tin quyền riêng tư Firebase](https://firebase.google.com/support/privacy) và [Chính sách TomTom](https://www.tomtom.com/en-gb/privacy/).

Khi bạn gửi email hỗ trợ, nội dung thư và tệp bạn đính kèm được xử lý bởi nhà cung cấp email cùng người phụ trách hỗ trợ. Nếu mở liên kết ngoài, dịch vụ được mở áp dụng chính sách riêng cho việc sử dụng của bạn.

Trang thông tin này được lưu trên GitHub Pages. Trang không cài công cụ thống kê, phông chữ từ xa hoặc biểu mẫu thu thập dữ liệu riêng. GitHub có thể xử lý thông tin truy cập để cung cấp và bảo vệ dịch vụ lưu trữ theo [Chính sách quyền riêng tư GitHub](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

## 11. Bảo vệ dữ liệu

Ứng dụng sử dụng xác thực tài khoản, kiểm tra quyền truy cập và các cơ chế kiểm tra yêu cầu để bảo vệ dữ liệu. Kết nối với các dịch vụ Firebase, Google và các dịch vụ trực tuyến được hỗ trợ sử dụng cơ chế bảo mật của từng dịch vụ. Không phương thức truyền hoặc lưu trữ nào có thể bảo đảm an toàn tuyệt đối.

Hãy bảo vệ thiết bị và tài khoản của bạn. Không gửi mật khẩu, mã dùng một lần, mã đăng nhập hoặc mã xác minh giao dịch đầy đủ qua email hỗ trợ. Nếu cần gửi ảnh hoặc tệp chẩn đoán, hãy kiểm tra và che thông tin riêng không cần thiết.

## 12. Câu hỏi, dữ liệu trẻ em và thay đổi chính sách

Nếu bạn cho rằng dữ liệu của trẻ em đã được cung cấp không phù hợp hoặc cần hỗ trợ về dữ liệu của người bạn đại diện hợp pháp, hãy liên hệ để được xem xét và xác minh yêu cầu. Việc sử dụng dịch vụ Google, YouTube hoặc nhà cung cấp khác còn phụ thuộc điều kiện tài khoản của những dịch vụ đó.

Chúng tôi có thể cập nhật chính sách khi tính năng hoặc cách xử lý dữ liệu thay đổi. Ngày cập nhật ở đầu trang giúp bạn nhận biết phiên bản. Với nội dung cần xác nhận lại trong ứng dụng, ứng dụng có thể hiển thị thông báo để bạn xem lại.

Mọi câu hỏi hoặc yêu cầu về quyền riêng tư vui lòng gửi tới **Lâm Đại Ka / LÂM MUSIC** tại [lamdltb@gmail.com](mailto:lamdltb@gmail.com).
