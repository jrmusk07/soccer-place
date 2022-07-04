<template>
  <div>
    <header>
      <div class="hero" id="hero">
        <nav>
          <div class="my__options">
            <div class="logo">
              <span><img src="../assets/images/ball-32px.png" alt="" /></span>
              <p>Alibeyköy</p>
            </div>
            <ul>
              <li>
                <a href="#hero"> Anasayfa </a>
              </li>
              <div id="hero">
                <span class="option"
                  ><img
                    src="../assets/images/home.svg"
                    alt="homepage"
                    width="30px"
                    height="30px"
                /></span>
              </div>
              <li>
                <a href="#how__its__works"> İşlem</a>
              </li>
              <span class="option"
                ><img
                  src="../assets/images/success.svg"
                  alt="homepage"
                  width="30px"
                  height="30px"
              /></span>
              <li>
                <a href="#features"> Özellikler</a>
              </li>
              <span class="option"
                ><img
                  src="../assets/images/awards.svg"
                  alt="homepage"
                  width="30px"
                  height="30px"
              /></span>
              <li>
                <a href="#contact"> İletişim</a>
              </li>
              <span class="option"
                ><img
                  src="../assets/images/call-phone.svg"
                  alt="homepage"
                  width="30px"
                  height="30px"
              /></span>
            </ul>
          </div>
        </nav>
        <div class="div__information">
          <h4>Takımınla ve rakibinle harika , keyifli zaman geçir!</h4>
          <p>
            Takımını topla , rakibini belirle ve gerisini bize bırak! Seni
            ulaşım kolaylığı olan,<b><i>UEFA onaylı</i></b> harika bir çime
            sahip olan,güvenliği ve temizliği titizlikle yapılan sahamıza
            bekliyoruz.
          </p>
          <button><a href="#contact">İletişim</a></button>
        </div>
      </div>
    </header>

    <!-- How it's works -->
    <div class="how__its__works" id="how__its__works">
      <p class="how_its_works_title">Nasıl bir süreç işler ?</p>
      <div class="how_its_works">
        <div class="item item1">
          <img
            src="../assets/images/team.svg"
            width="200px"
            height="200px"
            alt="team"
          />
          <p>
            8'e 8 veya 7'e 7 olacak şekilde (önerilen) takımını ve rakibini
            belirle.
          </p>
        </div>
        <div class="item item2">
          <img
            src="../assets/images/calling.svg"
            width="200px"
            height="200px"
            alt="team"
          />
          <p>Bize kolayca ulaş ve istediğin saat için rezarvasyon yap.</p>
        </div>
        <div class="item item3">
          <img
            src="../assets/images/booking.svg"
            width="200px"
            height="200px"
            alt="team"
          />
          <p>
            İşlem tamam! Rezarvasyon saatinde halısahada ol ve keyfini çıkar!
          </p>
        </div>
      </div>
    </div>

    <div class="gallery">
      <p class="place__title">Sahamızdan bazı görüntüler</p>
      <div class="soccerplace__images">
        <div class="soccerplace__image">
          <img
            src="../assets/images/image4.png"
            height="400px"
            width="400px"
            alt=""
            class="place_image_one place_image1"
          />
        </div>
        <div class="soccerplace__image">
          <img
            src="../assets/images/image2.png"
            height="400px"
            width="400px"
            alt=""
            class="place_image_one place_image2"
          />
        </div>
        <div class="soccerplace__image">
          <img
            src="../assets/images/image3.png"
            height="400px"
            width="400px"
            alt=""
            class="place_image_one place_image3"
          />
        </div>
        <div class="soccerplace__image">
          <img
            src="../assets/images/image5.png"
            height="400px"
            width="400px"
            alt=""
            class="place_image_one place_image4"
          />
        </div>
        <div class="soccerplace__image">
          <img
            src="../assets/images/image1.png"
            height="400px"
            width="400px"
            alt=""
            class="place_image_one place_image5"
          />
        </div>
        <div class="soccerplace__image">
          <img
            src="../assets/images/image6-second.png"
            height="400px"
            width="400px"
            alt=""
            class="place_image_one place_image6"
          />
        </div>
      </div>
    </div>
    <p class="feature__title">Bazı kolaylaştırıcı özelliklerimiz</p>
    <div class="our__features" id="features">
      <div class="feature feature1">
        <img
          src="../assets/images/approve.svg"
          width="260px"
          height="260px"
          alt=""
        />
        <h4>UEFA onaylı çim</h4>
        <p>
          Halısahamızın çimi daha yeni yapılmış ve UEFA onaylı , birince derece
          kalitededir.
        </p>
      </div>
      <div class="feature feature2">
        <img
          src="../assets/images/secure.svg"
          width="280px"
          height="280px"
          alt=""
        />
        <h4>Güvenlik</h4>
        <p>
          Sahamız 7/24 kamera ile izlenir ve personellerimiz her zaman dikkatle
          davranır.
        </p>
      </div>
      <div class="feature feature3">
        <img
          src="../assets/images/coffe.svg"
          width="300px"
          height="300px"
          alt=""
        />
        <h4>Hizmet</h4>
        <p>
          Maçtan sonra bir şeyler içmeye ne dersiniz ? Size hizmet sunacak bir
          kafetaryamız da mevcut.
        </p>
      </div>
      <div class="feature feature4">
        <img
          src="../assets/images/subway.svg"
          width="300px"
          height="300px"
          alt=""
        />
        <h4>Ulaşım</h4>
        <p>
          T5 Cibali - Alibeyköy Cep Otagarı hattını kullanırsanız Alibeyköy
          durağında inin, saha önünüzde olacak :)
        </p>
      </div>
    </div>
    <p class="title__contact">Zaman kaybetme , hemen iletişime geç !</p>
    <div class="contact__us" id="contact">
      <div class="images__contact">
        <img
          src="../assets/images/contact.svg"
          alt=""
          width="300px"
          height="300px"
        />
      </div>
      <div class="information__us">
        <h3>Aramıza katıl !</h3>
        <p>Bize kolayca ulaş ve yerini ayırttır. Sizi bekliyor olacağız !</p>
        <p>
          Adres : Alibeyköy, Namık Kemal Cd. No:4, 34060
          Eyüp/Eyüpsultan/İstanbul
        </p>
        <span class="contact__number"
          ><img src="../assets/images/calling_contact.svg" alt="" />İletişim :
          536 935 66 15</span
        >
        <span class="contact__number"
          ><img src="../assets/images/calling_contact.svg" alt="" />İletişim :
          552 547 19 22</span
        >
      </div>
      <div class="social__media">
        <ul>
          <li><img src="../assets/images/instagram.svg" alt="" /></li>
          <li><img src="../assets/images/facebook.svg" alt="" /></li>
          <li><img src="../assets/images/twitter.svg" alt="" /></li>
        </ul>
      </div>
    </div>
    <div class="copyright">
      <span class="copyright__span">&#169; oquzhN. All rigths reserved</span>
    </div>
  </div>
</template>
<script></script>
<style>
:root {
  --orange: #ff8200;
  --blue: #2176ff;
  --blue2: #1f71ff;
  --black: #000;
  --background-white: #f8f9fa;
  --white: #fff;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
.hero {
  background: url(../assets/images/soccer-img3-original.jpg);
  width: 100%;
  height: 100vh;
  background-size: cover;
  background-position: top;
}
nav {
  height: 8%;
  width: 100%;
  overflow: hidden;
  background-color: var(--blue2);
  position: fixed;
  top: 0;
  display: flex;
}
.my__options {
  width: 80%;
  height: 40%;
  /* background-color: black; */
  margin: auto;
  display: flex;
  justify-content: space-around;
  align-items: center;
}
.my__options ul {
  display: flex;
  justify-content: space-around;
  max-width: 600px;
}
.my__options ul li {
  padding: 0 20px;
  list-style: none;
}
.my__options ul li a {
  text-decoration: none;
  color: var(--white);
}

.option {
  display: none;
  cursor: pointer;
}
.my__options ul li a:hover {
  color: rgb(229, 229, 229);
  transition: all ease-in 0.3s;
}
.logo {
  display: flex;
  justify-content: center;
  align-items: center;
}
.logo p {
  padding-left: 0.5rem;
  font-size: 24px;
  color: var(--white);
  font-weight: 600;
}
.div__information {
  margin: auto;
  text-align: center;
  max-width: 1000px;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding-top: 12rem;
  color: var(--white);
}
.div__information > * {
  margin: 2rem;
}
.div__information h4 {
  font-size: 30px;
}
.div__information p {
  font-size: 24px;
}
.div__information button {
  padding: 14px;
  border-radius: 7px;
  border: none;
  /* border: 2px solid var(--blue2); */
  background-color: var(--blue2);
  font-size: 18px;
  font-weight: 700;
}
.div__information button a {
  text-decoration: none;
  color: var(--white);
}
.div__information button a:hover {
  color: var(--black);
  background-color: var(--blue2);
  transition: all 0.7s;
}
.how_its_works {
  display: grid;
  grid-gap: 20px;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  margin-top: 4rem;
  background-color: var(--background-white);
}
.item {
  text-align: center;
  padding: 20px;
  width: 80%;
  margin: auto;
  /* background-color: black; */
}
.item p {
  font-size: 16px;
  font-weight: 300;
  letter-spacing: 1px;
  margin-top: 0.6rem;
}
.how_its_works_title {
  font-size: 28px;
  display: flex;
  justify-content: center;
  margin-top: 4rem;
  font-weight: 300;
}
/* .how__title {
  display: grid;
  grid-column: 1 / -1;
  margin: auto;
  font-size: 20px;
  font-weight: 700;
  margin-bottom: 0.7rem;
} */

.soccerplace__images {
  display: grid;
  grid-template-columns: repeat(auto-fit, 400px);
  grid-auto-rows: 400px;
  grid-gap: 20px;
  margin-top: 3rem;
  justify-content: center;
  align-content: center;
  /* grid-auto-flow: dense; */
}
.soccerplace__images .soccerplace__image {
  overflow: hidden;
  margin: auto;
  /* grid-column: 1 / -1; */
}
.place_image_one {
  opacity: 0.8;
  transition: all 0.6s;
}
.place_image_one:hover {
  opacity: 1;
}
.place_image_one:clic {
  opacity: 1;
}
.place__title {
  text-align: center;
  margin-top: 3rem;
  font-size: 28px;
  font-weight: 300;
}
.our__features {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: repeat(2, 1fr);
  margin: 3rem;
  align-items: center;
  text-align: center;
  grid-gap: 2rem;
  padding: 2rem;
  background-color: #f8f9fa;
}
.feature {
  max-width: 300px;
  margin: auto;
}
.feature p {
  margin-top: 0.8rem;
  font-weight: 300;
}
.feature h4 {
  font-weight: 400;
  font-size: 18px;
  color: var(--black);
}
.feature__title {
  font-size: 28px;
  font-weight: 300;
  letter-spacing: 1px;
  display: flex;
  justify-content: center;
  margin-top: 3rem;
}
.information__us {
  padding: 1rem;
}
.contact__us {
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color: var(--background-white);
  color: var(--black);
  padding-top: 2rem;
  font-weight: 400;
}
.contact__us h3 {
  margin: 1rem 0;
}
.contact__us span {
  margin: 1rem 0;
  display: flex;
  align-items: center;
}
.contact__number {
  font-weight: 600;
  font-size: 16px;
  color: var(--black);
  border-bottom: 1px solid var(--blue);
  padding-bottom: 0.4rem;
}
.title__contact {
  font-weight: 900;
  font-size: 34px;
  text-align: center;
  margin: 2rem 0;
  color: var(--blue2);
  letter-spacing: 1px;
}
.social__media {
  position: absolute;
  text-align: center;
  right: 0.4rem;
  bottom: 2rem;
}
.social__media ul {
  display: flex;
  position: relative;
  flex-direction: column;
}
.social__media ul li {
  list-style: none;
  margin: 12px;
}
.social__media ul li img {
  height: 20px;
  width: 20px;
}

.copyright {
  width: 100%;
  display: flex;
  margin: 4rem 0 0.2rem 0;
}
.copyright__span {
  color: var(--orange);
  margin: auto;
  background-color: var(--background-white);
}

@media (max-width: 900px) {
  .my__options {
    position: fixed;
    background-color: var(--background-white);
    box-shadow: 0 8px 24px hsla(228, 66%, 45%, 0.15);
    /* ??????????????? */
    width: 90%;
    height: 7%;
    left: 0;
    right: 0;
    bottom: 2rem;
    margin: 0 auto;
    padding: 0.5rem 0.4rem;
    border-radius: 1.25rem;
    transition: 0.5s;
    color: var(--black);
  }
  .my__options ul li {
    display: none;
  }
  .my__options ul li a {
    display: none;
  }
  .option {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
  }
  .option img {
    grid-column: 2 / 3;
  }
  .logo {
    display: none;
  }
  nav {
    background-color: transparent;
  }
  .images__contact img {
    width: 200px;
    height: 200px;
  }
  .information__us p {
    font-size: 14px;
    padding: 0.4rem 0 0.4rem 0;
  }
  .information__us h4 {
    font-size: 14px;
  }
  .information__us span {
    font-size: 12px;
  }
  .div__information {
    max-width: 1000px;
    padding-top: 6rem;
    color: var(--white);
  }
  .contact__number {
    font-weight: 700;
    color: var(--black);
    border-bottom: 1px solid var(--blue);
    padding-bottom: 0.4rem;
  }
}
@media (max-width: 800px) {
  .our__features {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  }
  .title__contact {
    font-size: 26px;
  }
}
@media (max-width: 600px) {
  .div__information {
    padding-top: 1rem;
    color: var(--white);
  }
  .place_image_one {
    height: 340px;
    width: 340px;
    margin-top: 0;
  }
  .our__features {
    display: grid;
    grid-template-columns: repeat(1, 1fr);
    grid-template-rows: repeat(1, 1fr);
    margin: 1rem;
    grid-gap: 2rem;
    padding: 1rem;
  }
  .feature {
    max-width: 250px;
    margin: auto;
  }
  .feature h4 {
    font-weight: 400;
    font-size: 18px;
    color: var(--blue2);
  }
  .feature img {
    height: 200px;
    width: 200px;
  }
  .feature__title {
    font-size: 18px;
    font-weight: 300;
    letter-spacing: 1px;
    display: flex;
    justify-content: center;
    margin-top: 4rem;
  }
  .contact__us {
    flex-direction: column;
    justify-content: center;
  }
  .title__contact {
    font-size: 22px;
  }
}
@media (max-width: 344px) {
  .place_image_one {
    height: 320px;
    width: 320px;
    margin-top: 0;
  }
}
</style>
