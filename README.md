# Football_Club
Full-Stack Django + React App

```sh
#Để kết nối thư mục code hiện tại với một repository (repo) trên GitHub, bạn thực hiện các bước sau
Bước 1: Khởi tạo Git trong thư mục hiện tại
Mở Terminal (Command Prompt, Git Bash hoặc PowerShell) và điều hướng đến thư mục code của bạn:


cd đường-dẫn-đến-thư-mục-code
Sau đó, khởi tạo Git trong thư mục:

git init
Lệnh này sẽ tạo một repository Git cục bộ trong thư mục của bạn.

Bước 2: Thêm repository từ GitHub
🔹 Nếu bạn chưa có repo trên GitHub:
Truy cập GitHub và đăng nhập.
Nhấn New repository và tạo một repo mới (chưa có file README, LICENSE).
Sao chép đường dẫn repo, ví dụ:
https://github.com/username/repo-name.git
🔹 Nếu bạn đã có repo trên GitHub:
Thêm GitHub repo làm remote cho thư mục hiện tại bằng lệnh:


git remote add origin https://github.com/username/repo-name.git
Kiểm tra lại remote đã thêm:


git remote -v
Bước 3: Thêm, commit và đẩy code lên GitHub
Chạy các lệnh sau để đưa code lên GitHub:



git add .
git commit -m "First commit"
git branch -M main
git push -u origin main
git add . → Thêm tất cả các file vào Git
git commit -m "First commit" → Commit các file với mô tả
git branch -M main → Đổi tên nhánh chính thành main
git push -u origin main → Đẩy code lên GitHub
```
