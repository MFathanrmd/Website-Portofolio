<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="z_style.css" />
    <title>simpe portofolio</title>
  </head>
  <body>
    <header class="header">
      <a href="#" class="logo"><span>M.Fat</span>han</a>

      <nav class="navbar">
        <a href="#" class="logo">portofolio</a>
        <a href="#">services</a>
        <a href="#">experimence</a>
        <a href="#">projects</a>
        <a href="#">education</a>
      </nav>

      <a href="#" class="contact">Contact Me</a>
    </header>

    <section class="home">
        <div class="home-content">
            <h3>Hello..</h3>
            
            <h1>I'm <span>Fathan<br></span>a Frontend Develover</h1>
            <p>I study at Jendral Soedirman University, Faculty of Engineering, majoring in Informatics</p>

            <div class="btn-box">
                <button class="btn-1">Hire Me</button>
                <button class="btn-2">experimence</button> 

            </div>
        </div>
        <div class="img-box">
            <img src="fathan_Image.jpg" alt="">
        </div>
    </section>

    <section class="about">

        <div class="about-img">
            <!-- <img src="fathan_Image.jpg" alt=""> -->
        </div>

        <div class="about-content">
            <h2 class="heading">About <span>Me</span></h2>
            <h3>Frontend <span>Develover</span></h3>
            <p>I study at Jendral Soedirman University, Faculty of Engineering, majoring in Informatics</p>
            <a href="#" class="btn-2">Experimence</a>
        </div>
    </section>

    <section class="contact-form">
      <h2 class="contact-me">Contact <span>Me</span></h2>

      <form action="#">

        <div class="input-box">
          <input type="text" placeholder="full
           Name">
           <input type="email"
           placeholder="email">
        </div>

        <div class="input-box">
          <input type="number" 
          placeholder="phone number">
           <input type="text"
           placeholder="subject">
        </div>

        <textarea name="" id="" cols="30"
        rows="10" placeholder="Your Message"></textarea>
        <input type="submit" value="Send Message"
        class="btn-1">
      </form>
    </section>
  </body>
</html>

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins',sans-serif;
    text-decoration: none;list-style: none;
}
.header{
    position: fixed;
    top: 0;
    left: o;
    width: 100%;
    padding: 35px 12%;
    background: black;
    backdrop-filter: blur(10px);
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 100;
}
.logo{
    font-size: 25px;
    color: white;
    font-weight: 600;
    transition: 0.3s ease;
}
.logo:hover{
    color: orangered;
    text-shadow: 0 0 25px orangered,
                 0 0 50px orangered;
    transform: scale(1.1);
}
span{
    color: orangered;
}
.navbar a{
    font-size: 18px;
    color: white;
    font-weight: 500;
    margin: 0 20px;
    border-bottom: 3px solid transparent;
    transition: 0.3s ease;
}
.navbar a:hover,
.navbar a.active{
    color: orangered;
    border-bottom: 3px solid orangered;
}
.contact{
    padding: 10px 28px;
    background-color: white;
    color: black;
    border: 2px solid transparent;
    border-radius: 8px;
    font-size: 16px;
    letter-spacing: 1px;
    font-weight: 600;
    transition: 0.3s ease;
}
.contact:hover{
    background-color: orangered;
    box-shadow: 0 0 25px orangered;
    color: white;
}


/* section home */
.home{
    margin-top: 132px;
    display: flex;
    background: rgb(241, 241, 241);
}
.home-content{
    width: 100%;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    /* align-items: center; */
    gap: 1em;
    padding: 30px 12% 0;
    
}

.home-content h3{
    text-align: left;
    font-size: 42px;
}
.home-content h1{
    font-size: 62px;
    line-height: 1.2;
}
.home-content p{
    font-size: 18px;
    margin: 25px 0 30px;
}
.btn-box{
    width: 400px;
    display: flex;
    gap: 2em;
}
.btn-1{
    padding: 15px 28px;
    background-color: black;
    color: white;
    border: 2px solid transparent;
    border-radius: 8px;
    font-size: 18px;
    letter-spacing: 1px;
    font-weight: 600;
    transition: 0.3s ease;
    cursor: pointer;
}
.btn-1:hover{
    background-color: white;
    color: black;
    border: 2px solid black;
}
.btn-2{
    padding: 15px 28px;
    background-color: orangered;
    color: white;
    border: 2px solid black;
    border-radius: 8px;
    font-size: 18px;
    letter-spacing: 1px;
    font-weight: 600;
    transition: 0.3s ease;
    cursor: pointer;
}
.btn-2:hover{
    background-color: white;
    color: orangered;
}
.img-box img{
    border-radius: 50%;
    width: 300px;
}

::-webkit-scrollbar{
    width: 15px;
}
::-webkit-scrollbar-thumb{
    background-color: orangered;
}
::-webkit-scrollbar-thumb{
    background-color: rgb(0, 0, 0, 0.6);
    width: 50px;
}

.about{
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 12% 8%;
    gap: 100px;
    background: black;
}
.about-img img{
    /* position: relative; */
    width: 550px;
    box-shadow: 0 0 25px orangered,
                0 0 50px orangered;
                border-radius: 50px;
}
.about-content h2{
    text-align: right;
    color: white;
    font-size: 42px;
}
.about-content h3{
    font-size: 62px;
    color: white;
}
.about-content p{
    color: white;
    font-size: 20px;
    margin: 2em 0 3em;
}

