# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:** Nguyễn Gia Thịnh
- **Lớp:** CNTT1
- **Link repository:**
- **Hệ điều hành (Windows/macOS):** Windows

## Phần A. Tổ chức thư mục bằng GUI 

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```PowerShell
B1: pwd
B2: ls -Force
B3:
mv ".\Trung Tam Tieng Anh FINAL\lich_hoc.txt" ".\docs"
mv ".\Trung Tam Tieng Anh FINAL\anh_lop_hoc.JPG" ".\media"
mv ".\Trung Tam Tieng Anh FINAL\logo_trung_tam.PNG" ".\media"
B4: cp ".\media\logo_trung_tam.PNG" ".\archive\"
B5:
rm ".\Trung Tam Tieng Anh FINAL\temp_201.tmp"
rm ".\Trung Tam Tieng Anh FINAL\temp_202.tmp"
B6:
cd ".\logs"
ls
cd..
B7:
cd docs
cp "..\media\anh_lop_hoc.JPG" "..\archive\"
cd..
B8: Get-ChildItem -r -force
```

### Kết quả B1 (pwd)

```PowerShell
pwd
Path
----
C:\trung-tam-tieng-anh

```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```PowerShell
Get-ChildItem -r -force
Directory: C:\trung-tam-tieng-anh\archive


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   10:04 PM          13559 anh_lop_hoc.JPG
-a----        10/20/2026   10:04 PM           5184 logo_trung_tam.PNG


    Directory: C:\trung-tam-tieng-anh\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   10:04 PM           5070 hoc_vien_khoa_3.xlsx


    Directory: C:\trung-tam-tieng-anh\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   10:04 PM             67 lich_hoc.txt


    Directory: C:\trung-tam-tieng-anh\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   10:04 PM           1072 access.log


    Directory: C:\trung-tam-tieng-anh\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   10:04 PM          13559 anh_lop_hoc.JPG
-a----       10/20/2026   10:04 PM             5184 logo_trung_tam.PNG


    Directory: C:\trung-tam-tieng-anh\Trung Tam Tieng Anh FINAL


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   10:04 PM              83 .env
-a----        10/20/2026   10:04 PM           902 bai_lam_ngay1.md



## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**
