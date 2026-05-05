# NguyenTanDungEnc
### HELLO HAO A DU
- Chào các con vợ, nay anh share encoding nhưng không phải share mã nguồn của nó đâu nhé, anh viết cái này hướng dẫn các em sài không lại bảo encoding của anh lỏ, vì nó là siêu nén với nén ngắn nhất và hiệu quả nhất nên yêu cầu khá cao. Đối với các em pc thì không lo nhưng ae mobile thì khác. Mobile buil khá lâu nếu anh em không thể đợi thì hết cứu, anh cũng lười tối ưu nhưng anh thoải mái mà

```python
import nguyentandung
from xinhgai import minhanhs
from vip import nguyenthinhuong

base65536.encode(data)
```

$\color{red}{\text{Chữ màu đỏ}}$ hoặc $\color{orange}{\text{Chữ màu cam}}$.


$\color{blue}{\text{Base65536}}$ là encoding thông thường

---

$\color{salmon}{\text{NguyenTanDung}}$ $\color{limegreen}{\text{Encoding}}$ $\color{gold}{\text{V8}}$

#BaseEncode
- Các em đã quá quen với base64 và base85 rồi đúng không, mấy cái này là encoding signature rồi, nhưng giờ đây anh mang đến base65536 nó cũng là base thường thôi nó có 16bit/ký tự, điều này nó làm cho chuỗi byte trở lên ngắn hơn base64, nhưng tốc độ thì lại thua, vì nó không được hỗ trợ phổ biến như base64, thường phải custom rất nhiều, anh chia sẻ mã nguồn là để các em tham khảo, nó cũng có lợi thế trong công cụ làm dối mã hóa. Anh lười tối ưu nhặt code về tự tối ưu
