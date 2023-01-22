<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->
<link rel="stylesheet" href="style.css">
  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  <link rel="preconnect" href="https:fonts.gstatic.com">
  <link rel="https://fonts.googleepis.com/css2?fammily=karla&display=swap" href="">
  <title>Frontend Mentor | Single Price Grid Component</title>
  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>
    .attribution { font-size: 11px; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%); }
  </style>
</head>
<body>
  <main>
    <div class="container">
      <div class="community-sec">
        <h2 class="com-header">Join our community</h2>
        <h3> 30-day, hassle-free money back guarantee</h3>
        <p> Gain access to our full library of tutorials along with expert code reviews. <br>
          Perfect for any developers who are serious about honing their skills.</p>
          <div>
          <div class="flex-contain">
            <div class="flex-left">
              <h3> Monthly Subscription </h3>
              <span class="dol">&dollar;29</span> <span class="date">per month</span>
              <p> Full access for less than &dollar;1 a day</p>
              <botton class="btn">Sign Up</botton>
            </div>
            <div class="flex-ringt">
              <h3 class="fle-ringt-header">Why Us</h3>
              <ul class="ringt-container">
                <li>Tutorials by industry experts</li>
                <li> Peer &amp; expert code review</li>
                <li>Coding exercises</li>
                <li> Access to our GitHub repos</li>
                <li>Community forum</li>
                <li> Flashcard decks</li>
                <li>New videos every week</li>
              </ul>
            </div>
          </div>
      </div>
  </main>
  <footer>
    <p class="attribution">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
      Coded by <a href="#">Your Name Here</a>.
    </p>
  </footer>
</body>
</html>

*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
body{
    background-color: whitesmoke;
    font-family: "karla";
    font-size: 100%;
    font-weight: 600%;
}
main{
    display: flex;
    height: 100vh;
    width: 100%;
    padding: 100px 30px;
}
.container{
    width: 80%;
    padding: 30px;
    margin: 345px;
    margin: auto;
    border-radius: 8px;
    background-color: white;
    box-shadow: 0px 0px 14px 1px #00000024;
}
.com-header{
    color: hsl(179, 62%, 43%);
}
.community-sec p{
    color: hsl(218, 22%, 67%);
    margin-top: 23px;
    line-height: 1.6;
    margin-bottom: 70px;
}
.flex-contain{
    margin: -30px;
    color: white;
}
.flex-left{
    background-color: hsl(179, 62%, 43%);
    padding: 30px;
    line-height: 1.6;
}
.flex-left p{
    color: rgba(255, 255, 255, 0.855);
}
.flex-right{
    background-color: hsl(179, 62%, 45%);
    padding: 30px;
}
.date{
    position: absolute;
    color: rgba(247, 234, 243, 0.589);
    margin-top: 10px;
    margin-left: 17px;
}
.dol{
    font-size: 34px;
    font-weight: 700;
}
.btn{
    color: white;
    background-color: hsl(71, 73%, 54%);
    border: none;
    outline: none;
    cursor: pointer;
    min-width: 100%;
    padding: 15px;
    margin-top: 26px;
    border-radius: 4px;
}
.btn:hover{
    background-color: hsl(71, 73%, 48%);
}
.flex-right-header{
    color: white;
}
.right-container{
    color: rgba(255, 255, 255, 0.855);
    margin-top: 20px;
    list-style: none;
    line-height: 1.4;
}

@media screen and (max-width:786px){
    footer{
        display: none;
    }
}
.attribution a{
    text-align: center;
    color: white;
}
.attribution a{
    color: wheat;
}
@media screen and (max-width:786px){
    .container{
        width: 60%;
        display: flex;
        flex-direction: column;
    }
    .flex-contain{
        display: flex;
    }
    .flex-left{
        width: 50%;
    }
    .flex-right{
        width: 50%;
    }
    footer{
        margin-top: auto;
    }
    .attribution a{
    color: black;
    margin-bottom: 20px;
    }
    .attributiona a{
        color: black;
    }
}
