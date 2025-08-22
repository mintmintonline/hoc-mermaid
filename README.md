```mermaid
classDiagram
 class NhanVien {
 -String maNV
 -String hoTen
 -double luong
 +tinhLuong()
 +inThongTin()
 }

 class QuanLy {
 -double phuCap
 +duyetDon()
 }

 class NhanVienBanHang {
 -double doanhSo
 +tinhHoaHong()
 }

 NhanVien <|-- QuanLy
 NhanVien <|-- NhanVienBanHang
```
