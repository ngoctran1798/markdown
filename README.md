# BÁO CÁO GITHUB.

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

[II. GITHUB](#II)  

[Github là gì?](#github)  

[1.Tìm Hiểu Các Khái Niệm](#timhieu)  

[2. Cài đặt git, Generate, add key SSH...  ](#caidat)



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
   - **Alignment** => Căn lề (Ctrl + Alt + A)  
   - **Vn Ime** => Gõ tiếng việt trên Sublime Text 3 => Nhấn F2 để gõ.  
   - **TrailingSpaces**: Giúp bạn phát hiện bỏ đi những khoảng trắng dư thừa trong quá trình code. Sau khi cài đặt thì bạn có thể nhận thấy rằng các vùng có khoảng trắng dư nó sẽ tự hightlight lên.  
   - **Jquery**  
   - **jQuery Snippets**  
   - **Nettuts+ Fetch** => Hỗ trợ reset file => Ctrl + Alt + P > Fetch > Single File  
   - **Sublime CodeIntel** => Nó hỗ trợ cho bạn việc hiển thị các gợi ý ngay khi bạn code, về các functions, biến, object, string. Nó chính là bộ xương sống của tính năng Intelligent Suggesstion.  
   - **Tag** => Hỗ trợ tag html  
   - **Google Search**  
   - **WordPress**  
   - **HTML5**  
   - **Sublime Linter**: Gói mở rộng này sẽ giúp bạn biết ngay khi bạn gõ, rằng có thể bạn đã làm một điều gì đó sai, ví dụ, mở ngoặc mà quên đóng, quên dấu ; ở cuối dòng lệnh,…Với riêng PHP + CSS + Javascript, bạn nên cài một số thành phần phụ cho SublimeLinter này, nhờ vào Package Control  
   - **SublimeLinter-phplint** => Check lỗi php  
   - **SublimeLinter-json**  
   - **Xdebug Client**: Dễ dàng debug ứng dụng PHP của mình.  
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
 **Git là một công cụ để quản lý mã nguồn, nhưng tôi không phải là một coder nên tôi sẽ không sử dụng Git theo cách mà các coder hay sử dụng. Tôi sử dụng git và github để lưu trữ các file cấu hình của mình, các script, viết các bài hướng dẫn, các bản nháp,... Các repo là những nơi tôi phân loại, lưu trữ những thứ bên trên và nó được lưu cả ở máy trạm và ở server github. Để làm việc với repo thì bạn phải hiểu về nó. Một số điều bạn cần biết là:**  
 ![](https://www.bogotobogo.com/WebTechnologies/images/Git/Git_Local_Operations.png)  
 - **Committed**: file ở thư mục làm việc (working directory) đã đồng nhất với file được lưu trong local repository
 - **Modified**: file đang thay đổi
 - **Staged**: file thay đổi, được chuẩn bị để chốt hạ (commit) vào local repository lần tới. Nếu commit thành công, thì file lại chuyển về trạng thái Commited.   
 <a name = "timhieu"></a>  
  ## 1.Tìm Hiểu Các Khái Niệm
  ### 1.1.Repository. 
  *- Repository hay được gọi tắt là Repo, đơn giản là nơi chứa tất cả những thông tin cần thiết để duy trì và quản lý các sửa đổi và lịch sử của toàn bộ project. Trong Repo có 2 cấu trúc dữ liệu chính là Object Store và Index. Tất cả dữ liệu của Repo đèu được chứa trong thư mục bạn đang làm việc dưới dạng folder ẩn có tên là .git*  
  ![](https://4.bp.blogspot.com/-fC2tMlgfHXo/VTvNssnSP1I/AAAAAAAACWI/C6nTDooFOiE/s1600/git-repo.png)
  - Repository của Git được phân thành 2 loại là remote repository và local repository.  
    - Remote repository: Là repository dùng để chia sẽ giữa nhiều người và bố trí trên server chuyên dụng.  
    ![](https://2.bp.blogspot.com/-aBPG-ztqfk0/VTvHH59jZkI/AAAAAAAACVc/eXqR_iG3oys/s1600/basic-remote-workflow.png)
    - Local repository: Là repository ở trên máy tính của chính bản thân mình, dành cho một người dùng sử dụng.
  ### 1.2 Add, Pull, Push, Clone , Fetch , Commit , Fork , Star
  - **Add**: thao tác đẩy một tệp tin từ working directory vào staging area để chuẩn bị cho việc commit.
       - *git add "tên_file"*: dùng để add file chỉ định
       - *git add*:	dùng để add tất cả
       - *git add --all*:	dùng để add tất cả  
  - **Pull**: thao tác lấy mã nguồn từ một hoặc nhiều nhánh cụ thể nào đó ở remote server nào đó về local repository trên máy tính của bạn
  - **Push**: thao tác đẩy mã nguồn hiện tại đã được commit của bạn lên remote server.
  - **Clone**: thao tác tải mã nguồn từ một remote server về máy tính,chỉ tải về máy local repository nhánh master  
  - **Fetch**: cập nhật thay đổi từ repository server về repository local  
  - **Commit**: Ghi lại trạng thái thay đổi tại máy local (ví dụ như bạn có thể ấn Save nhiều lần với file README.md nhưng chỉ khi commit thì trạng thái của lần ấn Save cuối cùng trước đó mới được lưu lại) - tương ứng với câu lệnh git commit  
  - **Fork**: (khái niệm này trên GitHub) là hành động một người dùng khác copy một bản sao của repo về kho của họ. Trước khi tham gia vào một dự án của người khác thì bạn sẽ fork repo của họ và kho của mình nếu như người khác chưa cho phép bạn trở thành thành viên.  
  - **star**: có lẽ được nhiều người dùng như là một công cụ đánh dấu, nếu thấy project đó hay thì sẽ đánh dấu cái project đó lại bằng cách star nó một phát.  
  - **Remove**:Để remove một thư mục hay một file nào đó bạn có thể xóa ở máy local sau đó add và commit lại là xong.Nếu muốn xóa repo bạn vào repo đó trên server và chọn Delete this repository ở phần Setting. Đọc warning và chọn yes...  
  - **Watch**:Để thực hiện bạn chọn Watch trên repo mà bạn muốn và khi đó bạn sẽ nhận được thông báo cho các yêu cầu mới hay vấn đề gì xảy ra với repo đó.  
  <a name = "caidat"></a>  
 ## 2.Cài đặt git, Generate, add key SSH...  
 ### 2.1.Cài đặt Git  
 - Với HĐH là Ubuntu, Debian:
     > apt-get install git
 - Với HĐH là Fedora, CentOS
     > yum install git
 - Với Arch
     > pacman -S git
 
  
  
  
  
 
 
 

 


 

 
 ~~THE END~
 




 





