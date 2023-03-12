# HTML

HTML (viết tắt của từ HyperText Markup Language, hay là "Ngôn ngữ Đánh dấu Siêu văn bản")
là một ngôn ngữ đánh dấu được thiết kế ra để tạo nên các trang web trên World Wide Web.

## Tag `<img>`

```
<img src ="..." alt =" chỉ định đoạn văn bản thay thế cho hình ảnh">
```

## Tag` <a>`

```
<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>
```

- \_target: chỉ định nơi mở tại liệu được liên kết, có các giá trị sau:

- \_self - Mặc định. Mở tài liệu trong cùng một cửa sổ / tab khi nhấp vào

* \_blank - Mở tài liệu trong cửa sổ hoặc tab mới

* \_parent - Mở tài liệu trong parent frame

* \_top - Mở tài liệu trong toàn bộ phần nội dung của cửa sổ

## Tags list element:

1. `<ul>`:Xác định một danh sách không có thứ tự

2. `<ol>`: Xác định một danh sách có thứ tự

3. `<li>`: xác định một item trong danh sách

4. `<dl>` (description list) : xác định danh sách mô tả ! Note

5. `<dt>` : Xác định một thuật ngữ trong danh sách mô tả

6. `<dd>` (defines description): mô tả một thuật ngữ trong danh sách mô tả

vd:

```
<dl>  <!-- tạo 1 danh sách mô tả -->
  <dt>Coffee</dt> <!-- Thuật ngữ -->
  <dd>Black hot drink</dd> <!-- Mô tả của thuật ngữ -->
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>

```

Output:

```
Coffee
	Black hot drink
Milk
	White cold drink

```

Các thuộc tính quan trọng:

- list-style-type:square (hiển thi hình vuông-square đầu danh sách)

* type="A"/ "I": hiển thị các chữ cái hoa/số la mã đầu dòng thay vì chữ thường

## Table tag:

vd:

```
<table>
		<tr>
			<th>Name</th>
			<th>Age</th>
			<th>Adress</th>
		</tr>
		<tr>
			<td>Ho Tan Nhut</td>
			<td>24</td>
			<td>abc@gmail.com</td>
		</tr>
		<tr>
			<td>Ho Tan Nhut</td>
			<td>24</td>
			<td>abc@gmail.com</td>
		</tr>
	</table>
```

note:

- `<table>`: (table) Defines a table
- `<th>`: (table header) Defines a header cell in a table
- `<tr>`: (table row) Defines a row in a table
- `<td>`: (table data) Defines a cell in a table

## Block element:

Một phần tử mức cấp khối luôn luôn bắt đầu trên một dòng mới, và các trình duyệt sẽ tự động thêm khoảng trắng (lề) trước và sau phần tử.
Một phần tử cấp khối luôn chiếm toàn bộ chiều rộng có sẵn (trải dài sang trái và phải hết mức có thể).

Here are the block-level elements in HTML:

```
<address> <article>  <aside> <blockquote> <canvas> <dd> <div> <dl> <dt>
<fieldset> <figcaption> <figure> <footer> <form> <h1>-<h6> <header> <hr> <li> <main> <nav> <noscript> <ol> <p> <pre> <section> <table> <tfoot> <ul>  <video>
```

## Inline Elements:

Một phần tử nội tuyến không bắt đầu trên một dòng mới.

Một phần tử nội tuyến chỉ chiếm đủ chiều rộng cần thiết.

Here are the inline elements in HTML:

```
<a> <abbr> <acronym> <b> <bdo> <big> <br> <button>	<cite>
<code> <dfn> <em> <i> <img> <input> <kbd> <label> <map> <object> <output> <q> <samp> <script> <select> <small> <span> <strong> <sub> <sup> <textarea> <time> <tt><var>
```

## Tag `<spam>`:

để đánh dấu văn 1 phần văn bản hay 1 phần tài liệu trong 1 đoạn (thongwf dụng để CSS rieng cụm văn bản đó)

## Tag `<ifram>`:

Là thẻ chỉ định 1 khung nội tuyến sử dụng để nhúng tài liệu khác vào tài liệu hiện tại

vd:

```
<iframe src="demo_iframe.htm" height="200" width="300" title="Iframe Example"></iframe>

```

hoặc tương tự dùng style:

```
<iframe src="demo_iframe.htm" style="height:200px;width:300px;" title="Iframe Example"></iframe>

```

Một iframe có thể được sử dụng như khung đích cho một link.
Thuộc tính target của link phải được tham chiếu tới thuộc tính name của iframe:

```
<iframe src="demo_iframe.htm" name="iframe_a" title="Iframe Example"></iframe>

<p><a href="https://www.w3schools.com" target="iframe_a">W3Schools.com</a></p>
```

# CSS

CSS stands for Cascading Style Sheets (các cay đin - sờ tai- ships) : là ngôn ngữ để tạo
style cho 1 trang web.
CSS mô tả phần tử HTML sẽ được hiển thị như thế nào trên màn hình, giấy, hoặc các phương tiện khác.

inline stylesheet ( nội tuyến)
internal stylesheet(nội bộ , đặt trong thẻ style ở trong thẻ head)
external stylesheet (từ bên ngoài )

## Background:

1. background-color :

```
div {
  background-color: green;
  opacity: 0.3;
}
```

2. background-image

```
body {
  background-image: url("bgdesert.jpg");
}
```

3. background-repeat:

`background-repeat: repeat-x;` : hình nền lặp lại theo chiều ngang
`background-repeat: repeat-y;` : hình nền lặp lại theo chiều dọc
`background-repeat: no-repeat;` : hình nền k lặp 4. ebackground-attachment

5. background-position:

`background-position: right top;` : định vị vị trí của hình nền.

6. background-attachment:

Dùng để chỉ định hình nền có cuộn theo nội dung khác khi cuộn chuột hay không.
`background-attachment: fixed;` : cố định, không cuộn theo chuột.
`background-attachment: scroll;`: cuộn theo chuột

7. background:

```
body {
  background: #ffffff url("img_tree.png") no-repeat right top;
}
```

Khi sử dụng thuộc tính viết tắt, thứ tự của các giá trị thuộc tính là:

background-color
background-image
background-repeat
background-attachment
background-position

## color:

```
div {
  background-color: blue;
  color: white;
}
```

## text-align:

1. text-align: left|center|right|justify
2. text-align-last: left|center|right|justify ==> căn chỉnh dòng cuối cùng của văn bản

XEM THÊM CÁC THUỘC TÍNH SAU TRÊN W3SCHOOL

3. direction 4. unicode-bidi 5. vertical-align

## font:

1. font-family:

```
p {
font-family: Tahoma, Verdana, sans-serif;
}
```

2. font-style:

có các giá trị sau:

- normal : bình thường
- italic" in nghiên
- ...

3. font-weight:

thuộc tính độ dày cuiar chữ, có các giá trị sau:

```
 font-weight: normal;
```

```
font-weight: bold;
```

3. font-size:

độ lớn của chữ.

## google font:

Chỉ cần link đường link font của google vào trong thẻ head

```
<head>
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Sofia">
<style>
body {
  font-family: "Sofia", sans-serif;
}
</style>
</head>
```

## font:

```
p.b {
  font: italic small-caps bold 12px/30px Georgia, serif;
}
```

The font property is a shorthand property for:

font-style
font-variant
font-weight
font-size/line-height
font-family

## CSS selector:

Có bốn combinator khác nhau trong CSS:

1. descendant selector - bộ chọn hậu duệ (dấu cách)
2. child selector - bộ chọn con (>)
3. adjacent sibling selector - bộ chọn anh em kế cận (+)
4. general sibling selector - bộ chọn anh em chung (~)

## link

Bốn trạng thái link là:

a:link - một link bình thường, không được truy cập
a:visited - một link mà người dùng đã truy cập
a:hover - một link khi người dùng di chuột qua nó
a:active - một link ngay khi nó được click vào

```
/* unvisited link */
a:link {
  color: red;
}

/* visited link */
a:visited {
  color: green;
}

/* mouse over link */
a:hover {
  color: hotpink;
}

/* selected link */
a:active {
  color: blue;
}
```

a:hover PHẢI đi sau a:link và a:visited
a:active PHẢI đi sau a:hover

## CSS list:

1. list-style-type: chỉ định các kiểu đánh dấu mục trong danh sách.

```
ul.a {
  list-style-type: circle;
}

ul.b {
  list-style-type: square;
}

ol.c {
  list-style-type: upper-roman;
}

ol.d {
  list-style-type: lower-alpha;
}
```

## CSS table:

1. border-collapse : chir định các đường viền bảng có được thu gọn thành 1 đường viền duy nhất hay không.

## Sự khác nhau giữa block , inline-block , inline:

### display: inline

- Các phần tử có display inline nằm cạnh nhau sẽ hiển thị trên một hàng ngang
- Không thể tác động vào padding-top, padding-bottom , margin-top, margin-bottom của phần tử
- Thẻ mặc định inline : a, span, b, i,...

chú ý :

- nó k tác động lên , nhưng khi có background color: thì nó vẫn tô màu nhưng k chiếm đi không gian trên dưới, tức k đẩy các phần tử trên và dưới của nó xa ra
- tức là : các nói không tác động lên trên và dưới tức là nó k chồng lên các phần tử khác, k chiếm diện tích của các phần tử khác chứ thật ra nó vẫn có

![inline](./NOTE_imgs/inline%2Cblock%2Cinline-block%201.png)

### display: block

- Các phần tử display block sẽ chiếm không dang và nằm một mình trên 1 hàng
- Có thể tác động vào padding, margin (top bottom left right) của phần tử
- Thẻ mặc định block: div, h1->h6, p, section, nav,..

### display: inline-block

- Các phần tử có display inline-block khi ở gần nhau sẽ nằm trên 1 hàng ==> giống inline
- Có thể tác động lên padding margin (top bottom left right)==> giống block

### Kinh nghiệm :

- Khi xây dựng menu chúng ta nên cho thẻ a là display inline-block để tăng không gian người dùng có thể nhấp chuột
- Nắm vững để thực hành và trả lời phỏng vấn xin việc

## Sự khác nhau giữa margin và padding :

Chú ý: box-sizing: border-box : là đảm bảo rằng border, padding luôn cộng vào kích thước mình đặt ra , tức : border vs padding thay đổi thì phần content sẽ thu nhỏ phóng to lại để đảm bảo kích thước của pần tử là cố định như ban đầu chúng ta đã đặt

- padding : phần đệm, là khoảng cách giữa phần nội dung và đừng viền (border)
- border : là đường viền bao quang bên ngoài padding
- marging : phần lề , là phần khoảng cách giữa phần tử với các phần tử xung quanh

LƯU Ý:

- padding và border sẽ được tính vào kích thước của phần tử ( ví dụ: muốn tăng độ lớn của thẻ a để user di chuột vào được dể dàng hơn thì ta dùng padding cho nó rộng lên để răng kích thước cho thẻ a, người dùng sẽ dể dàng click trúng phần tử a hơn )
- margin sẽ không được tính vào kích thước của phần tử ( ví dụ: muốn tăng khoảng cách giữa phần tử này với phần tử khác ta sẽ margin để làm tăng khoảng cách của nó vs phần tử khác )

## Hiểu hơn về float , clear:

- clear: both tạo điểm dừng để ngắt float , và đảm bảo rằng các phần tử con bên trong đang float nó sẽ luôn nằm trong phần tử cha, dù chiều dài, rộng có thay đổi

## Hiểu rõ về position: relative, assolute

1. Relative:
   Giá trị thuộc tính này sẽ dựa trên chính nó làm gốc tọa độ để định vị
   Lưu ý là : khi định vị nó đi cách trên dưới trái phải gì đó thì nó vẫn chiếm vị trí ban đầu của nó và sẽ không cho phần tử khác chiếm lấy phần không gian đó , mặc dù nó đã di chuyển sang chổ khác, và khi di chuyển sang vị trí khác với vị trí ban đầu ấy , thì thật sự nó cũng k chiếm không gian chổ đó mà nó chiếm không gian lúc đầu, nó giống như kiểu được đẩy lên lớp trên và đè lên phần tử khác chứ k chiếm không gian của các phần tử mà đẩy các phần tử khác ra để chiếm lấy không gian

2. Absolute:
   Giá trị thuộc tính này sẽ dựa vào phần tử cha gần nhất của nó có thuộc tính position ( bất kể giá trị là gì : relative, absolute hay fixed đều được) để làm tọa độ định vị trí.
   Lưu ý là : khi định vị thì nó sẽ k chiếm khoảng không gian nào cả, kiểu nó sẽ lên 1 tầng lớp trên và đè lên các tầng lớp dưới nó theo định vị của tọa độ nói trên chứ nó k chiếm không gian nào cùng cấp với các phần tử khác, mà nó sẽ được nổi lên ở 1 tầng khác

## Box model:

Content - nội dung của hộp, nơi xuất hiện văn bản và hình ảnh.
Padding - khoảng cách giữa nội dung và đường viền (border). Padding là trong suốt.
Border - đường viền bao quanh padding và nội dung.
Margin - không gian bên ngoài border (khoảng cách giữa border và các thành phần khác bên ngoài. Margin là trong suốt.

## Outline:

Outline là một đường bao xung quanh phần tử, bên ngoài đường viền, để khiến cho phần tử "nổi bật".

CSS có những thuộc tính outline dưới đây:

outline-style
outline-color
outline-width
outline-offset
outline

Lưu ý: Outline khác với đường viền! Không giống như đường viền, outline được vẽ bên ngoài đường viền của phần tử và có thể chồng chéo lên các nội dung khác. Ngoài ra, outline KHÔNG phải một phần kích thước của phần tử; tổng chiều rộng và chiều cao của phần tử không bị ảnh hưởng bởi chiều rộng của outline.

chú ý:

outline-offset: tính thêm khoảng cách giữa đường viền và cạnh / đường viền của một phần tử. Khoảng cách giữa một phần tử và đường viền của nó là trong suốt. Tức là nó tính thêm khoảng cách giữ đường vền và cộng thêm 1 khoảng , sau đó mới đổ màu tạo cho outline.

```
p {
  margin: 30px;
  background: yellow;
  border: 1px solid black;
  outline: 1px solid red;
  outline-offset: 15px;
}
```

## float:

Thuộc tính float float được dùng để chỉ định vị trí và định dạng nội dung, ví dụ như đặt hình ảnh ở bên trái văn bản trong vùng chứa.

## Display: flex

Học thêm qua đường link sau ( sẽ có cái nhìn trực quan hơn về Flex)

[Link học về Display: flex](https://codepen.io/enxaneta/full/adLPwv/)

Hay dùng thay cho float để thiết kế nhanh các phàn tử
muốn dùng ta cần có 1 thẻ div (container) bao quanh các phần tử bên trong là ( item )
Nó có các giá trị thuộc trính hay dùng sau :

### flex-direction (dùng cho container)

Là thuộc tính giúp xác định các phàn tử item xếp theo hàng hay cột

- row (mặc định) : xếp các phần tử bên trong theo hàng
- row - reverse : cũng theo hàng nhưng mà ngược lại với thứ tự mà nó được viết ra tức là anh viết ra cuối cùng sẽ xuất hiện đầu dòng và anh viết đầu tiên sẽ ở cuối dòng
- column : xếp các phần tử bên trong theo cột
- column- reverse: tương tự nhưng ngược thứ tự

### flex-wrap (dùng cho container)

Là thuộc tính giúp xác định sự đổ xuống của các phần tử khi nó bị tràng về chiều rộng hoặc cao

- nowrap (mặc định) : không tự động xuống hàng (hoặc cột) khi bị tràn
- wrap : xuống hàng (cột) khi nó bị tràng, nổi xuống vd : 12345 ==> 123 ( hàng dưới là : 45)
- wrap-reverse : xuống hàng (cột) nhưng là nổi lên vd: 12345 ==>45 (hàng dưới là 123)

### justify-content (dùng cho container)

Là thuộc tính giúp căn chỉnh các item theo chiều ngang

- flex-start: căn về hướng điểm bắt đầu (thường là bên trái vs hàng và bên trên với cột)
- flex-end: căn về hướng kết thúc
- space-between: căn về 2 bên
- center: căn giữa
- space-around: căn các item cách đều nhau 1 khoảng ( 2 bên sẽ cách 1 khoảng bằng 1 nữa khoảng cách của 2 item )

### align-content (dùng cho container)

Tương tự như justify-content nhưng mà là căn chỉnh trên chiều dọc

### align-items (dùng cho container)

Tự tìm hiểu thêm

### align-self (dùng cho item)

Là thuộc tính áp dụng lên mỗi item riêng biệt giúp căn chỉnh them chiều dọc , cũng có các giá trị tương tự như align-content

### justify-felf (dùng cho item)

Là thuộc tính áp dụng lên riêng biệt mỗi item, cũng có các giá trị giống justify-content

### flex-basis (dùng cho item)

xác định khoảng không gian trên chiều ngang (dọc) mà phần tử ấy chiêm
hay dùng dạng viết tắt là:

flex: 1;

### flex-order (dùng cho item)

Là thuộc tính xác định thứ tự xuất hiện của phần tử theo thứ tự từ star đên end

vd: ta muốn phần tử đầu tiên xuất hiện ở vị trí số 2 chứ k phải số 1 thì ta dùng flex-order:2 để nó xuất hiện ở vị trí thứ 2 (khi ấy cái số 2 sẽ ở vị trí đầu )

## Các lưu ý khác :

- text-indent: để thụt lề dòng đầu tiên của văn bản
- font-style : kiểu của font chữ , vd : italic (in nghiên)
- font-weight : ddppj dày của chữ , vd: bold hoăc 100 200 ..900
- font-variant : xác định đoạn văn được in chữ hoa nhỏ hay không
  ( thông thường khi in hoa kích thước sẽ to hơn bình thường)
  có các giá trị : normal small-caps(chữ hoa nhỏ) initial inherit(thừ kế từ cha nó)
- list-style-image : chỉ định phần đánh dấu list là 1 hình ảnh nào dó
  ( truyền vô url("..") )

# HTML5:

Là phiên bản mới nhất của của ngôn ngữ HTML.

- Hiểu cơ bản về HTML5.
- Sử dụng được các thành phần media của HTML5.

có hổ trợ socket , các thẻ đa phương tiện như video,audio,... mô hình API

HTML k phân biệt hoa thường, nhưng HTML5 thì chỉ sử dụng chữ thường.

## Các phần tử semantic (ngữ nghĩa) trong HTML:

Ví dụ về các phần tử phi ngữ nghĩa : <div> và <span> - không nói lên điều gì về nội dung của nó.

Ví dụ về các phần tử ngữ nghĩa : <form>, <table>, và <article> - định nghĩa rõ ràng nội dung của nó.

Nhiều trang web chứa mã HTML như: <div id="nav"><div class="header"><div id="footer"> để chỉ ra phần điều hướng (navigation), phần đầu trang (header) và chân trang (footer).

Trong HTML, có một số phần tử ngữ nghĩa có thể dùng để định nghĩa các phần khác nhau của một trang web:

- <article> : 
  chỉ ra 1 nội dung động lập , không phụ thuộc, thường có ý nghĩa riêng và 
         có thể phân phối độc lập với phần còn lại của trang.

  Ta hay sử dụng <article> ở :bài đăng (post) diễn đàng, bài đăng blog, bình luận của người dùng, thẻ mô tả sản phẩm, bài báo.

  chú ý:
  Lồng <article> trong <section> hoặc ngược lại?
  Phần tử <article> chỉ ra nội dung độc lập, không phụ thuộc.
  Phần tử <section> xác định một section trong một văn bản.
  Liệu chúng ta có thể sử dụng các định nghĩa để quyết định cách lồng những phần tử đó?
  `KHÔNG`, chúng ta không thể!
  Bạn cũng sẽ tìm thấy các trang có các phần tử <section> chứa các phần tử <article> , và các phần tử <article> chứa các phần tử <section>.

- <aside>: (QUA MỘT BÊN)
  Phần tử <aside> xác định một số nội dung mà nó được đặt bên trong ( như một thanh sidebar- thanh bên)

  Nội dung <aside> nên liên quan gián tiếp đến nội dung xung quanh.

- <details>
- <figcaption>:
  Xác định phụ đề cho <figure>.Phần tử <figcaption> có thể được đặt làm phần tử con đầu tiên hoặc cuối cùng của phần tử <figure>.
  Phần tử <img> xác định hình ảnh / hình minh họa thực tế.
- <figure> :
  chỉ định nội dung độc lập, như hình minh họa, sơ đồ, ảnh,danh sách mã,...
- <footer>:
  Phần tử <footer> chỉ ra phần chân trang cho một văn bản hoặc một section (phần)

  một phần tử <footer> thường bao gồm :

  - thông tin về quyền tác giả
  - thông tin bản quyền
  - thông tin liên lạc
  - sitemap ( sơ đồ trang )
  - quay lại liên kết trên đầu
  - tài liệu liên quan

- <header>:
  Phần tử header đại diện cho 1 container(bộ chứ) cho nội dung
  giới thiệu hoặc một tập hợp các liên kết điều hướng

  Một phần tử <header> thường bao gồm

  - một hoặc nhiều phần tử tieu đề (h1-h6)
  - logo hoặc icon
  - thông tin về quyền tác giả

- <main>:
  Chỉ định nội dung chính của tài liệu
- <mark>
- <nav>:
  Phần tử <nav> xác định một tập hợp các liên kết điều hướng
- <section> : 
  xác định 1 section ( 1 phần ) trong tài liệu:
    Hay dùng cho các phần : chương, giới thiệu, mục tin tức, thông tin liên lạc.
- <summary>

- <time> :
  xác định ngày giờ

  ### chú ý: ==> Tại sao cần các phần tử ngữ nghĩa?

  Theo W3C: "Web ngữ nghĩa cho phép dữ liệu được chia sẻ và sử dụng lại trong nhiều ứng dụng, doanh nghiệp và cộng đồng."

## Tag `<video>`:

Phần tử <video> được sử dụng để hiển thị video trên trang web

```
<video width="320" height="240" controls autoplay>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
Your browser does not support the video tag.
</video>
```

- phần tử control (điều khiển) thêm bảng điều khiển video
- source : chỉ định các file video thay thế mà trình duyệt có thể chọn
  Trình duyệt sẽ sử dụng định dạng nhận dạng được đầu tiên
- Văn bản giữa các thẻ <video> và </video> sẽ chỉ được hiển thị trong các trình duyệt không hỗ trợ phần tử <video>.
- autoplay : để phát video tự động
- muted (câm): tự phát nhưng tắt tiếng

## Tag `<audio>` :

cũng tương tự như thẻ <video>

## HTML5 Drag and Drop (kéo và thả):

Drap and Drop là 1 tính năng rất phổ biến. Đó là khi bạn "tóm" một đối tượng và kéo nó vào vị trí khác

Trong HTML , drap and drop là 1 phần của tiêu chuẩn: Bất cứ phần tử nào đều có thể kéo được (dragabble)

# CSS3

1. Đầu óc phải luôn để tâm đến DOM (Document Object Model). Đó là nền tảng cho hầu hết những thứ chúng ta gặp trên web, bao gồm cả HTML, CSS và JavaScript.

2. Học cách sử dụng các công cụ Web Inspector tích hợp sẵn trên trình duyệt. Trên Chrome, nó được kích hoạt bằng cách nhấn phải chuột, chọn "Inspect Element". Trên Safari, bạn cần kích hoạt nó - chuyển đến Preferences Menu -> Advanced và nhấn chọn hộp "Show Develop Menu in Menu Bar". Sau đó nó sẵn sàng hoạt động khi nhấn phải chuột. Với Firefox, bạn có thể sử dụng Firebug.

## text-overflow : tràn văn bản

- text-overflow : clip => cắt bớt đi phần chữ bị thừa
- text-overflow : ellipsis => phần dôi ra sẽ k được hiển thị và hiển thị dấu ...

## overflow : sự tràn ra

vd:

- overflow: hidden; // ẩn hết đi
- overflow: visible;// quan sát được
- overflow: auto; // thuộc tính này nên chú ý, nó dùng chung vs float để phần div container bên ngoài tự động giản nở để luôn bao chứa các phần tử float bên trong, nếu độ rộng thiết bị giảm làm cho các phần tử tự xuống dòng thì chắc chắn block chứa bên ngoài vẫn luôn bao quanh lấy mấy thằng bên trong

## word-wrap: bọc văn bản

Thuộc tính CSS word-wrap (bọc văn bản) cho phép các từ dài được tách ra và chuyển xuống dòng dưới

Thuộc tính này cho phép chúng ta bộc văn bản lại ngay cả khi phải tác ra ở giữa 1 từ.

## writing-mode : chỉ định các dòng văn bản đặt theo chiều dọc và ngang

tra thêm tài liệu !

- text-align-last Chỉ định cách căn chỉnh dòng - cuối cùng của văn bản
- text-justify Chỉ định cách căn lề và dãn cách các văn bản đã được chỉnh
- text-overflow Chỉ định cách báo hiệu nội dung tràn ra không được hiển thị cho người dùng.
- word-break Chỉ định các quy tắc ngắt dòng cho các tập lệnh non-CJK
- word-wrap Cho phép các từ dài được tách ra và chuyển xuống dòng dưới
- writing-mode Chỉ định xem các dòng văn bản nên được đặt bố cục là ngang hay dọc.

## transition : (chuyển tiếp)

Thuộc tính này cho phéo chúng ta thay đổi các giá trị thuộc tính một cách trơn tru, trong một khoảng thời gian nhất định

Để tạo được sự chuyển đổi, chúng ta cần xác định sẵn 2 điều:

- Thuộc tính CSS mà ta muốn thêm hiệu ứng
- Khoảng thời gian diễn ra hiệu ứng

```
div {
  width: 100px;
  height: 100px;
  background: red;
  transition: width 2s; // thuộc tính width sẽ thay đổi từ 100px lên 300px trong vòng 2s
}

div:hover {
  width: 300px;
}
}
```

## transition-timing-function :

Thuộc tính này bổ trợ cho thuộc tính trên giúp chỉ định đường công tốc độ của hiệu ứng

- ease : chỉ định hiệu ứng chuyển đổi bắt đầu từ chậm, rồi nhanh, sau đó kết thúc chậm (đây là mặc định)
- linear : chỉ định một hiệu ứng chuyển đổi với cùng tốc độ từ đầu đến cuối
- ease-in : chỉ định hiệu ứng chuyển đổi với bắt đầu chậm
- ease-out : chỉ định hiệu ứng chuyển đổi với kết thúc chậm
- ease-in-out : chỉ định hiệu ứng chuyển đổi với bắt đầu và kết thúc chậm
- cubic-bezier(n,n,n,n) : giúp bạn định nghĩa giá trị của riêng bạn với hàm cubic-bezier

## transition-delay:

Chỉ định sự trì hoãn ( tính bằng giây ) cho hiệu ứng chuyển đổi

Chúng ta có thể thêm cả hiệu ứng transform vào trong thuộc tính transition

```
  transition: width 2s, height 2s, transform 2s;
  transform: scale(2.1); ==>thay đổi tỷ lệ lên gấp 2.1 lần

```

## viết gọn transition :

Có thể viết gọn lên 1 dòng , nhiều thuộc tính có chuyển tiếp thì cách nhau bởi dấu phẩy

```
  transition: width 2s linear 1s;
```

## Animation:

Animation cho phép chúng ta thay đổi một element dần dần từ kiểu này sang kiểu khác

Để sử dụng hiệu ứng, trước tiên chúng ta cần phải chỉ định 1 số (key khung hình ) cho hiệu ứng

- @keyframes : Chỉ định code animation
  animation Thuộc tính thu gọn để thiết lập tất cả các thuộc tính animation
- animation-delay : Chỉ định độ trễ cho khởi động của hiệu ứng
- animation-direction : Chỉ định liệu hiệu ứng nên được phát tiến, lùi hay theo các chu kỳ thay thế.
- animation-duration : Chỉ định khoảng thời gian cần để hiệu ứng hoàn thành một chu kỳ
- animation-fill-mode : Chỉ định kiểu phần tử khi hiệu ứng không phát (trước khi bắt đầu, sau khi kết thúc hoặc cả hai)
- animation-iteration-count : Chỉ định số lần phát của hiệu ứng
- animation-name : Chỉ định tên của hiệu ứng @keyframes
- animation-play-state : Chỉ định xem hiệu ứng đang chạy hay dừng
- animation-timing-function : Chỉ định đường công tốc độ của hiệu ứng

1. @keyframes:
   Trong quy tắc @keyframes, hiệu ứng sẽ dần thay đổi từ kiểu hiện tại sang kiểu mới tại một số thời điểm nhất định

vd: (dùng to from)

```
div {
width: 100px;
height: 100px;
background-color: red;
animation-name: example; --> chỉ định tên animation
animation-duration: 4s;  --> chỉ định thời gian diễn ra trong bao lâu
}

@keyframes example {
from {background-color: red;} --> từ màu đỏ
to {background-color: yellow;} --> đến màu vàng
}
```

Chúng ta có thể sử dụng phần trăm % để thêm nhiều thay đổi tùy thích

ví dụ:

```
/* The animation code */
@keyframes example {
  0%   {background-color: red;}
  25%  {background-color: yellow;}
  50%  {background-color: blue;}
  100% {background-color: green;}
}

/* The element to apply the animation to */
div {
  width: 100px;
  height: 100px;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
}

```

2. animation-iteration-count:

thiết lập số lần hiệu ứng sẽ chạy

vd:
animation-iteration-count: 3; ==> chạy 3 lần trước khi nó dừng lại
animation-iteration-count: infinite; ==> chạy mãi mãi

!!!! Chú ý, đọc thêm document khi thực hành thực tế

3. animation-fill-mode :
   Thuộc tính animation-fill-mode chỉ định kiểu cho phần tử khi hoạt ảnh không phát
   (trước khi bắt đầu, sau khi kết thúc hoặc cả hai).
   Hoạt ảnh CSS không ảnh hưởng đến phần tử trước khi khung hình chính đầu tiên được phát
   hoặc sau khi khung hình chính cuối cùng được phát. Thuộc animation-fill-modetính có thể ghi đè hành vi này.

   vd:

   ```
   animation-fill-mode: forwards; ==> chuyển tiếp ; giữ được vị trí cuối sau khi hết time hoạt ảnh // ok

   ```

## background: linear-gradient(gradient_direction, color 1, color 2, color 3, ...);

đối số đầu tiên chỉ định hướng bắt đầu chuyển đổi mau - nó có thể được biểu diễn dưới dạng gốc độ <deg>
tạo màu nền có độ dốc phối hợp từ nhiều màu
vd:

```
background: linear-gradient(90deg, red, yellow, rgb(204, 204, 255));

```

## repeating-linear-gradient()

giống ở trên nhưng nó khác là nó lặp lại mẫu gradient được chỉ định

## transform: biến đổi

- scale(só x) : phóng to lên tỷ lệ x lần
- skewX (độ x deg): làm nghiên phần tử theo trục X ( trục ngang ) đi x độ
- skewY (..) tương tự nhưng với trục Y ( trục đứng)

## Phần tử giả:

- `::before` tạo 1 phần tử giả là phần tử con đầu tiên của phàn tử được chọn -`::after` tạo 1 phần tử giả là phần tử con cuối cùng của phần tử giả

@font-face: font của ta tự định nghĩa bên trong quay tắc CSS này

# CSS reponsive : (đáp ứng)

- max-width: 100% , height: auto; để xác định ảnh
  không bao giờ rộng hơn vùng chứa nó, và giữ được tỷ lệ ban đầu

## Đơn vị tuyệt đối , tương đối :

Ưu tiên sử dụng đơn vị tương đối cho CSS reponsive

-`vw` (viewport width) chiều rộng khung nhìn, 1vw=1% chiều rộng khung nhìn

- `vh` ( viewport height )
- `vmin` ( viewport minimum )
- `vmax` (viewport maximum)

- em Relative to the font-size of the element (2em means 2 times the size of the current font)
- rem Relative to font-size of the root element
- vw Relative to 1% of the width of the viewport\*
- vh Relative to 1% of the height of the viewport\*
- vmin Relative to 1% of viewport's\* smaller dimension
- vmax Relative to 1% of viewport's\* larger dimension
- % Relative to the parent element

## viewport (khung nhìn)

```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

- Phần tử <meta> về viewport hướng dẫn trình duyệt cách thức kiểm soát kích thước của trang và việc mở rộng.

- Thuộc tính width=device-width thiết lập chiều rộng của trang theo chiều rộng màn hình của thiết bị (sẽ khác nhau tùy thuộc vào thiết bị).

- huộc tính initial-scale=1.0 thiết lập mức thu phóng ban đầu khi trang được nạp lần đầu bởi trình duyệt.

Một số quy tắc bổ sung cần tuân thủ:

1. KHÔNG sử dụng các phần tử cố định chiều rộng lớn - Ví dụ, nếu một hình ảnh được hiển thị với một chiều rộng lớn hơn so với viewport nó có thể làm cho viewport phải cuốn theo chiều ngang. Hãy nhớ điều chỉnh nội dung này phù hợp trong chiều rộng của viewport.

2. KHÔNG làm cho nội dung hiển thị tốt dựa trên một chiều rộng viewport cụ thể - Vì kích thước màn hình và chiều rộng tính theo pixel rất khác nhau giữa các thiết bị, nội dung không nên dựa vào một chiều rộng viewport cụ thể để làm cho nó hiển thị tốt.

3. Sử dụng các truy vấn media (@media) trong CSS để áp dụng các style khác nhau cho các màn hình nhỏ và lớn - Cài đặt độ rộng CSS tuyệt đối lớn cho các phần tử của trang, sẽ làm cho phần tử quá rộng trong viewport trên một thiết bị nhỏ hơn. Thay vào đó, xem xét sử dụng các giá trị tương đối cho chiều rộng, chẳng hạn như width: 100%. Ngoài ra, hãy cẩn thận khi sử dụng các giá trị định vị tuyệt đối lớn. Nó có thể làm cho phần tử nằm ngoài viewport trên các thiết bị nhỏ.

## Grid view:(chế độ xem lưới)

Trước tiên, hãy đảm bảo rằng tất cả các phần tử HTML có thuộc tính box-sizing được đặt thành border-box. Điều này đảm bảo rằng phần padding (đệm) và đường viền đã được tính trong tổng chiều rộng và chiều cao của các phần tử.

Xóa luồng

```
.row::after {
  content: "";
  clear: both;
  display: table;
}
```

Các phần tử float sàn trái

```
[class*="col-"] {
  float: left;
}
```

Tạo view 12 cột

```
.col-1 {width: 8.33%;}
.col-2 {width: 16.66%;}
.col-3 {width: 25%;}
.col-4 {width: 33.33%;}
.col-5 {width: 41.66%;}
.col-6 {width: 50%;}
.col-7 {width: 58.33%;}
.col-8 {width: 66.66%;}
.col-9 {width: 75%;}
.col-10 {width: 83.33%;}
.col-11 {width: 91.66%;}
.col-12 {width: 100%;}
```

## Media query:

Media query (truy vấn media) là một kỹ thuật CSS được giới thiệu trong CSS3.

Kỹ thuật này sử dụng quy tắc @media để chứa một khối các thuộc tính CSS chỉ khi thỏa mãn một điều kiện nhất định.

vd:

```
@media only screen and (max-width: 600px) {
  body {
    background-color: lightblue;
}
}
```

breakpoint ( điểm ngắt ) : ở đó một số phần của thiết kế sẽ xử lý các thiết kế sẽ xử lý khác nhau với mỗi điểm ngắt

`PHẢI TƯ DUY THEO KIỂU CSS VIẾT SAU SẼ ĐÈ LÊN CSS VIẾT TRƯỚC HOẶC PHÂN BREAKPOINT CHO TỪNG THIẾT BỊ`

`LUÔN LUÔN THIẾT KẾ CHO ĐIỆN THOẠI TRƯỚC==>LÀM CHO WEBSITE HIỂN THỊ NHANH TRÊN THIẾT BỊ NHỎ HƠN`

vd:

```
/ * Cho điện thoại di động: * /
[class*="col-"] {
  width: 100%;
}

@media only screen and (min-width: 768px) {
/ * Cho máy tính để bàn: * /
  .col-1 {width: 8.33%;}
  .col-2 {width: 16.66%;}
  .col-3 {width: 25%;}
  .col-4 {width: 33.33%;}
  .col-5 {width: 41.66%;}
  .col-6 {width: 50%;}
  .col-7 {width: 58.33%;}
  .col-8 {width: 66.66%;}
  .col-9 {width: 75%;}
  .col-10 {width: 83.33%;}
  .col-11 {width: 91.66%;}
  .col-12 {width: 100%;}
}
```

Cho máy tính để bàn:

Phần đầu tiên và phần thứ ba sẽ chiếm 3 cột mỗi phần. Phần giữa sẽ chiếm 6 cột.

Cho máy tính bảng (tablet):

Phần đầu tiên sẽ chiếm 3 cột, phần thứ hai sẽ chiếm 9, và phần thứ ba sẽ được hiển thị bên dưới hai phần đầu tiên, và nó sẽ chiếm 12 cột:

```
<div class="row">
<div class="col-3 col-s-3">...</div>
<div class="col-6 col-s-9">...</div>
<div class="col-3 col-s-12">...</div>
</div>
```

## Reponsive-image:

Nếu thuộc tính width được đặt thành phần trăm và thuộc tính height được đặt thành "auto", hình ảnh sẽ trở thành responsive và tăng và giảm tỷ lệ:

```
img {
  width: 100%;
  height: auto;
}
```

Nếu thuộc tính max-width được đặt thành 100%, nếu cần, hình ảnh sẽ giảm tỷ lệ, nhưng hình ảnh sẽ không bao giờ tăng tỷ lệ để nó lớn hơn kích thước ban đầu của hình ảnh:

```
img {
  max-width: 100%;
  height: auto;
}
```

- Nếu thuộc tính background-size được đặt thành "contain", hình nền sẽ chia tỷ lệ (scale) để vừa với vùng nội dung. Tuy nhiên, hình ảnh sẽ giữ nguyên tỷ lệ khung hình (mối quan hệ tỷ lệ giữa chiều rộng và chiều cao của hình ảnh):(nếu có độ cao cố định)

- Nếu thuộc tính background-size được đặt thành "100% 100%", hình ảnh nền sẽ kéo dài để bao phủ toàn bộ khu vực nội dung (nếu có độ cao cố định)

Phần tử HTML <picture> giúp các nhà phát triển web có thể linh hoạt hơn trong việc chỉ định các hình ảnh.

Phần tử <picture> được dùng phổ biến nhất với các hình ảnh được sử dụng trong các thiết kế responsive. Thay vì thiết kế một hình ảnh sẽ tăng hoặc giảm tỷ lệ dựa trên chiều rộng khung nhìn, chúng ta sẽ có nhiều hình ảnh được thiết kế để lấp đầy khung nhìn của trình duyệt một cách đẹp hơn.

Phần tử <picture> hoạt động tương tự như phần tử <video> và <audio>. Bạn thiết lập các nguồn khác nhau và nguồn đầu tiên phù hợp với ý muốn (preference) sẽ được sử dụng:

```
<picture>
  <source srcset="img_smallflower.jpg" media="(max-width: 400px)">
  <source srcset="img_flowers.jpg">
  <img src="img_flowers.jpg" alt="Flowers">
</picture>

```

## Reponsive-video:

```
video {
  width: 100%;
  height: auto;
}

// ok
video {
  max-width: 100%;
  height: auto;
}
```

## Responsive Web Design - Frameworks

Sử dụng các framworks để hổ trợ làm web reponsive nhanh và tiện lợi hơn

## CSS Selector (hay dùng):

1. Các nhóm `.class| #id |element `:
   chọn tất cả các phần tử có class , id hoặc thẻ element

2. Các nhóm `A B C ..` :
   chọn tất cả các element có class id hoặc element được bao quanh bở (từ ngoài vào trong)

3. Các nhóm `>`:
   chọn con trực tiếp

4. Các nhóm ` [attribute*=value]`:
   chọn tất cả thẻ có thuộc tính chứa chuổi con `value`

5. Các nhóm `A+B`:
   chọn thẻ `B` đầu tiên được đặt ngay bên cạnh của thẻ A

6. Các nhóm `A~B`:
   chọn tất cả các thẻ B đứng trước thẻ A

7. Các nhóm `A,B,C,..`:
   chọn tất cả các thẻ A,B,C,...

8. các nhóm `[attribute]`:
   chọn tất cả các thẻ có thuộc tính đó

# Bootstrap

## Giới thiệu về bootstrap

### Bootstrap là gì?

- Bootstrap là một front-end framework miễn phí để phát triển web nhanh hơn và dễ dàng hơn
- Bootstrap gồm các mẫu thiết kế dựa trên HTML và CSS dành cho typography, các biểu mẫu, nút bấm, bảng, trình đơn, phương thức, đăng tải hình ảnh và nhiều thứ khác,cùng với các tùy chọn plugin JavaScript
- Bootstrap cũng cung cấp cho bạn khả năng tạo các thiết kế responsive dễ dàng

### Lấy bootstrap ở đâu

Có 2 cách sử dụng bootstrap cho trang web của chúng ta

- Tải bootstrap từ trang web [getbootstrap.com](https://getbootstrap.com/)
- Nhúng Bootstrap vào trang từ một CDN (Content Delivery Network - nguồn trực tuyến) ==> ưu tiên sử dụng cách này vì nhanh chống và k càn phải dưa file quá nặng lên server và sẽ giúp trang web tải được nhanh hơn

```
LƯU Ý:

Nhiều người dùng đã tải Bootstrap về từ MaxCDN khi truy cập vào một trang web khác. Kết quả là, nó sẽ được nạp từ cache khi họ truy cập vào trang web của bạn, dẫn đến thời gian tải nhanh hơn. Ngoài ra, hầu hết CDN sẽ đảm bảo rằng khi người sử dụng yêu cầu một tập tin từ nó, tập tin đó sẽ được phục vụ từ máy chủ gần nhất với họ, điều này cũng làm cho thời gian tải nhanh hơn.

```

### .container và .container-fluid

Muốn sử dụng bootstrap thì ít nhất trong file html của mình phải có class này để bao quanh các phần tử

- .container sẽ là một một khung chứa không cố định , nó có padding margin thay đổi tùy theo loại thiết bị

- .container-fluid sẽ là 1 khing chưa cố định , thường là full 100 % độ rộng , không có padding margin, muốn có ta phải thêm vào

## Bootstrap Girds (lưới)

Chia trang web thành 12 column độc lập, ta có thể nhóm các cột với nhau để tạo thành những cột khác to hơn cho trang web

Hệ thống grid của Bootstrap có bốn class:

- xs (for phones - screens less than 768px wide)
- sm (for tablets - screens equal to or greater than 768px wide)
- md (for small laptops - screens equal to or greater than 992px wide)
- lg (for laptops and desktops - screens equal to or greater than 1200px wide)

Các class ở trên có thể được kết hợp để tạo các bố cục động và linh hoạt hơn.

Lưu ý : nếu sử dụng class trên kích thước lớn mà k chỉ dịnh cụ thể trên các màng hình nhỏ hơn thì tự động xuống màn hình nhỏ hơn các cột sẽ chiếm 100% width và sẽ nằm trên mỗi dòng khác nhau. Và trên các kích thước màn hình lớn hơn nữa nó cũng sẽ có giá trị % width giống với ở kích thước bạn tạo hiện tại.

## Bootstrap Table

- .table : thêm các style cơ bản của bảng
- .table-striped : thêm sọc ngựa vằn vào bảng
- .table-bordered : thêm đường viên trên tất cả các mặt của bảng và các ô
- .table-hover : thêm hiệu ứng di chuột (màu nền xám) trên các hàng của bảng

## Một số skil hay của Bootstrap

1. `<small>`
   Dùng để tạo văn bản phụ nhẹ hơn trong các tiêu đề h1-->h6 . tức là sẽ nhẹ hơn cha của nó, lưu ý la small phải ở trong các thẻ h1-->h6

2.
