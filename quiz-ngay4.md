# 🧠 Quiz – Ngày 4: Linear Regression, Gradient Descent, Loss Functions

## 🟩 Phần 1: Trắc nghiệm (Multiple Choice)

1. Mục tiêu của Linear Regression là gì?

A. Tối đa hóa khoảng cách giữa các điểm và đường thẳng  
B. Tìm đường thẳng khớp dữ liệu nhất (giảm sai số)  
C. Chia dữ liệu thành nhóm  
D. Ước lượng xác suất thuộc về 1 lớp  

→ **Đáp án của em: B**

---

2. Hàm mất mát MSE có công thức là gì?

A. (1/n) ∑ |yᵢ - ŷᵢ|  
B. ∑ (yᵢ - ŷᵢ)  
C. (1/n) ∑ (yᵢ - ŷᵢ)²  
D. √(yᵢ - ŷᵢ)  

→ **Đáp án của em: C**

---

3. Trong Gradient Descent, bước cập nhật weight w là gì?

A. w = w + rate × ∇w  
B. w = w - rate × ∇w  
C. w = w × ∇w  
D. w = ∇w - rate  

→ **Đáp án của em: B**

---

4. Loss function nào bền vững hơn với outlier?

A. MSE  
B. MAE  
C. Cross Entropy  
D. Accuracy  

→ **Đáp án của em: B**

---

5. Mục tiêu của Huber Loss là gì?

A. Loại bỏ tất cả outlier  
B. Tối ưu tốc độ tính toán  
C. Kết hợp ưu điểm của MSE và MAE  
D. Chỉ dùng cho bài toán phân loại  

→ **Đáp án của em: C**

---

## 🟨 Phần 2: Tự luận (Viết 2–5 dòng mỗi câu)

1. **Vì sao MSE lại nhạy cảm với outlier hơn MAE?**  
MSE dùng bình phương sai số nên outlier có ảnh hưởng lớn gấp bội.

---

2. **Khi nào thì nên dùng Gradient Descent thay vì giải công thức chính xác (closed-form)?**  
Khi số lượng biến (feature) rất lớn hoặc dữ liệu quá nhiều, giải công thức đóng không khả thi → cần dùng Gradient Descent để lặp tìm nghiệm gần đúng.

---

3. **So sánh MSE và Huber Loss (gói gọn trong 1–2 câu).**  
MSE nhạy cảm với outlier, trong khi Huber kết hợp MAE & MSE để giữ độ ổn định.

---

4. **Linear Regression có thể ứng dụng vào bài toán không gian như thế nào?**  
Linear Regression có thể dự đoán chi phí nhiên liệu dựa trên khối lượng tải, độ cao bay, hoặc dự đoán thời gian trễ của tên lửa dựa vào thời tiết.

---

5. **Điều gì là quan trọng nhất khi học Linear Regression (tư duy cá nhân)?**  
Điều quan trọng không chỉ là giảm sai số mà còn là hiểu mô hình đang học gì, và nó có đủ đơn giản, ổn định để giải thích hay không.
