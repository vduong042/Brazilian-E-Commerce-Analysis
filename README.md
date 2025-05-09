# 🛒 Customer Behavior Analysis in E-Commerce (Olist Dataset)

## 🇬🇧 English Version

### 📌 Project Objective

Understand customer behavior in Brazil's e-commerce sector using the Olist dataset, with a focus on shopping time, purchase value & frequency, product categories, and factors affecting customer experience.

### 🧰 Dataset

- Source: [Kaggle - Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data)  
- 100,000+ records from multiple linked tables (orders, customers, products, reviews, etc.)

### 🔍 Key Insights

1. **Shopping Time**
    - Order volume grew quickly in early 2017 and peaked in November 2017, staying stable throughout 2018.
    - Mondays had the highest order volume.
    - Most purchases were made in the afternoon or evening.

2. **Purchase Value & Frequency**
    - Average Order Value (AOV) is around R$180, with slight monthly fluctuation: drop mid-year, rise toward the end.
    - Orders valued between R$100–R$500 were most common and contributed the most to revenue.
    - Most customers made only one purchase; repeat rate is very low (~1–2%).
    - New customers dominate, with returning customers increasing slightly over time.

3. **Product & Category**
    - Popular categories: `bed_bath_table`, `health_beauty`, `sports_leisure`.
    - Most customers only bought one product/category per order.

4. **Causal Analysis**
    - Delivery time strongly affected customer reviews.
    - Orders delivered in <15 days received high ratings (avg. >4.2).
    - Deliveries >30 days received very low ratings (avg. 2.2).
    - Greater shipping distance → longer delivery time → lower rating.

5. **RFM Analysis**
    - Nearly 60% of customers show signs of churn.
    - 40% of customers are new.
    - Loyal and VIP customers are very rare and insignificant in proportion.

### 🧩 Challenges

- Missing product category data limits in-depth behavior analysis.
- Low customer return rate makes loyalty-building difficult.
- Uneven distribution of orders and reviews across states.

### 🚀 Future Suggestions

- Develop strategies to retain and re-engage customers.
- Predict high-value or high-return-potential customers.

---

## 🇻🇳 Phiên bản Tiếng Việt

### 📌 Mục tiêu dự án

Hiểu rõ hành vi tiêu dùng của khách hàng trong thương mại điện tử tại Brazil thông qua phân tích dữ liệu Olist, tập trung vào thời gian mua sắm, giá trị & tần suất, danh mục sản phẩm và các nguyên nhân ảnh hưởng đến trải nghiệm.

### 🧰 Dữ liệu sử dụng

- Nguồn: [Kaggle - Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data)
- Hơn 100,000 bản ghi từ nhiều bảng liên kết (đơn hàng, khách hàng, sản phẩm, đánh giá,...)

### 🔍 Phân tích chính

1. **Thời gian tiêu dùng**
    - Số lượng đơn hàng tăng nhanh từ đầu nawmg 2017, đạt đỉnh vào tháng 11/2017 sau đó duy trì ở mức tương đối ổn định trong năm 2018.
    - Thứ Hai là ngày có lượng đơn đặt hàng cao nhất trong tuần, sau đó giảm dần vào các ngày sau đó.
    - Hoạt động mua sắm tập trung vào chiều/tối.

2. **Giá trị & Tần suất mua**
    - AOV theo tháng có biến động nhẹ, giảm vào giữa năm và tăng nhẹ vào cuối năm.
    - Những đơn hàng có phân khúc giá trung bình (R$100 -R$500) được đặt mua phổ biến đem về lượng doanh thu cao. Các đơn hàng có giá trị cao (>R$500) tuy ít nhưng cũng đóng góp đáng kể vào tổng doanh thu.
    - Phần lớn các khách hàng chỉ mua hàng một lần duy nhất. Tỉ lệ khách hàng quay trở lại là rất thấp.
    - Lượng khách hàng mới chiếm tỉ trọng áp đảo hàng tháng. Số lượng khách hàng quay lại tăng nhẹ nhưng không đáng kể.

3. **Sản phẩm & Danh mục**
   - Các danh mục phổ biến: "bed_bath_table", "health_beauty", "sports_leisure".
   - Đa số khách hàng chỉ mua 1 sản phẩm/danh mục duy nhất trong mỗi đơn hàng.

4. **Phân tích nguyên nhân**
   - Thời gian giao hàng ảnh hưởng lớn đến đánh giá.
   - Giao hàng <15 ngày thường được đánh giá cao (>4.2 sao).
   - Khoảng cách địa lý càng xa → giao hàng càng chậm → điểm đánh giá thấp hơn.

5. **Phân tích RFM**
    - Tỉ lệ khách rời bỏ chiếm gần 60% trong tổng số khách hàng.
    - 40% khách hàng tại Olist là khách hàng mới.
    - Khách hàng trung thành và khách hàng VIP chiếm tỉ lệ cực nhỏ, không đáng kể

### 🧩 Khó khăn

- Dữ liệu thiếu danh mục sản phẩm ảnh hưởng đến phân tích hành vi chi tiết.
- Tỉ lệ khách hàng quay lại rất thấp.
- Sự phân bố đánh giá và đơn hàng giữa các bang không đồng đều.

### 🚀 Đề xuất mở rộng

- Xây dựng chiến lược giữ chân khách hàng.
- Dự đoán khách hàng có giá trị cao hoặc có khả năng quay lại.

---

### 📁 Notebook: `E-Commerce-Analysis.ipynb`
To explore full code and visualizations, check out the notebook file in this repository.