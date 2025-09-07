## 1. Flex box là gì ?

- là công cụ Css để xắp sếp bố cục theo 1 chiều ngang hoặc dọc
- Nó giúp căn chỉnh co giãn phần tử item trong một container linh hoạt
- Dùng để thay thế các cách cũ như float , inline-block
- Nên dùng khi : Menu navbar , sidebar, ...

- Trục chính là ox và trục phụ là oy

## 2. Cấu trúc Flexbox

- Có 2 cấp

## 3. Các thuộc tính quan trọng

- 1. display : flex
- 2.flex-direction (Xác định trục chính Ox ): _ row (ngang , mặc định)
  _ row-reverse (ngược ngang) \* column (dọc) và column-reverse (dọc ngược)
- 3.flex-wrap : xuống dòng khi thiếu chỗ
  - nowrap (mặc định, không xuống dòng)
  - wrap (xuống dòng)
  - wrap-reverse (xuống dòng nhưng ngược chiều)
- 4. justify-content : Căn chỉnh theo trục chính Ox
  - flex-start : dồn về đầu
  - flex-end : dồn về cuối
  - center : giữa
  - space-between : chia đều 2 đầu mép dính
  - space-around : chia đều mép có khoảng cách
  - space-evenly : chia đều tuyệt đối
- 5. align-items : Căn theo trục phụ
  - flex-start
  - flex-end
  - center
  - baseline (theo dòng chữ)
  - stretch (mặc định kéo giãn)
- 6. flex-flow : là thuộc tính rút gọn
  - flex-direction : Hướng trục
  - flex-wrap : Xuống dòng hay không
    Công thức : flex-flow : Hướng trục ngang or đứng + xuống dòng
    .container gọi là cái vòm chứa
- 7. align-self : căn riêng 1 item
  - flex-start : dồn lên
  - flex-end : dồn xuống
  - center : giữa
  - stretch : kéo giãn
- 8. order : thứ tự sắp xếp phần tử con
- 9. flex-grow : cho phép nở ra chiếm chỗ trống
- 10. flex-shrink : cho phép co lại khi thiếu chỗ
- 11. flex-basic : kích thước cơ bản
- 12. Gộp lại flex: 1 1 200px; /_ grow shrink basis _/
- 13. align-content : dùng khi có wrap và có nhiều hàng ;
  - flex-start: Các dòng được dồn về phía trên cùng của hộp chứa.
  - flex-end: Các dòng được dồn về phía dưới cùng của hộp chứa.
  - center: Các dòng được dồn về trung tâm của hộp chứa.
  - space-between: Các dòng được trình bày với khoảng cách bằng nhau giữa chúng.
  - space-around: Các dòng sẽ được trình bày với khoảng cách bằng nhau xung quanh chúng.
  - stretch: Các dòng sẽ được kéo dài để phù hợp với hộp chứa.
