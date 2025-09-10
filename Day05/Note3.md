# 1. Animation và @keyframes

- Animation là chuyển động mượt mà không cần Javascript
- @keyframe : định nhĩa các bước thay đổi trạng thái (frame) cho animation

## 2. Cú pháp cơ bản của @keyframes

p{
animation : myAnimation
}
@keyframes myAnimation{
0%{}
50%{}
100%{}
}

### 3 Thuộc tính animation

1. animation-name : tên animation
2. animation-duration : khoảng thời gian chạy
3. animation -timing-function : đường cong tốc độ

- linear : đều
- ease : chậm nhanh chậm
- ease-in : chậm dần đều lúc bắt đầu
- ease-out : chậm dầu đều lúc kết thúc
- ease-in-out : chậm dần đầu và cuối nhanh ở giữa

4. animation-delay : trễ trước khi chạy
5. animation-iteration-count : số lần lặp (1,2,infinite : vô tận)
6. animation-direction : hướng chạy (mặc định : normal)
   - reverse : đảo ngược
   - alternate : chạy hết từ 0-100 rồi quay lại 100-0
   - alternate-reverse : chạy từ 100-0 rồi quay lại 0-100
7. animation-fill-mode : trạng thái sau khi kết thúc

- none : không giữ lại
- forwards : giữ nguyên trạng thái ở frame cuối 100 %
- backwards : áp dụng trạng thái ban đầu 0%
- both : kết hợp forwards + backwards

8. animation-paly-state : điều khiển vào animation

- running : đang chạy
- pasused : tạm dừng

#### Cú pháp shorthand (viết gọn)

animation: name duration timing-function delay iteration-count direction fill-mode play-state;
