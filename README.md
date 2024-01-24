<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Undangan Pernikahan</title>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width" />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@48,400,0,0"
    />
    <link rel="stylesheet" href="mike.css" />
    <script type="module" src="script.js"></script>
  </head>
  <body>

    @import url('https://fonts.googleapis.com/css2?family=Inria+Serif:wght@300;400;700&display=swap');

@import url('https://fonts.googleapis.com/css2?family=Style+Script&display=swap');

@import url('https://fonts.googleapis.com/css2?family=Niconne&display=swap');

* {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  padding: 0;
  margin: 0;
  overflow-x: hidden;
  font-family: 'Inria Serif', sans-serif;
  background-image: url('https://images.unsplash.com/photo-1601662528567-526cd06f6582?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=415&q=80');
  background-size: cover;
  background-position-x: center;
}

.navbar {
  position: fixed;
  top: 0;
  width: 100vw;
  height: 70px;
  background-color: rgba(255, 255, 255, 0.753);
  box-shadow: 0 3px 3px rgba(0, 0, 0, 0.253);
}

.navbar_wrapper {
  display: flex;
  flex: row;
  max-width: 1080px;
  height: inherit;
  margin: 0 auto;
  justify-content: space-between;
  align-items: center;
}

.brand {
  user-select: none;
  margin: 0;
  color: rgb(41, 41, 41);
}

.navbar_menu a {
  text-decoration: none;
  color: rgb(41, 41, 41);
  margin-left: 30px;
}

.navbar_menu a:hover {
  cursor: pointer;
  background-color: rgb(255, 190, 68);
  padding: 5px 8px;
  border-radius: 10px;
}

.hero {
  width: 100vw;
  height: 600px;
  background-image: url('weding.jpg');
  background-size: cover;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background-position: top;
  animation: start 1s alternate-reverse;
}

.hero h1 {
  font-size: 100px;
  margin: 0;
  color: rgb(12, 61, 12);
  font-family: 'Style Script';
  font-weight: lighter;
  letter-spacing: 5px;
  padding: 0;
}

.hero h3 {
  font-size: 32px;
  margin: 0;
  color: rgb(41, 41, 41);
  background-color: rgba(255, 255, 239, 0.37);
  padding: 5px 10px;
  border-radius: 20px;
}

.hero h2 {
  font-size: 45px;
  margin: 10px 0;
  color: rgb(41, 41, 41);
}

#akad {
  margin: 80px 0;
}

.line {
  height: 5px;
  border-radius: 10px;
  width: 35%;
  background-color: rgb(41, 41, 41);
  animation: line 2s infinite alternate;
}

@keyframes line {
  to {
    width: 30%;
  }
}

.ornament {
  width: 60%;
}

.bingkai {
  display: flex;
  justify-content: space-around;
  align-items: center;
  height: 90px;
}

#akad h1 {
  text-align: center;
  font-size: 64px;
  color: rgb(12, 61, 12);
  margin: 30px 0;
  font-family: 'Niconne';
  font-weight: bold;
}

/* Reset some default styles */
body, h1, h2, h3, p, img {
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Arial', sans-serif;
}

.invitation {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  
  
}

.header {
  text-align: center;
  margin-bottom: 20px;
}

.header h1 {
  color: rgb(12, 61, 12);
}
.header h2 {
  color: #333;
  font-size: 20px;
  margin-bottom: 30px;
}

.couple {
  display: flex;
  justify-content: space-around;
  margin-bottom: 20px;
}

.person {
  text-align: center;
  
}
.person h2 {
  font-family: 'Niconne';
  font-size: 40px;
  color: rgb(12, 61, 12);
}
.person img {
  width: 300px;
  height: 300px;
  border-radius: 50%;
  margin-bottom: 10px;
}

.details, .family {
  margin-bottom: 20px;
  color: rgb(12, 61, 12);

}

.details h3, .family h3 {
  
  border-bottom: 2px solid #333;
  padding-bottom: 20px;
  margin-bottom: 10px;
}

.details p {
  margin-bottom: 10px;
}

a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
  display: inline-block;
  padding: 10px 20px;
 
  border: 1px solid #333;
  border-radius: 5px;
  transition: background-color 0.3s;
}

a:hover {
  background-color: #333;
  color: #fff;
}

.section_wrap {
  max-width: 1080px;
  display: flex;
  flex-direction: row;
  margin: 0 auto;
  
}

.section_container_akad {
  height: 400px;
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  
}

#akad h3 {
  font-size: 30px;
  margin: 10px 0;
  color: rgb(41, 41, 41);
  height: 0px;
  text-align: center;
  font-size: 22px;
  
}

#akad p {
  font-size: 18px;
  margin: 10px 0;
  color: rgb(41, 41, 41);
  text-align: center;
}

#resepsi {
  margin: 80px 0;
}

#resepsi h1 {
  text-align: center;
  font-size: 64px;
  color: rgb(12, 61, 12);
  margin: 30px 0;
  font-family: 'Niconne';
  font-weight: bold;
}

.resepsi_img {
  flex: 1;
  height: 350px;
  border-radius: 10px;
  background-image: url('https://images.unsplash.com/photo-1511795409834-ef04bbd61622?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=869&q=80');
  background-size: cover;
  box-shadow: 3px 3px 3px rgba(0, 0, 0, 0.425);
}


.section_container_resepsi {
  height: 350px;
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

#resepsi h3 {
  font-size: 40px;
  margin: 10px 0;
  color: #333;
  font-family: 'Niconne';

}

#resepsi h4 {
  font-size: 18px;
  margin: 10px 0;
  color: rgb(41, 41, 41);
}

.details {
  color: rgb(41, 41, 41);

}
.details h1 {
  font-size: 20px;
}
.details h4 {
  font-family: 'Niconne';
  font-size: 45px;
  color: rgb(12, 61, 12);
 
}
.details p {
  color: rgb(41, 41, 41);
  font-weight: 500;
  margin-bottom: 10px;
}

.buku_tamu_container {
  height: 400px;
  background-image: url('https://images.unsplash.com/photo-1625038032515-308ab14d10b9?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80');
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: center;
}

#buku_tamu h1 {
  text-align: center;
  font-size: 64px;
  color: rgb(12, 61, 12);
  margin: 30px 0;
  font-family: 'Niconne';
  font-weight: bold;
}

#buku_tamu form {
  background-color: whitesmoke;
  max-width: 30%;
  height: auto;
  display: flex;
  flex-direction: column;

  padding: 30px 40px;
  gap: 10px;
  border-radius: 10px;
  box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.432);
}

#buku_tamu form input,
#buku_tamu form select,
#buku_tamu form textarea {
  padding: 5px;
  background-color: white;
  border-color: rgb(170, 170, 170);
  width: 100%;
}

#buku_tamu form select {
  padding: 5px;
  background-color: white;
  border-color: rgb(170, 170, 170);
  width: 100%;
}

#buku_tamu form button {
  border: none;
  padding: 10px;
  margin-top: 10px;
  background-color: rgb(12, 61, 12);
  color: white;
  width: 100%;
  border-radius: 10px;
}

#buku_tamu form button:hover {
  background-color: rgb(255, 190, 68);
  color: black;
  cursor: pointer;
}

.input {
  display: flex;
  justify-content: space-between;
  margin-top: 20px;
}

.btn {
  display: flex;
  flex-direction: row-reverse;
}

#map h1 {
  text-align: center;
  font-size: 64px;
  color: rgb(12, 61, 12);
  margin: 30px 0;
  font-family: 'Niconne';
  font-weight: bold;
}

.section_container_map {
  height: 350px;
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.map_img iframe {
  border-radius: 10px;
  box-shadow: 3px 3px 3px rgba(0, 0, 0, 0.425);
  width: 100%;
}

.map_img {
  flex: 1;
  height: 350px;
}

.map_list {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: whitesmoke;
  width: 160px;
  border-radius: 10px;
  margin: 10px 0;
  padding: 5px 10px;
  border: none;
  box-shadow: 3px 3px 3px rgba(0, 0, 0, 0.418);
  animation: zoom 1s infinite alternate;
}

@keyframes zoom {
  to {
    /* width: 165px; */
    padding: 7px 12px;
  }
}

.map_list:hover {
  cursor: pointer;
  background-color: rgb(255, 190, 68);
}

#gallery h1 {
  text-align: center;
  font-size: 64px;
 color: rgb(12, 61, 12);
  margin: 30px 0;
  font-family: 'Niconne';
  font-weight: bold;
}

.gallery_container {
  max-width: 1080px;
  border: 1px solid green;
  height: auto;
  margin: 0 auto;
  display: flex;
}

.selector_wrapper {
  max-width: 1080px;
  margin: 0 auto;
  display: flex;
  flex-direction: row;
  gap: 20px;
}

.gallery_list {
  width: 50%;
}

.gallery_list img {
  width: 100%;
  margin: 10px 0;
  border-radius: 20px;
  box-shadow: 3px 3px 3px rgba(0, 0, 0, 0.425);
}
.details {
  text-align: center;
  margin-bottom: 10px;
  font-weight: bold;
}
.details p {
  margin-bottom: 10px;

}
.details h2 {
  font-family: 'Niconne';
  color: rgb(12, 61, 12);
  font-size: 50px;
}


footer {
  width: 100vw;
  height: 70px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background-color: black;
  color: white;
  margin-top: 50px;
}
.family {
  font-family: 'Niconne';
  text-align: center;
  color: rgb(12, 61, 12);
 
}
.family h4 {
  font-size: 40px;
  
}
.family p {
  font-size: 30px;
}

footer h3,
footer p {
  margin: 0;
}

.bouquet {
  width: 400px;
  position: absolute;
  left: 0;
  top: 1050px;
  animation: animasi 2s infinite alternate;
}

.bouquet2 {
  width: 300px;
  position: absolute;
  right: 0;
  top: 1600px;
  animation: animasi 2s infinite alternate;
}

@keyframes animasi {
  to {
    transform: translateY(50px);
  }
}
    <!------------------------- NAVIGASI ------------------------->
    <nav class="navbar">
      <div class="navbar_wrapper">
        <h1 class="brand">Aryan & Rilin</h1>
        <menu class="navbar_menu">
          <a href="#akad">Undangan</a>
          <a href="#resepsi">Akad & Resepsi</a>
          <a href="#buku_tamu ">Buku Tamu</a>
          <a href="#map">Map</a>
          <a href="#gallery">Gallery</a>
        </menu>
      </div>
    </nav>
    <!------------------------- END NAVIGASI ------------------------->

    <!------------------------- HERO ------------------------->
    <div class="hero">
      <h2>The Wedding</h2>
      <h1>Aryan & Rilin</h1>
      <h3>Kupang, 24 Juli 2024</h3>
    </div>
    <!------------------------- END HERO ------------------------->

    <!------------------------- SECTION AKAD ------------------------->
    <section id="akad">
      <div class="bingkai">
        <div class="line"></div>
        <h1>Undangan</h1>
        <div class="line"></div>
      </div>
      <div class="invitation">
        <div class="header">
            <h2>dengan segala kerendahan hati dan dengan ungkapan syukur  atas karunia Tuhan,kami mengundang bapak/ibu saudara/i untuk menghadiri Acara pernikahan kami:</h2>
            <p>Tuhan membuat segala sesuatu indah pada waktunya.</p>
            <p>Indah saat Dia mempertemukan, indah saat Dia menumbuhkan kasih,</p>
            <p>dan indah saat Dia mempersatukan dalam suatu ikatan pernikahan kudus.</p>
        </div>
    
        <div class="couple">
            <div class="person">
                <img src="aryan.jpeg" alt="Foto Laki-laki">
                <h2>Ferdinan Aryan Bulu</h2>
                <p>Putra dari Bpk.Stefanus  & ibu Makdalena </p> 
            </div>
            <div class="person">
                <img src="Rilin.jpeg" alt="Foto Perempuan">
                <h2>Rilin</h2>
                <p>Putri dari Bpk.Umbu Yosep  & ibu Marta </p>
                
            </div>
           
        </div>
       
        
    </div>
    

            
        <section class="akad_img"></section>
        
      </div>
    </section>
    <!------------------------- END SECTION AKAD ------------------------->
    <div class="bouquet_container">
      <img
        class="bouquet"
        src="https://cdn.pixabay.com/photo/2020/09/01/18/13/background-5535928_960_720.png" alt="" />
    </div>

    <!------------------------- SECTION RESEPSI ------------------------->
    <section id="resepsi">
      <div class="bingkai">
        <div class="line"></div>
        <h1>Pemberkatan</h1>
        <div class="line"></div>
      </div>
      <div class="section_wrap wrap">
        <section class="resepsi_img"></section>
        <div class="section_container_resepsi">
          <h3>Pemberkatan:</h3>
          <p>Sabtu, 24 September 2024</p>
          <p>Pukul: 09.00 WIT s/d selesai</p>
          <p>Jl.2 lontar kayu putih</p>
          <p>Kupang</p>
          <h3>Resepsi :</h3>
          <p>Sabtu, 24 September 2024</p>
          <p>Pukul: 11.00 WIT s/d selesai</p>
          <p>Jl.2 lontar kayu putih</p>
          <p>Kupang</p>
        </div>
      </div>
    </section>

    <section>
      <div class="details">
        <p>merupakan suatu kebahagiaan bagi kami apabila bapak/i saudara/i berkenan hadir untuk memberikan doa restu </p>
        <p>atas perhatian kami ucapkan terima kasih.</p>
        <h4>Turut Mengundang :</h4>
        <h1>Keluarga Besar Mempelai Pria :</h1>
          <p>Bpk.Yohanes </p>
          <p>Ibu.Maria Makdalena</p>
          <h1>Keluarga Besar Mempelai Wanita :</h1>
          <p>Bpk.Jordan </p>
          <p>Ibu.Ratna wati</p>
        </div>
    </section>
    <!------------------------- END SECTION RESEPSI ------------------------->

    <img
      class="bouquet2"
      src="https://cdn.pixabay.com/photo/2016/06/27/14/42/flowers-1482644_960_720.png"
      alt=""
    />

    <!------------------------- SECTION BUKU TAMU ------------------------->
    <section id="buku_tamu">
      <div class="bingkai">
        <div class="line"></div>
        <h1>Buku Tamu</h1>
        <div class="line"></div>
      </div>
      <div class="buku_tamu_container">
        <form action="">
          <input required type="text" placeholder="Nama" />
          <textarea
            name="ucapan"
            placeholder="Ucapan & Doa"
            cols="30"
            rows="8"
          ></textarea>
          <select name="kehadiran">
            <option value="hadir">Hadir</option>
            <option value="tidak_hadir">Tidak Hadir</option>
          </select>

          <div class="btn">
            <button type="submit">Submit</button>
          </div>
        </form>
      </div>
    </section>
    <!------------------------- END SECTION BUKU TAMU ------------------------->

    <!------------------------- SECTION MAP ------------------------->
    <section id="map">
      <div class="bingkai">
        <div class="line"></div>
        <h1>Map</h1>
        <div class="line"></div>
      </div>
      <div class="section_wrap wrap">
        <div class="section_container_map">
          <button class="map_list">
            <span class="material-symbols-outlined"> </span>
            Dapatkan Lokasi
          </button>
          <button class="map_list">
            <span class="material-symbols-outlined"></span>
            Save ke Calender
          </button>
          <button class="map_list">
            <span class="material-symbols-outlined">  </span>
            Share Instagram
          </button>
        </div>
        <section class="map_img">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3927.184954988896!2d123.62047477409442!3d-10.165616609731858!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2c56835202965667%3A0x7c3f19dec6c4d69a!2sGMIT%20Jemaat%20Gloria%20Kayu%20Putih!5e0!3m2!1sid!2sid!4v1704711897223!5m2!1sid!2sid" 
            width="500" 
            height="350" 
            style="border:0;" 
            allowfullscreen="" 
            loading="lazy" 
            referrerpolicy="no-referrer-when-downgrade"></iframe>
        </section>
      </div>
    </section>
    <!------------------------- END SECTION MAP ------------------------->

    <!------------------------- SECTION GALLERY ------------------------->
    <section id="gallery">
      <div class="bingkai">
        <div class="line"></div>
        <h1>Gallery</h1>
        <div class="line"></div>
      </div>
      <div class="selector_wrapper">
        <div class="gallery_list">
          <img
            src="https://images.pexels.com/photos/1128782/pexels-photo-1128782.jpeg?auto=compress&cs=tinysrgb&w=500&h=750&dpr=1"
            alt="gallery"
          />
          <img
            src="https://images.unsplash.com/photo-1623428454614-abaf00244e52?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=387&q=80"
          />
          <img
            src="https://images.unsplash.com/photo-1520854221256-17451cc331bf?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80"
            alt="gallery"
          />
          <img
            src="https://images.unsplash.com/photo-1525328302834-764f32276842?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=387&q=80"
            alt="gallery"
          />
          <img
            src="https://images.unsplash.com/photo-1522673607200-164d1b6ce486?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80"
            alt="gallery"
          />
        </div>
        <div class="gallery_list">
          <img
            src="https://images.unsplash.com/photo-1582738412147-d29ca77b95cc?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=387&q=80"
          />
          <img
            src="https://images.pexels.com/photos/2970287/pexels-photo-2970287.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
            alt="gallery"
          />
          <img
            src="https://images.unsplash.com/photo-1544577081-57925b5dccb1?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=415&q=80"
            alt="gallery"
          />
          <img
            src="https://images.unsplash.com/photo-1509927083803-4bd519298ac4?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80"
            alt="gallery"
          />
        </div>

        
      </div>
      <div class="family">
       <h4>Terima Kasih</h4>
       <p>Atas Kehadiran Bapak/i,Saudara/i</p>
        <p>dalam pernikahan kami yang sederhana.</p>
        <p>Kebersamaan Anda Membuat hari ini menjadi luar biasa.</p>
        

       
    </section>
    <!------------------------- END SECTION GALLERY ------------------------->

    <!------------------------- FOOTER ------------------------->
    <footer>
      <p>Design By</p>
      <h3>MIkail Adi Moni</h3>
    </footer>
    <!------------------------- END FOOTER ------------------------->
  </body>
</html>
