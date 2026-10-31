HUY DUNG – PHẦN MỀM QUẢN LÝ HÀNG HÓA

CÁC TỆP
- index.html: ứng dụng chính
- manifest.json: cấu hình cài đặt như ứng dụng
- sw.js: bộ nhớ đệm/offline cơ bản

CÁCH DÙNG NHANH
1. Giải nén ZIP.
2. Mở index.html để dùng thử trên máy tính. Trình duyệt có thể hạn chế service worker khi mở bằng file://.
3. Để cài như ứng dụng trên điện thoại và dùng offline ổn định hơn, tải cả 3 tệp lên GitHub repository và bật GitHub Pages.
4. Mở đường dẫn HTTPS GitHub Pages trên Chrome Android > menu ⋮ > Thêm vào màn hình chính / Cài đặt ứng dụng.
5. Dữ liệu được lưu trong localStorage của trình duyệt trên thiết bị. Không tự đồng bộ giữa thiết bị. Hãy sao lưu JSON định kỳ.
6. Xuất Excel: cần internet để tải thư viện SheetJS; nếu không tải được, dùng nút CSV để mở bằng Excel.

NGHIỆP VỤ
- Nhập kho làm tăng tồn kho.
- Bán hàng làm giảm tồn kho và không cho bán vượt số lượng hiện có.
- Sửa/xóa phiếu nhập hoặc giao dịch bán sẽ cập nhật lại tồn kho theo lịch sử.
- Lợi nhuận gộp = doanh thu - giá vốn tại thời điểm bán.
- Không xóa được mặt hàng đã có giao dịch để bảo toàn lịch sử; có thể sửa tên hoặc ngừng dùng.

LƯU Ý
Đây là bản chạy cục bộ, không có đăng nhập, máy chủ hay đồng bộ đám mây. Nếu xóa dữ liệu trình duyệt hoặc đổi thiết bị, cần khôi phục từ file JSON đã sao lưu.
