
# Hi! 👋
## GIAO DIỆN NGƯỜI DÙNG (GUI)
### Thiết kế giao diện
- Sử dụng ứng dụng Qt Designer để thiết kế giao diện
![App Screenshot](https://github.com/user-attachments/assets/a79a8f34-55b2-4922-a6e2-1b2952cc4c3c)
- Sử dụng ứng dụng Visual Studio Code và ngôn ngữ Python để thêm các chức năng vào giao diện trên.
- Để xuất giao diện người dùng ta sử dụng Command Line như sau:
```bash
pyuic6 -o .\GUI_control.ui -x GUI.py
``` 

Trong đó: 
.\GUI_control.ui là tên file được lưu từ Qt Designer và GUI.py được tự động tạo và giao diện được lưu vào đó

Để gọi giao diện chính vào chương trình GUI:
```bash
from GUI import Ui_MainWindow
``` 
### Các chức năng của GUI

![App Screenshoy](https://github.com/user-attachments/assets/f4d6e692-5197-47a2-8007-f17ee9e2a93d)

Trong giao diện đồ họa người dùng này bao gồm:
- Vùng giao tiếp với Arduino thông qua cổng Serial với cổng COM và Baudrate. 
- Vùng Manual Mode để điều chỉnh góc của động học thuận và 2 bộ nghiẹm của động học nghịch với 2 nút MOVE để di chuyển tới các vị trí ứng với bộ nghiệm. 
- Vùng thể hiện góc hiện tại và vị trí hiện tại. 
- Đồ họa 3D tái hiện hình dáng của cánh tay robot.





