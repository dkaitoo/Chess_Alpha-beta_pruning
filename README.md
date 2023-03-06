# Chess_Alpha-beta_pruning
INTRODUCTION TO ARTIFICIAL INTELLIGENCE - 503043 HK2/21-22

Lecturer: TS.BTH

Project No.24: Viết chương trình cờ vua bằng giải thuật anpha-beta cắt tỉa. Chương trình cho phép người chơi với máy

Cắt tỉa Alpha-Beta là một thuật toán tìm kiếm nhằm mục đích giảm số lượng các nút được tính toán bởi thuật toán Minmax trong cây tìm kiếm của nó. Ưu điểm của thuật toán này nằm ở chỗ, các nhánh của cây tìm kiếm, không ảnh hưởng đến kết quả cuối cùng của việc di chuyển, có thể được loại bỏ trong quá trình đánh giá. Bằng phương pháp này, tìm kiếm có thể được giới hạn trong cây con thực sự hữu ích và có thể thực hiện tìm kiếm tập trung vào chiều sâu hơn. Thuật toán Alpha-Beta giữ lại giới hạn trên và giới hạn dưới của các giá trị để phân tích xem có thể cắt các nhánh hay không. Loại lược bớt này có thể dẫn đến việc giảm lượng tìm kiếm đáng kể - về cơ bản là tăng gấp đôi độ sâu tìm kiếm so với thuật toán Minimax ban đầu khi cho cùng một thời gian tìm kiếm.
