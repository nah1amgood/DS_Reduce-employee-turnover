Chào bạn mình góp ý cho bạn một vài chỗ mình nghĩ là cần làm thêm để bài của bạn đẹp hơn:
1. Chỗ phân chia dữ liệu train test bác nên để random state tức là ai vào thì nó đều chia data như vậy ko bị phối trộn. Tỉ lệ data tương đối lớn có thể thay đổi 0.2 hoặc 0.1 cho test size thử xem có cải thiện tốt hơn hay không.
2. Data của bác bị imbalanced kha khá. Nên có thử nghĩ cách cải thiện bằng các phương pháp oversampling,...
3. Như số 2 trên nên phương pháp đánh giá của bác bị ảnh hưởng. Có thể suy nghĩ thêm f1_score, hoặc thêm nhiều chỉ số như PPV, NPV, Specificity, Sensitivity để cụ thể hóa mô hình mình tốt và kém chỗ nào. Nên so thêm với train để xem có bị overfiting hay ko, thường ba cái tree hay bị vậy.
4. Thử các phương pháp học máy khác nhau làm benchmarking vì ko phải mô hình học máy nào cũng tốt. Nên tập trung các mô hình đơn giản đừng thêm cái deep learning chạy lâu lắm.
