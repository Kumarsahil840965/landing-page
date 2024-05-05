# landing-page
this is my first git repository
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Landing page</title>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
      integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div id="main">
      <div class="top">
        <div class="overlay">
          <div class="text">
            <h1>Images</h1>
            <div class="image"></div>
            <div class="rtext">
              <p>Mesmerizing</p>
              <p>Astonishing</p>
            </div>
            <div class="icons">
              <i class="fa-brands fa-twitter"></i>
              <i class="fa-brands fa-facebook"></i>
              <i class="fa-brands fa-instagram"></i>
            </div>
          </div>
        </div>
      </div>
      <div class="bottum">
        <div class="b1">
          <h1>Populer</h1>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit.
            Cupiditate, eius tempora ducimus veniam eos ipsum!
          </p>
        </div>
        <div class="b2">
          <div class="up">
            <h1>latest</h1>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam cum
              eaque quae nemo, eligendi inventore!
            </p>
          </div>
          <div class="down">
            <h1>More....</h1>
          </div>
        </div>
        <div class="b3">
          <div class="overlay">
            <p>Privacy policy</p>
            <p>terms and Condition</p>
            <p>Contact us</p>
            <p>About us</p>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>



*{
    margin: 0;
    padding: 0;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    box-sizing: border-box;
  }
  html,body{
    width: 100%;
    height: 100%;
  }
  .main{
    width: 100%;
    min-height: 100vh;
  }
  .top{
    width: 100%;
    min-height: 60vh;
    background-color: blue;
    background-image: url(a.jpeg);
    background-size: cover;
    background-position: center;
  }
  .top .overlay{
    position: relative;
    width: 100%;
    min-height: inherit;
    background-color: rgba(0, 0, 0, 0.312);
  }
  .text{
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: absolute;
    width: 100%;
    padding: 0 10vh;
    color: white;
  }
  .text h1{
    font-weight: 600;
    font-size: 8vh;
  }
  .text .image{
    background-image: url();
    background-size: cover;
    background-position: center;
    height: 300px;
    width: 220px;
  }
  .rtext{
    display: flex;
    width: 25%;
    align-items: center;
    justify-content: space-between;
  }.rtext p{
    font-size: 25px;
  }
  .bottum{
    display: flex;
    width: 100%;
    min-height: 40vh;
  }
  .b1{
    width: 30%;
    min-height: inherit;
    background-image: url(c.jpeg);
    background-size: cover;
    background-position: center;
  }
  .b1 h1{
    text-align: center;
    padding: 30px;
  }
  .b1 p{
    color: white;
    text-align: center;
    padding: 15px;
  }
  .b2{
    width: 30%;
    min-height: inherit;
    display: flex;
    flex-direction: column;
  }
  .b2 .up{
    width: 100%;
    min-height: 20vh;
    background-image: url(r.jpeg);
    background-size: cover;
    background-position: center;
  }
  .b2 .up h1{
    text-align: center;
    padding: 30px;
  
  }
  .b2 .up p{
    color: white;
    text-align: center;
    padding: 15px;
  }
  .b2 .down{
    width: 100%;
    min-height: 20vh;
    background-image: url(d.jpeg);
    background-size: cover;
    background-position: center;
  }
  .b2 .down .overlay{
    position: relative;
    width: 100%;
    min-height: 20vh;
    background-color: rgba(0, 0, 0, 0.312);
  }
  .b3{
    width: 40%;
    min-height: inherit;
    background-image: url(e.jpeg);
    background-size: cover;
    background-position: center;
  }
  .b3 .overlay{
    justify-content: right;
    position: relative;
    margin-left: 50%;
    width: 50%;
    height: 100%;
    padding: 4vh 3vh;
  }
  .b3 .overlay p{
    padding: 1.2vh;
  }
  /* responsive */
  @media(max-width:500px){
    .text{
      flex-direction:column;
      align-items: flex-start;
    }
    .text h1{
      font-size: 5vh;
    }
    .text .image{
      height: 200px;
      width: 140px;
      margin-top: 20px;
    }
    .rtext{
      flex-direction: column;
      align-items: flex-start;
    }
    .rtext p{
      margin-top: 10px;
    }
    .bottum{
      flex-direction: column;
      align-items: flex-start;
    }
    .b1{
      width: 100%;
      min-height: 30vh;
    }
    .b2{
      width: 100%;
    }
    .b2 .up{
      min-height: 30vh;
    }
    .b3{
      width: 100%;
      min-height: 30vh;
      background-position: left;
    }
  }
