# Tích hợp Zimbra và Openroad

## Tổng quan Zimbra và Openroad
### Zimbra 

[Zimbra](http://www.zimbra.com/) là một giải pháp thư điện tử, lịch và cộng tác hữu ích hướng đến các doanh nghiệp.

### Openroad

[OpenRoad](http://openroad.vn/) là một phần mềm nguồn mở được phát triển dựa trên [Joinup](https://joinup.ec.europa.eu/), một nền tảng cộng tác và chia sẻ các công nghệ mở nói chung và các ứng dụng nguồn mở nói riêng dành cho khu vực cộng đồng chính phủ Châu Âu.

Xem thêm thông tin: [dự án Openroad](https://github.com/Openroadvietnam/openroad).

## Tại sao phải tích hợp Openroad và Zimbra?

Openroad chưa có một nền tảng nhắn tin (thư điện tử) cho người dùng. Người dùng Openroad cần sử dụng tính năng thư điện tử (Zimbra) để trao đổi thông tin trong hoạt động chia sẻ các công nghệ mở và các ứng dụng nguồn mở.

## Sử dụng Single Sign-On

Thiết lập cơ chế [single sign-on](http://en.wikipedia.org/wiki/Single_sign-on) (sử dụng Central Authentication Server - CAS) cho phép người dùng Openroad sử dụng hệ thống thư điện tử (Zimbra) mà chỉ cần đăng nhập hệ thống duy nhất một lần.

## Mô đun tích hợp Openroad và Zimbra
### Mô đun tích hợp trên Openroad

Openroad sử dụng [mô đun của Drupal](https://drupal.org/project/cas_services) (CAS client) để kết nối với hệ thống sử dụng CAS.

### Mô đun tích hợp trên Zimbra

Zimbra sử dụng [CAS client](https://wiki.jasig.org/display/CAS/CASifying+Zimbra) để kết nối với hệ thống sử dụng CAS.

## Tài liệu

Tài liệu hướng dẫn cài đặt và tích hợp Openroad - Zimbra được đặt trong thư mục [docs](docs).

## Kênh thông tin

* IRC: #openroad on irc.freenode.net
* Mailing list: http://lists.openroad.vn/mailman/listinfo/

## Giấy phép sử dụng

Openroad và module tích hợp do nhóm phát triển Openroad và module giữ quyền tác giả, được phân phối kèm theo giấy phép GNU GPL v2.0. Nguyên văn giấy phép sử dụng có thể được xem trong file [LICENSE](LICENSE).
