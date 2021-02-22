<template>
  <div>
    <div id="header">
      <nav class="navbar navbar-expand-lg navbar-dark">
        <img id="icone" src="../assets/Icon.png" />
        <p id="logo">MASTERCLASS</p>
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#nav-mobile"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="menu collapse navbar-collapse" id="nav-mobile">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item"><a href="#" class="nav-link">HOME</a></li>
            <li class="nav-item"><a href="#" class="nav-link">SERVICES</a></li>
            <li class="nav-item"><a href="#" class="nav-link">GALLERY</a></li>
            <li class="nav-item"><a href="#" class="nav-link">TESTIMONY</a></li>
            <li id="icons" class="nav-item">
              <a href="#" class="nav-link"
                ><img class="social img-fluig" src="../assets/twitter.png"
              /></a>
              <a href="#" class="nav-link"
                ><img class="social img-fluig" src="../assets/facebook.png"
              /></a>
            </li>
          </ul>
        </div>
      </nav>
    </div>
    <div id="services" class="p-3 p-md-5">
      <div class="information">
        <img
          id="iconYellow"
          src="../assets/IconYellow.png"
          class="img-fluig"
        /><br />
        <h1>The Master<span>&nbsp;Class!</span></h1>
        <h2>
          At vero eos et accusam us odio digniss imos At vero eos et accusam us
          odio dignissimos At vero eos et accusam us odio dignissimos
        </h2>
        <br />
        <button type="button" class="btn">EXPLORE NOW!</button>
        <div id="circle" />
        <div id="box">
          <h3>Don't Forget<span>&nbsp;To Join With Us!</span></h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed dolor
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ur
            incididunt ut labore
          </p>
          <button id="btn1" type="button" class="btn">START NOW</button>
          <button id="btn2" type="button" class="btn">JOIN NOW</button>
        </div>
      </div>
    </div>
    <div class="gallery">
      <h1>Master<span>&nbsp;Classes!</span></h1>
      <h2>The Most Creative Company That Leads You !</h2>
      <div id="circle" />
    </div>
    <div class="gallery2">
      <div class="row">
        <div class="col-lg">
          <div id="img"><img src="" alt="" /></div>
          <h4>JUNIOR CLASS</h4>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Explicabo
            id iure dolores tempora. Odio deleniti atque ex.
          </p>
          <button id="btn2" type="button" class="btn">See More</button>
        </div>
        <div class="col-lg">
          <div id="img"><img src="" alt="" /></div>
          <h4>MIDDLE CLASS</h4>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Explicabo
            id iure dolores tempora. Odio deleniti atque ex.
          </p>
          <button id="btn2" type="button" class="btn">See More</button>
        </div>
        <div class="col-lg">
          <div id="img"><img src="" alt="" /></div>
          <h4>THIRD CLASS</h4>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Explicabo
            id iure dolores tempora. Odio deleniti atque ex.
          </p>
          <button id="btn" type="button" class="btn">See More</button>
        </div>
      </div>
    </div>
    <div id="footer" class="p-3 p-md-5">
      <div class="row">
        <div class="col-lg">
          <h3>About Us</h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Lorem
            ipsum dolor sit amet, consectetur adipisicing elit.
          </p>
        </div>
        <div class="col-lg">
          <h3>Link Website</h3>
          <p>www.MasterClass22.com<br />www.MasterClassCompany.com</p>
        </div>
        <div class="col-lg">
          <h3>Address</h3>
          <p>Grande Street 54D 4545 <br />Fax 1006767 Grande ST, Copenhagen</p>
          <p>
            Kurtheus Street 12D 6767 <br />Fax 1004323 Kurtheus ST, Copenhagen
          </p>
        </div>
        <div class="col-lg">
          <h3>Follow Our Social Media</h3>
          <div class="redesSociais">
            <span
              ><a href=""><img width="40" src="../assets/Icon-3.png" /></a
            ></span>
            <span
              ><a href=""><img width="40" src="../assets/Icon-2.png" /></a
            ></span>
            <span
              ><a href=""><img width="40" src="../assets/Icon-1.png" /></a
            ></span>
            <span
              ><a href=""><img width="40" src="../assets/Icon-0.png" /></a
            ></span>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {},
};
</script>
<style scoped>
.container {
  font-family: "Segoe UI" !important;
}
#header {
  font-family: "Segoe UI";
  display: block;
  background-color: #d8cd00;
  width: 100%;
  height: 15vh;
  align-items: center;
}

#icone {
  height: 5vh;
  margin: 2vh 3vh 0vh 5vh;
}
#logo {
  font: 2em sans-serif;
  font-weight: 700;
  color: #fff;
  margin-top: 3vh;
  align-self: center;
}
.menu ul {
  background-color: #d8cd00;
  border-radius: 12px;
  display: inline-flex;
  float: right;
  justify-content: space-between;
  align-items: center;
}
.menu li {
  font: 1.3em sans-serif;
  padding: 0vh 1vh;
  font-weight: 600;
  color: #fff;
}
.menu li#icons {
  display: inline-flex;
}
.social {
  height: 6vh;
  margin-right: 1vh;
}
#services {
  font-family: "Segoe UI";
  display: flex;
  background: url("../assets/bg.svg");
  max-height: 110vh;
  justify-content: center;
  align-content: center;
}
#iconYellow {
  margin-top: 3vh;
  height: 15vh;
}
.information h1 {
  color: #fff;
  margin-top: 5vh;
  font: 3.5em sans-serif;
  font-weight: 600;
  letter-spacing: 0.4rem;
}
span {
  color: #d8cd00;
}
.information h2 {
  display: inline-flex;
  width: 60vw;
  color: #fff;
  margin-top: 3vh;
  font: 1.3em sans-serif;
  opacity: 0.6;
  line-height: 2;
}
.btn {
  background-color: #d8cd00;
  color: #fff;
  border-radius: 30px;
  letter-spacing: 0.3rem;
  height: 8vh;
  font: 1.8em sans-serif;
  margin-top: 5vh;
  font-weight: 700;
  padding: 5px 50px 5px 50px;
}
.btn:hover {
  opacity: 0.7;
}
#circle {
  background-color: #d8cd00;
  height: 5vh;
  width: 5vh;
  border-radius: 80px;
  margin: 5vh auto 0 auto;
}
#box {
  font-family: "Segoe UI";
  position: relative;
  background-color: #fff;
  align-content: space-between;
  width: 80vw;
  margin-top: 5vh;
  min-height: 30vh;
  padding: 6vh;
  border-radius: 60px;
  box-shadow: #252223;
  box-shadow: 0px 10px 10px 5px rgba(37, 34, 35, 0.2);
}
#box h3 {
  font: 2.5em sans-serif;
  font-weight: 600;
  color: #252223;
  opacity: 0.8;
}
#box p {
  margin-top: 3vh;
  font: 1.3em sans-serif;
  color: #252223;
  opacity: 0.2;
  max-width: 130vh;
  margin-left: auto;
  margin-right: auto;
}
#box #btn1 {
  background-color: #d8cd00;
  color: #fff;
  border-radius: 13px;
  height: 5.5vh;
  font: 1.5em sans-serif;
  font-weight: 600;
  padding: 7px 30px 7px 30px;
  margin-right: 2vh;
}
#box #btn2 {
  background-color: #fff;
  color: #d8cd00;
  border: 2px #d8cd00 solid;
  border-radius: 13px;
  height: 5.5vh;
  font: 1.5em sans-serif;
  font-weight: 600;
  padding: 7px 30px 7px 30px;
}
.gallery {
  background-color: white;
  height: 80vh;
  padding: 30vh;
  font-weight: 700;
}
.gallery h1 {
  font: 3.5em sans-serif;
  font-weight: 700;
}
.gallery h2 {
  font-family: "Segoe UI";
  font: 1.9em sans-serif;
  color: #252223;
  opacity: 0.4;
  font-style: italic;
  letter-spacing: 0.2rem;
}
.gallery2 {
  background-color: #d8cd00;
  min-height: 40vh;
  padding: 0 25vh 0 25vh;
}
.gallery2 #img {
  height: 30vh;
  width: 30vh;
  background-color: #a3a3a3;
  margin: -15vh auto 5vh auto;
  border-radius: 50px;
}
.gallery2 h4 {
  font-family: "Segoe UI";
  font: 1.5em sans-serif;
  color: #fff;
  font-weight: 600;
}
.gallery2 p {
  width: 40vh;
  font-family: "Segoe UI";
  font: 1.2em sans-serif;
  color: #fff;
  margin: 5vh auto 0 auto;
  opacity: 0.8;
}
.gallery2 .btn {
  color: #fff;
  border: 1px #fff solid;
  border-radius: 5px;
  font: 1em sans-serif;
  padding: 0 20px 0 20px;
  margin: 5vh 0 5vh 0;
  letter-spacing: 0.1rem;
  font-weight: 500;
  height: 5vh;
}
.btn:hover {
  box-shadow: 0px 5px 5px 5px rgba(92, 88, 88, 0.2);
}
#footer {
  border-top: 2vh #fff solid;
  background-color: #252223;
}
#footer h3 {
  color: #d8cd00;
  font-weight: 600;
  font: 1.2em sans-serif;
  margin-bottom: 1.5vh;
}
#footer p {
  color: #fff;
  opacity: 0.5;
  font: 0.9em sans-serif;
}
.redesSociais img {
  display: inline-flex;
  margin-bottom: 2vh;
}
@media (max-width: 767px) {
  #header {
    max-height: 10vh;
    width: 100%;
  }
  #icone {
    height: 5vh !important;
    margin: 0vh;
  }
  #logo {
    font: 1.2em sans-serif;
    font-weight: 700;
    color: #fff;
    margin: 0vh;
  }
  span {
    display: inline-flex;
  }
  #services {
    width: 100%;
    max-height: 210vh;
  }
  .btn {
    height: 10vh;
    font: 1.2em sans-serif;
    margin-top: 5vh;
    font-weight: 700;
    padding: 0 4vh;
  }

  .information h2 {
    width: 80vw;
  }
  #box {
    width: 100%;
    margin: 5vh auto 0 auto;
  }
  #box p {
    max-width: 40vh;
    font: 1.2em sans-serif;
  }
  #box #btn1 {
    height: 8vh;
    font: 1em sans-serif;
    padding: 0 2vh;
    font-weight: 700;
  }
  #box #btn2 {
    height: 8vh;
    font: 1em sans-serif;
    padding: 0 2vh;
    font-weight: 700;
  }
  .gallery {
    margin-top: 50vh;
    height: 55vh;
    padding: 0;
    width: 100%;
  }
  .gallery h1 {
    display: inline-flex;
    font: 2em sans-serif;
    font-weight: 700;
    margin: 0 auto;
  }
  .gallery h2 {
    font: 1.5em sans-serif;
    margin: 0 auto;
  }
  .gallery2 {
    padding: 0;
    max-height: 240vh;
    width: 100%;
  }
  .gallery2 h4 {
    max-width: 180px;
    margin: 0 auto;
  }
  .gallery2 .btn {
    margin-bottom: 20vh;
  }
  .gallery2 .row{
    margin: 0 !important;
  }
}
@media (max-width: 420px) and (min-width: 350px) {
  #services {
    height: 190vh;
  }
  .information h2 {
    width: 80vw;
  }
  .gallery {
    margin: 40% auto 0 auto;
    height: 45vh;
    padding: 0 0 20vh 0;
    width: 100%;
  }
  .gallery h2{
    max-width: 80%;
  }
  .gallery2 {
    width: 100%;
    max-height: 220vh;
  }
  .gallery2 .row{
    margin: 0 !important;
  }
}
@media (max-width: 599px) and (min-width: 421px) {
  #services {
    height: 180vh;
  }
  .information h2 {
    width: 90vw;
  }
  .gallery {
    width: 100%;
    margin: 60% auto 0 auto;
    height: 45vh;
    padding: 0 0 15vh 0;
  }
  .gallery2 {
    width: 100%;
  }
  .gallery2 .row{
    margin: 0 !important;
  }
}
@media (max-width: 800px) and (min-width: 600px) {
  #box p {
    max-width: 70vh;
  }
  .gallery {
    width: 100%;
    margin-top: 35vh;
    height: 45vh;
    padding: 0 0 15vh 0;
  }
  .gallery h2 {
    max-width: 70vh;
    margin: 2vh auto 0 auto;
  }
  .gallery2 {
    width: 100%;
    margin: 5vh auto 0 auto;
    padding: 0;
    max-height: 170vh;
  }
  .gallery2 .row{
    margin: 0 !important;
  }
  .gallery2 .btn {
    margin-bottom: 20vh;
  }
  .gallery2 p {
    width: 100vh;
    margin: 0 auto;
  }
}
</style>
