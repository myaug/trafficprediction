# Traffic Prediction
**Tính chất của dữ liệu:**
- Dữ liệu là thông tin về traffic của các cell 4G (Cell 4G là thiết bị phát sóng vô tuyến để phục vụ các thiết bị). Traffic của cell 4G được hiểu đơn giản như sau: Khi người dùng sử dụng dịch vụ data trên thiết bị di động, thì thiết bị di động đó sẽ được phục vụ bởi 1 cell 4G được đặt gần đó. Tổng dung lượng data của tất cả các người dùng được phục vụ bởi 1 cell trong vòng 1 giờ được gọi là Traffic của cell đó trong vòng 1 giờ. VD: Cell 039872 đang phục vụ cho 50 thuê bao, mỗi thuê bao trong 1 giờ x sử dụng trung bình 10Mb => Traffic của cell 039872. Vậy traffic của cell này trong giờ x = 50 * 10 = 500Mb.
- Tập dữ liệu có: 57 cell
- Dữ liệu được lấy trong vòng xấp xỉ 1 năm x 24 giờ x 57 cell.
- Tính chất của traffic sẽ có sự khác nhau theo từng giờ (VD: vào khoảng thời gian 10-12h và 19-23h traffic sẽ rất cao, 0-6h traffic sẽ rất thấp); khác nhau giữa các ngày trong tuần (VD: đồ thị traffic của các cell phục vụ tòa nhà công sở, sẽ có traffic cao vào thứ 2-6 và thấp vào thứ 7, chủ nhật); khác nhau vào các sự kiện đặc biệt (lễ hội, tết, ...)

<img src="data.png" />

