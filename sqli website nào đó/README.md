## Tìm lỗ hổng

Đầu tiên là mình tìm được một trang login của web, Dùng một số payloads để check 

![](https://raw.githubusercontent.com/d0DuyKh3ng/websecurity/main/sqli%20website%20n%C3%A0o%20%C4%91%C3%B3/images/1.JPG)
![](https://raw.githubusercontent.com/d0DuyKh3ng/websecurity/main/sqli%20website%20n%C3%A0o%20%C4%91%C3%B3/images/2.JPG)

Như mọi người thấy thì sau khi thêm dấu phẩy ' thì website đã gặp một lỗi truy vấn sql

## Login Bypass

Mình đã sử dụng một payload như sau:

' or 1=1; -- -

Cái này thì khá cơ bản trong SQLi nên mình sẽ không nói về nó nhiều.

![](https://raw.githubusercontent.com/d0DuyKh3ng/websecurity/main/sqli%20website%20n%C3%A0o%20%C4%91%C3%B3/images/3.JPG)

Như trên màn hình thì mình đã truy cập được vào tài khoản của admin, bây giờ chỉ cần Deface lại web cho giống Hacker là xong.
