---
title: "Làm Custom Brush trong Zbrush"
description: Ghi chú đề phòng khi quên.
date: 2025-04-14T12:05:20Z
image: post/make-custom-brush-in-zbrush/cover-lam-custom-brush-trong-zbrush.webp
categories: 3D
tags: [zbrush, Notes]
math: 
license: 
hidden: false
comments: true
---
Ghi chú để phòng khi quên cách làm brush.
## IMM Brush
Là những brush dùng để insert một mesh hay vật thể (ví dụ: đinh, óc, tóc,...). Thông thường với những vật thể như đinh óc thì không cần curve mode để vẽ ra như tóc.
### Đối với mấy thứ không cần curve mode
Tạo được xong subtool ưng ý > Đảm bảo có ít nhất từ 2 subtool trở lên > Nhìn thanh menu top > bấm 'Brush' > menu hiện ra > Bấm 'Create' > Bấm Create InsertMultiMesh'.
Xong giờ chỉ việc lưu.
### Với những thứ cần curve mode
Sao khi tạo xong đảm bảo hướng của vật thể như hình.
![Làm Custom Brush trong Zbrush](post/make-custom-brush-in-zbrush/lam-custom-brush-trong-zbrush-1.webp)
Tạo được xong subtool ưng ý > Đảm bảo có ít nhất từ 2 subtool trở lên > Nhìn thanh menu top > bấm 'Brush' > menu hiện ra > Bấm 'Create' > Bấm Create InsertMultiMesh'.
> Tiến hành dùng thử brush. Hãy tạo một Polymesh3D của một đối tượng bất kỳ rồi vẽ lên đó.
> Đảm bảo 'Z Intensity' của Brush vừa tạo là 100 và 'Focal Shift' là 0 (Ấn 'Space' > Kéo 'Z Intensity' lên 100 và kéo 'Focal Shift' về 0) để tránh tình trạng vẽ ra vật thể bị ép dẹp lép.
Nhìn thanh menu trên top > Bấm 'Stroke' > Bấm 'Curve' > Bấm 'Curve Mode' > Hạ 'Curve Step' ~ 0.8, vì đối với các vật thể như dây xích nếu không hạ thì khi vẽ ra dây xích các mắc xích sẽ không luồn vào nhau. Đối với tóc thì không cần chỉnh 'Curve Step'.
> Khi đã ứng ý thì tiếng hành lưu. Khi lưu tất cả cài đặt về 'Curve' cũng sẽ được lưu lại. Lúc xài nếu cần chỉnh lại 'Curve Step' có thể chỉnh thoải mái.
## Cách lưu để xài
Nhìn thanh menu top > bấm 'Brush' > menu hiện ra > Bấm 'Save as' > Cửa sổ win dow hiện ra > Nhập tên cần lưu 'IMM_something.ZBP' > Chọn nơi lưu '(C:\Program Files\Maxon ZBrush 2023\ZData\BrushPresets)' > Bấm 'Save'.
> Nếu muốn mỗi lần khởi động Zbrush mà brush tự load thì Save ở (C:\Program Files\Maxon ZBrush 2023\ZStartup\BrushPresets)
## Nếu mở ZBrush lến mà không thấy brush mình lưu?
Bấm 'b' > Bấm 'Load Brush' đi đến chỗ lưu file '.ZBP' > Chọn file cần mở > Xong.
