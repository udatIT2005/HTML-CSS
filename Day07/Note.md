# CSS Grid là gì ?

- Css grid layout là hệ thống 2 chiều ( hàng và cột)
- Chia layout thành grid container (cha) và grid items (con)

## Cấu trúc

- 2 cấp : cha và con

## thuộc tính cho container(cha) : display : grid

- justify-content, align-content → dịch chuyển toàn bộ lưới trong container (khi container lớn hơn grid).

### Định nghĩa cột hàng

- grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));

* repeat(n, value) : lập lại (n : là cột, value : mỗi cột bao nhiêu px) fr : là co giãn tối đa chia theo tỉ lệ
* minmax(min, max) : giới hạn kích thước
* Auto-fill: giữ nguyên số cột cần thiết, phần trống còn lại vẫn để trống.
* Auto-fit: co giãn các cột hiện có để lấp đầy khoảng trống.

#### Khoảng cách giữa các ô

- gap : khoảng cách giữa các row column

##### Thuộc tính cho item (con)

- grid-column: 1 / 3; /_ span từ cột 1 → 2 _/
  : grid-column-start + grid-column-end
- grid-row: 2 / 4; /_ span từ hàng 2 → 3 _/
- grid-column: span 2; /_ chiếm 2 cột _/
- grid-row: span 3; /_ chiếm 3 hàng _/
- justify-self, align-self, place-self → tác động từng item trong ô.

- justify-items, align-items, place-items → tác động tất cả item trong grid (bên trong từng ô).

##### Chọn được phần tử đầu tiên của Css là nth-child hoặc first-child và trong thẻ cha có nhiều thẻ con thì dùng > \* để css chung

###### Grid-template-area vẽ layout bằng grid cực dễ và quản lý layout phức tạp

grid-template-areas:
"header header"
"sidebar main"
"footer footer";

###### grid-area: grid-row-start / grid-column-start / grid-row-end / grid-column-end;

###### grid-template: <grid-template-rows> / <grid-template-columns>;

- fraction : phần chia
- repeat : lập lại
- grid : lưới
- fx : là tỉ lệ tương đối
- px : tỉ lệ cứng
- Cách xem tài liệu là di chuột hover vào phần tử và tra xem trên MDN reference
