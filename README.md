## Mô tả

Danh sách các thư viện phổ biến, được dùng nhiều trong lập trình Android kèm theo đánh giá cá nhân của các lập trình viên của VSII.

### Phổ biến nhất

Danh sách các thư viện phổ biến và được sử dụng rộng rãi.

| Tên            | Mô tả |Ưu điểm  |Nhược điểm | Thư viện khác tương tự                    |  
| ----            | ------------      | ------------  | ------------  | ------------       |
| [Universal Image Loader](https://github.com/nostra13/Android-Universal-Image-Loader) | Làm việc với Image: Hiển thị ảnh, load ảnh…|Dễ dùng cho các loại listview, gridview mà nội dung có hiển thị ảnh, quản lý bộ nhớ, cache tốt. Được đông đảo người dùng.|  |  |
| [Glide](https://github.com/bumptech/glide) |Thư viện hỗ trợ loading, caching image.|"Hỗ trợ ảnh GIF, Khi download ảnh to, draw vào một view nhỏ, đạt hiệu suất cao nhất, do thực hiện tính toán, và tải về ảnh chính xác theo kích thước đó. Picaso cũng có thể như vậy, nhưng phải config phức tạp hơn, còn glide thì tự động."| Nhưng khi caching ảnh, thì glide lại chỉ cache ảnh bé theo kích thước view, chứ ko cache ảnh gốc. Trong khi Picaso lại download và cache ảnh kích thước lớn nhất.| Picaso, UImageLoader, Fresco, Glide vs Picaso khá là giống nhau. UImageLoader em dùng thấy khá phức tạp. Hiệu năng thì ko rõ lắm. Fresco thì là lib của anh FB, cũng khá ngon cơ mà e chưa thử.|
|[Retrofit](http://square.github.io/retrofit/) | Làm việc với http API| Các tham số request và response được chuyển thành đối tượng Java, code tường minh, dễ thực hiện, hỗ trợ đầy đủ cấc giao thức.| Nếu muốn tự xử lý dữ liệu nhận về có vẻ khó khăn. Cancel 1 request chưa  hỗ trợ|[android-volley](https://github.com/mcxiaoke/android-volley), [robospice](https://github.com/stephanenicolas/robospice)|

| [Calligraphy ](https://github.com/chrisjenx/Calligraphy/blob/master/README.md)       | Làm việc với font| Cài đặt đơn giản, set font mặc định toàn app đơn giản
Có thể custom cho từng View trong xml  |một số định dạng font không chạy được | [Fontain](https://github.com/scopely/fontain) |
