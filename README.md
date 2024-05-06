# Thực hiện các thay đổi với ứng dụng 
* "title" Thay đổi giả trị thuộc tính trong lớp tiêu đề.

# Biên tập viên anh hùng
* Sử dụng "ng generate" để tạo một thành phần mới có tên heroes: bao gồm 4 tệp tin HTML, Spec.ts, TypeScript và CSS.
* "@Component" là một hàm trang trí chỉ định siêu dữ liệu Angular cho thành phần.
* "ng generate" đã tạo ba thuộc tính siêu dữ liệu:
    + selector : Bộ chọn phần tử CSS của thành phần.
    + templateUrl : Vị trí của tệp mẫu của thành phần.
    + styleUrls : Vị trí của các kiểu CSS riêng tư của thành phần.
* Thêm một <app-heroes> phần tử vào AppComponent tệp mẫu, ngay bên dưới tiêu đề.g 
* "ng generate interface hero" : Tạo một Hero giao diện trong tập tin riêng của nó trong src/app thư mục . Cung cấp cho nó id và name tài sản.
* <h2>{{hero.name}} Details</h2>
<div><span>id: </span>{{hero.id}}</div>
<div><span>name: </span>{{hero.name}}</div>
-> Cập nhật ràng buộc.

* "uppercase": trong liên kết nội suy sau |ký tự ống dẫn, kích hoạt tệp UppercasePipe.
* "input": Chỉnh sửa name.  
* "*ngFor<li>" : Nó lặp lại phần tử máy chủ cho từng phần tử trong danh sách.
* "*ngIf<div>": Lệnh này yêu cầu Angular chỉ hiển thị phần khi được xác định sau khi nó được chọn bằng cách nhấp vào anh hùng.