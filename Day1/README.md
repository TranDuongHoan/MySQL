### BÀI TẬP VỀ NHÀ

```sql
CREATE TABLE post(
    title varchar(250),
    content text,
    cot_datetime DATETIME,
    author varchar(100),
    category ENUM('Sport', 'Politics', 'Health', 'Tourism', 'Economy', 'Education', 'Technology', 'Science'),
    published boolean
);
```

![](./bangpost.png)

```sql
CREATE TABLE Product(
    name varchar(300),
    description text,
    manufacturer varchar(250),
    madein varchar(100),
    unit_price int,
    category ENUM('Quần áo', 'Mỹ phẩm', 'Đồ chơi', 'Dụng cụ học tập', 'Máy tính', 'Di động', 'Điện tự dân dụng', 'Văn phòng')
);
```

![](./bangProduct.png)
