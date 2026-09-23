## [Trang chủ](./README.md)|[Giới thiệu](./about.md)|Cập nhật

Nơi đây sẽ chứa những thông báo mới nhất của dự án. 

+ 2019-12-21:
    + Easy to install precompiled JSLinux demo

+ 2019-02-10:
    + compilation fixes

+ 2018-09-23:
    + Changed name from riscvemu to TinyEMU
    + Single executable for all emulated machines
    + Added a RISC-V Buildroot port with an integrated RISC-V 32 bit and 64 bit toolchain
    + Support for separate RISC-V BIOS and kernel

+ 2018-08-29:
    + compilation fixes

+ 2017-08-06:
    + added JSON configuration file
    + added graphical display with SDL
    + added VirtIO input support
    + added PCI bus and VirtIO PCI support
    + x86: added IDE, PS/2, vmmouse and VGA devices
    + added user mode network interface

+ 2017-06-10:
    + Support of user level ISA version 2.2, priviledged architecture version 1.10 1.4x faster emulation
    + Device tree support
    + Can be used online

Tham khảo ở web [đây](https://bellard.org/tinyemu/): <a href="https://bellard.org/tinyemu/" target="_blank">https://bellard.org/tinyemu/</a>

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