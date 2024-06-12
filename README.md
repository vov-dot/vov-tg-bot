 <!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="utf-8" />
    <link rel="stylesheet" href="../first_site/StyleSheet1.css">
    <title></title>
</head>
<body>

<div class="intro">
    <div class="container">
        <div class="header_inner">
            <h1>Chat team</h1>
            <nav class="nav">
                <a class="nav_link" href="#contacts">contacts</a>
                <a class="nav_link" href="#blog">blog</a>
                <a class="nav_link" href="#about us">about us</a>
                <a class="nav_link" href="#teachers">our teachers</a>
            </nav>
        </div>
        <div class = "h1">Welcome to our site</div>
        <div class="navigation">
                <a class='first_page_links'href="reg">Register </a>
                <a class='first_page_links'href="buy">Buy a course</a>
                <a class='first_page_links'href="weel">Spin weel</a>
        </div>
    
        <div class="midle_inner">
            <div class = "galary">
                <div class ="midle_cont">
                    <div class = "midle_h2">our site was made for:</div>
                    <h3>
                        <ul class= "table">
                            <li>teach you how to do busnes</li>
                            <li>how to start programming</li>   
                            <li>how to manage your team</li>
                        </ul>
                    </h3>
                </div>
                <div class ="midle_cont" id = "about us">
                    <div class = "midle_h2">why us?</div>
                    <h3>
                        <ul class = "table">
                            <li>our teachers are one of the best</li>
                            <li>we have a lot of courses about every think what you want</li>
                        </ul>
                    </h3>
                </div>
                <div class ="midle_cont">
                    <div class = "midle_h2"></div>
                    <h3>
                        <ul class = "table">
                            <li></li>
                            <li></li>
                        </ul>
                    </h3>
                </div>
            </div>
            <div class="blog">
                <div class="galary">
                    <div class="blog_cont">
                        <div class="blog_h2" id = "blog">blog</div>
                        <div class="blog_h3">
                            <ul class="blog_table">
                                <li><a class= "blog_links" href="https://www.facebook.com/">facebook</a></li>
                                <li><a class= "blog_links" href="https://www.instagram.com/">instagram</a></li>
                                <li><a class= "blog_links" href="https://www.youtube.com/">youtube</a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="blog_cont">
                        <div class="blog_h2" id="contacts">contacts</div>
                        <div class="blog_h3">
                            <ul class="blog_table">
                                <li><a class= "blog_links" href="https://www.facebook.com/">work_facebook</a></li>
                                <li><a class= "blog_links" href="https://www.instagram.com/">work_instagram</a></li>
                                <li><a class= "blog_links" href="https://www.telegram.com/">work_telegram</a></li>
                            </ul>
                        </div>
                    </div>
                </div>  
            </div>
        </div>
</div>
</body>
</html>

body {
	font-family: "Kaushan Script", cursive;
	font-size: 10px;
	font-style:normal;
	color: #222;
	padding: 0px;
	margin: 0px;
}
*,
*: before,
*: after {
	box-sizing: border-box;
}
/* тексты */
h2,h3,h4,h5,h6{
margin: 0;
}

h1 {
	font-size:40px;
}

/* контейнер */
.container {
	width: 100%;
	height: 1000px;
	padding-left: 10px;
}


/* приветствие */
.intro {
	width:100%;
	height: 1000px;
	background:url('../first_site/images/Фон2.png');
	background-size:cover;
	background-repeat: no-repeat;
	background-position: center;
}

/* навигация */
.nav_link{
    font-size: 20px;
	display: inline-block;
	vertical-align:top;
	padding:0 10px;
	color:black;
	margin-top:-20px;
	margin-left:-10px;
	transition:color .4s linear;

}
.nav_link:hover{
	color:#FFE4B5;
}

.h1 {
	width:475px;
    font-family: "Kaushan Script", cursive;
    font-size: 50px;
	color:black;
	margin-left:500px;
	position:center;
}

.navigation {
	display:inline-block;

	margin-left:450px;

}

.first_page_links {
    font-family: "Kaushan Script", cursive;
    font-size: 35px;
	position:center;
	margin: 0 10px;
	color:black;
	text-decoration:none
}

/*body*/

.galary {
	display:flex;
	left:calc(50% - 330px);
}

.midle_cont {
	position:relative;
	width: 150px;
	height: 250px;
	padding:8px;
	border-radius:10px;
	box-shadow:20px 5px 40px black;
	transition:1s easy-in-out;
	background-color:#FFE4B5;
	margin-top:300px;
	margin-left:40px;
}

.midle_cont:hover {
	transform:translateY(-16px);
	font-weight:bold;
	cursor:pointer;
}
.midle_cont:hover ~ .midle_cont {
	left:55px
}

.midle_cont:nth-child(2){
    margin-left:-50px;
	background-color:#87CEEB;
}

.midle_cont:nth-child(3){
    margin-left:-50px;
	background-color:#DDA0DD;
}


.midle_h2 {
	margin-left:10px;
	font-family: "Kaushan Script", cursive;
	font-size: 25px;
	color:black;

}

.table{
	font-family: "Kaushan Script", cursive;
	font-size: 15px;
	color:black;
}
.blog_cont {
	position:relative;
	width: 150px;
	height: 150px;
	padding:8px;
	border-radius:10px;
	box-shadow:20px 5px 40px black;
	background-color:#FFE4B5;
	margin-left:1150px;
}
.blog_cont:hover {
	transform:translateY(-16px);
	font-weight:bold;
	cursor:pointer;
}
.blog_cont:hover ~ .blog_cont {
	left:55px
}

.blog_cont:nth-child(2){
    margin-left:-50px;
	background-color:#87CEEB;
}


.blog_h2{
    font-family: "Kaushan Script", cursive;
    font-size: 25px;
	color:black;
}
.blog_table {
    font-family: "Kaushan Script", cursive;
	font-size: 15px;
	color:black;
}

.blog_links {
	color:black;
	font-family: "Kaushan Script", cursive;
    font-size: 15px;
}
