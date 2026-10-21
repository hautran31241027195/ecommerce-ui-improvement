# AI Usage Log

## 1. Công cụ AI
- **Tên công cụ:** Gemini (Google)

## 2. Mục đích sử dụng
- Hỗ trợ phân tích nghiệp vụ và trải nghiệm người dùng (UX/UI) cho 5 khu vực của website FAHASA.
- Đề xuất bố cục, cấu trúc thẻ HTML5 và mã nguồn CSS3 tối ưu cho phần cải tiến thẻ sản phẩm.
- Giải thích cách thiết kế giao diện tương thích đa màn hình (Responsive Design).

## 3. Prompt đã sử dụng
- *Prompt 1 (Khảo sát website):* Yêu cầu AI đóng vai chuyên gia BA/UX phân tích 5 khu vực (Trang chủ, Danh mục, Chi tiết sản phẩm, Tìm kiếm, Giỏ hàng) với các tiêu chí mục đích, UI, điểm thuận tiện, vấn đề phát sinh và đề xuất cải tiến.
- *Prompt 2 (Tạo mã nguồn):* Yêu cầu AI đề xuất phương án và tạo mã nguồn HTML5/CSS3 cho phần cải tiến thẻ sản phẩm với tối thiểu 4 sản phẩm mẫu, hỗ trợ hiển thị trên máy tính và điện thoại.

## 4. Kết quả AI đề xuất
- Cung cấp khung bảng phân tích chuẩn thương mại điện tử cho 5 khu vực chức năng.
- Cung cấp đoạn mã HTML và CSS hoàn chỉnh sử dụng CSS Grid và Flexbox, tách biệt rõ ràng file cấu trúc và file định dạng kiểu dáng.

## 5. Kiểm tra và điều chỉnh
- **Điểm giữ nguyên:** Cấu trúc lưới sản phẩm 4 cột và cơ chế đổi màu theo bảng màu chuẩn của thương hiệu FAHASA (`#C92127`).
- **Điểm đã chỉnh sửa/bổ sung:** 
  - Đối chiếu thực tế website FAHASA để loại bỏ các giả định không chính xác của AI (ví dụ: thực tế giỏ hàng chưa tính sẵn phí ship chính xác như dự đoán ban đầu).
  - Điều chỉnh thêm các thuộc tính CSS trên thiết bị di động (`@media (max-width: 599px)`) để chuyển cụm nút thao tác mua hàng sang dạng hàng dọc, giúp tránh lỗi tràn chữ và tăng kích thước vùng bấm trên màn hình cảm ứng.

## 6. Phần tôi hiểu và có thể giải thích
- **CSS Grid & Flexbox:** Hiểu cách dùng `grid-template-columns: repeat(4, 1fr)` để chia đều 4 cột sản phẩm trên máy tính và tự điều chỉnh xuống 2 cột trên điện thoại.
- **Media Queries (`@media`):** Hiểu cách áp dụng điểm dừng (breakpoint) để thay đổi thuộc tính giao diện tùy theo kích thước màn hình.
- **Pseudo-classes (`:hover`):** Hiểu cơ chế tạo hiệu ứng tương tác khi người dùng di chuột vào sản phẩm (`transform: translateY(-4px)`, phóng to ảnh và hiện nút xem nhanh).
