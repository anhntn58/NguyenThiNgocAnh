
## Description
Chương trình nhập một số bất kì từ bản phím và tính số đảo ngược của chính nó. 
viết bằng java, unit test sử dụng thư viện junit trên eclipse

## Áp dụng phương pháp giá trị biên BVA test hàm SoDaoNguoc:

- CT nhận 1 biến đầu vào kiểu int là N.
- N có MXD: -2147483648 <= N <= 2147483647
- BVA chọn các giá trị sau: -2147483648, -2147483647, 0, 1, 2147483646, 2147483647

## BVA phù hợp vì:

- chương trình chỉ có duy nhất một biến đầu vào độc lập
- biến này bị chặn trong kiểu int -2147483648.. ...2147483647
- các ca kiểm thử cũng không tính đến chức năng của hàm.

## Độ bao phủ:

![Coverage](file:///C:/Users/Ngoc%20Anh/Documents/a.png)

![Đồ Thị](file:///C:/Users/Ngoc%20Anh/Documents/cd.png)
