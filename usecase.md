**ONLINE WATCHING MOVIE USECASE**


![alt text](https://github.com/TienAnh0802/WebXemPhim/blob/master/use-case%20draft/UseCaseTongQUat.png)

***USECASE tổng quát***

Đặc tả

Các tác nhân:

-Guest : Người vào trang web lần đầu hoặc chưa đăng nhập ( Khách)

-User : Người sử dụng ( Đã đăng nhập)

Các chức năng chính:

***Login: Đăng nhập**

Mô tả:

+Tiền điều kiện : Người dùng đã đăng kí tài khoản.Nhập tài khoản và mật khẩu.

+Luồng xử lý:

1. Hệ thống kiểm tra mật khẩu

2. Sai mật khẩu, hoặc tài khoản hiện thông báo.

3. Đúng mật khẩu thì trả về trang Home

***Sign up : Đăng kí**

Mô tả:

+Người dùng chưa có tài khoản, cần đăng kí để truy cập trang web.

+Luồng xử lý:

1. Ngay khi truy cập vào trang web, form đăng kí hiện ra.

2. Người dùng điền thông tin vào form.

3. Hệ thống kiểm tra thông tin tài khoản

4. Tiến hành đăng nhập

+Ngoại lệ: Người dùng đã có tài khoản, chọn chức năng đăng nhập

***Preview: Xem trước**

Mô tả:

+Tiền điều kiện: Người dùng đăng nhập vào hệ thống.

+Luồng xử lý:

1. Trang web sẽ chạy trước phim nhưng không phát âm thanh

2. Người dùng có thể chọn Play để xem và ấn vào biểu tượng Volume để bật tiếng

***Search: Tìm kiếm**

Mô tả:

+Tiền điều kiện: Người dùng đăng nhập vào hệ thống.

+Luồng xử lý:

1. Người dùng chọn biểu tượng "Kính lúp" để thực hiện chức năng tìm kiếm.

2. Người dùng gõ nội dung cần tìm kiếm

3. Hệ thống trả về kết quả

+Ngoại lệ:Không có nội dung trùng khớp thì báo "Không có kết quả".

***Browse: Duyệt**

*![alt text](https://github.com/TienAnh0802/WebXemPhim/blob/master/use-case%20draft/UseCasebrowse.png)

***Usecase Browse***

             +Tiền điều kiện: Người dùng đã đăng nhập vào hệ thống

+Luồng xử lý

1. Người dùng đăng nhập vào hệ thống, chức năng duyệt sẽ mở trang mặc định Home

2. Người dùng chọn nội dung duyệt trên thanh điều hướng : TVShow; Movies

3. Trang web trả về nội dung , các thể loại .

![alt text](https://github.com/TienAnh0802/WebXemPhim/blob/master/use-case%20draft/playusecase.png)

***USCASE chức năng Play***

***Play: Phát**

Mô tả:

+Người dùng muốn xem nội dung.

+Tiền điều kiện: Người dùng đã đăng nhập.

+Luồng xử lý:

1. Người dùng chọn nội dung cần xem

2. Trang web sẽ thực hiện chức năng "Preview"

3. Ấn vào biểu tượng "Play" để xem.

4. Thanh Player hiện ra, người dùng có thể tua, dừng , điều chỉnh âm lượng

+Ngoại lệ:

Người dùng xem hết nội dung:

1. Trang web trả về tùy chọn

2. Người dùng chọn biểu tượng "Replay" để xem lại

3. Ấn "Play" để mở nội dung tiếp theo.

![alt text](https://github.com/TienAnh0802/WebXemPhim/blob/master/use-case%20draft/UseCase%20Acsetting.png)

***USECASE quản lý tài khoản***

**Account Setting: Quản Lý Tài khoản**

Mô tả:

+Người dùng cần thay đổi thông tin tài khoản.

+Luồng xử lý:

1. User bấm vào biểu tượng "Cá nhân" trên thanh điều hướng

2. User chọn "User Details"

3. Trang web hiển thị thông tin về tên và email người dùng, cũng như các chỗ điền để sửa các thông tin này và password

4. User chọn chỗ điền thông tin mà mình muốn sửa

5. Hệ thống cập nhật thông tin.

*Log Out : Đăng xuất.
