
<!DOCTYPE html>
<html lang="vi">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>My New Project</title>


<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}


body{

    font-family:Arial, sans-serif;
    background:#f4f6f8;

}


/* HEADER */

header{

    background:#0077b6;
    color:white;

    text-align:center;

    padding:50px;

}


header h1{

    font-size:40px;

}


header p{

    margin-top:15px;

    font-size:18px;

}



/* MENU */

nav{

    background:#023e8a;

    padding:15px;

    text-align:center;

}


nav a{

    color:white;

    text-decoration:none;

    margin:20px;

    font-size:18px;

}



/* CONTENT */

.container{

    display:flex;

    justify-content:center;

    gap:30px;

    padding:50px;

}



.card{

    background:white;

    width:320px;

    padding:30px;

    border-radius:15px;

    box-shadow:0 5px 15px #ccc;

}



.card h2{

    color:#0077b6;

    margin-bottom:15px;

}



.card p{

    line-height:1.6;

}



button{

    margin-top:20px;

    padding:12px 25px;

    border:none;

    background:#0096c7;

    color:white;

    border-radius:5px;

    cursor:pointer;

}



button:hover{

    background:#023e8a;

}



/* FOOTER */

footer{

    background:#023e8a;

    color:white;

    text-align:center;

    padding:20px;

}



/* RESPONSIVE */

@media(max-width:700px){

.container{

    flex-direction:column;

    align-items:center;

}

}



</style>


</head>



<body>


<header>

<h1>
Welcome To My Website
</h1>


<p>
Dự án Web Frontend đầu tiên với HTML và CSS
</p>


</header>




<nav>

<a href="#">Trang chủ</a>

<a href="#">Giới thiệu</a>

<a href="#">Dịch vụ</a>

<a href="#">Liên hệ</a>


</nav>




<section class="container">


<div class="card">


<h2>
HTML & CSS
</h2>


<p>
Website được xây dựng bằng HTML và CSS.
Đây là sản phẩm thực hành trong khóa học
Web Frontend tại CodeGym.
</p>


<button>
Xem thêm
</button>


</div>





<div class="card">


<h2>
GitHub Project
</h2>


<p>
Dự án được quản lý bằng Git,
lưu trữ trên GitHub Repository
và thực hiện các thao tác commit,
push mã nguồn.
</p>


<button>
Learn More
</button>


</div>




<div class="card">


<h2>
Frontend Learning
</h2>


<p>
Rèn luyện kỹ năng xây dựng giao diện,
bố cục website và quản lý mã nguồn
bằng Git.
</p>


<button>
Start
</button>


</div>



</section>




<footer>


<p>
© 2026 My New Project | CodeGym Internship
</p>


</footer>



</body>


</html>
