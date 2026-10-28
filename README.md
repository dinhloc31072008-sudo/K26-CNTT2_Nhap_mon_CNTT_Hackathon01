BÀI LÀM – HACKATHON 01
Mã đề: 22

Họ tên: Trần Đình Lộc

Lớp:

Link repository:

Hệ điều hành (Windows/macOS):

4.2. Thao tác máy tính cơ bản bằng CLI
Các lệnh đã chạy
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng
pwd
Get-childitem
ls [-Force]
cd folder
cp file other
rm file
Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)
----                 -------------         ------ ----
------        10/27/2026   1:32 AM             64 .env
-a----        10/27/2026   1:32 AM             53 Bang Quy Trinh.txt.txt
-a----        10/27/2026   1:32 AM           1029 carwash.log.log
-a----        10/27/2026   1:32 AM           6191 Logo Rua Xe.PNG.PNG
-a----        10/27/2026   1:32 AM           6114 Luot Rua Xe Thang
                                                  2.xlsx.xlsx
------        10/27/2026   1:32 AM             22 temp_305.tmp


4.3. Lọc log thủ công
Lệnh đã chạy
...|Select-String "ERROR"
2 dòng lỗi đầu tiên trong daily_report.txt
(Dán kết quả vào đây – xoá dòng này)
