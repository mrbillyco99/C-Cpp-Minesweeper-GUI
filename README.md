# C-Cpp-Minesweeper-GUI

Source Code GUI trò chơi Minesweeper (Dò mìn) bài tập nhóm cuối kì môn C/C++.

# Cách chơi

Khi di chuyển chuột vào các text boxes "cell grid X * X" hoặc "mines", các text sẽ chuyển màu và chúng ta có thể nhập giá trị cho số hàng, cột của bảng trò chơi và số mìn. Sau đó, khi click chuột trái vào "Start" cửa sổ settings sẽ đóng lại và cửa sổ trò chơi sẽ hiện ra.
![settings](https://github.com/mrbillyco99/C-Cpp-Minesweeper-GUI/blob/master/Images/MinesweeperSettings.png)
![gameplay](https://github.com/mrbillyco99/C-Cpp-Minesweeper-GUI/blob/master/Images/MinesweeperGamePlay.png)
Click chuột trái vào ô bất kì trong bảng trò chơi sẽ mở ra giá trị của ô đó, click chuột phải vào ô sẽ đặt cờ lên trên ô. Khi mà số ô chưa được mở bằng với số mìn đã được chọn trong settings, trò chơi kết thúc và bạn chiến thắng. Ngược lại, nếu mở một ô chứa mìn, trò chơi kết thúc và bạn thua. Click chuột trái vào icon hình mặt cười sẽ restart trò chơi với các settings hiện tại. Tắt cửa sổ trò chơi sẽ đưa chúng ta trở lại cửa sổ settings.
![gameplay1](https://github.com/mrbillyco99/C-Cpp-Minesweeper-GUI/blob/master/Images/MinesweeperGamePlay1.png)

# Yêu cầu

Project yêu cầu thư viện SFML 2.5.1 và trình biên dịch phù hợp để có thể biên dịch.

# Lưu ý

Trong quá trình cài đặt project, sửa các đường dẫn đến các thư mục chứa hình ảnh và font tùy theo nơi bạn lưu project trên máy cá nhân để không gặp lỗi khi biên dịch.
