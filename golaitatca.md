# BÀI LÀM – THI THỬ HACKATHON 02 (GAMEZONE)

- **Họ tên: Chu Gia Huy
- **Lớp: cntt4 **
- **Link repository:** 
- **Hệ điều hành (Windows/macOS):Window ** 

## 4.2. Thao tác CLI

### Các lệnh đã chạy

```shell
# 1. pwd
2. ls -Force
3.mv cap_nhat.txt docs/
- mv logo_gamezone.png media/
4.cp media/logo_gamezone.png backup/
5. rm temp_207.tmp
6. cd logs/
- ls -Force
- cd ..\
7. Get-ChildItem -Recurse -Force

```

### Kết quả liệt kê toàn bộ dự án

```text
(Dán kết quả vào đây)

```

## 4.3. Lọc log thủ công

### 1.Get-Content logs/game.log | Select-String "ERROR" | Set-Content logs/daily_report.txt
2.Get-Content logs/daily_report.txt
3.Get-Content logs/daily_report.txt | Select-Object -First 2
```shell
# Ghi lệnh vào đây

```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
2025-11-05 08:03:15 [ERROR] Mat ket noi may chu game
2025-11-05 08:09:15 [ERROR] Mat ket noi may chu game

```

## 4.4. README.md

> Chấm trực tiếp trên `README.md` ở gốc dự án.

- [x] Heading 1
- [x] Mô tả in đậm + in nghiêng
- [x] Bảng `Thư mục | Nội dung` (≥3 dòng)
- [x] Code block lệnh liệt kê
- [x] Task list (≥2 việc, ≥1 đã xong)
- [x] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report

### Lệnh chạy

```shell
# Tac gia: Chu Gia Huy
# Ngay tao: 29/10/2026

"=== BAO CAO LOI GAMEZONE ===" > .\logs\auto_report.txt 
Get-Content .\logs\game.log | Select-String "ERROR" >> .\logs\auto_report.txt
Write-Host "Da tao bao cao: thanh cong"


```

### Nội dung file logs/auto_report.txt

```text
(Dán kết quả vào đây)

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
# Get-Content logs/game.log | Select-String "ERROR" | Measure-Object

```

### Kết quả đếm

```text
(Dán kết quả vào đây)

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lệnh vào đây

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây)

```

## 4.8. Excel

> Chấm trực tiếp trên file `data/giao_dich_thang_11.xlsx`.

