# Project3
Trong project này chúng ta dùng mô hình LSTM để dự đoán giá cổ phiếu của VNM. Các tham số tối ưu của mô hình được tìm bằng kỹ thuật gridsearch.
Do hạn chế về tài nguyên nên ta sẽ chia nhỏ khối lượng công việc ra để tìm từng tham số tối ưu.Cụ thể trong bài này ta sẽ tìm các tham số tối ưu theo thứ tự: model_units,model_dropout,batchsize,epochs,time_steps.Điều này được thể hiện ở "Đồ_thị_MAE_VNM". 
