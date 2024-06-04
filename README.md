# DATN
- Chủ đề: Bán giày (+ phụ kiện thời trang)
- Giảng viên hướng dẫn: Lê Trọng Đạt (-> thầy Đức -> thầy Hoàng -> thầy Sơn)

<!--  -->
- rfc : React Function Component
- prefix: tiền tố
- port: cổng

<!-- Quy chuẩn code (cấu trúc thư mục, cách đặt tên, ...) -->
- Tên các hằng số: Viết hoa hết và cách nhau bởi dấu gạch dưới (ví dụ: DISCOUNT_PERCENT)
- Tên các biến, hàm: camelCase (từ đầu tiên viết thường, các từ tiếp theo viết hoa chữ cái đầu, ví dụ: thisIsMyVariable.)
- Tên các rfc, class, tên file jsx : PascalCase (viết hoa tất cả các chữ cái đầu, ví dụ: ThisIsMyVariable)
- Tên các interface: PascalCase + prefix "I" (ví dụ: IMyInterface)
- Tên bảng, tên cột trong Database sử dụng underscore và sử dụng danh từ số nhiều (ví dụ: user_accounts)
- Tên các file, hàm trong custom hook (các hook tự tạo): camelCase + prefix "use" (ví dụ: useMyHook)

- Sử dụng "export default" cho các rfc (ví dụ: export default MyComponent)
- Sử dụng "export" cho các method (ví dụ: export const myFunction = () => { // })
- 1 file chỉ được "export default" 1 function (hoặc biến)
- 1 file có thể "export" nhiều method

- Trong môi trường development, Front-end chạy ở port 3000 (http://localhost:3000), Back-end chạy ở port 5000 (http://localhost:5000)


<!-- Thiết kế giao diện -->
- Figma (FE)


<!-- Coding -->
- API + Db (BE)
- Front-end (BE + FE)

- Devops (BE)


<!-- Công nghệ sử dụng (Lib, Framkework) -->
- FE: Vite + React + Typescript + Tailwind + daisyUI (thư viện component Tailwind) + axios
- BE: Node + Express + MongoDB ( || PHP Laravel + Mysql)
- (Cache)


<!-- Tính năng: -->
    -Trang User:
        + Đăng nhập, đăng ký, quên mật khẩu, login by google account
        + Hiển thị danh sách
        + Giỏ hàng
        + Wishlist (yêu thích)
        + Tìm kiếm
        + Trạng thái đơn hàng (đang giao, đã giao,...)
        + Voucher
        + Lịch sử mua hàng
        + Profile (xem, chỉnh sửa thông tin)
        + Thanh toán online
        + Gợi ý tìm kiếm

