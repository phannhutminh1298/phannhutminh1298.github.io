---
title: "Merge 2 Subtool to 1"
description: 
date: 2025-05-13T06:51:01Z
image: post/merge-2-subtool-to-1/merge-2-subtool-to-1.webp
categories: 3D
tags: [zbrush, Notes]
math: 
license: 
hidden: false
comments: true
draft: false
---
Ghi chú để phòng khi quên cách làm.

## Dynamesh

Cách này phụ thuộc vào mật độ lưới rất nhiều, 2 subtool góc càng dày lưới thì càng tốt.

Subtool > xếp 2 subtool cần gộp liền kề nhau > chọn subtool bên trên > 'merge' >'merge down' > duplicate 1 lần để back up > bấm subtool mới vừa được gộp > Dynamesh (chỉnh resolution càng cao thì càng giữ được chi tiết) > Sau khi ưng ý unmask subtool (nếu có mask) > Hiện subtool back up (icon con mắt góc trên phải của subtool) > bấm subtool vừa Dynamesh > Project All > Smooth artifact/etc > Ưng ý thì tăng Subdiv lên > Project all tiếp > lặp lại... > Khi đã ưng thì ngừng.

> Dùng để gọp các khối lớn không cần góc cạnh nhọn

## Boolean

Như trên cũng cần lưới cao nhưng tuỳ trường hợp, cũng phải > ZRemesh > project all > smooth > lặp lại...

Chuẩn bị một Folder chứa 2 subtool > xuống subtool thứ 2 từ trên xuống > bấm icon 2 vòng tròn giao nhau góc trên bên tái subtool, đứng thứ 2 từ trái qua > Bấm Live Boolean > Lên subtool trên cũng bấm "live boolean" > bấm icon bánh răng chọn:

- "Boolean Folder" > Subtool mới được tạo ra từ 2 subtool cũ.
- "Boolean with DynamicSubDivision > Subtool mới được tạo ra từ 2 subtool cũ nhưng sẽ đi kèm với DynamicSubDivision > lưới dày hơn smooth hơn/bù lại nặng hơn là load lâu hơn.

**Lưu ý:** Boolean with DynamicSubDivision sẽ cho ra kết quả **REVIEW TRƯỚC CỦA LƯỚI DÀY** > Để có lưới dày thực vào Geometry > tắt Dynamic đi > Ctrl + D cho đến khi vừa ý.

> Dùng để gọp những thứ cần độ chính xác cao hơn.
