# Project-AI-apply-Searching-Algorithm
Mô tả bài toán: Một người sẽ bắt đầu từ nhà của mình tới một cafe gặp đối tác. Người đó không biết đường đi tới quán cafe đó nhưng lại có địa chỉ của quán cafe đó. Và khi bắt đầu đi thì xe người đó chỉ có n lít xăng. Khi đi được 1KM thì xe người đó chỉ còn lại n - 1 lit xăng. Và trên đường đi sẽ có những hẻm cụt, tường không thể đi qua được. Nếu người đó hết xăng mà vẫn chưa đi tới quán cafe được thì coi như việc gặp đối tác bị hủy. Với 4 thuật toán BFS, DFS, DLS, A* hãy tìm ra thuật toán giúp người đó đi tới được quán cafe.
Problem của bài toán:
- Initial state là một tọa dộ trên ma trận start = (x1, y1)
- Goal state là đích đến end = (x2, y2)
- Possible actions là những action mà người đó có thể đi được.
Biểu diễn bài toán: Bài toán sẽ được biểu diễn bằng một ma trận có kích thước N * N. Trong đó những ô có màu trắng là những ô có thể đi được, ô màu vàng là ô biểu diễn nơi xuất phát của người đi gặp đối tác, màu đỏ sẽ biểu diễn đích đến là quán cafe, màu đen sẽ biểu diễn cho tưởng(hẻm cụt) không thể đi qua được những ô có màu đen này. Khi người đó tìm đường thì chúng ta sẽ tô màu cho những ô đó bằng màu xanh lá cây, và riêng con đường đi tới được đích sẽ được tô bằng màu xanh nước biển.
Công nghệ sử dụng: Trong dự án này nhóm chúng em sẽ sử dụng công nghệ là ngôn ngữ python và các thư viện của python để thực hiện dự án này. Các thư viện được sử dụng trong dự án này bao gồm:
Thư viện Tkinter: Thư viện này là một thư viện của ngôn ngữ python dùng để tạo nên các ứng dụng Graphical User Interface(GUI). Thư viện này là một thư viện phổ biến để tạo GUI bằng python vì nó rất đơn giản và dễ tiếp cận. Để cài đặt tkinter chúng ta sẽ sử dụng câu lệnh pip install tkinter.
Một số thư viện khác có sẵn khi chúng ta cài python.
Các thuật toán được sử dụng trong dự án
- BFS: Breadth First Search (Tìm kiếm theo chiều rộng)
- DLS: Depth Limit Search (Tìm kiếm theo chiều sâu có giới hạn)
- A*(A Star)
