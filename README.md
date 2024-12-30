# MKE-M20 TTL to RS485 Module
![](/image/04_z6161366599727_a17e342b0945f859f2d1ab5663fb82b2.jpg)

## Giới thiệu

Mạch chuyển giao tiếp MKE-M20 TTL to RS485 được thiết kế để có thể giúp bạn chuyển giao tiếp từ chuẩn giao tiếp UART TTL (Vi điều khiển, máy tính nhúng,...) sang chuẩn giao tiếp RS485 và ngược lại. Với khả năng chống nhiễu cao, tích hợp các bộ đệm, chuyển mức logic 5V-3V3, Cầu chì tự phục hồi, Diod chống nhiễu giúp hệ thống chạy ổn định, an toàn hơn và không làm cháy board điều khiển trung tâm. Phần chân giao tiếp RS485 trên mạch có chân Mass, nếu hệ thống có đường đây mass tiếp đất thì có thể sử dụng để nối vào chân Mass này giúp tăng khả năng chống nhiễu và chống sét.

Mạch hỗ trợ kết nối nhiều điểm RS485 trên đường Bus, mạch được thiết kế để các điểm có thể nối "nóng" mà không sợ hiện tượng module bị chết khi chưa ngắt đường truyền tổng.

### Tính năng

- Tích hợp IC chuyển mức logic TTL 3.3-5VDC.
- Chống sét, bảo vệ quá áp GDT.
- Cầu chì tự phục hồi bảo vệ quá dòng.
- Bảo vệ chống xung điện áp (tĩnh điện) TVS.  

![](/image/05_z6161497935934_38dab30a0624157af4a818e1ff45fdbf.jpg)

Trong mạch RS485 TTL, các thành phần như GDT (Gas Discharge Tube), fuse (cầu chì), và TVS (Transient Voltage Suppressor) đóng vai trò quan trọng trong việc bảo vệ mạch khỏi các sự cố điện áp và dòng điện quá mức. Dưới đây là chức năng của từng thành phần:

1. **GDT (Gas Discharge Tube)**
   - **Chức năng:** GDT là một thiết bị bảo vệ chống sét và quá áp. Khi điện áp vượt quá một ngưỡng nhất định, khí bên trong GDT sẽ ion hóa và tạo ra một đường dẫn dòng điện, giúp chuyển hướng dòng điện quá mức ra khỏi mạch bảo vệ.
   - **Ứng dụng trong RS485 TTL:** GDT thường được sử dụng để bảo vệ mạch RS485 khỏi các xung điện áp cao do sét hoặc các sự cố điện áp khác. GDT giúp bảo vệ các linh kiện nhạy cảm trong mạch khỏi bị hư hỏng.

2. **Fuse (Cầu chì)**
   - **Chức năng:** Cầu chì là một thiết bị bảo vệ quá dòng. Khi dòng điện vượt quá giá trị định mức của cầu chì, nó sẽ nóng chảy và ngắt mạch, ngăn chặn dòng điện quá mức tiếp tục chảy qua mạch.
   - **Ứng dụng trong RS485 TTL:** Cầu chì được sử dụng để bảo vệ mạch RS485 khỏi các sự cố quá dòng, chẳng hạn như ngắn mạch hoặc dòng điện quá mức do lỗi thiết bị. Khi cầu chì ngắt, nó giúp ngăn chặn hư hỏng nghiêm trọng cho các linh kiện khác trong mạch.

3. **TVS (Transient Voltage Suppressor)**
   - **Chức năng:** TVS là một thiết bị bảo vệ chống xung điện áp. Khi có xung điện áp cao xuất hiện, TVS sẽ kẹp điện áp ở mức an toàn bằng cách tạo ra một đường dẫn dòng điện thấp trở kháng, giúp bảo vệ các linh kiện khỏi bị hư hỏng do điện áp quá mức.
   - **Ứng dụng trong RS485 TTL:** TVS thường được sử dụng để bảo vệ mạch RS485 khỏi các xung điện áp ngắn hạn, chẳng hạn như xung ESD (Electrostatic Discharge) hoặc các xung điện áp khác. TVS giúp duy trì điện áp trong khoảng an toàn cho các linh kiện trong mạch.

Những thành phần này kết hợp với nhau để cung cấp một giải pháp bảo vệ toàn diện cho mạch RS485 TTL, giúp đảm bảo hoạt động ổn định và bền bỉ trong các điều kiện môi trường khắc nghiệt.

Ngoài ra mạch còn tích hợp chuyển mức logic nên có thể giao tiếp Uart trực với các vi điều khiển 3V3 như ESP8266, ESP32, STM32F103, ...

## Thông số kỹ thuật

- Điện áp hoạt động: 3V3 - 5VDC.
- Điện áp giao tiếp TTL: 3V3 - 5VDC.
- Khoảng cách truyền RS485 có thể lên đến 1.2km (khuyến nghị sử dụng dưới 800m và dây bus chuyên dụng cho RS485).
- Chuẩn chân cắm: TTL 2.54mm, RS485 Domino 5.08mm
- Có đèn led thông báo trạng thái truyền nhận RX và TX.

## Hình ảnh sản phẩm

![](/image/01_z6161363600645_826b10180d7e5e907609d3ebd44f8fb1.jpg)  
Mặt trước
![](/image/02_z6161364849347_18d98a1dadfcc866e54c6302dd85e497.jpg)  
Mặt sau

## Kích thước sản phẩm

![](/image/dimension.png)

## Các chân tín hiệu

| Chân | Mô Tả |
|------|-------|
| GND  | Chân nguồn GND (0V) của mạch |
| 5V   | Chân nguồn 5V của mạch  |
| TX   | Chân truyền tín hiệu tới chân RX của MCU |
| RX   | Chân nhận tín hiệu được truyền từ chân TX của MCU |
| A    | Chân A theo chuẩn RS485 |
| B    | Chân B theo chuẩn RS485 |
| PE   | Nối đất chống sét |

## Hướng dẫn sử dụng

![](/image/RS485toTTL.png)

## Hỗ trợ và liên hệ

- Website: [https://www.makerlab.vn/](https://www.makerlab.vn/)
- Facebook: [https://www.facebook.com/makerlabvn](https://www.facebook.com/makerlabvn)

## Nhà phân phối

- Các bạn có thể mua sản phẩm của MakerLab tại các [Nhà Phân Phối.](https://www.makerlab.vn/distributor/)
