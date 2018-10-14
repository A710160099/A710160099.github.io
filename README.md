<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Karma">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Karma", sans-serif}
.w3-bar-block .w3-bar-item {padding:20px}
</style>
<body>

<!-- Sidebar (hidden by default) -->
<nav class="w3-sidebar w3-bar-block w3-card w3-top w3-xlarge w3-animate-left" style="display:none;z-index:2;width:40%;min-width:300px" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()"
  class="w3-bar-item w3-button">Close Menu</a>
  <a href="#galery" onclick="w3_close()" class="w3-bar-item w3-button">Home</a>
  <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">About</a>
</nav>

<!-- Top menu -->
<div class="w3-top">
  <div class="w3-white w3-xlarge" style="max-width:1200px;margin:auto">
    <div class="w3-button w3-padding-16 w3-left" onclick="w3_open()">☰</div>
    <div class="w3-right w3-padding-16">Jati Wahyu</div>
    <div class="w3-center w3-padding-16">My Galery (Laira_Hijab)</div>
  </div>
</div>
  
<!-- !PAGE CONTENT! -->
<div class="w3-main w3-content w3-padding" style="max-width:1200px;margin-top:100px">

  <!-- First Photo Grid-->
  <div class="w3-row-padding w3-padding-16 w3-center" id="food">
    <div class="w3-quarter">
      <img src="gamis set alliya.png" alt="Klliya" style="width:100%">
      <h3>Gamis Set Alliya </h3>
      <p>Bahan yang digunakan wolfis, sangat adem dan tidak transparan. Harganya Rp 265.000,-.</p>
    </div>
    <div class="w3-quarter">
      <img src="gamis set kayla.png" alt="Kayla" style="width:100%">
      <h3>Gamis Set Kayla </h3>
      <p>Bahan yang digunakan juga wolfis namun bermotif jadi terlihat lebih cantik.Harganya Rp 285.000,-.</p>
    </div>
    <div class="w3-quarter">
      <img src="gamis set asyita.png" alt="Asyita" style="width:100%">
      <h3>Gamis Set Asyita</h3>
      <p>Bahan yang digunakan wolfis, adem dan tidak mudah kusut.Harganya Rp 270.000,-.</p>
    </div>
    <div class="w3-quarter">
      <img src="gamis set alana.png" alt="Alana" style="width:100%">
      <h3>Gamis Set Alana</h3>
      <p>Bahan katun dan tebal. Harganya Rp 270.000,-.</p>
    </div>
  </div>
  
  <!-- Second Photo Grid-->
  <div class="w3-row-padding w3-padding-16 w3-center">
    <div class="w3-quarter">
      <img src="gamis set kiara.png" alt="Kiara" style="width:100%">
      <h3>Gamis Set Kiara</h3>
      <p>Bahan wolfis embos dan harganya Rp 285.000,- .</p>
    </div>
    <div class="w3-quarter">
      <img src="gamis couple alliya.png" alt="Couple Alliya" style="width:100%">
      <h3>Gamis Couple Alliya</h3>
      <p>Bahan gamis wolfis, bahan kemeja katun, dan harganya Rp 380.000,- .</p>
    </div>
    <div class="w3-quarter">
      <img src="gamis set anaya.png" alt="Anaya" style="width:100%">
      <h3>Gamis Set Anaya</h3>
      <p>Bahan gamis maxmara, bahan khimar wolfis dan harganya Rp 275.000,-.</p>
    </div>
    <div class="w3-quarter">
      <img src="khimar serut.png" alt="Khimar Serut" style="width:100%">
      <h3>Khimar serut</h3>
      <p>Bahannya Wolfis dan harganya Rp 100.000,-.</p>
    </div>
  </div>

  <!-- Pagination -->
  <div class="w3-center w3-padding-32">
    <div class="w3-bar">
      <a href="#" class="w3-bar-item w3-button w3-hover-black">«</a>
      <a href="#" class="w3-bar-item w3-black w3-button">1</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">2</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">3</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">4</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">»</a>
    </div>
  </div>
  
  <hr id="about">

  <!-- About Section -->
  <div class="w3-container w3-padding-32 w3-center">  
    <h3>About Me</h3><br>
    <img src="jati.JPG" alt="Jati Wahyu Sriartianingsih" style="width:100%">
    <div class="w3-padding-32">
      <p>Assalamu'alaikum shalihah. Perkenalkan nama saya Jati Wahyu Sriartianingsih,saat ini saya kuliah di Universitas Muhammadiyah Surakarta semesster 5.
	  kalian lagi nyari gamis syar'i ? nih aku ada solusinya. Insya Allah tidak mengecewakan. kepoin aja ignya ya (Laira_hijab).</p>
    </div>
  </div>
  <hr>
  
  <!-- Footer -->
  <footer class="w3-row-padding w3-padding-32">
    <div class="w3-third">
      <h3>FOOTER</h3>
      <p>ONLINE SHOP GAMIS SYAR'I</p>
      <p>Owner Laila Nisaul Hikmah dan Admin Jati Wahyu Sriartianingsih  <a href="https://www.w3schools.com/w3css/default.asp" target="_blank">w3.css</a></p>
    </div>
	
	<!-- Contact Section -->
  <div class="w3-container w3-padding-large w3-grey">
    <h4 id="contact"><b>Contact Me</b></h4>
    <div class="w3-row-padding w3-center w3-padding-24" style="margin:0 -16px">
      <div class="w3-third w3-dark-grey">
        <p><i class="fa fa-envelope w3-xxlarge w3-text-light-grey"></i></p>
        <p>jatiwahyu2298@gmail.com</p>
      </div>
      <div class="w3-third w3-teal">
        <p><i class="fa fa-map-marker w3-xxlarge w3-text-light-grey"></i></p>
        <p>Surakarta, ID</p>
      </div>
      <div class="w3-third w3-dark-grey">
        <p><i class="fa fa-phone w3-xxlarge w3-text-light-grey"></i></p>
        <p>082137801563</p>
      </div>
	  </div>
    <hr class="w3-opacity">
    <form action="/action_page.php" target="_blank">
      <div class="w3-section">
        <label>Name</label>
        <input class="w3-input w3-border" type="text" name="Name" required>
      </div>
      <div class="w3-section">
        <label>Email</label>
        <input class="w3-input w3-border" type="text" name="Email" required>
      </div>
      <div class="w3-section">
        <label>Message</label>
        <input class="w3-input w3-border" type="text" name="Message" required>
      </div>
      <button type="submit" class="w3-button w3-black w3-margin-bottom"><i class="fa fa-paper-plane w3-margin-right"></i>Send Message</button>
    </form>
  </div>

  
    <div class="w3-third">
      <h3>BLOG POSTS</h3>
      <ul class="w3-ul w3-hoverable">
        <li class="w3-padding-16">
          <img src="gamis set alliya.png" class="w3-left w3-margin-right" style="width:50px">
          <span class="w3-large">Gamis</span><br>
          <span>Gamis Alliya</span>
        </li>
        <li class="w3-padding-16">
          <img src="khimar serut.png" class="w3-left w3-margin-right" style="width:50px">
          <span class="w3-large">Khimar</span><br>
          <span>Khimar Serut</span>
        </li> 
      </ul>
    </div>

    <div class="w3-third w3-serif">
      <h3>POPULAR TAGS</h3>
      <p>
        <span class="w3-tag w3-black w3-margin-bottom">Boyolali</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Surakarta</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Indonesia</span>
        <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Gamis Anaya</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Hijau</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Baju</span>
        <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Gamis Kiara</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Abu</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Baju</span>
        <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Gamis Alana</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Cream</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Baju</span>
        <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Gamis Kayla</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Ungu</span>
      </p>
    </div>
  </footer>

<!-- End page content -->
</div>

<script>
// Script to open and close sidebar
function w3_open() {
    document.getElementById("mySidebar").style.display = "block";
}
 
function w3_close() {
    document.getElementById("mySidebar").style.display = "none";
}
</script>

</body>
</html>
