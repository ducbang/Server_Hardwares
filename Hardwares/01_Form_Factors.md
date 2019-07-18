# Form Factors
## **1) Rack Mount**
- **Rack Mount Servers** là những Server được thiết kế để được gắn vào trong 1 khung sắt gọi là **tủ rack** và do đó chúng được thiết kế để vừa với một trong vài tiêu chuẩn về kích cỡ của slot trong **tủ rack** , hay còn gọi là **bays** .
- Chúng cũng yêu cầu những **bộ thanh ray** , giúp Server trượt ra/vào trong **tủ rack** .
- Lợi ích của việc sử dụng **tủ rack** để gắn Servers , Routers , Switches hoặc các thiết bị phần cứng khác là :
    - **Tủ rack** cho các thiết bị tránh xa mặt sàn
    - Tạo nên nhiều không gian hơn cho phòng Server
    - Tạo được vòng tuần hoàn gió tản nhiệt tốt hơn
- Các thông số của **tủ rack** :

    <img src=https://i.imgur.com/Atu2ARY.png>

    - Có 2 dạng **tủ rack** :
        - **`19-inch`** : mỗi thiết bị phải có chiều rộng mặt trước là `19-inch` ( `48,26cm` )
        - **`23-inch`** : mỗi thiết bị phải có chiều rộng mặt trước là `23-inch` ( `58,42cm` )
    - Các thiết bị được phân biệt dựa trên chiều cao của chúng . Thông số chung này được gọi là **`rack units`** , hay gọi tắt là **`U`** . Có 4 chuẩn **`U`** dành cho Server :
        - **`1U`** : dành cho những thiết bị nhỏ chỉ cao `1,75 inch` ( như **KVM switch** , **Ethernet switch** ,... )

            <img src=https://i.imgur.com/NZ14hX2.png>

        - **`2U`** : là 1 loại cũng khá phổ biến , dành cho những Server , Router , Firewall lớn hơn với chiều cao `3,5 inch` 

            <img src=https://i.imgur.com/IimwH2q.png>

        - **`3U`** : không phổ biến bằng 2 loại trên

            <img src=https://i.imgur.com/05YwRkb.png>

        - **`4U`** : cao gấp đôi Server **`2U`** và cũng là 1 dạng phổ biến

            <img src=https://i.imgur.com/OvC38Yz.png>

    - Các loại màn LCD gắn sẵn trên **tủ rack** thường có kích cỡ **`7U`** . Server cũng có những loại như **blade server** lên tới **`10U`** .
    - 1 **tủ rack** tiêu chuẩn cung cấp khoảng **`42U`**
- Các **bộ thanh ray** :
    - 1 **bộ thanh ray** sẽ chia thành 2 phần : 1 phần gắn vào Server ( **inner rail** ) và 1 phần gắn vào **tủ rack** ( **outer rail** ) . **Inner rail** được thiết kế nhỏ hơn để có thể trượt trong **outer rail**

        <img src=https://i.imgur.com/NYeBn7O.png>

## **2) Tower**
- Một dạng Server thứ 2 cũng khá quen thuộc là **tower server** , có hình dạng thẳng đứng , tương tự những máy workstation mà ta thường sử dụng .
- Khi các Server này được đặt trong phòng Server , chúng không được gắn trên **rack** mà gắn trên giá :

    <img src=https://i.imgur.com/oBoLrZ3.jpg>

- Chúng cũng có thể sử dụng những bộ chuyển đổi để gắn được trên **rack** :

    <img src=https://i.imgur.com/TOaNL1v.jpg>

## **3) Blade**
- Cuối cùng , Server có thể xuất hiện với hình dạng băng dẹt ( **blade** )

    <img src=https://i.imgur.com/4hjSo1G.jpg>

- Công nghệ này bao gồm 1 khoang máy chủ chứa bên trong nhiều bảng mạch mỏng , gọi là **server blades** . Mỗi **blade** ( hoặc **card** ) chứa **CPU** , **RAM** , **card mạng tích hợp** , và một số **cổng I/O** .
- Công nghệ **blade** cho phép giảm tới `85%` số lượng cáp so với server **`1U`** và **tower** truyền thống .
- Công nghệ **blade** sử dụng ít không gian hơn trong **tủ rack** :

    <img src=https://i.imgur.com/M9cveY8.png>

### **3.1) Khoang blade ( blade enclosure )**
- **Khoang blade** là 1 hệ thống chứa nhiều **blade servers** .
- Bên dưới gầm khoang cung cấp điện và làm mát cho **blade server**

    <img src=https://i.imgur.com/U9qCIrE.png>

### **3.2) Bảng nối ( Backplane/Midplane )**
- 