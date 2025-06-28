# Đồ án nhóm môn Machine Learning
**Đề tài: Phân loại khách hàng tiềm năng của một ngân hàng để xem khách hàng có đăng ký sản phẩm tiền gửi có kỳ hạn hay không.**
## Sơ lược dữ liệu
**Dữ liệu về khách hàng của ngân hàng:**
1. Age: tuổi (số, dạng số).

2. Job: loại công việc (phân loại: "admin.", "unknown", "unemployed", "management", "housemaid", "entrepreneur", "student", "blue-collar", "self-employed", "retired", "technician", "services").

3. Marital: tình trạng hôn nhân (phân loại: "married", "divorced", "single"; lưu ý: "divorced" có thể bao gồm đã ly hôn hoặc góa).

4. Education: trình độ học vấn (phân loại: "unknown", "secondary", "primary", "tertiary").

5. Default: có nợ tín dụng không? (nhị phân: "yes", "no").

6. Balance: số dư trung bình hàng năm, tính bằng euro (số, dạng số).

7. Housing: có khoản vay nhà ở không? (nhị phân: "yes", "no").

8. Loan: có khoản vay cá nhân không? (nhị phân: "yes", "no").

**Dữ liệu liên quan đến lần liên hệ cuối cùng của chiến dịch:**

9. Contact: Phương thức liên lạc với khách hàng (phân loại: "unknown","telephone","cellular").

10. Day: Ngày thực hiện chiến dịch (số).

11. Month: Tháng thực hiện chiến dịch (phân loại: "jan", "feb", "mar", …, "nov", "dec").

12. Duration: Thời gian của cuộc gọi (tính bằng giây, số nguyên).

**Các dữ liệu khác:**

13. Campaign: Số cuộc gọi đã thực hiện trong chiến dịch (số).

14. Pdays: Số ngày kể từ chiến dịch trước (số, -1 tức là khách hàng chưa từng được liên lạc).

15. Previous: Số cuộc gọi đã thực hiện trong các chiến dịch trước đó (số).

16. Poutcome: Kết quả của chiến dịch trước đó (phân loại: "unknown","other","failure","success").

**Biến Output:**

17. y: Khách hàng có đăng ký sản phẩm "tiền gửi có kỳ hạn" hay không (có/không).
