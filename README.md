# Bài 1: Xử lý cảnh báo đăng nhập giả mạo GitHub

## 1. Phân tích URL

URL đáng ngờ: `https://githúb.com/login`

- Ký tự lạ là `ú` 
- Đây là hình thức tấn công Homograph Attack, sử dụng ký tự có hình dạng gần giống để tạo website giả mạo.

## 2. Quy trình kiểm tra URL

1. Quan sát kỹ tên miền, kiểm tra ký tự lạ, lỗi chính tả.
2. Đối chiếu với địa chỉ GitHub chính thức: `https://github.com`.
3. Không nhấn vào liên kết trong email đáng ngờ.
4. Tự nhập địa chỉ GitHub vào trình duyệt để đăng nhập.
5. Không nhập mật khẩu nếu chưa xác minh được website.

## 3. Công cụ hỗ trợ

- VirusTotal: Kiểm tra URL có dấu hiệu độc hại.
- Google Safe Browsing: Kiểm tra mức độ an toàn của website.
- Bitwarden: Kiểm tra tên miền trước khi tự động điền mật khẩu.

## 4. Kết luận

URL `githúb.com` có ký tự Unicode bất thường, có dấu hiệu giả mạo GitHub bằng kỹ thuật Homograph Attack. Cần kiểm tra kỹ tên miền, sử dụng công cụ hỗ trợ và chỉ nhập Master Password trên website hoặc ứng dụng chính thức.
