# UIT SMART CHECKIN 

*UIT SMART CHECKIN* là phần mềm được phát triển nhằm phục vụ cho việc điểm danh sinh viên tại trường Đại học Công Nghệ Thông Tin thông qua công nghệ nhận diện khuôn mặt (Face Recognition). Với ứng dụng này sinh viên khi đến lớp học chỉ cần đứng trước một tablet hoặc một smartphone để xác nhận cho việc điểm danh thay vì cách gọi tên giơ tay truyền thống.   

Phần mềm thích hợp chạy trên các thiết bị Android verison `8.1` trở xuống (tối thiểu `4.0.4`)

___

*Sau đây là một số hướng dẫn sử dụng và giải thích các màn hình:*

## Màn hình bắt đầu

<img src="https://raw.githubusercontent.com/tiendv/mmlabdemo/master/pictures/samsung_welcome.jpg" weight="540" height="1110">  

>Bấm vào `ĐĂNG NHẬP` để vào màn hình đăng nhập

>Bấm vào `HƯỚNG DẪN SỬ DỤNG` để tới trang web hướng dẫn sử dụng (trang này)

## Màn hình đăng nhập hệ thống đối với các Giảng viên: 
>Tài khoản dành cho giảng viên sẽ được cấp riêng cho từng giảng viên sử dụng hệ thống (liên hệ nhà phát triển)

<img src="https://raw.githubusercontent.com/tiendv/mmlabdemo/master/pictures/samsung_login.jpg"  weight="540" height="1110" >   

>Sử dụng tài khoản giảng viên để đăng nhập, lưu ý có phân biệt chữ hoa chữ thường.

>Bấm `ĐĂNG nhập` để đăng nhập vào hệ thống

## Màn hình chọn lớp điểm danh 
>Chọn lớp để điểm danh lên hệ thống

### Chọn lớp có sẵn
>Nếu giảng viên muốn điểm danh lớp đã có trên hệ thông từ trước, vui lòng chọn từ danh sách mã lớp

<img src="https://raw.githubusercontent.com/tiendv/mmlabdemo/master/pictures/samsung_selectClass.jpg"  weight="540" height="1110">   

>Chọn lớp muốn điểm danh và bấm `XÁC NHẬN`, lớp học được chọn sẽ được áp dụng vào hệ thống điểm danh

### Thêm lớp mới
>Nếu lớp Giảng Viên chưa có thì thêm mã lớp mới cần điểm danh, nhấn `THÊM LỚP`

<img src="https://raw.githubusercontent.com/tiendv/mmlabdemo/master/pictures/samsung_addClass.jpg"  weight="540" height="1110">  

>Nhập mã lớp học và bấm `Thêm` để thêm lớp vào hệ thống, lớp học được thêm mới sẽ được áp dụng vào hệ thống điểm danh

## Màn hình chọn chức năng
>Chọn chức năng điểm danh sinh viên hoặc đăng kí sinh viên mới

<img src="https://raw.githubusercontent.com/tiendv/mmlabdemo/master/pictures/samsung_start.jpg"  weight="540" height="1110">  

>Bấm `ĐIỂM DANH` để vào chức năng điểm danh sinh viên

>Bấm `ĐĂNG KÍ` để đăng kí sinh viên mới

### Màn hình điểm danh   
>Màn hình chính để nhận diện khuôn mặt sinh viên

<img src="https://raw.githubusercontent.com/tiendv/mmlabdemo/master/pictures/samsung_recognitionUI.jpg"  weight="540" height="1110">   

>Sinh viên làm theo hướng dẫn để lấy khuôn mặt gửi lên hệ thống xử lý

<img src="https://raw.githubusercontent.com/tiendv/mmlabdemo/master/pictures/samsung_process.jpg"> 

>Chờ đợi để hệ thông xử lý hình ảnh của sinh viên, tốc độ phụ thuộc và đường truyền mạng của người dùng  


#### Màn hình xác thực thông tin
>Sau khi gửi dữ liệu lên hệ thống máy chủ, sinh viên cần xác thực thông tin

<img src="https://raw.githubusercontent.com/tiendv/mmlabdemo/master/pictures/samsung_recognition.jpg" weight="540" height="1110">   
 
>Nếu thông tin chính xác, nhấn `ĐIỂM DANH` để tiến hành điểm danh

>Nếu thông tin không đúng, nhấn `SAI THÔNG TIN` để từ chối thông tin

>Theo dõi các thông báo để chắc chắn dữ liệu đã được gửi đi và xử lý

### Màn hình đăng kí
>Màn hình đăng kí dành cho sinh viên chưa có trong hệ thống hoặc muốn cập nhật thông tin   

<img src="https://raw.githubusercontent.com/tiendv/mmlabdemo/master/pictures/samsung_registerUI.jpg"  weight="540" height="1110">  

>Sinh viên làm theo hướng dẫn hiển thị trên màn hình để lấy dữ liệu khuôn mặt

>Nếu trong quá trình lấy dữ liệu, chất lượng ảng kém, chạm vào hình muốn lấy lại và thử lại

#### Màn hình nhập thông tin cá nhân
>Sau khi lấy đủ dữ liệu, sinh viên cần nhập thông tin các nhân để đăng kí vào hệ thống

<img src="https://raw.githubusercontent.com/tiendv/mmlabdemo/master/pictures/samsung_register.jpg"  weight="540" height="1110">   

>Nhập MSSV của sinh viên

>Nhấn `ĐĂNG KÍ` để tiến hành đăng kì

>Nhấn `THOÁT` để thoát ra màn hình chọn chức năng

>Theo dõi các thông báo để chắc chắn dữ liệu đã được gửi đi và xử lý

## Một số lỗi gặp phải khi sử dụng
>Các lỗi đã được thông báo ra màn hình, ngoài ra còn một số vấn đề cần lưu ý

>Tải app cần dựa vào phiên bản Android trong máy để tải bản phù hợp

>Updating
___

Mọi thắc mắc, góp ý vui lòng email: mmlab@uit.edu.vn  

## Nhóm thực hiện Project:  
* [Thanh Duc Ngo](https://www.facebook.com/ngodthanh)  - Project Manager
* [Duy Dinh Le](https://www.facebook.com/profile.php?id=100014113847694)  - Project Manager
* [Tiến Đỗ](https://www.facebook.com/dotien)  - Team Leader
* [Thừa Nguyễn](https://www.facebook.com/Unknown.name.789)  - Developer - Team Server
* [Duong Nguyen Xuan](https://www.facebook.com/duonghoangvn)  - Developer - Team Mobile Android
* [Huy Nguyễn](https://www.facebook.com/rknguyen)  -Developer - Team Mobile IOS

Cảm ơn bạn [Đào Thị Thu Nga](https://www.facebook.com/vonguocmo03092000) xinh đẹp đã đồng ý làm mẫu ảnh.

