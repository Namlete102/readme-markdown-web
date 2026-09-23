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

<!-- Mermaid -->

### Mermaid 

<pre class="mermaid">
  timeline TD
    title MermaidChart 2023 Timeline
      section 2023 Q1 <br> Release Personal Tier
        Bullet 1 : sub-point 1a : sub-point 1b
        Bullet 2 : sub-point 2a : sub-point 2b
      section 2023 Q2 <br> Release XYZ Tier
        Bullet 3 : sub-point <br> 3a : sub-point 3b
        Bullet 4 : sub-point 4a : sub-point 4b
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

<!-- css -->

<style>
body{
  background-color: rgb(28, 26, 23);
  color:aliceblue; 
}

/* Kích hoạt tính năng cuộn mượt cho toàn bộ trang */
html {
  scroll-behavior: smooth;
}

/* Chuyển đổi trang mượt mà */

@view-transition {
  navigation: auto;
  types: slide, rotate;
}

/* Đổi tên tiêu đề mặc định của github tham khảo Source - https://stackoverflow.com/a/26889106
Posted by G-Cyrillus
Retrieved 2026-09-17, License - CC BY-SA 3.0 */

h1 {
  text-indent:-9999px;
  font-size: clamp(1.8rem, calc(7vw + 1rem), 2rem);
}

h1:before {
  text-indent:0;
  content:'Make web by file REAME.md in Github';
  float:left;
} 


/* Chèn bảng */

.table-container table{
  margin: 0px auto;  /* căn giữa bảng */
  border-collapse: collapse;
  width: 800px;
  font-size: 20px;
}

.table-container table th{
  font-weight:lighter;
  border-bottom: 1px solid black;
}

th, td {
          /* Adds a right border to all cells */
          border-right: 1px solid black;  
        	padding: 5px; 
}

/* Removes the border from the very last column */
th:last-child, td:last-child {
          border-right: none; 
}

caption {
  caption-side: bottom;
  margin-top: 5px;
  font-size: 20px; 
}

/* Chèn ảnh */

figure{
  margin: 0 auto;
  text-align: center;
  display: block;
}

figure img{
  max-width: 80%;
  max-height: 80%;
}

figure figcaption {
    margin-top: 15px;
    text-align: center;
    font-size: 16px;
}

/* Chèn code */


  
/* Mathjax */

.MathJax {
  overflow-x: auto;
  overflow-y: hidden;
  max-width: 100%;
}

/* Thêm thuộc tính này cho phần tử/phương trình nhận tham chiếu */
 
[id^="eq-"], 
[id] { 
    /* Đặt giá trị bằng chiều cao Nav (? px) + khoảng hở mong muốn (ví dụ 15px) */
    scroll-margin-top: 15px; 
}
</style>