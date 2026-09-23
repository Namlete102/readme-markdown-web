<!-- css --> 

<link rel="stylesheet" href="custom.css">

<!-- Lời nói đàu -->

Chào mừng bạn đến với web được tạo bằng `README.md` và với các tệp trình bày nội dung cũng được viết cũng bằng đuôi `.md`. 

<!-- Thanh menu -->

## Trang chủ|[Giới thiệu](./about.md)|[Cập nhật](./news.md) 

Ở đây chưa có gì cả, nên tôi lấp đại khoảng trống bằng mấy dòng. 

Và dưới đây sẽ là các mục các vấn đề được chỉnh sửa ở file `README.md` này. 

### Tiêu đề: 

```markdown
# Tiêu đề loại 1

## Tiêu đề loại 2

### Tiêu đề loại 3

#### Tiêu đề loại 4

##### Tiêu đề loại 5

###### Tiêu đề loại 6
```

### Viết văn bản: 

Văn bản thường nè. 

**In đậm**, *In nghiêng*, <u>Gạch chân chữ</u>, ~~Gạch giữa chữ~~. 

Văn bản có <span style="color:red;">màu đỏ</span>


### Chèn link: 

Trực tiếp: Mã nguồn dự án [https://github.com/Namlete102/README-markdown-web](https://github.com/Namlete102/README-markdown-web)

Gián tiếp: Nhấp [vào đây](https://github.com/Namlete102/README-markdown-web) để được chuyển đến mã nguồn dự án.  

Có thể sử dụng thẻ `<a>` bên HTML để chèn link: Nhấp <a href="https://github.com/Namlete102/README-markdown-web" target="_blank">vào đây</a> để được chuyển đến mã nguồn dự án ở một tab khác bên trong trình duyệt web.

### Chèn danh sách: 

Danh sách không có thứ tự: 

+ Một
+ Hai
+ Ba

Danh sách có thứ tự: 

1. Một 
2. Hai 
3. Ba

<p id="math-web"></p>
### Chèn phương trình toán học:
 
Viết phương trình định lý Pytago ở chế độ `inline math`: \\(z^2 = x^2 + y^2\\)  

Viết phương trình Dirac trong cơ học lượng tử ở chế độ `display math`: 

$$
\begin{equation} \tag{1.1}
(i \gamma^\mu \partial_\mu - m) \psi = 0
\label{eq:1.1}
\end{equation}
$$

Tham chếu đến phương trình \eqref{eq:1.1}

### Tham chiếu chéo nội dung

Nhấp vào <a href="#math-web">chèn phương trình toán học</a> để được chuyển đến nội dung chèn toán học vào website.

<!-- Footnote  -->

### Chú thích 

Chú thích đầu tiên link[^first]

Chú thích thứ hai link[^second]

### Chèn code 

Display code: 

LaTeX: 

```latex
\documentclass{article}
\begin{document}
Hello \LaTeX
\end{document}
```

Python:

```python
import random

# Tạo một số ngẫu nhiên từ 1 đến 10
so_bi_mat = random.randint(1, 10)
so_lan_doan = 0

print("=== GAME ĐOÁN SỐ (1 đến 10) ===")

while True:
    # Nhận dữ liệu nhập từ người dùng
    doan = int(input("Nhập số bạn đoán: "))
    so_lan_doan += 1

    # Kiểm tra kết quả
    if doan < so_bi_mat:
        print("Số bí mật LỚN HƠN số bạn đoán!")
    elif doan > so_bi_mat:
        print("Số bí mật NHỎ HƠN số bạn đoán!")
    else:
        print(f"🎉 Chúc mừng! Bạn đã đoán đúng số {so_bi_mat} sau {so_lan_doan} lần thử.")
        break
```

<!-- figure -->

### Chèn ảnh

Sử dụng thẻ `figure`, và viết chú thích ảnh bằng `figcaption`. 

jpg: 

<figure>
    <img src="./images/sumida (shimeji simulation).jpg" alt="Shimuda">
    <figcaption>Nhân vật Shimuda trong Shimeji Shimulation.</figcaption>
</figure> 

gif: 

<figure>
    <img src="./images/Satanichia McDowell Kurumizawa.gif" alt="Satanichia McDowell Kurumizawa">
    <figcaption>Nhân vật Satanichia McDowell Kurumizawa trong Gabriel DropOut.</figcaption>
</figure> 

<!-- Đạo lý -->

### Blockquote

Sử dụng thuần thẻ `div`, `blockquote`. 

<div align="left">
    <blockquote>
        <b>The more real you get, the more unreal everything else is.</b>
        <br>
        -John Lennon- 
   </blockquote>
</div>

<figure>
    <img src="./images/John Lennon.jpg" alt="John ">
    <figcaption>Nhạc sĩ người Anh John Lennon</figcaption>
</figure> 

## Chèn bảng

<div align="center" class="table-container">
<table>
        <tr>
            <th></th>
            <th></th>
            <th>Thứ hai</th>
            <th>Thứ ba</th>
            <th>Thứ tư</th>
            <th>Thứ năm</th>
            <th>Thứ sáu</th>
        </tr>
        <tr>
            <td rowspan="5">Sáng</td>
            <td>Tiết 1</td>
            <td>Chào cờ</td>
            <td>GDĐP</td>
            <td>Lịch sử</td>
            <td>GDQP</td>
            <td>Địa lý</td>
        </tr>
        <tr>
           <td colspan="6"><div align="center">Ra chơi 1</div></td>
        </tr>
        <tr>
            <td>Tiết 2</td>
            <td>Ngoại ngữ</td>
            <td>Ngoại ngữ</td>
            <td>HĐ TNHN</td>
            <td>Tin học</td>
            <td>Địa lí</td>
        </tr>
        <tr>
            <td>Tiết 3</td>
            <td>Toán</td>
            <td>Ngoại ngữ</td>
            <td>HĐ TNHN</td>
            <td>Tin học</td>
            <td>GDQP</td>
        </tr>
        <tr>
            <td colspan="6"><div align="center">Ra chơi 2</div></td>
        </tr>
</table>
Thời khóa biểu
</div>

## Callout 

> [!NOTE]  
> Nhấn mạnh những thông tin mà người dùng nên lưu ý, ngay cả khi chỉ đọc lướt qua.

<!-- Mermaid -->

### Mermaid 

<pre class="mermaid">
timeline
    title History of Social Media Platform
    2002 : LinkedIn
    2004 : Facebook
         : Google
    2005 : YouTube
    2006 : Twitter
</pre>

<!-- footer -->

## Chân trang 

Tạo thuần thẻ `div`, `span` và `center` cơ bản. 

<div align="center">
  <span><a href="https://github.com/Namlete102/readme-markdown-web" target="_blank"><b>Github</b></a></span> 
  .
  <span><a href="https://namlete102.github.io/Namleteblog.github.io/aboutme.html" target="_blank"><b>Contact</b></a></span>
</div>

<div align="center">
  <b>Copyright ©2026; Designed and edited by Namlete</b>
</div>

<hr> 

<!-- footnote -->

[^first]: Cái đầu tiên

[^second]: Cái thứ hai


<!-- Mathjax -->
<script type="text/javascript" id="MathJax-script" async
    src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>

<script>
    window.MathJax = {
      tex: {
        inlineMath: [['$', '$'], ['\\(', '\\)']]
      }
    };

    MathJax = {
      tex: {
        tags: 'ams'  // or 'all'
      }
    };
    
    function zoomOut() {
      let img = document.getElementById("myImage");
        img.style.width = (img.clientWidth - 50) + "px"; // Reduces width by 50px
      }
</script>

<!-- Mermaid -->

<script type="module">
    import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@9/dist/mermaid.esm.min.mjs';
    mermaid.initialize({ startOnLoad: true});
</script>
