---
title: "Cách làm dây ốp trong ZBrush"
description: 
date: 2025-04-15T14:49:51Z
image: post/make-straps-lines-zbrush/cover-lam-day-op-trong-zbrush.webp
categories: 3D
tags: [ZBrush, Notes]
math: 
license: 
hidden: false
comments: true
---
Ghi chú để phòng khi quên cách làm.
Khi làm quần áo nhiều khi sẽ cần các bộ phận lồi ra. Ví dụ như các lằn vải,... Để làm chúng thì có nhiều cách.

## Sử dụng Mask rồi Extract

Dùng cọ Mask vùng cần thiết (có thể mask bằng Polygroup/Color cho tiết kiệm thời gian) > Bấm 'Tool' trong menu top > Bấm  'SubTool' > Bấm Extract > Điều chỉnh để có được mức mong muốn > Bấm 'Extract' > Phần được Mask sẽ được tạo một mesh lồi ra > Nếu ứng ý bấm 'Accept' trong menu 'Extract'.

### Ưu & nhược

| Ưu    | Nhược |
| :--------: | :-------: |
| Đơn giản  | Phần Extract ra khá xấu cần điều chỉnh lại    |
| Kiểm soát được độ dày của mesh được extract | Dễ xuất hiện Artifact do mask, và lưới siêu dày đặc khó đảm bảo kết cấu |

## Sử dụng MaskLasso

Lưới phải đẹp khi xài cách này và yêu cầu vật thể hơi hard surface một tý và phải có mật độ lưới dày, cộng không bị biến dạng quá.
Bấm 'B' > Bấm 'MaskLasso' > Bật lưới subtool = bấm 'Shift + F' > Zoom lên nếu cần > Giữ 'Ctrl + Shift' click một 'edge' > làm đúng thì nguyên 1 đường kể từ  edge đó sẽ bị ẩn > đảo ngược ẩn = 'Ctrl + Shift + quét một vùng bên ngoài' > 'Mask' line hiện lên > Bấm 'Ctrl + Shift' bên ngoài để show phần bị ẩn > từ menu top kiếm thanh trược 'Inflate' kéo tăng/để làm lồi hoặc giảm/để tạo lằng kẻ > ưng ý thì > đảo ngược Mask = 'Ctrl + Bấm ngoài nền' > đổi Brush 'Pinch' đồ theo đường để làm khít > có thể chuyển tiếp qua brush 'Inflate' để đồ tiếp cho nó hơi có tính vải.

### Ưu & nhược

| Ưu    | Nhược |
| :--------: | :-------: |
| Thích hợp với vật thể có lưới quá dày + có hình dạng hơi hard surface  | muốn đẹp phải đồ cọ 'Pinch' với 'Inflate' nhiều    |

## Sử dụng brush Topology

Bấm 'B' > Bấm 'T' > Chọn brush có tên 'Topo...' > Vẽ theo kiểu lưới geometry trong zmodeler: các ô vuông > Vd: Để vẽ một cộng dây strap > đây là hình chữ nhật > Vẽ hai đường thẳng song song trên bề mặt của subtool (vd: quần áo) > vẽ tiếp các gạch ngang để chia thành các ô như lưới geometry > Khi đã ưng ý click ra ngoài lên subtool đang vẽ line > Nếu ưng ý với kết quả bấm 'Split Unmasked...'
> Lưu ý:
>
> 1. Đảm bảo vật thể được vẽ strap lên không có subdivision > có thể tạm dupliacte vật thể có nhiều Subdivision rồi del lower/higher subdivision để dùng tạm.
> 2. Cỡ brush càng nhỏ thì càng tạo được nhiều ô nên strap tạo ra sẽ chi tiết hơn.

### Ưu & nhược

| Ưu    | Nhược |
| :--------: | :-------: |
| Phần extact ra có lưới thấp dể kiểm soát hơn nên thành phẩm đẹp hơn  | Phải chỉnh lưới hơi nhiều    |

## Kẻ thẳng lên để tạo lằng

### Dùng cọ IMM

Thường phải đi tải trên mạng về xài. Nhưng kết quả lại đẹp, thích hợp để đặt tả đường chỉ, khâu,...

### Dùng cọ có sẵn

Thường là 'DamStan...' và 'Standard'. Cần kéo thanh 'LayzyRadius' ~ 20, kéo thanh RollDist một xíu lên, tăng/giảm size brush và ZIntensity = giữ 'Space' để hiện menu điều chỉnh. Rồi vẽ lên vật thể.

### Ưu & nhược

| Ưu    | Nhược |
| :--------: | :-------: |
| Ít điều chỉnh nhiều bước  | Nếu chỉ cần kể một line, dây ốp thì ok nhưng nếu phải tạo nhiều line/dây ốp cùng lúc (cùng kích cỡ) thì ko nên xài cách này|
