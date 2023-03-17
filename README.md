# BOOSTRAP 5


## Flexbox
* tạo 1 vùng chứa hàng ngang
```html
<div class = "d-flex"></div>
```

## Container
####  .container : chiều rộng cố định
```html 
<div class = "container">
```
![alt](./images/Screenshot%20from%202023-03-17%2009-25-11.png)
    					
#### .contrainer-fulid: chiều rộng tự động bao chùm khung hình
```html
<div class = "container-fulid">
```

### Container Padding
* Theo mặc định, vùng chứa có phần đệm bên trái và bên phải, không có phần đệm trên cùng hoặc dưới cùng,pt- thêm vùng đệm trên,p- vùng đệm xung quanh
```html
<div class = "container pt-3">
```
### Container margin
* mở rộng vùng thẻ
```html
<div class = "container my-3">
```
### Container Border and Color
* thêm viền
```html
<div class = "container border">
```

* màu nền
```html
<div class = "container bg-primary">
```

* màu chữ
```html
<div class = "container text-color">
```

### Responsive Containers
* sử  dụng .container-sm|md|lg|xl
```html
<div class = "container-sm">
```

## Grid
### Equal Columns
* tạo ra số cột có chiều rộng bằng nhau bằng bn thẻ col 
```html 
<div class="row">
  <div class="col">.col</div>
  <div class="col">.col</div>
  <div class="col">.col</div>
</div>
```
### Unequal Responsive Columns
* độ rộng các cột khác nhau
```html
<div class="row">
  <div class="col-sm-3">.col</div>
  <div class="col-sm-6">.col</div>
  <div class="col-sm-3">.col</div>
</div>
```



