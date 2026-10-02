# Lâm Camera R11 — Điền bốn mục trong Google Play Console

Cập nhật: 02/10/2026. Áp dụng cho ứng dụng `vn.lamdai.camera` và bản R11 được đối chiếu trong lần chuẩn bị này. Đây là hướng dẫn điền; chưa phải xác nhận các mục đã được lưu trong tài khoản Play Console hoặc ứng dụng đã được Google phê duyệt.

## 1. Chính sách quyền riêng tư

Dán URL sau vào ô **URL của chính sách quyền riêng tư**, rồi bấm **Lưu**:

https://dlthoibinh.github.io/lam-music-pro/lam-camera/privacy-policy.html

Trang có tiếng Việt và tiếng Anh, ghi rõ Lâm Camera, tên gói, nhà phát triển Lâm Đại Ka và email hỗ trợ `lamdltb@gmail.com`. Nội dung gồm camera/micro, ảnh/video trên máy, quét chữ và chỉ mục tìm kiếm, vị trí/Geocoder, bản đồ OpenStreetMap, chia sẻ ảnh chứa GPS/QR/EXIF, Google AdMob, số liệu kỹ thuật ML Kit và cách xóa dữ liệu.

**Việc cần hoàn thiện trong ứng dụng trước khi gửi bản công khai:** R11 hiện có nút Quyền riêng tư mở nội dung tóm tắt và tham chiếu chính sách Google, nhưng chưa liên kết tới URL chính sách Lâm Camera đầy đủ ở trên. Cần bổ sung đường dẫn này trong ứng dụng và đưa vào AAB cập nhật. Việc tạo trang web không tự thay đổi AAB đã tải lên. Nếu tạo AAB mới, dùng đúng khóa tải lên và versionCode lớn hơn bản đã tải.

## 2. Thông tin đăng nhập

Ở câu **“Có phần nào trong ứng dụng của bạn bị hạn chế không?”**, chọn **Không**, rồi **Lưu**.

Căn cứ R11: không có đăng ký/đăng nhập, OTP, gói thuê bao, mua trong ứng dụng hoặc khu vực nội dung yêu cầu tài khoản riêng. Các hộp xin quyền camera, micro, vị trí và ảnh của Android không phải tài khoản đăng nhập dành cho người xét duyệt. Chế độ camera có tên “Pro” là chế độ chụp; không đồng nghĩa có gói trả phí.

## 3. Quảng cáo

Chọn **“Có, ứng dụng của tôi có chứa quảng cáo”**, rồi **Lưu**.

R11 tích hợp banner Google AdMob. Vẫn phải chọn Có khi quảng cáo đang chưa hiển thị do mạng, vùng, tài khoản quảng cáo hoặc thiếu lượt phân phối.

## 4. Mức phân loại nội dung

Ảnh hiện tại mới là trang bắt đầu; bộ câu hỏi cụ thể sẽ xuất hiện sau khi bấm **Bắt đầu trả lời bộ câu hỏi**.

1. Email nhận trao đổi IARC: `lamdltb@gmail.com`.
2. Nếu danh mục gồm “Trò chơi”, “Mạng xã hội hoặc thông tin liên lạc”, “Tất cả các loại ứng dụng khác”, chọn **Tất cả các loại ứng dụng khác** cho tiện ích camera này.
3. Trả lời theo ý nghĩa chính xác của từng câu, dựa vào các thông tin dưới đây.
4. Bấm Tiếp theo, xem lại câu trả lời, rồi lưu/gửi bảng hỏi bằng nút hệ thống hiển thị. IARC sẽ tính mức phân loại; không tự chọn một mức tuổi như 3+ hay 18+ để thay bảng hỏi.

| Nội dung được hỏi | Đối chiếu với Lâm Camera R11 |
|---|---|
| Nội dung bạo lực, tình dục/khỏa thân, kinh dị, ngôn từ tục tĩu hoặc nội dung người lớn được nhà phát triển cung cấp trong ứng dụng | Không có. Ảnh riêng do người dùng tự chụp hoặc mở không phải bộ nội dung người lớn được nhà phát triển cung cấp. |
| Cờ bạc, đặt cược, giải thưởng tiền thật, mua vật phẩm ngẫu nhiên | Không có. |
| Mua nội dung số/gói thuê bao trong ứng dụng | Không có. |
| Ứng dụng tin tức, giáo dục, trình duyệt web hoặc công cụ tìm kiếm Internet | Không phải các loại này. Tìm ảnh R11 tìm trong ảnh được cấp quyền trên thiết bị. Mở liên kết chỉ đường ra Google Maps/trình duyệt không biến ứng dụng thành trình duyệt web. |
| Trò chuyện, bảng tin, nội dung cộng đồng hoặc trao đổi nội dung ngay bên trong Lâm Camera | Không có hệ thống này. Nút chia sẻ chuyển tệp sang Zalo/ứng dụng ngoài qua Android. Nếu câu hỏi nói rõ tương tác “ngay trong ứng dụng / natively”, đối chiếu theo phạm vi đó. |
| Khả năng chia sẻ vị trí chính xác tới người khác | Có khả năng chia sẻ vị trí chụp qua chữ, mã QR và GPS EXIF gắn trong ảnh. Không khai “không chia sẻ vị trí” chỉ vì ứng dụng không có chat. Nếu câu hỏi giới hạn riêng việc theo dõi vị trí trực tiếp/thời gian thực, R11 không có chức năng theo dõi trực tiếp giữa người dùng. |
| Quảng cáo | Có Google AdMob. |

Nếu câu hỏi có định nghĩa, điều kiện hoặc ví dụ khác bảng trên, đọc phần trợ giúp cạnh câu hỏi và đối chiếu đúng phạm vi. Không đánh dấu “Không” đồng loạt cho toàn bộ bảng hỏi. Mức phân loại nội dung khác với mục “Đối tượng mục tiêu” của ứng dụng.

## Cần nhất quán ở bước An toàn dữ liệu tiếp theo

Không khai “ứng dụng không thu thập dữ liệu” chỉ vì ảnh lưu trên điện thoại. Google AdMob xử lý dữ liệu quảng cáo, Google ML Kit gửi số liệu kỹ thuật; Geocoder và bản đồ trực tuyến cũng có hoạt động trao đổi dữ liệu. Cần khai theo từng loại dữ liệu, mục đích, nhà cung cấp và điều kiện thực tế. Bốn ảnh hiện tại chưa bao gồm biểu mẫu An toàn dữ liệu; không suy ra mọi câu trả lời cho biểu mẫu đó từ danh sách quyền Android.

## Nguồn chính thức

- [Hoàn thiện ứng dụng để chuẩn bị xem xét](https://support.google.com/googleplay/android-developer/answer/9859455?hl=vi)
- [Phân loại nội dung](https://support.google.com/googleplay/android-developer/answer/9859655?hl=vi)
- [Google Mobile Ads — công bố dữ liệu](https://developers.google.com/admob/android/privacy/play-data-disclosure)
- [ML Kit — quyền riêng tư](https://developers.google.com/ml-kit/terms)
- [ML Kit — công bố dữ liệu Android](https://developers.google.com/ml-kit/android-data-disclosure)
