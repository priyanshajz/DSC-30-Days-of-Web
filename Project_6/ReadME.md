<!doctype html>
<html lang="en">
  <head>
<meta name name="viewpoint" content="width-device-width",initial-scale=1">
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
<link rel="stylesheet" type="text/css" href="blog.css">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<style>
body{
      backgroung-color: #1d2126;
     color: purple;
}
.wrapper{ width: 400px;
          max-width: 90%;
         margin: 0 auto;
}
.wrapper label{
     display: block;
    margin: 0.5em 0;
}
.wrapper label input{
font-size:18px;
padding: o.5em;
}
.wrapper input[type="submit"]{
font-size:25px;
color:blue;
}
</style>
    <title>Hello, world!</title>
  </head>
  <body>
<header>
<h1>OUR BLOG</h1>
</header>
<div class="row">
<div class="left-column">
<div class="card">
<h2>Title of Blog</h2>
<h5>title description,jan24,2021</h5>
<img src="The-Evolution-Of-Web-Development-Via-Machine-Learning.jpg" alt ="blog"/>
<p>WEB DEVELOPMENT nowadays is a highly growing field</p>
<p>Web  develpoment is the work involved in develpoing a web site for the internet<br> 
or an develpoing a Web site for the internet or an intranet.web development can range from developing<br>
 a simple single static page of plain text<br> to complex Web-based internet <br>applications, business and social network
Web development is the work involved in developing a Web site for the Internet (World Wide Web) or an intranet (a private network).
</p>
</div>
<div class="card">
<h2>Title of Blog</h2>
<h5>title description,jan24,2021</h5>
<img src="Blog-Types-of-Web-Dev.jpg" alt ="blog"/>
<p>WEB DEVELOPMENT nowadays is a highly growing field</p>
<p>As human beings, we pride ourselves on our superb adaptation skills and ability to change with the times.<br>
 Stemming from this, when the social world shifted from a place of interpersonal connections to internet connections<br>
, so did the world of business. There's no getting around it; our digitally-driven lifestyle has given us little choice but to <br>
adapt to technology, and if you haven't already, it's time to get a move on. It's a no-brainer; website development is now<br>
 essential to you as a business person. For your business to generate more business, your voice needs to be heard, your brand<br>
 needs to be seen, and your goals need to be reached. Website development is the key to making those things happen. The same <br>
way an eye is the window to the soul, a website is the window to the business, giving customers a taste of what you have to offer and<br>
 enticing them to delve deeper for more
</p>
</div>

</div>
<div class="right-column">
<div class="card">
<h2>PURPOSE</h2>
<img src="8Y8jVFchXJF6TPpQ6i6weW-320-80.jpg" alt="about"/>
<p>Reasons You Should Learn Web Development
7 Reasons You Should Learn Web Development. ...
1 Now Hiring! ...<br>
2 A Great Income. ...<br>
3 No Wasted Time in Learning How to Code. ...<br>
4 You Can Work From Anywhere. ...<br>
5 You Can Work at an Awesome Tech Company. ...<br>
6 There Are Always Freelance Opportunities. ...<br>
7 It's Creative and Fun.<br>
</p>
</div>
<div class="card">
<h3>JOB PORTFOLIOS</h3>
<img src="web-development-team_1.png" alt="JOBS"/>
<img src="web-develop-1024x512.png" alt="JOBS"/>
<img src="what-is-a-web-developer.jpg" alt="JOBS"/>
</div>
<div class="card">
<h3>FOLLOW ME</h3>
<p>ig=@priyanshajz</p>
</div>
</div>
</div>
<footer><h2>KIIT UNIVERSITY</h2></footer>
<nav class ="navbar navbar-dark bg-dark">
<a class="navbar.brand color:white; bg-success">PRIYANSHA </a>

<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
<script src="main1.js"></script>
<h1>Form Data</h1>
<div class="wrapper">
<form class="form">
<label id="nameField">
<input type="text" name="nameField" placeholder="name" required/>
</label>
<label id="emailField">
<input type="email" name="emailField" placeholder="email" required/>
</label>
<label id="passwordField">
<input type="password" name="passwordField" placeholder="password" required/>
</label>
<label id="passwordVerifyfield">
<input type="password" name="passwordVerifyField" placeholder="Verify-password" required/>
</label>
<input type="submit" value="submit" name="submit"/>
 </form>
</div>
<script>
const wrapper=document.querySelector('.wrapper'),
         form=wrapper.querySelectorALL('.form'),
       submitInput=form[0].querySelector('input[type="submit"]');

function getDataForm(e){
e.preventDefault();
var formData=new FormData(form[0]);
alert( formData.get('nameField')+' - '+formData.get('emailField')+' - '+formData.get('passwordField'));
}
document.addEventListener('DOMContentLoaded', function(){
 submitInput.addEventListener('click', getDataForm,false);
}, false);
</script>
  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item d-flex justify-content-center">
        <a class="nav-link" href="#about">About <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item d-flex justify-content-center">
        <a class="nav-link" href="#information">Information</a>
      </li>
            <li class="nav-item d-flex justify-content-center">
        <a class="nav-link " href="#image">Images</a>
      </li>
    </ul>
</div>
</nav>
<div class="p-3 mb-2 bg-warning text-blue  container.fluid Containerone"id="about" >
<center><h1 style="color:blue;">MYSELF</h1></center>
<img src="muskan2.jpg" alt="MY PIC" width="200" height="300"/>
<h2 style="color:purple;">My name is Priyansha Jaiswal</h2>
<h2 style="color:purple;">I am currently in 2 year</h2>
<h2 style="color:purple;">KIIT University</h2>
<h3>I have keen intrest in learning new things</h3>
<h3>I am just a beginner in this Web Development area</h3>
<h3>This 30 days of Web Development helped me a lot to learn about all the ne things</h3>
<h3>The sessions that were conducted were Amazing and Very helpful for me</h3> 
<button  style="color:blue;" type="button" class"btn Contact me">CONTACT</button>
</div>
<div class="p-3 mb-2 bg-secondary text-light green  container.fluid Containertwo" id="information" >
<center><h1 style="color:blue;">Web Development</h1></center>
<source src="holi.mp4" type="video/mp4">
<p style ="color:purple;">Web  develpoment is the work involved in develpoing a web site for the internet<br> 
or an develpoing a Web site for the internet or an intranet.web development can range from developing<br>
 a simple single static page of plain text<br> to complex Web-based internet <br>applications, business and social network
Web development is the work involved in developing a Web site for the Internet (World Wide Web) or an intranet (a private network).<br>
 Web development can range from developing a simple single static page of plain text to complex Web-based Internet applications<br>
 (Web apps), electronic businesses, and social network services. A more comprehensive list of tasks to which Web development commonly<br>
 refers, may include Web engineering, Web design, Web content development, client liaison, client-side/server-side scripting, <br>
Web server and network security configuration, and e-commerce development.

Among Web professionals, "Web development" usually refers to the main non-design aspects<br>
 of building Web sites: writing markup and coding. Web development may use content management systems (CMS) to make <br>
content changes easier and available with basic technical skills.

For larger organizations and businesses, Web development teams can consist of hundreds of people (Web developers) and<br>
 follow standard methods like Agile methodologies while developing Web sites. Smaller organizations may only require a single<br>
 permanent or contracting developer, or secondary assignment to related job positions such as a graphic designer or information <br>
systems technician. Web development may be a collaborative effort between departments rather than the domain of a designated<br>
 department. There are three kinds of Web developer specialization: front-end developer, back-end developer, and full-stack developer.<br>
 Front-end developers are responsible for behavior and visuals that run in the user browser, while back-end developers deal with the servers.




<div class=" p-3 mb-2 bg-danger text-white container-fluid Containerthree" id="image">  
<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block w-100" src="IMG_20191102_204940.jpg" alt="First slide" width="300" height="200">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="IMG_20191102_203024.jpg" alt="Second slide" width="300" height="200">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="IMG_20191102_204055.jpg" alt="Third slide" width="300" height="200">
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
  </body>
</html>