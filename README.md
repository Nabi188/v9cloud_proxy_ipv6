# v9cloud_proxy_ipv6
Tạo hàng loạt proxy ipv6 từ 1 ipv4.
Lưu ý: Các trang web không phân giải được ipv6 sẽ không truy cập được qua proxy ipv6

**Yêu cầu**
1 VPS chạy CentOS 7 trở lên
Cấu hình sẵn /64 IPv6 (V9Cloud đã cấu hình sẵn IPv6 )

**Các bước cài đặt**
[Video chi tiết]: , sử dụng CentOS (thuê tại V9Cloud) để cài đặt

Bước 1. Chạy lệnh trên CentOS: bash <(curl -s "https://raw.githubusercontent.com/Nabi188/v9cloud_proxy_ipv6/main/proxy.sh")

Bước 2: Vào SFTP theo đường dẫn trên SSH

Bước 3: Tải file proxy.zip, cấu trúc proxy: IP4:PORT:LOGIN:PASS
