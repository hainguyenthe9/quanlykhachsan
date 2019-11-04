# quanlykhachsan

1. Goals
- Xây dựng phần mềm quản lý khách sạn với các chức năng đáp ứng được nhu cầu của người dùng khi sử dụng các dịch vụ liên quan đến khách sạn, nhà nghỉ.
- Những đối tượng phù hợp để quản lý và sử dụng phần mềm:
+ Nhân viên lễ tân: Đặt phòng, checkout, in hóa đơn cho khách hàng
+ Quản lý: quản lý thông tin các phòng và xem các loại báo cáo
+ Khách hàng: Có thể đặt phòng hủy, hủy phòng, checkin, checkout, thanh toán tại quầy
+ Nhân viên bán hàng: giao dịch với khách hàng

2.Business objectives 
* Vì thần mềm tích hợp cho máy tính cá nhân, cho phép người quản trị quản lý đầy đủ thông tin của các phòng, người dùng cũng có thể tương tác thông qua phần mềm nên phù hợp với những mô hình như khách sạn, resort, nhà nghỉ

* Phần mềm đươc quản lý bởi người quản trị. Khách hàng chỉ có thể tương tác các chức năng cơ bản . Phần mềm đáp ứng đầy đủ nhu cầu thiết yếu của khách hàng như:
- Khách hàng có thể checkout và thanh toán bất cứ lúc nào
- Mỗi phòng có thể được đặt/ở bởi nhiều khách hàng khác nhau tại những thời điểm khác nhau.
-	Mỗi khách hàng có thể đặt/ở nhiều phòng khác nhau tại những thời điểm khác nhau.
-	Tại một thời điểm, chỉ có một khách ở trong một phòng, và xác định một giá phòng cụ thể.
-	Khách hàng chỉ có thể đặt phòng nếu phòng đó còn trống trong suốt thời gian khách hàng muốn đặt.
-	Khách hàng có thể thanh toán nhiều lần cho đến ngày trả phòng.
-	Mỗi lần thanh toán, lễ tân sẽ in hóa đơn cho lần thanh toán đó bao gồm các thông tin: họ tên và địa chỉ khách hàng, số phòng, ngày đến, ngày đi, giá phòng, các dịch vụ đi kèm (mỗi dịch vụ bao gồm tên dịch vụ, đơn vị tính, đơn giá, tổng tiền), số tiền thanh toán.
-	Khách hàng có thể hủy đặt phòng (miên phí) nếu hủy trước ngày đến. Nếu khách hàng hủy sau ngày đặt thì khách hàng bị lưu vào danh sách đen và có thể bị từ chối đặt phòng trong các lần tiếp theo.
