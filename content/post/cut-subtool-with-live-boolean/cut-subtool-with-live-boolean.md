---
title: "Cắt subtool bằng LiveBoolean"
description: 
date: 2025-06-03T12:24:02Z
image: post/cut-subtool-with-live-boolean/cover-cut-subtool-with-live-boolean.webp
categories: 3D
tags: [ZBrush, Notes]
math: 
license: 
hidden: false
comments: true
draft: false
---
## Tóm tắt

Để sử dụng LiveBoolean để cắt một subtool thì:

- Để subtool cần cắt (gọi là `Target`) nằm trên subtool dùng để cắt (gọi là `Cutter` ). Theo tứ tự từ trên xuống: `Target`, `Cutter`.
- Chỉ hiện 2 subtool này (icon con mắt bên phải hai subtool).
- Bấm icon ngoài cùng bên trái của subtool `Target` > Icon sẽ thêm chữ `Start`.
- Chuyển qua suntool `cutter`, bấm icon thứ 3 từ trái sang của subtool Cutter.
- Bật `LiveBoolean` (Menu top> Render > Render Booleans > bấm LiveBoolean).
- `Cutter` giờ sẽ tàn hình > di chuyển cutter sao cho vừa ý.
- Qua danh sách subtools, kéo xuống kiếm `Boolean`, bấm vào sẽ hiện ra `Make Boolean Mesh`, rồi bấm vào.
- Một Tool mới sẽ được tạo ra với tên có `UMesh...`
- Chỉ cần kéo xuống từ menu subtool > Bấm `Append` > Chọn tool có tên `Umesh...` > là xong, `Target` sau khi bị cắt đã được thêm vào lại.

## Youtube guide

{{< youtube "IbGBL1grZ7A" >}}
