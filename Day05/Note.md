## 1 . Transform (biến đổi hình dạng thứ tự hiển thị của phần tử)

- Thay đổi hình dạng, vị trí góc độ của phần tử. Nó không tạo hiệu ứng mượt chỉ nhảy sang trạng thái mới.

# Thuộc tính :

- 1. translate(x,y) : Dịch chuyển theo phần tử theo trục X và Y.
- 2. translateX(n) : Dịch chuyển theo trục X.
- 3. translateY(n) : Dịch chuyển theo trục X, Y.
- 4. scale(x,y) : Phóng to thu nhỏ x : nganng y : dọc
- 5. scaleX(n) : Phóng to thu nhỏ x
- 6. scaleY(n) : Phóng to thu nhỏ y dọc
- 7. rotate(angle) : xoay theo độ (deg)
- 8. skew(x-angle, y-angle) : nghiêng theo x,y
- 9. skewX(angle) : Nghiêng theo góc X
- 10. skewY(angle) : Nghiêng theo góc Y
- 11. rotateX(angle) : Xoay quanh trục X
- 12. rotateY(angle) : Xoay quanh trục Y
- 13. rotateZ(angle) : Xoay quanh trục Z giống rotate thường
- 14. translateZ(n) : Dịch chuyển theo chiều sâu
- 15. scaleZ(n) : Phóng to thu nhỏ chiều sâu
- 16. perspective(n) : tạo chiều sâu (giả 3D)

### Lưu ý có thể gộp nhiều thuộc tính vào cùng 1 lúc.

#### Lưu ý không lên khai báo 2 thẻ tranform thì sẽ bị ghi đè

- Ex : .box {
  transform: translate(50px, 50px) rotate(45deg) scale(1.5);
  }

##### ::before : trước và :: after : sau là gì ?

- Css pseudo-elements (Phần tử giả)
- Nó không có sẵn trong HTML nhưng Css có thể chèn thêm nội dung (content) vào trước (::before) hoặc sau (::after) phần tử.
