_Bài viết được viết bằng Obsidian!!!_

Obsidian là ứng dụng ghi chú và quản lí kiến thức. Obsidian được miêu tả như là một công cụ giúp chúng ta xây dựng "Second Brain", một bộ não thứ hai. 

### Hỗ trợ các nền tảng (Windows, Mac, Linux, iOS, Android) đều có, và giá thì hoàn toàn miễn phí
Obsidian có các ứng dụng dành riêng cho Mac, Linux và Windows. Nó cũng có một ứng dụng dành cho iOS và Android, bạn có thể đồng bộ hóa với máy tính của mình (Chỉ đồng bộ là phải trả phí :D, đồng bộ ở đây giúp chuyển dữ liệu viết của bạn qua các thiết bị, à mà giá cả của Obsidian Sync cũng rất phải chăng, khoản gần 100k ($4/months) một tháng thôi).
Và hãy nhớ là Obsidian HOÀN TOÀN MIỄN PHÍ! Bạn không cần phải chi một đồng nào cả để bắt đầu nâng cấp khả năng ghi chú của mình.
### Một số kiến thức cơ bản về Building a second brain (Xây dựng bộ não thứ 2) hay PKM (Personal Knowledge Management - Quản lý kiến thức cá nhân)
- **Building a second brain**: là một phương pháp lưu trữ và nhắc lại có hệ thống cho chúng ta về những ý tưởng, cảm hứng, thấu hiển và liên kết mà chúng ta có được thông qua kinh nghiệm sống. Nó cho phép chúng ta mở rộng trí nhớ và trí tuệ thông qua mạng lưới liên kết và các công cụ hiện đại.
- Personal Knowledge Management:

Về các lý do sử dụng Obsidian, thì có cả tá các bài viết trên mạng nói với bạn rằng tại sao bạn nên sử dụng Obsidian, mình sẽ tóm gọn nó lại trong một dòng.
- Nó có thể liên kết các ghi chú bạn ghi (bằng Markdown - Ở đây là một cách đánh dấu văn bản đơn giản, học Markdown để viết trên Obsidian rất nhanh) như một mạng lưới Nơ-ron (Graph view), và lưu toàn bộ trên máy tính/điện thoại của bạn chứ không phải cloud, nên bạn không cần kết nối mạng liên tục để sử dụng như Notion hay Google Notes. Đơn giản, nhanh, và cực hiệu quả.

### Cách cài đặt
- Với máy tính, bạn lên trang web của Obsidian [tại đây](https://obsidian.md/download), sẽ có mục `More Platforms`, bạn chọn tương ứng với nền tảng (hệ điều hành mình dùng).
	- [Windows](https://github.com/obsidianmd/obsidian-releases/releases/download/v1.5.3/Obsidian.1.5.3.exe) (Bạn có thể bấm vào chữ Windows để nó tự động tải về luôn, phiên bản mình để là 1.5.3, bản mới nhất tính đến đầu năm 2024): Bạn chỉ cần chọn `Standard (64-bit)`, vì đa phần mọi người đều sử dụng Windows trên máy tính bàn hoặc Laptop, nên sẽ chọn bản này, nếu bạn không cài được do lỗi, thì bạn có thể thử bản `Legacy (32-bit)`, cho các loại máy tính cổ :v. Bạn chỉ cần bấm chạy tệp cài đặt trong trình quản lý tệp rồi bấm Next mấy lần là xong.
	- [Mac](https://github.com/obsidianmd/obsidian-releases/releases/download/v1.5.3/Obsidian-1.5.3-universal.dmg): Bạn chọn luôn ở phần Universal, vì nó hỗ trợ cả chip Apple Silicon và Intel. Cá nhân mình chưa dùng Mac bao giờ nên mình cũng không biết cài nó như thế nào. Bạn có thể tham khảo trên Youtube hoặc hướng dẫn trên mạng nha.
	- Linux: Nếu bạn sử dụng Linux như mình, thì bạn nên cài đặt qua cửa hàng ứng dụng (Flatpak). Nếu bạn là một người không ngại dùng Terminal (Dòng lệnh ma thuật) thì bạn có thể cài bằng cách này, bạn chỉ cần sao chép lệnh ném vào đó rồi nhập mật khẩu bạn tạo lúc cài Linux Distro vào máy là xong. Dùng Linux để làm việc thì tuyệt vời ông mặt trời luôn! 
		- `Flatpak`: Nếu bạn chưa cài Flatpak thì nhập lệnh `sudo apt-get install flatpak` (Cho Ubuntu/Debian), nếu là các dòng khác như Arch hay Fedora thì thay bằng Package Manager tương tự `pacman` cho Arch hoặc `yum` cho Fedora. Nhập lệnh tải này `flatpak install flathub md.obsidian.Obsidian`, là xong, nó sẽ tự cài phiên bản mới nhất cho bạn.
- Với điện thoại thì
	- Android: Cài qua cửa hàng ứng dụng hoặc bấm vào [đường link này luôn](https://play.google.com/store/apps/details?id=md.obsidian)
	- iOS: Cài qua cửa hàng ứng dụng hoặc bấm vào [đường link này luôn](https://apps.apple.com/us/app/obsidian-connected-notes/id1557175442)
- Với hệ điều hành khác như là FreeBSD hay Windows trên Nokia thì mình bó tay =)) vì nó không có hỗ trợ. Nhưng đa phần mọi người đều dùng các nền tảng trên nên không có gì phải lo lắng cả xD!

### Một số tính năng hay ho mà Obsidian có:
- **Tree-style organization**: Giao diện phía trên bao gồm: từ trái sang phải là cây thư mục các file lưu trữ > khung soạn thảo markdown > khung preview > phía dưới là các tài liệu có link đến tài liệu này. Ngoài ra ta còn có thể sắp xếp theo tag nữa.
- 

### Kết thúc
Vậy là xong, về cơ bản mình nghĩ là không cần giới thiệu gì quá nhiều, như là tại sao nó tốt hay các thứ tương tự, vì nó có nhan nhản trên mạng, và có một vấn đề là đa phần các bài viết đó đều hướng dẫn cài đặt khá sơ sài hoặc cho có. Nên mình sẽ viết vào đây luôn.
		