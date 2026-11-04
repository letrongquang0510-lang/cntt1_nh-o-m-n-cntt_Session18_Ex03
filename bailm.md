# Yêu cầu đầu ra

## Báo cáo phân tích (IPO)
## Xác định Input (Dấu hiệu nhiễm), Process (Các bước xử lý), Output (Hệ thống sạch).
- input : tài khoản bị chiếm đoạt tự động , bỗng dưng nhận được thông báo lạ , bị đổi hoặc bị đăng xuất khỏi zaloi, facebook , gmail.
- process :
**quy trình 4 bước truy cập lại quyền kiểm soát và làm sạch hệ thống :** 
1. Ngắt toàn bộ kết nối Internet để chặn kẻ tấn công tiếp tục gửi dữ liệu cá nhân, mật khẩu, và cookie đã đánh cắp từ máy tính về máy chủ của chúng (Command & Control Server).
2. sử dụng thiết bị khác khác để đổi mật khẩu , Bật hoặc kiểm tra lại tính năng Xác thực 2 bước (2FA/MFA) bằng ứng dụng Authenticator (Google Authenticator, Authy...) thay vì chỉ dùng SMS.
3. vào setting , vào quản lý thiết bị ( đăng xuất tất cả ) thao tác này vô hiệu hóa toàn bộ các session token mà phần mềm độc hại đã trộm được.
4. Sử dụng phần mềm diệt virus uy tín quét toàn bộ hệ thống hoặc tiến hành cài đặt lại hệ điều hành (Clean Install) nếu máy tính bị nhiễm dòng malware quá sâu, đảm bảo loại bỏ triệt để mã độc ẩn giấu trước khi kết nối Internet trở lại.
## Mô tả chi tiết cách thực hiện "Đổi mật khẩu từ thiết bị khác" và "Revoke Token" trên GitHub.

**Cách đổi mật khẩu từ thiết bị khác:**
Tuyệt đối không dùng máy tính đang bị nghi ngờ để đổi mật khẩu. Hãy dùng điện thoại cá nhân.

Vào phần cài đặt tài khoản Google hoặc Facebook, chọn đổi mật khẩu mới, sau đó bấm đăng xuất khỏi tất cả các thiết bị hiện có.

**Cách thu hồi Token trên GitHub (Revoke Token):**

Đăng nhập vào tài khoản GitHub từ một thiết bị an toàn.

Vào mục Settings (Cài đặt) ở góc trên bên phải, kéo xuống chọn Developer settings.

Chọn mục Personal access tokens (hoặc Authorized OAuth Apps), kiểm tra các token/ứng dụng lạ và bấm nút Revoke để hủy quyền truy cập.
