##Snake Game – Artificial Intelligence Project
Môn học: Chuyên đề 2
Báo cáo cuối kỳ – Nhóm 21.44
Thành viên thực hiện:

Phạm Thị Phương

Dương Thị Thảo Vi

Nguyễn Văn An

1. Giới thiệu dự án

Dự án tập trung xây dựng và phân tích trí tuệ nhân tạo (AI) cho trò chơi Snake.
Mục tiêu của rắn là di chuyển, ăn thức ăn liên tục và lấp đầy toàn bộ bản đồ mà không va vào tường hoặc chính cơ thể mình.

Dự án gốc được viết bằng C++, và phiên bản này đã được viết lại bằng Python để:

Tạo giao diện đồ họa (GUI) thân thiện hơn.

Đơn giản hóa việc triển khai, thử nghiệm và quan sát hành vi AI.

Mô phỏng trực quan các thuật toán cổ điển và học tăng cường.

Các thuật toán được áp dụng:

Greedy Solver

Hamilton Solver

Deep Q-Network (DQN)

Chi tiết thuật toán có trong tài liệu Algorithms.

2. Cài đặt môi trường
Yêu cầu:

Python 3.6+

Thư viện Tkinter (tích hợp sẵn trong hầu hết phiên bản Python)

Cài đặt thư viện:
pip install -r requirements.txt

Chạy chương trình:
python run.py [-h]

Chạy unit tests:
python -m pytest

3. Tài liệu thuật toán

Xem mô tả chi tiết tại:

docs/algorithms.md

Liên kết nhanh:

Greedy Solver

Hamilton Solver

DQN Solver
