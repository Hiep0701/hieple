# **Hướng dẫn tải về từ Trang chủ và cài đặt Centos 7 và Ubuntu 16 trên VMware**

## __Cài đặt Centos 7 trên VMwware__

>Chuẩn bị:
>- Cấu hình tối thiểu : Ổ cứng : 40 GB , RAM : 4G
>- Cấu hình khuyến cáo : Ổ cứng : 100GB , RAM : 8GB đối với 64bit.
>- Phần mềm VMWare Workstation: [Link tải](https://my.vmware.com/web/vmware/downloads/details?downloadGroup=WKST-1412-WIN&productId=686&rPId=23138)
>- Tải Centos 7 theo link sau: [Click tại đây](www.centos.org/download/)


* Bước 1: Khởi động máy ảo __VMware__ > __File__ > __New Virtual Machine__.

![b1](https://tungphatcomputer.com/images/upload/images/buoc-1-cai-dat-centos.jpg)

* Bước 2: Chọn **Custom** > **Next**.

![b2](https://tungphatcomputer.com/images/upload/images/buoc-2-cai-dat-centos.jpg)

* Bước 3: Check vào ô __I will install the operating system later.__ > **Next**

![b3](https://tungphatcomputer.com/images/upload/images/buoc-3-cai-dat-centos.jpg)

* Bước 4: Chọn **Linux** > **Version: Centos 7 64-bit**

![b4](https://tungphatcomputer.com/images/upload/images/buoc-4-cai-dat-centos.jpg)

* Bước 5: Đặt tên và chọn nơi lưu file

![b5](https://tungphatcomputer.com/images/upload/images/buoc-5-cai-dat-centos.jpg)

* Bước 6: Chọn tốc độ xử lý của máy ảo.

![b6](https://tungphatcomputer.com/images/upload/images/buoc-6-cai-dat-centos.jpg)

* Bước 7: Chọn RAM.

![b7](https://tungphatcomputer.com/images/upload/images/buoc-7-cai-dat-centos.jpg)

* Bước 8: Thiết lập card mạng cho máy ảo (chọn card nat hoặc bried)

![b8](https://tungphatcomputer.com/images/upload/images/buoc-8-cai-dat-centos.jpg)

* Bước 9: Thiết lập chế độ nhập xuất

![b9](https://tungphatcomputer.com/images/upload/images/buoc-9-cai-dat-centos.jpg)

* Bước 10: Click **Next**

![b10](https://tungphatcomputer.com/images/upload/images/buoc-10-cai-dat-centos.jpg)

* Bước 11: Tạo một ổ đĩa ảo mới. Chọn **Create a new virtual disk > Next**

![b11](https://tungphatcomputer.com/images/upload/images/buoc-11-cai-dat-centos.jpg)

* Bước 12: Chọn dung lượng cho ổ đĩa. ***NHỚ CHỌN*** **Store virtual disk as a single file**

![b12](https://tungphatcomputer.com/images/upload/images/buoc-12-cai-dat-centos.jpg)

* Bước 13: Chọn đường dẫn lưu file ổ đĩa ảo, sau này có thể copy và chuyển qua máy tính khác mã vẫn dùng được máy ảo

![b13](https://tungphatcomputer.com/images/upload/images/buoc-13-cai-dat-centos.jpg)

* Bước 14: Chọn **Customize Hardware** để kiếm tra lại các thiếp lập.

![b14](https://tungphatcomputer.com/images/upload/images/buoc-14-cai-dat-centos.jpg)

* Bước 15:  **New CD/DVD  (IDE) > Use ISO image file** và chọn đến đường dẫn **file ISO centos 7** đã tải về ở trên. Sau đó ấn **Close**.

![ab15lt](https://tungphatcomputer.com/images/upload/images/buoc-15-cai-dat-centos.jpg)

* Bước 16: Chọn **Finish**

![b16](https://tungphatcomputer.com/images/upload/images/buoc-16-cai-dat-centos.jpg)

* Bước 17: Khởi động **Centos** bằng __Power on this virtual machine__

![b17](https://tungphatcomputer.com/images/upload/images/buoc-17-cai-dat-centos.jpg)

* Bước 18: Chọn **Install centos 7**

![b18](https://tungphatcomputer.com/images/upload/images/buoc-18-cai-dat-centos.jpg)

* Bước 19: Thiết lập **Ngôn ngữ > Continue**

![b19](https://tungphatcomputer.com/images/upload/images/buoc-19-cai-dat-centos.jpg)

* Bước 20: Thiết lập **Ngày, Giờ. DATE & TIME > Done** (set giờ Việt Nam)

![b20](https://tungphatcomputer.com/images/upload/images/buoc-20-cai-dat-centos.jpg)

* Bước 21: Ở mục **SOFTWATE SELECTION**, chọn giao diện đồ hoạ (GUI) để dễ dàng thao tác: **Server with GUI > KDE > Done**

![b21](https://tungphatcomputer.com/images/upload/images/buoc-21-cai-dat-centos.jpg)

* Bước 22: Mục **INSTALLATION DESTINATION**, chọn ổ đĩa ảo đã tạo > **Done**

![b22](https://tungphatcomputer.com/images/upload/images/buoc-22-cai-dat-centos.jpg)

* Bước 23: Mục **NETWORK & HOST NAME**, chọn **ON > Done**

![b23](https://tungphatcomputer.com/images/upload/images/buoc-23-cai-dat-centos.jpg)

* Bước 24: Chọn **Begin Installation**

![b24](https://tungphatcomputer.com/images/upload/images/buoc-24-cai-dat-centos.jpg)

* Bước 25: Thiết lập tài khoản **ROOT**, tài khoản này rất quan trọng nên cần phải ghi nhớ mật khẩu

![b25](https://tungphatcomputer.com/images/upload/images/buoc-25-cai-dat-centos.jpg)

* Bước 26: Chờ máy tự động cài đặt, khoảng 3 đến 5 phút tuỳ vào cấu hình của máy tính. Click **Reboot**

![b26](https://tungphatcomputer.com/images/upload/images/buoc-26-cai-dat-centos.jpg)

* Bước 27: chọn **I accept the license agreement**

![b27](https://tungphatcomputer.com/images/upload/images/buoc-27-cai-dat-centos.jpg)

* Bước 28: Tạo tài khoản mới để đăng nhập vào hệ thống.

![b28](https://tungphatcomputer.com/images/upload/images/buoc-28-cai-dat-centos.jpg)

* Bước 29: Set mật khẩu cho tài khoản của bạn vừa tạo. __Lưu ý là mật khẩu root và user phải khác nhau__

![b29](https://tungphatcomputer.com/images/upload/images/buoc-29-cai-dat-centos.jpg)

* Bước 30: Bạn đã có thể chạy được Centos trên máy ảo VMware

![b30](https://tungphatcomputer.com/images/upload/images/buoc-30-cai-dat-centos.jpg)

___

## __Cài đặt Ubuntu 16__

>Chuẩn bị:
> - Phần mềm VMWare Workstation: [Link tải](https://my.vmware.com/web/vmware/downloads/details?downloadGroup=WKST-1412-WIN&productId=686&rPId=23138)
> - File cài đặt Ubuntu (file ISO): [Link tải](https://ubuntu.com/download/desktop)

+ Bước 1: Bạn nhấn vào nút **Create a New Virtual Machine**.

![b1](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-8.png)
 
+ Bước 2: Chọn dạng cài đặt là **Typical** => sau đó nhấn chọn **Next** để tiếp tục.

![b2](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-9.png)

+ Bước 3: Tích chọn __Installer disc image file (iso)__ => nhấn vào __Browse.....__ để chọn đường dẫn trỏ tới file ISO của bộ cài Ubuntu => và __Next.__

![b3](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-10.png)

+ Bước 4: Đặt Tên và Password (lưu ý không viết hoa chữ cái đầu tiên cho user name). Sau đó nhấn __Next__

![b4](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-11.png)

Đặt lại tên trong mục __Virtual machine name__: , hoặc có thể giữ nguyên theo mặc định => chọn __Next__.

![b4](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-12.png)

+ Bước 5: Chọn dung lượng ổ cứng cho máy ảo như hình, nên để trong khoản 20 – 50 GB tùy vào dung lượng ổ cứng và nhu cầu sử dụng của bạn

![b5](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-13.png)

+ Bước 6: Bạn có thể chọn __Customize Hardware__ để thay đổi tùy chọn và có nhiều tùy chọn hơn.

![b6](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-14.png)

+ Bước 7: Các tùy chọn có thể thay đổi như hình dưới. Nếu như máy tính của bạn có dung lượng RAM lớn, thì nên để RAM nhiều nhiều một chút để máy tính ảo chạy mượt hơn. Sau đó nhấn __Close__ và __Finish__

![b7](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-15.png)

+ Bước 8: Giao diện cài xong như hình bên dưới => chọn __Power on the virtual machine__ để khởi động và boot vào bộ cài Ubuntu.

![b8](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/
cai-ubuntu-tren-may-ao-vmware-16-768x414.png)

Quá trình boot và bung file Ubuntu ra máy ảo đang diễn ra. Bạn đợi cho quá trình này kết thúc

![b8](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-19-768x431.png)

Done!!! Bạn đã cài thành công

![b8](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-20-768x432.png)

Giao diện sẽ như hình bên dưới

![b8](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-21-768x432.png)

>Tham khảo tại các bài viết:
>> + https://blogchiasekienthuc.com/thu-thuat-hay/cai-dat-ubuntu-tren-may-tinh-ao-vmware.html
>> + https://tungphatcomputer.com/huong-dan-cai-dat-centos-7.html
