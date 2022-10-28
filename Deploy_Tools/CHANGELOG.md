### DHG.Hospital Printer - Thông tin cập nhật

<div align="center" style="font-size:xx-small">(✨: Chức năng mới,🐛: Chỉnh lỗi, #️⃣: Giải quyết công việc) </div>

##### [v3.22.1028.1]()

-  🐛: Fix lỗi không theo mô tả [Vinh.-.Mo.ta.cap.phat.thuoc.nguoi.benh.Lao.theo.TT36.va.CV3153.-.17-08-2022v2](../MoTaThayDoi/Vinh.-.Mo.ta.cap.phat.thuoc.nguoi.benh.Lao.theo.TT36.va.CV3153.-.17-08-2022v2.pdf). Xử lý chỉ cần psdangky.benhnhan_lao = 1 không cần chuẩn đoán Z22.7 sẽ thực hiện xuất xml theo MA_LYDO_VVIEN=7, MA_LOAI_KCB=7
-  #️⃣: https://github.com/dh-hos/dhg.hospitaladmin/issues/23

##### [v3.22.1024.3]()

-  🐛: Fix lỗi thiếu tập tin khi mở module ![](../MoTaThayDoi/Errors/Error-Thieu-file-khi-mo-module.jpg) 

##### [v3.22.1024.2]()

-  🐛: Fix lỗi thiếu tập tin khi mở module ![](../MoTaThayDoi/Errors/Error-Thieu-file-khi-mo-module.jpg)

##### [v3.22.1024.1]()

-  🐛: Thêm chức năng xuất xml vào thư mục cấu hình trên admin khi gửi xml lên cổng BHXH đối với mabvbh=87190
-  #️⃣: https://github.com/dh-hos/dhg.hospitalprinter/issues/77

##### [v3.22.1020.1]()

-  🐛: Thêm chức năng xuất xml vào thư mục cấu hình trên admin khi gửi xml lên cổng BHXH đối với mabvbh=87190
-  #️⃣: https://github.com/dh-hos/dhg.hospitalprinter/issues/77

##### [v3.22.0929.1]()

-  ✨: Hỗ trợ xóa XML (không có chi phí gửi BHXH) trên bảng kê kiểm tra XML
-  #️⃣: https://github.com/dh-hos/dhg.hospitaladmin/issues/21
-  ✨: Thực hiện theo Mô tả thực hiện Thông tư 36/2021/TT-BYT [Mô tả](https://github.com/dh-hos/Mo-ta-he-thong/files/9553579/Vinh.-.Mo.ta.cap.phat.thuoc.nguoi.benh.Lao.theo.TT36.va.CV3153.-.17-08-2022v2.pdf)
-  ✨: Hỗ trợ không cập nhật lại kết quả chuẩn đoán đối với bệnh nhân Lao theo Thông tư 36/2021/TT-BYT (đã ghi nhận khi in phiếu 01) khi xem XML hoặc gửi XML lên cổng BHXH
-  #️⃣: https://github.com/dh-hos/Mo-ta-he-thong/issues/12

##### [v3.22.0924.1]()

-  ✨: Thực hiện theo Mô tả thực hiện Thông tư 36/2021/TT-BYT [Mô tả](https://github.com/dh-hos/Mo-ta-he-thong/files/9553579/Vinh.-.Mo.ta.cap.phat.thuoc.nguoi.benh.Lao.theo.TT36.va.CV3153.-.17-08-2022v2.pdf)
-  #️⃣: https://github.com/dh-hos/Mo-ta-he-thong/issues/12

##### [v3.22.0721.1]()

-  🐛: Bổ sung license mabvbh=77150
-  #️⃣: https://github.com/dh-hos/DH.HIS/issues/2

##### [v3.22.0719.1]()

-  ✨: Cập nhật ngày giờ y lệnh trên xml 3 theo mô tả mới
-  #️⃣: https://github.com/dh-hos/Mo-ta-he-thong/issues/11

##### [v3.22.0703.1]()

-  ✨: Xuất NGAY_YL, NGAY_KQ theo mô tả (#11) (Vinh - Mo ta cot [dien_bien] [hoi_chan] va [phau_thuat] XML5 - 20220602.3.pdf), lấy theo ngày giờ bắt đầu và kết thúc nếu có lập phiếu phẫu thuật
-  #️⃣: https://github.com/dh-hos/Mo-ta-he-thong/issues/11

##### [v3.22.0701.2]()

-  #️⃣: https://github.com/dh-hos/dhg.hospitalservices/issues/10
-  🐛: Lỗi gởi tự động bn điều trị nội trú có lập toa ngoại trú không thanh bhyt
-  ✨: Nâng cấp Dotnet 4.5
