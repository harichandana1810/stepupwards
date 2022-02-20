<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Raleway", sans-serif}

body, html {
  height: 100%;
  line-height: 1.8;
}

/* Full height image header */
.bgimg-1 {
  background-position: center;
  background-size: cover;
  background-image: url("https://lh3.googleusercontent.com/nlVKfs_mLW0l2aYfxcbOvKJyu8LjUKCGsqoH50OguBEMvrCKcHOV5jAkMdHAdgRaRfN8ug=s170");
  min-height: 70%;
}

.w3-bar .w3-button {
  padding: 5px;
}
</style>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar w3-white w3-card" id="myNavbar">
    <a href="#home" class="w3-bar-item w3-button w3-wide"><img src="https://lh3.googleusercontent.com/g7Gi4QRerEJFWVowKRqjVOAlozN9OgH3VcjyrU0n7tR9IHdNLyLgBtafu1nC_WOcoi2ypQ=s170" /></a>
    <!-- Right-sided navbar links -->
    <div class="w3-right w3-hide-small">
      <button href="#about" class="btn btn-primary dropdown-toggle w3-bar-item w3-button">
      Courses
    <span class="caret"></span></button>
    <ul class="dropdown-menu">
      <li><a href="#">HTML</a></li>
      <li><a href="#">CSS</a></li>
      <li><a href="#">JavaScript</a></li>
    </ul>
      <a href="#team" class="w3-bar-item w3-button"><i class="fa fa-user"></i> TEAM</a>
      <a href="#work" class="w3-bar-item w3-button"><i class="fa fa-th"></i> WORK</a>
      <a href="#pricing" class="w3-bar-item w3-button"><i class="fa fa-usd"></i> PRICING</a>
      <a href="#contact" class="w3-bar-item w3-button"><i class="fa fa-envelope"></i> CONTACT</a>
    </div>
    <!-- Hide right-floated links on small screens and replace them with a menu icon -->

    <a href="javascript:void(0)" class="w3-bar-item w3-button w3-right w3-hide-large w3-hide-medium" onclick="w3_open()">
      <i class="fa fa-bars"></i>
    </a>
  </div>
</div>

<!-- Sidebar on small screens when clicking the menu icon -->
<nav class="w3-sidebar w3-bar-block w3-black w3-card w3-animate-left w3-hide-medium w3-hide-large" style="display:none" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-large w3-padding-16">Close ×</a>
  <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">Courses</a>
  <a href="#team" onclick="w3_close()" class="w3-bar-item w3-button">TEAM</a>
  <a href="#work" onclick="w3_close()" class="w3-bar-item w3-button">WORK</a>
  <a href="#pricing" onclick="w3_close()" class="w3-bar-item w3-button">PRICING</a>
  <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button">CONTACT</a>
</nav>
<br>
<br>
<br>
<!-- Header with full-height image -->
<header class="bgimg-1 w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-left w3-text-white" style="padding:28px">
  <span style="font-size:10px">Management &gt; Time Management &gt; Speed Reading &amp; Dynamic Memory</span><br>
    <span class=" w3-hide-small" style="font-size:25px;">Start something that matters</span><br>
    <span style="font-size:15px;">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam semper, elit nec sus-<br>cipit vestibulum.</span><br>
    <span><figure class="w3-bar-item w3-button"><img src="https://harry578398781.files.wordpress.com/2022/02/ratingstaredited1-2.png" width="110" height="25"/></figure>
    <p class="has-background-color has-text-color" style="font-size:14.3914px">(1.5 ranking) | 4,697 students</p></span>
    
    <div class="w3-left w3-hide-small">
    <figure class="w3-bar-item w3-button"><img src="https://lh3.googleusercontent.com/JjDN_XGPPYa-o0BE5jybn_LyOvkpr6JOYsRDOPk3dcwQxpJsIe98s4ak3-O8BoroTkVvtjY=s170" alt="" class="wp-image-49" width="116" height="30"/></figure>
    <figure class="w3-bar-item w3-button"><img src="https://lh3.googleusercontent.com/UD3Rw4KwXVIaZN5ILofl7tTMdubujMxktutxoTxFr7CPEI-yxo-lJaQaL7HYgCYGIFbWXw=s170" alt="" class="wp-image-50" width="140" height="37"/></figure>
    <figure class="w3-bar-item w3-button"><img src="https://lh3.googleusercontent.com/w_voi9Nv4TIHhLfba3k3jrtB8265hwe0mcO-HuVNCKiH503Su6yvjrqiJ-JbtGz2rKJLIg=s170" alt="" class="wp-image-52" width="163" height="40"/></figure>
    </div><br>
    <button href="#about" class="btn btn-primary dropdown-toggle w3-bar-item w3-button">
      Request Training Proposal
      </button>
  </div> 
  
</header>


 
<script>
// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}


// Toggle between showing and hiding the sidebar when clicking the menu icon
var mySidebar = document.getElementById("mySidebar");

function w3_open() {
  if (mySidebar.style.display === 'block') {
    mySidebar.style.display = 'none';
  } else {
    mySidebar.style.display = 'block';
  }
}

// Close the sidebar with the close button
function w3_close() {
    mySidebar.style.display = "none";
}
</script>

</body>
</html>
