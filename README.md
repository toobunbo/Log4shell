# Log4shell
- Log4shell hay nhìn sợ hơn là CVE-2021-44228 là một lỗ hổng của thư viện Log4j ver 2.
- Nói cho vuông thì thư viện Log4j sẽ ghi nhật ký (log) của ứng dụng, vd: A create account at 00:00:22PM ... hong phải format v đâu nhưng v cho dễ hiểu
- Chuyện sẽ k có gì xảy ra nếu thằng Log4j này nó có thể bị chèn mã độc, đọc và thực thi cmn cái đoạn code bên ngoài truyền vào 🙂. Chỉ v thôi
- Đó là giải thích cho mấy thằng ngu k biết gì, mấy con gà đang học hack sẽ giải thích giống bên dưới. Vào việc

## Làm report nên sẵn làm luôn 
1. Tổng quan về Log4shell
2. Hướng khai thác
## Log4shell là cái qq gì?
- Dễ hiểu thôi CVE-2021-44228 nó là một lỗ của thư viện Log4j (java)
- Mà thư viện Log4j là cái gì 😀
### Log4j?
- Các nhà phát triển ~~với cái tôi cao~~ thường cho rằng log xử lý những kiểu dữ liệu và định dạng cơ bản. How é vờ, phiên bản Log4j ver 2 đã cập nhật thêm **Lookups**
- ### 
