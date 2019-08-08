## GITHUB.

> 
> Thực hiện: **Lê Thanh Nhàn + Trần  Thị Ngọc**
> 
> Cập nhật lần cuối: **07/08/2019**

### Mục lục  
[I. MARKDOWN](#I)  

[Markdown là gì?](#markdown)

[1. Tạo tiêu đề](#tieude)

[2. Định dạng chữ](#dinhdang)

[3.Xuống dòng](#xuongdong)

[4.Tạo danh sách](#danhsach)

[5. Tạo  liên kết](#lienket)

[6.Tạo hình ảnh](#hinhanh)

[7. Bảng](#bang)

[8.Cài đặt sublime text](#sublime)  

<a name = "I"></a>
# I.MARKDOWN
<a name="markdown"></a>
#  Markdown là gì?
- Markdown là ngôn ngữ đánh dấu văn bản thô được tạo ra bởi John Gruber. 
- Văn bản được viết bằng Markdown sẽ có thể được chuyển đổi sang HTML và ngược lại.
- Thường được dùng để:
 * tạo tập tin readme
 * viết tin nhắn trên diễn đàn
 * tạo văn bản có định dạng bằng một trình biên tập văn bản thô    
 
# Các cú pháp thường sử dụng:  

<a name="tieude"></a>
## 1. *Tạo tiêu đề*
> # Tiêu đề 1 (h1)  
> ## Tiêu đề 2 (h2)  
> ### Tiêu đề 3 (h3)  
> #### Tiêu đề 4 (h4)  
> ##### Tiêu đề 5 (h5)  
> ###### Tiêu đề 6 (h6)

<a name="dinhdang"></a>
## 2. *Định dạng chữ*
* *In nghiêng* : `*kí tự cần in nghiêng*` hoặc  `__ kí tự cần in nghiêng__`  
* **In đậm** :`**In đậm**` hoặc `__In đậm__`  
* ~~Gạch ngang~~: `~~gạch ngang~~`  

<a name="xuongdong"></a>
## 3. *Xuống dòng* :  
`<space><space>`: sử dụng hai khoảng trắng

<a name="danhsach"></a>
## 4. *Tạo danh sách*  
Chú pháp : `1. danh sách `

1. danh sách 1
2. danh sách 2
3. danh sách 3

hoặc `-danh sách` hoặc `* danh sách`
- danh sách 1
- danh sách 2
- danh sách 3

<a name="lienket"></a>
## 5. *Tạo liên kết*
- Có thể chèn Link trực tiếp  
https://www.w3schools.com/  
hoặc đặt trong cặp dấu ngoặc  
`<https://www.w3schools.com/>` 
hoặc
`![Tên link](đường dẫn) (<a>)`    
`![Tên link với chú thích](đường dẫn "chú thích") (<a name="chú thích">)`    

<a name="hinhanh"></a>
## 6. *Tạo hình ảnh*  
Cú pháp: `![mô tả](link)`  

![VÍ DỤ](http://imgt.taimienphi.vn/cf/Images/tt/2018/8/1/list-icon-facebook-bua-che.jpg)  

<a name="bang"></a>
##  7. *Bảng*
 Các cột được tách nhau bằng dấu ngăn thẳng đứng |   
 header được tách với content bằng dấu gạch ngang -.
  ~~~
  
|       A       |      B        | C     |
| :------------:|:-------------:|:-----:|
|    3          |        2      |  1    |
|     2         |        4      |   1   |
|     a         | b             |    d  |
~~~  

|       A       |      B        | C     |
| :-----------: |:-------------:| :----:|
|    3          |        2      |  1    |
|     2         |        4      |   1   |
|     a         | b             |    d  |  

<a name = "sublime"></a>
## 8. *Cài đặt sublime text*  
 ### 8.1.Download  
- Vào trang http://www.sublimetext.com/3 để download .
 ![](https://hungit.net/wp-content/uploads/2016/04/sublime-text-3.png)  
 
- Sau khi cài đặt, ta mở úng dụng lên sẽ có giao diện như hình sau:
 ![](https://hungit.net/wp-content/uploads/2016/04/giao-dien-sublime-text-3.png)  
 ### 8.2.Cài đặt Package Control thông qua wbond.net  
 - B1: Nhấn Ctrl + "`" Hoặc View/Show Console  
 - B2: Nhập code sau vào: 
 ~~~
 import urllib.request,os,hashlib; h = '2915d1851351e5ee549c20394736b442' + '8bc59f460fa1548d1514676163dafc88'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
 ~~~  
 ### 8.3.Cài đặt các extensions 
 - B1: Khởi động package control  
 - B2: Cài các gói sau:  
   - Alignment => Căn lề (Ctrl + Alt + A)  
   - Vn Ime => Gõ tiếng việt trên Sublime Text 3 => Nhấn F2 để gõ.  
   - TrailingSpaces: Giúp bạn phát hiện bỏ đi những khoảng trắng dư thừa trong quá trình code. Sau khi cài đặt thì bạn có thể nhận thấy rằng các vùng có khoảng trắng dư nó sẽ tự hightlight lên.  
   - Jquery  
   - jQuery Snippets  
   - Nettuts+ Fetch => Hỗ trợ reset file => Ctrl + Alt + P > Fetch > Single File  
   - Sublime CodeIntel => Nó hỗ trợ cho bạn việc hiển thị các gợi ý ngay khi bạn code, về các functions, biến, object, string. Nó chính là bộ xương sống của tính năng Intelligent Suggesstion.  
   - Tag => Hỗ trợ tag html  
   - Google Search  
   - WordPress  
   - HTML5  
   - Sublime Linter: Gói mở rộng này sẽ giúp bạn biết ngay khi bạn gõ, rằng có thể bạn đã làm một điều gì đó sai, ví dụ, mở ngoặc mà quên đóng, quên dấu ; ở cuối dòng lệnh,…Với riêng PHP + CSS + Javascript, bạn nên cài một số thành phần phụ cho SublimeLinter này, nhờ vào Package Control  
   - SublimeLinter-phplint => Check lỗi php  
   - SublimeLinter-json  
   - Xdebug Client: Dễ dàng debug ứng dụng PHP của mình.  
 
 
 
 

 <a name ="II"></a>  
 # II.GIHUB   
 <a name="github"></a>  
 # Github là gì?  
 **- Github là một trang web, cho phép bạn lưu source code của mình lên đó. Sự kết hợp hoàn hảo giữa Git và Github mang lại một sự thuận tiện không hề nhỏ cho người dùng. Bạn có thể thay đổi đoạn code của mình mọi lúc mọi nơi mà không sợ bị ghi đè lên hay bị mất dữ liệu do hỏng hóc vì dữ liệu của bạn được lưu cả trên trang web Github và máy cá nhân. Bạn cũng có thể khôi phục được code của mình về một thời điểm bất kỳ nào đó.**  
 *- Github có bản free và mất phí. Với Github free thì source code của bạn sẽ công khai, có nghĩa là ai cũng có thể xem code của bạn. Nó phù hợp với các phần mềm nguồn mở, và cũng có thể trở thành một blog cá nhân của chính các bạn như các trang blogspot, wordpress,...Muốn có thể tạo một kho code bí mật của riêng mình thì bạn phải trả phí.*  
 ![](https://www.pullrequest.com/blog/github-code-review-service/images/github-logo_hub2899c31b6ca7aed8d6a218f0e752fe4_46649_1200x1200_fill_box_center_2.png)  
 ## Cần phải làm gì để có thể sử dụng Github?  
 - B1: Đăng ký một tài khoản tại github và đăng nhập  
 - B2: Học cách sử dụng ngôn ngữ Markdown  
 - B3: Tạo một repo đầu tiên và gõ Hello world bằng Markdown  
 

 


 

 
 ~~THE END~
 




 





