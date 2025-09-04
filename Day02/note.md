- Vị trí phần tử : Position là thuộc tính can thiệp vào việc di chuyển vị trí của phần tử những không gian 3D trên các trang web

1. Static : Tĩnh ( Mặc định)

- Tất cả các thẻ html đều có position : mặc định
- Không thể dùng top, left right, bottom.

2. Relative : Tương đối

- Phần tử vẫn chiếm không gian ban đầu nhưng có thể thay đổi được vị trí dựa vào thuộc tính top left right bottom.
- Nếu top và bottom cùng được thiết lập thì top sẽ được ưu tiên hơn
- Nếu right và left cùng được thiết lập thì left sẽ được ưu tiên hơn

3. Absolute : Tuyệt đối

- Vị trí dựa theo phần tử cha gần nhất có position : relative
- Nếu không có cha nó sẽ tính toàn bộ trang body
- Muốn luôn ở trong giữa phần tử thì dùng thuộc tính transform : translate(-50%, 50%); và top : 50% và left : 50%;

4. Fixed : Cố định

- Dính cố định vào toàn màn hình , không phụ thuộc vào cha
- Dùng làm header menu cố định

5. Sticky : Dính

- Kết hợp giữa relative và fixed
- Bình thường nó chạy như realative nhưng khi bạn cuộn trang đến 1 điểm thì nó lại dính lại như fixed

- overley : là một lớp layer đè lên nội dung khác thường dùng để : hiển thị thông tin khi hover vào ảnh hoặc tạo hiệu ứng mờ nền , ...
