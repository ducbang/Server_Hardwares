# Các công nghệ lưu trữ
## **1) Direct Attached Storage ( DAS )**
- **DAS** là loại hình lưu trữ thường thấy trong các máy trạm .
- Các ổ cứng trong Server được kết nối đến các cổng local trên **mainboard** như **SATA** , **USB** , **SCSI** , hoặc Serial Attached SCSI ( **SAS** ) .
- Nếu các ổ cứng chạy RAID được gắn trực tiếp lên các cổng trên **mainboard** mà không thông qua card RAID thì vẫn được tính là **DAS** .
- Đặc điểm chính : Không có kết nối mạng giữa Server và Storage
## **2) Network-Attached Storage ( NAS )**
- **NAS - Network-Attached Storage** là các thiết bị lưu trữ được đặt trong mạng và Server phải truy cập vào chúng qua mạng TCP/IP .
- Với **NAS** , tất cả các máy nào ở trong mạng LAN ( hoặc kết nối vào mạng LAN đó qua đường truyền WAN ) đều có thể sử dụng các giao thức như **NFS** , **CIFS** hay **HTTP** để kết nối đến **NAS** và chia sẻ file .
- Các ưu điểm và <span style="color:red">nhược điểm</span> của **NAS** :

| **Ưu điểm** | **Nhược điểm** |
|-------------|----------------|
