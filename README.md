# Miêu tả
5 bảng: 
- hàng 
- shipper 
- khách hàng(KH) 
- nhà cung cấp(NCC)
- đơn hàng

Trường nào số 1 trong bảng thì là Primary key <space><space>
Trường nào số 2 mà có id ở sau thì là Foreign key

* Hang(hang_id, ncc_id, tên_sp, mau_sac, so_luong)
* Shipper(shipper_id, ten_shipper, ngay_sinh, dia_chi, luong)
* NCC(ncc_id, tên_công_ty, dia_diem)
* KH(kh_id, ten_kh, dia_chi)
* Don_hang(kh_id, hang_id, so_luong)

## Các tên bảng viết hoa chữ cái đầu
- Nếu viết tắt thì viết hoa tất
- Nếu 2 từ thì nối bằng dấu gạch chân _
## Các tên trường trong bảng chỉ viết thường
- Nếu 2 từ thì nối gạch chân _ 
- Lưu ý: có 2 trường cùng logic: dia_chi(Shipper, KH) và dia_diem(NCC)
- và các thể loại tên
