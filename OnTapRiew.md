11h-12h30

# 1. WEB101x_o1 : Hiểu cách thức hoạt động, cấu trúc và các thành phần của website

Hiểu môi trường hoạt động của trang web trên trình duyệt, cấu trúc trang web (file, thư mục, loại file, URL tương đối, tuyệt đối) và các thành phần của website (trang web, ảnh, media...)

## website là gì?

    Website là tập hợp các trang web đặt trê cùng 1 máy chủ trên internet và được liên kết với nhau

    - Các trang web(web page) là các trang HTML và các tài nguyên đa phương tượng ( văn bản , hình ảnh, video,..)
    - Khi các trang web được đưa lên mạng thì nó sẽ có 1 địa chỉ ỦL duy nhất
    - Trình duyệt (browser) là công cụ dùng để xem trang web

# 2. WEB101x_o2 :Hiểu được cú pháp HTML

Hiểu được cú pháp cơ bản cho các thành phần HTML như thẻ, thuộc tính, trình tự...

- mở đầu thường là <!DOCTYPE html> để khai báo là tài liệu html
- tiếp đến là thẻ <html> có 2 thẻ con là thẻ <head>(khai báo các thông tin trang web như tiêu đề, từ khóa, mô tả , nhúng các file css, font chữ,..) và thẻ <body> ( chứa nội dung chính của trang web bao gồm nhiều thẻ để cấu trúc các thành phần của 1 trang web, mổi thẻ đều có các attribute - thuộc tính và các property - đặc tính )

- Attribute : mỗi thẻ cần có các thuộc tính để cung cấp thông tin bổ sung về một phần tử, các attribute được đặt trong thẻ mở của mổi thẻ, thường đi theo cặp (name/value vd : name = "value").

# 3. WEB101x_o3 : Tạo được trang web (html) trên máy tính cá nhân và chạy thử được

    OK => tạo file có dạng.html ==> sau đó viết code => nhấn chạy bằng trình duyệt nào đó ==>ok

# 4. WEB101x_o4 : Tạo được trang web (html) trên một bộ soạn thảo online và chạy thử được

    OK

# 5. WEB101x_o5 : Chèn các thành phần HTML cơ bản vào trang web:

    Ok -> chèn được các thành phần cơ bản như các thẻ a, p , div, hay các thẻ video, img,..

# 6. WEB101x_o6 : Thiết lập được các thuộc tính thông tin cho trang web

    Thiết lập được các thuộc tính thông tin như :
    - <meta charset="UTF-8"> : để hổ trợ hiển thị tiếng việt
    - <meta name="viewport" content="width=device-width, initial-scale=1.0"> : dùng để hổ trợ hiển thị responsive cho trang web
    - <meta name="description" content="This is my project 1"> : dùng để mô tả nội dung chính của trang web nói về gì ?
    - <meta name="keywords" content=".."> : dùng để khai báo các từ khóa
    - <link rel="stylesheet" href="./css/main.css"> : dùng để nhúng các file khác từ bên ngoài , ví dụ file .css hay các font chữ google..
    - style : để viết css ngay bên trong file .html

# 7. WEB101x_o7 : Thiết lập được mã encoding tiếng Việt cho trang web

    @ ASCII - tiêu chuẩn mã hóa đầu tiên - 128 ký tự
    @ UTF-8 - 256 ký tự
    Để hiển thị trang HTML một cách chính xác, trình duyệt web phải biết bộ ký tự được sử dụng trong trang. Cái này được chỉ định trong tag <meta>
    ```
    <meta charset="UTF-8">
    ```

# 8. WEB101x_o8 : Biết cách sử dụng thành phần container phù hợp cho nội dung

    Tức là thành phần block, inline , inline-block

## Block :

    - Một phần tử cấp khối luôn bắt đầu trên một dòng mới và chiếm toàn bộ chiều rộng có sẵn
    - Lưu ý thêm là chúng ta có thể tác động là thay đổi trực quan khi tác động vào thuộc tính padding , margin : top,left,right,bottom ( tức là cho phép thiết lập chiều cao, chiều rộng của phần tử)

## Inline :

    - Một phần tử nội tuyến không bắt đầu trên một dòng mới và nó chỉ chiếm đủ chiều rộng cần thiết , khi các phần tử khối đặt cạnh nhau chúng sẽ ở trên 1 dòng nếu còn đủ chiều rộng khoảng trống
    - Lưu ý thêm là ta không thể tác động làm thay đổi trực quan khi tác động vào các tính chất padding , margin : top à bottom ( tức là chỉ cho phép thiết lập chiều rộng của phần tử chứ không cho phép thiết lập chiều cao của phần tử)

## Inline-block :

    - Giống inline vì không bắt đầu trên 1 dòng mới , đặt cạnh nhau trên cùng 1 dòng
    - Giống Block vì chúng ta có thể tác động và thiết lập được chiều cao lẫn chiều rộng của phằn tử
    - Hay dùng để làm thanh điều hướng cho các phần tử li, a trên menu==> tăng chiều cao ==> tăng khả năng click cho người dùng

# 9. WEB101x_o9 : Đưa được các thành phần media vào trang web

    OK=> đưa được các thành phần media vào trang web , như img , video ( html5 hổ trợ)
    vd: <img src = "nguồn" alt = "thông tin về ảnh">

# 10. WEB101x_o10 : Đưa được các thành phần cấu trúc nội dung của trang web

     ví dụ các thẻ định dạng danh sách, bảng như ul, ol, li, table, tr,th,td,..

# 11. WEB101x_o11 : Thay đổi được kích thước, định dạng ảnh

    Thay đổi được kích thước định dạng ảnh thông qua các phần mền photo,..

# 12. WEB101x_o12 : Nhúng được trang web từ các dịch vụ khác

    ví dụ : iframe
    - Thẻ iframe được dùng để hiển thị một trang web khác bên trong một trang web
    - Thẻ iframe có các thuộc tính cơ bản sau :
    	- src : nguồn của trang web đó , hay file tài liệu html dẫn đến trang web đó
    	- title : tiêu đề
    	- height , width : các thuộc tính về chiều cao, rộng ,..
    - Lưu ý: đã sử dụng để nhúng định vị bản đồ google map vào trang web qua Project 4

# 13. WEB101x_o13: Nguyên tắc thiết kế web

## Những nguyên tắc cơ bản trong thiết kế web

- Thiết kế trực quan hóa: có tính thẳm mỹ , ưa nhìn
- Thiết kế cũng liên quan đến chức năng à đảm bảo rằng thong tin được truyền tải rực quan và hiệu quả nhất có thể

## Composition ( bố cục ):

- Một bố cục rối: các phần tử của trang được sắp xếp lộn xộn, khó để biết cần phải tập trung và chổ nào
- Mộ bố cục rõ ràng : có nghĩa là được đơn giản hóa và dể dàng để xứ lý về mặt trực quan

## Hierarchy ( phân cấp ):==> thu hút

hỉ sự phân chia các yếu tố quan trọng, tổ chức về kích thước, màu sắc trên trang web

## Negative Space ( Không gian trống ):

Tức không quá nhồi nhét thông tin mà cần có các khoảng trống phù hợp sẽ giúp trang web bắt mắt và khoa học hơn, ví dụ khoảng cách giữa các chữ, các đoạn văn các dòng phù hợp hay các phần với nhau cũng phải phù hợp

# 14. WEB101x_o14 : Hiểu cơ bản về HTML5

    HTML5 được phát triển trên nền tảng HTML hay nâng cấp từ nó , HTML5 hổ trợ tối đa cho các phương tiện nhưng vẫn giúp trang web thân thiện với người dùng trên mọi thiết bị, trình duyêt

    - Một điểm cơ bản nhất về HTML 5 là về các element : HTML5 bổ sung rất nhiều thẻ mới và quan trọng như: audio, video, header, footer, secton,.. ( các thẻ ngữ nghĩa và hổ trợ thêm các thẻ media như video , âm thanh) và loại bỏ một số thẻ lỗi thời như thẻ : dir, big, font ,...

    - Các thẻ ngữ nghĩa : Một phần tử ngữ nghĩa mô tả rõ ràng ý nghĩa của nó cho cả trình duyệt và các nhà phát triển.
    	- các thẻ như div, span, ... không nói lên điều gì về nội dung của nó
    	- Các thẻ ngữ nghĩa như form, table, header, footer định nghĩa rõ nội dung của nó
    	- Ví dụ về 1 số thẻ ngữ nghĩa

## Tại sao phải sử dụng các phần tử ngữ nghĩa ?

    Trong HTML4, ta hay sử dụng các thuộc tính id, class kết hợp vs các thẻ div để định nghĩa các vùng của trang web. Tuy nhiên, điều này làm các cơ chế tìm kiếm (google) không thể nhận diện được nội dung, cấu trúc của trang dể dàng. Do đó, HTML5 ra đời và chứa các phần tử ngữ nghĩa giúp giải quyết vấn đề này, Theo W3C thì một web ngữ nghĩa: " cho phép dữ liệu được chia sẻ và tái sử dụng ở nhiều ứng dụng, doanh nghiệp và cộng đồng "

# 15. WEB101x_o15 : Sử dụng được các thành phần media của HTML5

==> Hướng dẫn sử dụng những thành phần media cơ bản nhất (video, audio, media)

## video:

==> để hiển thị video

```
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
Your browser does not support the video tag.
</video>
```

- Thuộc tính controls để điều khiển video : như các nút bấm âm lượng , dừng , play,..
- phần tử source dùng để chỉ định các dile video thay thế mà trình duyệt có thể chọn. Trình duyệt sẽ chọn nguồn đầu tiên nếu k đáp ứng được sẽ lượng chnj xuống các nguồn tiếp theo
- Thuộc tính autoplay: tự động phát video
- Thuộc tính muted : câm - dùng để tắc âm thanh video
- Thuộc tinh src : chỉ định nguồn file video

## audio

tương tự như video

# 16. WEB101x_o17 : Hiểu cú pháp định nghĩa CSS

==> Các thành phần và cú pháp định nghĩa các thuộc tính CSS, cách thức tra cứu các thuộc tính này

## CSS là gì?

    CSS là viết tắng của cụm từ Cascading Style Sheet là ngôn ngữ để tạo style cho 1 trang web, nó giúp mô tá các phần tử HTML sẽ hiển thị như thế nào trên 1 trang web

## Cú pháp CSS

==> Một bộ quy tắc CSS bao gồm một bộ chọn (selector) và một khối khai báo ( được đặc bên trong cặp dấu ngoặc nhọn {..})

- Bộ chọn (selector) chỉ tới các phần tử HTML mà ta muốn áp dụng để khao báo các style cho chúng
- Khối khai báo : bao gồm một hoặc nhiều mô tả phân tách nhau bằng dấu chấm phẩy

vd:

```
h1{
	color: red;
	font-size: 48px;
}
```

# 17. WEB101x_o17 : Biết cách sử dụng CSS selector

==> Phân biệt được các loại selector cho tag, id, class, nested element

## CSS selector ( bộ chọn css )

==> Bộ chọn được sử dụng để tìm chọn các phần tử HTML mà ta muốn tạo style
==> Chúng ta có thể chia các bộ chọn thành 5 loại chính đó là :

    - Bộ chọn đơn giản ( chọn các phần tử dựa trên tên thẻ, id, class)
    - Bộ chọn kết hợp : chọn các thẻ dựa trên mối quan hệ giữa chúng
    - Bộ chọn lớp giả : chọn các phần tử dựa trên một trang thái nhất định
    - Bộ chọn phần tử giả : chọn và tạo kiểu cho một phần tử giả
    - Bộ chọn thuộc tính : chọn các phần tử dựa trên một thuộc tính hoặc giá trị thuộc tính

    @ Lưu ý: có bộ chọn toàn cục dấu (*) chọn tất cả các phần tử HTML

## Một số dạng selector :

- dấu `cách` : chọn các con cháu ( hậu duệ ), lồng bên trong
- dấu `+`: chọn anh em kế cận
- dấu `~`: chọn anh em đồng cấp
- dấu `>`: chọn con trực tiếp
- dấu `,`: chọn nhiều phần tử cùng lúc
- trong class : đặt gần nhau ví dụ: .class1.class2 ==> chọn phần tử có cả class1 và class2
- [class*='ok']: chọn tất cả các phần tử có class có tên chứa 'ok'
- ... còn nhiều nữa , tự xem thêm sau !

# 18. WEB101x_o18 : Hiểu và áp dụng coding convention cho việc đặt tên file, CSS selector

==> Biết cách áp dụng nguyên tắc coding convention cơ bản nhất trong việc đặt tên file HTML, CSS, đặt tên CSS selector

==> ok, ví dụ về tiêu chuẩn BEM ( block element model ) , đặt tên class bằng chữ thường, nối dâu bởi gạch nối, ngữ nghĩa đúng với chức năng của nó

# 19. WEB101x_o19 : Biết cách áp dụng các thuộc tính định dạng cơ bản của text :

==> OK , xem thêm lại lý thuyết về các thẻ, các property của dạng text, ví dụ:

- color : màu
- text-align : canh chỉnh
- text-decoration : ví dụ: underline , .. để chỉ định gạch chân ,.
- text-transform : điều chỉnh chữ cái trong văn bản sang dạng chữ hoa hay thường
- text-indent : thụt lề , vd: 50px
- line-height: chiều cao dòng , vd: 30px
- letter-spacing: khoảng cách chữ , vd: 10px
- word-spacing: khoảng cách từ , vd: 20px
- text-shadow: tạo bóng cho văn bản, vd: text-shadow: 2px 2px 3px red; ( ngang - dọc - tỏa đều - màu sắc)
- ...

# 20. WEB101x_o20 : Biết cách định dạng cơ bản với ảnh

==> Định dạng ảnh nền, kích thước...
ok

# 21. WEB101x_o21 : Cách nhúng mã CSS trong trang web dạng inline ( nội tuyến bên trong thẻ )

==> Thiết lập định dạng trực tiếp trong thẻ HTML : ok

# 22. WEB101x_o22 : Cách nhúng mã CSS trong trang web dạng internal ( nội bộ)

==> Định nghĩa phần style ở thẻ <style> trong thẻ <head> : ok

# 23. WEB101x_o23 : Cách đưa mã CSS ra file riêng dạng external

==> Đưa định nghĩa style ra file .css để tách biệt mã cấu trúc HTML và mã trình bày CSS :ok
Nhúng file .css qua thẻ link có href chỉ đến file .css

# 24. WEB101x_o24 : Cách định kiểu một phần tử HTML

==> Đề cập sâu hơn về cách định kiểu dạng inline và id cho một phần tử HTML

==> xét đến độ ưu tiên định kiểu: selector qua tên thẻ --> selectro qua class (nhớ là cái nào khai báo sau sẽ ghi đè cái ghi trước)--> selector qua ID--> dạng style nội tuyến bên trong thẻ mở --> sử dụng !important

# 25. WEB101x_o25 : Cách định kiểu cho nhiều phần tử cùng loại dạng

==> Đề cập sâu hơn về cách định kiểu dạng class cho nhiều phần tử HTML cùng loại
==> ok --> các bộ chọn selector

Có các tổ hợp khác nhau trong CSS:

công cụ chọn hậu duệ - hậu duệ chọn bộ (dấu cách) ==> tất cả con cháu chắc chút chít , sâu bên trong
bộ chọn con - con selector (>) ==> tất cả các con cấp 1
Bộ chọn anh chị em kế cận - bộ chọn anh em kế cận (+) ==> phần tử đầu tiên liền kề
bộ chọn anh em chung - bộ chọn anh em chung (~) ==> tất cả sau

Selector Ví dụ Mô tả ví dụ
element element div p Chọn tất cả các phần tử <p> bên trong các phần tử <div>
element>element div > p Chọn tất cả các phần tử <p> là con của phần tử <div>
element+element div + p Chọn phần tử <p> đầu tiên được đặt ngay sau các phần tử <div>
element1~element2 p ~ ul Chọn tất cả các phần tử <ul> ở sau một phần tử <p>

Chú ý:
p ~ ul : chọn tất cả thẻ ul ở sau 1 phần tử p
div + p : chọn phần tử p ssaauf tiên đặt ngay sau các phần tử div

# 26. WEB101x_o26 : Hiểu và sử dụng Box model

==> Thay đổi các thành phần liên quan đến Box Model như margin, padding, border

# 27. WEB101x_o27 : Thêm khả năng responsive cho trang

==> Khả năng trang phản ứng lại thay đổi kích thước của trang web. Thích hợp cho trang khi thiết kế hiển thị trên cả thiết bị mobile

# 28. WEB101x_o28 : Cách tạo bố cục 2 cột cho trang web

==> Tạo bố cục phân trang web thành 2 phần cột nội dung. --> ok

# 29. WEB101x_o29 : Cách tạo bố cục 3 cột cho trang web

==> Tạo bố cục phân trang web thành từ 3 phần cột nội dung trở lên.. --> ok

# 30. WEB101x_o30 : Cách sử dụng một thư viện CSS cho trang web

==> Hiểu để có thể tự nghiên cứu, áp dụng những ví dụ cơ bản nhất. Ví dụ dùng framework bootstrap

# 31. WEB101x_o31 : Hiểu cơ bản về CSS3

==> Hiểu những nâng cấp của CSS3 so với CSS2, mức cơ bản để sinh viên có thể tự nghiên cứu nếu quan tâm

CSS3 chứa tất cả mọi thứ có trong CSS2.1 (phiên bản trước). Nó cũng bổ sung các tính năng mới để giúp các nhà phát triển giải quyết một số vấn đề mà không cần đánh dấu phi ngữ nghĩa, tập lệnh phức tạp hoặc hình ảnh bổ sung.

## Sự khác nhau giữa CSS và CSS3

Thay đổi lớn nhất hiện của CSS3 là việc giới thiệu các mô-đun. Ưu điểm của các mô-đun là ​​cho phép thuộc tính được hoàn thành và phê duyệt nhanh hơn vì các phân đoạn được hoàn thành và được phê duyệt theo từng khối.

Các tính năng được bao gồm trong CSS3 bao gồm hỗ trợ cho các bộ chọn bổ sung, đổ bóng, góc tròn, nhiều hình nền, hình động, độ trong suốt ..vv... Nó chứa “thuộc tính CSS” (đã được chia thành các phần nhỏ hơn). Ngoài ra còn có các mô-đun mới được thêm vào. Một số mô-đun quan trọng nhất trong CSS3 là:

- Bộ chọn
- Mô hình hộp
- Hình nền và đường viền
- Giá trị hình ảnh và nội dung thay thế
- Hiệu ứng văn bản
- Chuyển đổi 2D / 3D
- Ảnh động
- Bố cục nhiều cột
- Giao diện người dùng

[đọc thêm trong trang web sau](https://sukhacnhau.com/may-tinh-va-internet/su-khac-nhau-giua-css-va-css3/)

# 32. WEB101x_o32 : Sử dụng CSS3 cho một số thao tác động

==> Khai thác và ứng dụng một số tính năng hữu ích (transition, animation) được bổ sung trong CSS3

đọc thêm trên w3s

# 33. WEB101x_o33 : Sử dụng công cụ Developer trên trình duyệt

==> Dùng để dò mã, debug và test trang web -->ok

# 34. WEB101x_o34 : Đăng ký domain và hosting

==> Cách thức đăng ký domain và hosting cho cả trường hợp trả phí và miễn phí
