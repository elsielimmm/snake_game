# Dự án: Xây dựng thuật toán cho trò chơi rắn tìm đường
Môn học: Chuyên đề 2

Giảng viên hướng dẫn: TS. Nguyễn Văn Hiếu

Báo cáo cuối kỳ - Lớp học phần: 21.44

Nhóm 5

## Thành viên 

| Name              | Student ID    |
| ----------------- | ------------- |
| Nguyễn Văn An   | **10620045**  |
| Phạm Thị Phương | **106210050** |
| Dương Thị Thảo Vi     | **10621259**  |

## Mô tả dự án 

### Xây dựng thuật toán cho trò chơi rắn tìm đường

Dự án này triển khai một phiên bản thông minh của trò chơi Rắn (Snake Game) cổ điển, trong đó con rắn có khả năng **tự động tìm ra đường đi an toàn và tối ưu** để tiếp cận thức ăn trên lưới 8×8. Trò chơi tích hợp nhiều thuật toán khác nhau, bao gồm **chu trình Hamilton**, **tìm đường tham lam (Greedy)** và **DQN (Deep Q-Network)**, nhằm so sánh các chiến lược giải quyết khác nhau.

Mục tiêu chính của dự án là đánh giá hiệu quả của các **thuật toán xác định** (Hamilton, BFS tìm đường ngắn nhất/dài nhất, logic Greedy) và các **phương pháp học máy** (DQN) trong việc điều hướng trên không gian lưới giới hạn, tránh va chạm và tối đa hóa lượng thức ăn thu thập được.

### Dự án gồm:

- **Hamilton Solver**: Xây dựng và di chuyển theo một chu trình Hamilton để đảm bảo duyệt an toàn toàn bộ bản đồ. Hỗ trợ tối ưu đường tắt nhằm giảm các bước di chuyển không cần thiết.

- **Greedy Solver**: Sử dụng BFS tìm đường ngắn nhất kết hợp với kiểm tra an toàn để tiến về phía thức ăn khi có thể; trong trường hợp không an toàn, hệ thống sẽ lựa chọn đường đi dài nhất để tránh va chạm với chính cơ thể rắn.

- **Path Solver**: Cung cấp khả năng sinh đường đi ngắn nhất (BFS) và đường đi dài nhất dựa trên heuristic trong lưới.

- **DQN Solver**: Huấn luyện tác nhân bằng học tăng cường để điều khiển rắn thông qua mô hình DQN.
