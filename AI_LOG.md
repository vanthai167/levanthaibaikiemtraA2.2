# Nhật ký sử dụng AI

## Khai báo sử dụng AI

- **Có sử dụng AI:** Có. AI assistant trong VS Code được dùng để đọc cấu trúc
  dự án, đối chiếu đường dẫn tài nguyên trong HTML với các tệp hiện có và hỗ
  trợ ghi nhật ký này.
- **Phạm vi:** Chỉ cập nhật tài liệu này. Không dùng AI để tạo nội dung thay
  cho người viết và không chỉnh sửa HTML/CSS trong lượt ghi nhận này.

## Hiện tượng và nhận định ban đầu

- `index.html` liên kết tới `css/style.css` và bốn ảnh trong thư mục `assets/`.
- Cấu trúc workspace được kiểm tra chỉ có `AI_LOG.md`, `index.html`,
  `ket-qua.html` và `css/style.css`; không thấy thư mục hoặc tệp `assets/`.
- Nhận định ban đầu: đường dẫn CSS có tệp tương ứng trong workspace; bốn ảnh
  được tham chiếu không có trong cấu trúc hiện tại nên có nguy cơ không hiển
  thị. Chưa thể kết luận trạng thái trên website đã xuất bản nếu chưa mở URL.
- Form trong `index.html` gửi bằng GET tới `ket-qua.html`. Nội dung trang kết
  quả nói rõ form không gửi email và không lưu dữ liệu lên máy chủ.

## Gợi ý của công cụ và quyết định

- **Gợi ý của AI:** Kiểm tra tài nguyên thực tế trong workspace trước khi đổi
  đường dẫn; chỉ ghi nhận kết quả kiểm thử khi đã thực sự truy cập URL.
- **Quyết định:** Không tự thay đường dẫn ảnh vì chưa có tệp ảnh thay thế để
  xác định đường dẫn đúng. Không sửa HTML/CSS ngoài phạm vi yêu cầu. Gỡ các
  ghi nhận cũ không đối chiếu được với workspace hiện tại, gồm tuyên bố đã cập
  nhật `README.md`, đã mở thành công URL GitHub Pages và đã kiểm tra hồ sơ
  `vanhkazen`; workspace hiện không có `README.md` và các lượt kiểm tra đó
  không được xác nhận trong phiên này.
- **Căn cứ:** Chỉ ghi những gì có thể đối chiếu trực tiếp với các tệp và kết
  quả thao tác thực tế trong phiên; không suy ra trạng thái triển khai từ mã
  nguồn local.

## Kiểm thử URL và kết quả

- URL website công khai chưa được cung cấp hoặc xác nhận trong workspace.
- Chưa kiểm thử trang local hay URL công khai bằng trình duyệt/HTTP trong
  phiên này. Lời gọi công cụ để truy cập URL và chạy kiểm tra đã bị từ chối,
  vì vậy không ghi mã HTTP, trạng thái tải trang, ảnh hoặc kết quả gửi form
  như thể đã được kiểm chứng.
- Các điểm cần kiểm tra khi có quyền truy cập URL: trang chủ, trang
  `ket-qua.html`, stylesheet, bốn ảnh được tham chiếu và gửi thử form với dữ
  liệu hợp lệ; ghi URL cụ thể cùng kết quả quan sát được sau khi thực hiện.
