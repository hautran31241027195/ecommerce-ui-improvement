# E-commerce UI Improvement

## 1. Giới thiệu
Dự án tập trung khảo sát website thương mại điện tử **FAHASA** và tiến hành thiết kế cải tiến lại khu vực **Thẻ sản phẩm** cùng **Bố cục danh sách sản phẩm** nhằm tối ưu hóa trải nghiệm người dùng (UX) trên cả máy tính lẫn thiết bị di động.

## 2. Website tham khảo
- Tên website: FAHASA
- URL: [https://www.fahasa.com/](https://www.fahasa.com/)
- Khu vực đã khảo sát: Trang chủ, Danh mục sản phẩm, Chi tiết sản phẩm, Tìm kiếm, Giỏ hàng.

## 3. Chức năng
- Hiển thị lưới danh sách sản phẩm trực quan.
- Hiển thị đầy đủ hình ảnh, tên sản phẩm, tác giả, đánh giá sao.
- Hiển thị nổi bật giá khuyến mãi, giá gốc gạch ngang và nhãn phần trăm giảm giá (`-20%`).
- Tích hợp nút thao tác nhanh ("Thêm giỏ hàng", "Mua ngay", "Xem nhanh").
- Bố cục linh hoạt thích ứng mượt mà trên nhiều kích thước màn hình từ Desktop, Tablet đến Mobile.

## 4. Công nghệ sử dụng
- HTML5
- CSS3

## 5. Cách chạy dự án
1. Tải toàn bộ mã nguồn về máy tính.
2. Mở thư mục dự án và nhấp đúp chuột vào file `index.html` (hoặc mở bằng trình duyệt Google Chrome/Edge).

## 6. Cải tiến đã thực hiện
- **Vấn đề ban đầu:** Trên giao diện thực tế của FAHASA, các thẻ sản phẩm trên màn hình di động có mật độ quá dày, các nút bấm nhỏ dễ gây bấm nhầm, đồng thời việc hiển thị mức giảm giá chưa tạo điểm nhấn mạnh mẽ cho người mua.
- **Thay đổi đã thực hiện:** 
  - Thiết kế lại khung thẻ sản phẩm dạng hình chữ nhật đứng chuẩn tỉ lệ bìa sách (4:5).
  - Bổ sung huy hiệu giảm giá góc trên bên trái và nhóm giá tiền rõ ràng.
  - Tối ưu hóa bố cục CSS Grid (4 cột trên desktop, 3 cột trên tablet, 2 cột trên mobile) và chuyển các nút thao tác thành dạng hàng dọc trên màn hình nhỏ để mở rộng diện tích chạm (tap-target) cho người dùng điện thoại.

## 7. Hỗ trợ từ AI
- **Phần AI hỗ trợ:** Đề xuất cấu trúc HTML5 ngữ nghĩa, xây dựng hệ thống biến màu (CSS Variables) và viết mẫu bố cục CSS Grid đáp ứng đa màn hình.
- **Phần tôi kiểm tra, điều chỉnh và bổ sung:** 
  - Kiểm tra tính liên kết giữa file HTML và CSS trên trình duyệt thực tế.
  - Tự phát hiện lỗi vỡ nút bấm khi thu nhỏ màn hình điện thoại dưới 360px và chủ động điều chỉnh đoạn CSS `@media` chuyển nút sang hàng dọc để tối ưu trải nghiệm ngón tay cái.
