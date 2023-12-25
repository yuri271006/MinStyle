# MinSyle (minstyle - mins) #
### Tác giả: La Quí Cường [0782887860] (Yuri) ###

1. Giới thiệu:

--> MinStyle là file css được viết sẵn nhầm hỗ trợ code nhanh giao diện front-end.
--> Version: 0.1

2. Hạn chế:

--> Hiện tại MinStyle, số code của mins còn ít chưa đa dạng.
--> MinStyle chỉ hỗ trợ cấu trúc Class và không tồn tại cấu trúc Id.

3. Ưu điểm: 

--> Cấu trúc dễ hiểu.
--> Dễ dàng đọc.
--> Có hỗ trợ tiếng Việt.

4. Các cấu trúc viết cơ bản:

<Note> 
--> Nếu muốn dùng được code của MinStyle, vui lòng cho một Class với tên được đặt là minstyle vào thẻ body. 
Ví dụ: <body class="minstyle"></body>

--> Điều này giúp min được gọi vào trong tệp tin HTML của bạn, nếu không cần nữa, hãy loại bỏ nó! 

<!--///////////////////////////-->

--> MinStyle cố gắng theo hướng tùy biến nhất, vì vậy bạn có thể giới hạn vùng hoạt động của MinStyle bằng cách không đặt Class minstyle vào thẻ <body> mà đặt vào thẻ bạn cần nó.
Ví dụ: <div class="minstyle"></div>

--> Và vâng, MinStyle chỉ có tác dụng trong phạm vi thẻ div ấy!

</Note>

-->MinStyle thật sự là phong cách nhỏ dễ hiểu, dẫu vậy nó lại yêu cầu rất chặt chẽ!!! Có thể hình dung đó nó dự trên qui luật cha - con để hoạt động. Điều này có nghĩa, chỉ cần thiếu một class thuộc tính thì MinStyle sẽ không chạy.

-->MinStyle qui định class thuộc tính như sau: mins- + thuộc tính + kích thước.

<!--Dưới đây là các Class thuộc tính -->
.minstyle
.mins
.mins-border
.mins-alert
.mins-button
<!--/////////////////////////////-->

< Cách sử dụng tiếng Việt trong MinStyle >

--> Không còn gì dễ hơn với thuộc tính class của mins và thuộc tính mins-vi="Nội dung định dang bằng tiếng Việt". 

<!------------------------------------------------------->

--> #Copy code này dán vào file của bạn: 

# mins.css:  

<link rel="stylesheet" href="Đường dẫn của bạn /minstyle/mins.css">

--> #Khi code mins bằng tiếng Việt, các code sau là bắt buộc:

# jquery.min.js: (Thư viện Jquery)

# mins.min.js: 

<script src="Đường dẫn của bạn /minstyle/mins.min.js"></script>


<!------------------------------------------------------->
### Hãy sử dụng mins thật vui vẻ ###
