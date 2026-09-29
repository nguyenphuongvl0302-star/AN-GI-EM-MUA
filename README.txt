AN GI EM MUA - BAN PWA

Tính năng:
- Bản đồ OpenStreetMap
- Tìm địa chỉ lấy/giao và lấy GPS hiện tại
- Tính tuyến đường bộ qua OSRM, cập nhật km và phí ship
- Tiền mua hàng vẫn nhập thủ công
- Lịch sử lưu trên thiết bị bằng localStorage

CÀI TRÊN ANDROID:
1. Giải nén ZIP và đưa toàn bộ các file trong thư mục lên dịch vụ hosting HTTPS (ví dụ GitHub Pages hoặc hosting web bạn đang dùng).
2. Mở đường dẫn index.html bằng Chrome trên Android.
3. Chọn menu Chrome (⋮) > Cài đặt ứng dụng / Thêm vào màn hình chính.
4. Cho phép quyền vị trí khi muốn tính từ vị trí hiện tại.

LƯU Ý:
- PWA cần chạy từ HTTPS hoặc localhost để cài đặt và dùng GPS ổn định; mở file HTML trực tiếp không đủ điều kiện cài PWA.
- Bản đồ, tìm địa chỉ và định tuyến cần Internet. Dịch vụ định tuyến OSRM công cộng có thể giới hạn/tạm ngưng; không có cam kết SLA.
- Tự động tính hai chặng: vị trí hiện tại -> quán (khi đã lấy GPS) và quán -> khách. Nếu chưa lấy GPS, chặng từ bạn đến quán là 0 km. Chiều về nhập tay nếu cần và bật tính phí chiều về.
- Kiểm tra điểm ghim và lộ trình trên bản đồ trước khi báo phí; dữ liệu địa chỉ có thể không chính xác.
