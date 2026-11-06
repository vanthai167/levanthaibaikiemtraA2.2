# Ghi chú bàn giao - Portfolio CV Lê Văn Thái v7

- **Phiên bản tài liệu:** v7
- **Ngày ghi trên bản bàn giao:** 2026-10-30
- **Tác giả ghi trong dự án:** Lê Văn Thái
- **Sản phẩm:** Website portfolio tĩnh dùng HTML và CSS

## Nội dung bàn giao

- `index.html`: trang portfolio và form liên hệ.
- `ket-qua.html`: trang kết quả của form.
- `css/style.css`: định dạng giao diện và responsive.
- `README.md`: hướng dẫn chạy, kiểm tra và các liên kết dự án.
- `AI_LOG.md`: khai báo sử dụng AI, nhận định, quyết định và tình trạng kiểm
  thử.

Trong workspace được kiểm tra, không thấy thư mục `assets/`, dù `index.html`
đang tham chiếu tới ảnh trong thư mục đó. Vì vậy, ảnh có thể không hiển thị khi
chạy từ đúng workspace này. Cần bổ sung đúng các tệp ảnh hoặc sửa đường dẫn sau
khi xác định được nguồn ảnh; chưa tự thay đường dẫn khi chưa có tệp thay thế.

## Liên kết được ghi trong README

- **URL GitHub Pages được khai báo:** https://github.com/vanthai167/levanthaibaikiemtraA2.2.git/
- **Trang kết quả được khai báo:** https://github.com/vanthai167/levanthaibaikiemtraA2.2./ket-qua.html
- **Kho mã nguồn được khai báo:** https://github.com/vanthai167/levanthaibaikiemtraA2.2

Các URL trên được chép từ `README.md`; chưa xác minh khả năng truy cập hoặc
nội dung đang được xuất bản tại thời điểm ghi chú này. Không dùng các URL
`vanthai167.github.io/levanthaibaikiemtraA2.2/` trong bản ghi cũ làm kết quả
kiểm thử của dự án hiện tại.

## Chức năng và giới hạn đã đọc trong mã nguồn

- Menu trang chủ liên kết tới các phần trong portfolio.
- Form dùng `GET` để chuyển tới `ket-qua.html` và có kiểm tra dữ liệu HTML5.
- Form không gửi email và không lưu dữ liệu lên máy chủ; dữ liệu gửi có thể
  xuất hiện trên URL.
- Các liên kết dự án trên trang hiện là văn bản mẫu, chưa phải liên kết bấm
  được tới repository.

## Kiểm thử và tình trạng xác minh

- Đã đối chiếu nội dung tài liệu với HTML/CSS hiện có trong workspace.
- Chưa xác minh URL GitHub Pages, chưa kiểm tra trực quan ảnh hoặc responsive,
  và chưa gửi thử form trong trình duyệt. Do đó chưa thể kết luận bản đang
  xuất bản hoạt động như mong đợi.
- Chưa xác minh trạng thái Git hoặc commit được nêu trong bản ghi cũ. Không
  coi commit `96aa47952010f1efec0c7af9206cedeeaea5d1df` là commit bàn giao đã
  kiểm chứng trong ghi chú này.
- `git diff --check` cũng chưa được chạy trong lượt cập nhật này.

## Việc cần hoàn tất trước khi xác nhận bàn giao

1. Bổ sung các ảnh được tham chiếu trong `index.html` hoặc cập nhật đường dẫn
   cho khớp với các tệp ảnh thực tế.
2. Truy cập URL GitHub Pages được khai báo trong README và kiểm tra trang chủ,
   trang kết quả, CSS, ảnh, bố cục trên màn hình nhỏ và luồng form.
3. Nếu cần ghi nhận commit bàn giao, kiểm tra repository/nhánh và cập nhật
   permalink tới đúng commit chứa các tệp bàn giao.
