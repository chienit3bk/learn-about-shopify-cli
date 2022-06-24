
<h2>Authentication</h2>

Dựa theo <strong>https://github.com/Shopify/product-reviews-sample-app/blob/main/docs/technical-details/authentication.md</strong>

Để giữ cho các giao dịch trên nền tảng Shopify được giữ an toàn và bảo mật, tất cả các app kết nối với API của Shopify phải được xác thực khi gọi API

Khi 1 token được khởi tạo, có thể chọn 1 trong 2 cách truy cập khác nhau:

`*` Online access: các token với online access mode đã được kết nối tới một người dùng riêng biệt trên một của hàng, nơi mà access token's lifespan gắn với lifespan của phiên sử dụng của người dùng. Kiểu truy cập này có nghĩa là nó được sử dụng khi mà người dùng tương tác với app của bạn trên web, hoặc khi một app có phân quyền người dùng
`*` Ofline access: các token với ofline access mode được sử dụng cho việc truy cập lâu dài 1 cửa hàng, nời mà người dùng tương tác và làm việc. Offline access mod là ý tưởng để làm việc với webhook

