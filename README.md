# horse-colic
Đây là dự án xử lý dữ liệu trong Machine learning
Dự án sử dụng ngôn ngữ python trên jupyter noteboook

# Hướng dẫn
Để khởi động dự án, bạn cần tải jupyter notebook (có thể thông qua anaconda) hoặc sử dụng trực tiếp trên google chrome thông qua extension Colaboratory

# Thông tin dataset
- horse-colic được định nghĩa là đau bụng ở ngựa, nhưng đó là triệu chứng lâm sàng chứ không phải là chẩn đoán. Thuật ngữ đau bụng có thể bao gồm tất cả các dạng của tình trạng đường tiêu hóa gây đau cũng như các nguyên nhân khác của đau bụng không liên quan đến đường tiêu hóa.
- dataset horse-colic phù hợp đối các bài toán phân lớp bao gồm 3 giá trị dự đoán: 
  + alive: ngựa sẽ sống sót
  + deaded : ngựa sẽ chết
  + was euthanized : ngựa sẽ cần tiêm thuốc trợ tử
- số mẫu : 368 (300 train, 68 test)
- 27 thuộc tính
- 30% missing 
- các kiểu dữ liệu : liên tục,rời rạc
- có thể xem thêm thông tin của từng thuộc tính trong dataset thông qua file horse-colic_names.txt trong thư mục data hoặc đường dẫn: https://archive.ics.uci.edu/ml/datasets/Horse+Colic

# Các kĩ thuật sử dụng
- Tiền xử lý:
  + Handle Missing Data
  + Feature Selection
  + Feature Scaling
  + Discretization
- Thuật toán
  + Decision Tree
  + KNN
  + SVM

