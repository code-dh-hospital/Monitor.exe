<div align="center">

# Nhật ký thay đổi</div>

<div align="center" style="font-size:xx-small">(✨: Tính năng, chức năng mới. 🐛: Chỉnh lỗi. ☑: Giải quyết công việc, issue) </div>

#

## [v.3.26.0903.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32609032-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32609032-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32609032-NasDHSolutions.json)</sup></sup></sub>
- ✨: [Monitor & OTH.Entity, OTH.Adapter, OTH.XForms.v.1.0] Xây dựng và nâng cấp hệ thống Màn hình Tivi Cận lâm sàng động (FrmShow_OMon_CDHA):
  - Tự động kích hoạt nút [⚙ Cấu hình TV CLS] (btnOptionCLS) khi chọn phân hệ Cận lâm sàng (optCLS).
  - Hỗ trợ cấu hình tên phòng hiển thị theo combo phòng CLS trên màn hình chính (chọn giữa: Tên phòng danh mục, Text riêng tùy chỉnh, hoặc Tên khoa mặc định).
  - Nạp động giao diện Tivi theo thời gian thực (Tiêu đề, Màu nền Header, Màu chữ, Cỡ chữ, Logo Base64, Chiều cao Header).
  - Tùy biến chuỗi trạng thái Đang gọi / Chờ theo từng phòng và hiển thị nổi bật dòng bệnh nhân đang gọi.
  - Tích hợp Dải băng chữ chạy thông báo chân trang (Marquee Ticker Banner) cuộn chữ mượt mà.
  - Hỗ trợ 3 chế độ bố cục: Toàn màn hình danh sách, Luân phiên video khi nhàn rỗi, và Chia đôi màn hình song song (Split Screen 60/40) giữa danh sách chờ và video truyền thông.
  - Thêm nút bấm [🖥 Mở Form Tivi xem thử (Nhấn Esc để đóng)] kích thước chuẩn kèm nhãn phím tắt thoát (ESC, Alt+F4, nút [✕ Đóng (Esc)], menu chuột phải).
  - Bổ sung khối nhãn hướng dẫn quy chuẩn đường dẫn video chung vs riêng và lưu ý đồng nhất file trên các máy trạm.
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/903
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/886
- 📗: Đọc và ghi nhận dữ liệu cấu hình JSON qua bảng current.coderun (code = 'monitor_cls_tv_option'). Nạp danh sách phòng từ current.cauhinhmay và current.dmphong_cls.
- 📕: Trên màn hình Monitor.FrmMainV2, chọn phân hệ "Cận lâm sàng", chọn phòng CLS tương ứng rồi nhấp nút [⚙ Cấu hình TV CLS] để thiết lập giao diện và mở xem thử bằng nút [🖥 Mở Form Tivi xem thử]. Hoặc nhấp chuột phải / nhấn Ctrl+Shift+O ngay trên màn hình Tivi để cấu hình.
  ![](https://images-worker.tlt32.workers.dev/i/01a06699-0d46-75a0-8284-4bf59456874f)

## [v.3.26.0903.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32609031-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32609031-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32609031-NasDHSolutions.json)</sup></sup></sub>
﻿- ✨: [Monitor & OTH.Entity, OTH.Adapter, OTH.XForms.v.1.0] Xây dựng và nâng cấp hệ thống Màn hình Tivi Cận lâm sàng động (FrmShow_OMon_CDHA):
  - Tự động kích hoạt nút [⚙ Cấu hình TV CLS] (btnOptionCLS) khi chọn phân hệ Cận lâm sàng (optCLS).
  - Hỗ trợ cấu hình tên phòng hiển thị theo combo phòng CLS trên màn hình chính (chọn giữa: Tên phòng danh mục, Text riêng tùy chỉnh, hoặc Tên khoa mặc định).
  - Nạp động giao diện Tivi theo thời gian thực (Tiêu đề, Màu nền Header, Màu chữ, Cỡ chữ, Logo Base64, Chiều cao Header).
  - Tùy biến chuỗi trạng thái Đang gọi / Chờ theo từng phòng và hiển thị nổi bật dòng bệnh nhân đang gọi.
  - Tích hợp Dải băng chữ chạy thông báo chân trang (Marquee Ticker Banner) cuộn chữ mượt mà.
  - Hỗ trợ 3 chế độ bố cục: Toàn màn hình danh sách, Luân phiên video khi nhàn rỗi, và Chia đôi màn hình song song (Split Screen 60/40) giữa danh sách chờ và video truyền thông.
  - Thêm nút bấm [🖥 Mở Form Tivi xem thử (Nhấn Esc để đóng)] kích thước chuẩn kèm nhãn phím tắt thoát (ESC, Alt+F4, nút [✕ Đóng (Esc)], menu chuột phải).
  - Bổ sung khối nhãn hướng dẫn quy chuẩn đường dẫn video chung vs riêng và lưu ý đồng nhất file trên các máy trạm.
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/886
  https://i.dh-his.com/tolaptrinh-ai/loi/issues/17
- 📗: Đọc và ghi nhận dữ liệu cấu hình JSON qua bảng current.coderun (code = 'monitor_cls_tv_option'). Nạp danh sách phòng từ current.cauhinhmay và current.dmphong_cls.
- 📕: Trên màn hình Monitor.FrmMainV2, chọn phân hệ "Cận lâm sàng", chọn phòng CLS tương ứng rồi nhấp nút [⚙ Cấu hình TV CLS] để thiết lập giao diện và mở xem thử bằng nút [🖥 Mở Form Tivi xem thử]. Hoặc nhấp chuột phải / nhấn Ctrl+Shift+O ngay trên màn hình Tivi để cấu hình.
  ![](https://images-worker.tlt32.workers.dev/i/01a06699-0d46-75a0-8284-4bf59456874f)

## [v.3.26.0903.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32609030-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32609030-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32609030-NasDHSolutions.json)</sup></sup></sub>
- ✨: Thực hiện theo mô tả [THAM_SO_HE_THONG
  /Hau-mota-them-thamso-cauhinh_phong_cls.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/THAM_SO_HE_THONG/Hau-mota-them-thamso-cauhinh_phong_cls.md)
- ✨: Mở chức năng hiển thị hàng chờ Tivi Cận lâm sàng (optCLS) trên FrmMainV2 và FrmShow_OMon_CDHA, tự động khởi động FrmMainV2 khi bật tham số cauhinh_phong_cls = 1.
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/903
  https://i.dh-his.com/hdhiswork/YEUCAU/issues/886
- 📗: Đọc dữ liệu hàng chờ gọi bệnh nhân từ current.pscls_lcd, nạp danh sách phòng từ current.cauhinhmay và current.dmphong_cls.
- 📕: Chạy Monitor.exe trên PC kết nối Tivi phòng CLS (Extend screen), chọn Cận lâm sàng -> Chọn phòng CLS -> Bấm [Hiển thị] để chiếu danh sách gọi bệnh nhân và video truyền thông.
  ![](https://images-worker.tlt36.workers.dev/i/01a06633-b4e8-7682-91b3-1965c27c14fa)
  ![](https://images-worker.tlt26.workers.dev/i/01a06630-e46b-788d-95bf-daa43345ddc0)
  ![](https://images-worker.tlt34.workers.dev/i/01a06638-20a8-7a50-a75c-cf82caa80003)
  ![](https://images-worker.tlt43.workers.dev/i/01a0663e-51a3-7023-a271-d9540ce0e432)
  ![](https://images-worker.tlt41.workers.dev/i/01a0663d-9378-7656-ae22-bcaa5f265be7)
  ![](https://images-worker.tlt44.workers.dev/i/01a06641-5b79-7e58-94ce-8fb5a6055414)

## [v.3.26.0716.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32607162-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32607162-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32607162-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Monitor chỉnh lại tên Bệnh viện Gò Vấp #806 (không tải được nên push lại)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/806
- 📕: Hiện tại các form monitor sử dụng tại BV Gò Vấp đang bắt theo riêng và gán cứng tên bệnh viện
- Chỉnh sửa lại lấy tên bệnh viện theo key
![](https://i.vgy.me/4uKmWi.png)

## [v.3.26.0716.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32607161-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32607161-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32607161-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Monitor chỉnh lại tên Bệnh viện Gò Vấp #806 (không tải được nên push lại)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/806
- 📕: Hiện tại các form monitor sử dụng tại BV Gò Vấp đang bắt theo riêng và gán cứng tên bệnh viện
- Chỉnh sửa lại lấy tên bệnh viện theo key
![](https://i.vgy.me/4uKmWi.png)

## [v.3.26.0716.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32607160-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32607160-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32607160-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Monitor chỉnh lại tên Bệnh viện Gò Vấp #806 (không tải được nên push lại)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/806
- 📕: Hiện tại các form monitor sử dụng tại BV Gò Vấp đang bắt theo riêng và gán cứng tên bệnh viện
- Chỉnh sửa lại lấy tên bệnh viện theo key
![](https://i.vgy.me/4uKmWi.png)

## [v.3.26.0706.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32607060-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32607060-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32607060-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Monitor chỉnh lại tên Bệnh viện Gò Vấp #806
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/806
- 📕: Hiện tại các form monitor sử dụng tại BV Gò Vấp đang bắt theo riêng và gán cứng tên bệnh viện
- Chỉnh sửa lại lấy tên bệnh viện theo key
![](https://i.vgy.me/4uKmWi.png)

## [v.3.25.0930.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32509300-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32509300-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32509300-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Monitor: Bổ sung cấu hình chọn phân khu cho quầy tiếp nhận
![](https://i.vgy.me/6PAEVQ.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/478

## [v.3.25.0609.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32506090-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32506090-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32506090-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Yêu cầu - Monitor: Tùy chỉnh size chữ dòng Tiêu đề
![](https://i.vgy.me/UAxHMU.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/262

## [v.3.25.0513.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32505130-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32505130-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32505130-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu: Tùy chỉnh giao diện KIOS Ordinal, Monitor, Speaker(Gọi bệnh) TTYT huyện Châu Thành - Đồng Tháp
- ✨: Thêm cấu hình màu tiêu đề.
![](https://i.imgur.com/cpj4Pjo.gif)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/197

## [v.3.25.0418.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32504180-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32504180-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32504180-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Monitor: Không cập nhật được chức năng check chọn Nhân bệnh
![](https://i.imgur.com/ujOwYeZ.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/243

## [v.3.25.0414.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32504140-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32504140-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32504140-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix lỗi không Enble nút showTV khi đã có key dhkios

## [v.3.25.0402.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32504020-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32504020-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32504020-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - BV Trà Cú: Âm thanh gọi loa quầy phát thuốc bị mất âm gọi bệnh nhân số vào quầy khi có tiếng tintintin phát lên loa
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/206

## [v.3.25.0326.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32503260-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32503260-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32503260-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu: Monitor hiển thị thông tin bệnh nhân tại phòng khám bỏ cột Tuổi.
- ✨: Tại phòng khám Bác sĩ: Bác sĩ khám bệnh nhân nào thì trên Monitor hiển thị bệnh nhân đó ở trạng thái đang khám. Hiện tại đang lấy bệnh nhân đang khám+1 nên đơn vị không chịu.
![](https://i.imgur.com/nVF3wmt.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/129

## [v.3.25.0319.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32503190-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32503190-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32503190-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - BV Trà Cú: Phần mềm Monitor không trình chiếu clip ra màn hình TV sau thời gian chờ được cấu hình
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/142

## [v.3.25.0318.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32503180-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32503180-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32503180-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - BV Trà Cú: Phần mềm Monitor không trình chiếu clip ra màn hình TV sau thời gian chờ được cấu hình
![](https://i.imgur.com/W9hKc3e.gif)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/142

## [v.3.25.0227.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32502270-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32502270-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32502270-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu: Gọi bệnh vào phòng khám và hiển thị thêm thông tin đối với bệnh nhân ưu tiên
- 🐛: Bổ sung chuỗi (Ưu tiên) phía sau tên bệnh nhân đối với bệnh nhân ưu tiên tại danh sách phòng khám
![](https://i.imgur.com/ufSyQaD.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/38

## [v.3.25.0226.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32502260-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32502260-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32502260-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu: Gọi bệnh vào phòng khám và hiển thị thêm thông tin đối với bệnh nhân ưu tiên
![](https://i.imgur.com/xewD7i6.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/38

## [v.3.25.0122.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32501220-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32501220-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32501220-NasDHSolutions.json)</sup></sup></sub>
- ✨: Sử dụng chức năng kiểm tra chức năng riêng để mở chức năng theo yêu cầu: `OTH.Adapter.Common.HisPrivateCode.MabvIsUsePrivateCodeBy` với key là `dhkios`
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/31

## [v.3.25.0120.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32501200-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32501200-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32501200-NasDHSolutions.json)</sup></sup></sub>
- ✨: Đổi cách lấy danh sách phòng theo dmphong, dựa vào `makv` là `loai`
![](https://i.imgur.com/wUQo8TY.png)
- ✨: Cảnh báo yêu cầu chọn phòng khi chưa chọn phòng mà ấn show.
![](https://i.imgur.com/T5RUuTd.png)
- 🐛: Fix - lỗi khi ấn show ra màn hình LCD mà không có dữ liệu
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/1

## [v.3.25.0112.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32501121-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32501121-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32501121-NasDHSolutions.json)</sup></sup></sub>
- ✨: BV Phụ Sản - Cập nhật hiển thị theo khu vực 
- 🐛: Danh sách phòng bị trùng

## [v.3.25.0112.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32501120-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32501120-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32501120-NasDHSolutions.json)</sup></sup></sub>
- ✨: BV Phụ Sản - Cập nhật hiển thị theo khu vực

## [v.3.25.0111.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32501110-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32501110-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32501110-NasDHSolutions.json)</sup></sup></sub>
- ✨: BV Phụ Sản - Cập nhật hiển thị theo khu vực
![](https://i.imgur.com/Iy58ueE.gif)

## [v.3.25.0110.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32501100-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32501100-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32501100-NasDHSolutions.json)</sup></sup></sub>
- ✨: Hiển thị danh sách bệnh nhân tại phòng khám (BV Trà Cú)

## [v.3.24.1226.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412260-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412260-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412260-NasDHSolutions.json)</sup></sup></sub>
- ✨: Hỗ trợ hiển thị danh sánh bệnh nhân tại khu tiếp nhận (BV Tâm Phúc)

## [v.3.24.1225.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412252-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412252-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412252-NasDHSolutions.json)</sup></sup></sub>
- ✨: Hỗ trợ hiển thị danh sánh bệnh nhân tại phòng khám (BV Cái Răng)

## [v.3.24.1225.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412251-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412251-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412251-NasDHSolutions.json)</sup></sup></sub>
- ✨: Hiệu chỉnh cú pháp hiện thị bệnh nhân thu phí (Bệnh nhân --> Khách hàng) - BV Tâm Phúc

## [v.3.24.1225.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412250-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412250-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412250-NasDHSolutions.json)</sup></sup></sub>
- ✨: Hiệu chỉnh cú pháp hiện thị bệnh nhân thu phí (Bệnh nhân --> Khách hàng) - BV Tâm Phúc

## [v.3.24.1218.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412180-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412180-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412180-NasDHSolutions.json)</sup></sup></sub>
✨: Yêu cầu - Triển khai Kios TTYT quận Cái Răng
✨: Mở chức năng Hiển thị trên Monitor với mabvbh = 92006
☑: https://github.com/dhhiswork/YeuCau/issues/42

## [v.3.24.1214.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412140-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412140-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412140-NasDHSolutions.json)</sup></sup></sub>
- ✨: Thể hiện logo đơn vị, tên phân khu được chọn lên tivi.
- ☑: https://github.com/dhhiswork/YeuCau/issues/44

## [v.3.24.1211.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412111-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412111-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412111-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Mở khóa nút show ra màn hình - mabvbh = 60152
![](https://i.imgur.com/c50A1TR.png)
- ☑: https://github.com/dhhiswork/YeuCau/issues/34

## [v.3.24.1211.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412110-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412110-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FMonitorexe%2F32412110-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Triển khai Kios và phát thuốc hiển thị ra Tivi Bệnh viện Tâm Phúc
- ✨: Mở chức năng hiển thị danh sách tiếp nhận trên Monitor với mabvbh = 60152
- ☑: https://github.com/dhhiswork/YeuCau/issues/34

## [v.3.24.1002.0]()
- ✨: Mở chức năng hiển thị tại phòng khám - BV Thốt Nốt
![](https://i.imgur.com/tbCpgXY.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/649

## [v.3.24.0930.0]()
🐛: Fix lỗi khi ấn nút show ra TV thì báo lỗi
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/660

## [v.3.24.0926.1]()
- ✨: Mở chức năng hiển thị thông tin bệnh nhân lên TV tại phòng khám Bác sĩ - BV Sa Đéc (push lại)
![](https://i.imgur.com/8RLG37U.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/660

## [v.3.24.0926.0]()
- ✨: Mở chức năng hiển thị thông tin bệnh nhân lên TV tại phòng khám Bác sĩ - BV Sa Đéc
![](https://i.imgur.com/8RLG37U.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/660

## [v.3.24.0920.0]()
- ✨: Mở chức năng hiển thị thông tin lên màn hình LCD Tại Quầy Tiếp nhận BV Thốt Nốt
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/649

## [v.3.24.0919.0]()
- ✨: Mở chức năng hiển thị thông tin lên màn hình LCD Tại Quầy Tiếp nhận BV Sa Đéc
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/648

## [v.3.24.0805.0]()
- 🐛: Fix lỗi không show ra được tivi - BV Tâm Phúc
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/526

## [v.3.24.0801.0]()
- 🐛: fix lỗi khi chọn nhìu phòng khám. Cảnh báo khi chọn nhìu phòng khám
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/526
![](https://i.imgur.com/atYdnh3.png)

## [v.3.24.0730.0]()
- 🐛: Tiêu đề hiển thị tivi lấy theo tên phòng cấu hình - BV Tâm Phúc
- ☑:https://github.com/dh-hos/To_Lap_Trinh/issues/526

## [v.3.24.0611.0]()
- 🐛: fix lỗi hiển thị tên khoa tại quầy thuốc -> Sửa thành KHOA DƯỢC
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/368

## [v.3.24.0607.1]()
- 🐛: Fix lỗi không hiển thị được danh sách chờ tại quầy thuốc
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/368

## [v.3.24.0607.0]()
- 🐛: Fix lỗi hiển thị ra màn hình bị thiếu đơn vị 'Tuổi' phía sau số tuổi
![](https://i.imgur.com/Dk4YPhw.png)

## [v.3.24.0606.0]()
- ✨: Cập nhật điều kiện lấy danh sách chờ và danh sách phục vụ đối với hiển thị tại quầy thuốc
- 📕: set điều khiện chỉ load danh sách chờ và danh sách phục vụ tại quầy thuốc khi chọn phân khu từ 96 trở lên, và chọn duy nhất 1 phân khu

## [v.3.24.0605.1]()
- ✨: Thêm chức năng hiển thị đối với quầy thuốc
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/368

## [v.3.24.0605.0]()
- 🐛: Fix lỗi load sai danh sách phục vụ
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/368

## [v.3.24.0604.0]()
- 🐛: Fix lại cách load danh sách phục vụ - BV Trà Cú
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/368

## [v.3.24.0525.0]()
- ✨: Thêm chức năng hiển thị danh sách nhận bệnh tại Trà Cú
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/368

## [v.3.24.0521.3]()
- ✨: Cập nhật giao diện - thay đổi chiều cao logo - PK BS Bắc
![image](https://i.imgur.com/i2fbfQa.png)

## [v.3.24.0521.2]()
- ✨: Cập nhật gia diện - thay đổi kích thước logo - PK BS Bắc
![image](https://i.imgur.com/m3zB2wx.png)

## [v.3.24.0521.1]()
- ✨: Cập nhật gia diện - PK BS Bắc

## [v.3.24.0521.0]()
- ✨: Cập nhật giao diện - PK BS Bắc

## [v.3.24.0520.0]()
- ✨: chỉnh sửa giao diện hiển thị ra màn hình - phòng khám bác sĩ Bắc