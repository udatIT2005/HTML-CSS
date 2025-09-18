# Responsive web design là gì ?

- Là phương pháp thiết kế và phát triển web có thể hiển thị đẹp mắt dễ đọc trên mọi thiết bị, từ máy tính để bàn, laptop , điện thoại,..
    <meta charset="UTF-8" />
    - Mã hóa ký tự 
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    - Render dúng tỷ lệ theo màn hình thiết bị 
    <title>Document</title>
    - Tên website

## Render là quá trình vẽ giao diện ra màn hình từ code

## Đơn vị trong Css cho responve

- % là tính theo phần trăm cha
- vw/vh theo chiều rộng chiều cao của màn hình
- em, rem fonrt chữ padding margin linh hoạt
- minmax(), fr trong css grid, tự động co giãn

### Media Queries dùng để thay đổi Css dựa theo kích thước màn hình

- exam: @media (max-width: 990){
  body{
  background-color : red
  }
  }
  @media (min-width: 491px) and (max-width: 786px){
  body{
  background-color: blue;
  }
  }

#### Layout responive

1. Flex box
2. Css Grid

##### Ảnh và Video

ex : img{
max-width : 100%
height : auto
}

###### Mobile first và Destop first

###### Framework hỗ trợ responsive

1. Bootstrap
2. TailwinCss
