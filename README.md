# extra_exercise

Thiết kế hệ thống sấy khô nông sản, khi nhiệt độ đo được ngoài môi trường nhỏ hơn ngưỡng cho trước thì bật động cơ DC, nếu nhiệt độ đạt đến ngưỡng (cho trước) thì dừng động cơ và hiển thị thông báo nông sản đã khô. đồng thời đèn LEd nhấp nháy xanh-đỏ chu kỳ 1s (timer)

Thiết kế một chiếc máy giặt với các chức năng. 
Hiển thị các phím chức năng trên LCD/GLCD
Bấm chế độ giặt, ban đầu rơle 1 bật trong 2s (để cung cấp nước), sau đó động cơ sẽ quay nhanh dần (sau mỗi dây, tốc độ động cơ tăng lên 20% - tương đối), sau 10s động cơ dừng quay, rơle 2 bật trong 2s (để xả nước), sau đó động cơ sẽ quay với tốc độ 100% trong vòng 3s để vắt. sau khi vắt xong đèn xanh-đỏ nhấp nháy với chu kỳ 1s.
Bấm chế độ vắt (thực hiện chương trình từ lúc xả xong)

Thiết kế thang máy cho nhà 8 tầng thực hiện các chức năng sau
Khi bấm cửa tầng nào thì động cơ servo sẽ xoay từ góc 0 - 90 độ (chú ý khi đang ở tầng bất kỳ không trùng với tầng tương ứng với phím bấm thì quay động cơ để về tầng tương ứng) nếu số tầng bấm nhỏ hơn số tầng đang phục vụ thì động cơ quay chiều kim đồng hồ, số đếm giảm. Nếu số tầng bấm lớn hơn số tầng đang phục vụ thì động cơ quay chiều ngược lại và số đếm tăng. Khi số đếm bằng số tầng được bấm, thì động cơ dừng lại
Sau khi động cơ servo quay sang góc 90 độ thì dừng lại trong vòng 2s rồi lại quay về góc 0 độ. nếu số tầng bấm cao hơn số tầng hiện tại thì động cơ quay ngược kim đồng hồ và số đếm tăng; nếu số tầng nhỏ hơn tầng hiện tại thì động cơ quay theo chiều kim đồng hồ và số đếm giảm. số đếm tăng hoặc giảm khi bằng số bấm thì động cơ dừng lại, servo quay về góc 90 độ trong 2s và lại quay về góc 0 độ. Quá trình này lặp đi lặp lại.

Thiết kế thiết bị cho cá ăn tự động với các chức năng sau
có chức năng thiết lập giờ, phút, chế độ trên LCD/glcd
Khi đến giờ cho cá ăn, thì động cơ sẽ quay trong vòng 1s và servo sẽ mở góc từ 0 đến 90.
Khi bấm công tắc 1, đèn xanh đỏ sẽ nhấp nháy theo chu kỳ 1s và động cơ servo và động cơ dc sẽ ngừng ngay lập tức.


Thiết kế bộ cửa mã khóa phím, mật khẩu đúng là 666, nhập 3 lần sai mật khẩu sẽ bật role 1 và đen xanh đỏ nhấp nháy theo chu kỳ 1s.
(tùy chọn: sau khi nhập đúng mật khẩu, cho phép người dùng đổi mật khẩu và lưu mật khẩu mới vào eeprom)
(giải thích thêm: nếu rút nguồn ra, cắm nguồn lại thì phải nhập mật khẩu mới đổi)


Viết chương trình điều khiển xe điện thực hiện các chức năng sau.
Khi bấm tổ hợp phím 334 trên bàn phím thì đèn xanh sáng, rơ le 1 bật
Dùng chiết áp xoay theo chiều kim đồng hồ, ở vị trí giữa -> động cơ dừng. Xoay về phía max động cơ sẽ tăng dần tốc độ, nếu xoay về phía min động cơ sẽ tăng dần tốc độ nhưng ở chiều ngược lại.
Nếu bấm BT1, động cơ sẽ quay ở 1 tốc độ cố định (không còn chịu ảnh hưởng của chiết áp). Nếu bấm BT1 một lần nữa, tốc độ của động cơ lại phụ thuộc vào chiết áp như lúc đầu.

Viết chương trình điều khiển bắn pháo hoa ngày tết. theo kịch bản.
Khi bấm BT1 thì số đếm từ 10 xuống 0, khi số đếm về 0 thì bật role 1.
