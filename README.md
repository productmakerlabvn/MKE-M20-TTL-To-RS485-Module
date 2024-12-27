# MKE-M20 TTL to RS485 Module

## Giới thiệu

Mạch chuyển giao tiếp MKE-M20 TTL to RS485 được thiết kế để có thể giúp bạn chuyển giao tiếp từ chuẩn giao tiếp UART TTL (Vi điều khiển, máy tính nhúng,...) sang chuẩn giao tiếp RS485 và ngược lại.

Mạch chuyển giao tiếp UART TTL to RS485 V2 được thiết kế với khả năng chống nhiễu cao, tích hợp các bộ đệm, chuyển mức logic 5V-3V3, Cầu chì tự phục hồi, Diod chống nhiễu giúp hệ thống chạy ổn định, an toàn hơn và không làm cháy board điều khiển trung tâm. Phần chân giao tiếp RS485 trên mạch có chân Mass, nếu hệ thống có đường đây mass tiếp đất thì có thể sử dụng để nối vào chân Mass này giúp tăng khả năng chống nhiễu và chống  sét.

Mạch hỗ trợ kết nối nhiều điểm RS485 trên đường Bus, mạch được thiết kế để các điểm có thể nối "nóng" mà không sợ hiện tượng module bị chết khi chưa ngắt đường truyền tổng.

## Thông số kỹ thuật

- Điện áp hoạt động: 3 - 5VDC.
- Điện áp giao tiếp TTL: 3 - 5VDC.
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

<table><thead>
  <tr>
    <th>Chân</th>
    <th>Mô Tả</th>
  </tr></thead>
<tbody>
  <tr>
    <td>GND</td>
    <td>Chân nguồn GND (0V) của mạch</td>
  </tr>
  <tr>
    <td>5V</td>
    <td>Chân nguồn 5V của mạch</td>
  </tr>
  <tr>
    <td>TX</td>
    <td>Chân truyền tín hiệu tới chân RX của MCU</td>
  </tr>
  <tr>
    <td>RX</td>
    <td>Chân nhận tín hiệu được truyền từ chân TX của MCU</td>
  </tr>
  <tr>
    <td>A</td>
    <td>Chân A theo chuẩn RS485</td>
  </tr>
  <tr>
    <td>B</td>
    <td>Chân B theo chuẩn RS485</td>
  </tr>
  <tr>
    <td>PE</td>
    <td>Nối đất chống sét</td>
  </tr>
</tbody>
</table>

## Hướng dẫn sử dụng

![](/image/ttl-rs4851.png)

## Hỗ trợ và liên hệ

- Website: [https://www.makerlab.vn/](https://www.makerlab.vn/)
- Facebook: [https://www.facebook.com/makerlabvn](https://www.facebook.com/makerlabvn)

## Nhà phân phối

- Các bạn có thể mua sản phẩm của MakerLab tại các [Nhà Phân Phối.](https://www.makerlab.vn/distributor/)
