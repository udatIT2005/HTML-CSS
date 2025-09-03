Cấu trúc : ! là HTML phiên bản version : 5
Các thẻ Display : Inline , Block, Inline-block

- Thẻ block :

* là sẽ luôn ở trên một dòng mới và chiếm toàn bộ chiều rộng có sẵn của phần tử cha , đẩy các phần tử khác xuống dòng dưới.
* Có thể chỉnh width và height margin padding .
* Có thể chứa các thẻ inline và các thẻ block .

For example : div , p , h1-6 ,form , ...

- Thẻ inline :

* Không bắt đầu trên dòng mới các thể inline chỉ chiếm đủ không gian và không đẩy các phần tử khách xuống dòng . Đặc biệt là nằm ngay trên cùng một dòng với phần tử khác.
* Các thẻ margin và padding có tác dụng với margin, padding theo chiều ngang nhưng không ảnh hưởng tới vị trí các phần tử xung quanh chỉ thay đổi chính bản thân.
* Không thể chứa các thẻ block : có thể chứa thẻ inline khác.
* Nội dung thẻ bị đối xử như là text nên có khoảng trắng nếu xuống dòng ở giữa các thẻ. Cách xử lý : font-size : 0; display : flex và flex-wrap : wrap nhưng thường thì là nowrap .

For example : span ,i , strong , a , img , input ...

- Thẻ inline - block :

* Là sự kết hợp của inline và block : có cả 2 đặc điểm của 2 thẻ trên .
* Không bắt đầu trên dòng mới : nằm trên cùng 1 dòng giống inline .
* Có thể chỉnh sửa kích thước : như thẻ Block .

For example : display : inline-block;
