<head>
<title>Script HTML</title>
<!-- 
  Made with love by addy
     Instagram: @addykece_
  Thanks to all <3
-->
</head>
<style>
:root {
--warna-bg: rgba(0, 0, 0, .5); 
--warna-teks: #fff;
--warna-bingkai: #fff;
--bingkai: 8px;
--bingkai-kiri: 2px solid var(--warna-bingkai);
--bingkai-kanan: 2px solid var(--warna-bingkai);
--gaya-font: 'Josefin Sans', sans-serif;
}
</style>
<body>
	
   <!-- Ganti Audio di sini --><audio id="linkmp3">https://j.top4top.io/m_2403jl3910.mp3</audio>
   
   <div id="bodyblur" onClick="mulaikonten()">
   <img src="https://i.postimg.cc/3NTNY2jN/intan.jpg" id="wallpaper"/>
     <p id="ket">Hai kamu! Klik sembarang tempat ya...</p>
   </div>
   
   <div id='Content'>
    
     <div><blockquote id='bq'>
       <div>
         <!-- Stiker untuk Konten -->
         <img src="https://feeldreams.github.io/peach12.gif" id="fotoakhir"/>
         <img src="https://feeldreams.github.io/peach1.gif" id="fotoakhir2"/>
         <img src="https://feeldreams.github.io/peachktw.gif" id="fotoakhir3"/>
       </div>

       <!-- Konten Pembukaan -->
       <p id="kalimat">Hai, Mantanku.. </p>
       <p id="kalimatb">Yang ke: <b id="angka" style="font-size:24px"></b></p>
       <p id="kalimatc">Ehh, canda canda :v ...</p>
       
       <!-- Konten Pembukaan Lanjutan -->
       <p id="kalimat1">Hai, intanwardani..</p>
       <p id="kalimatb1">Yang <b>Terindah </b></p>
       <p id="kalimatc1">Balikan Yuk </p>

       <!-- Konten Jawaban -->
       <p id="kalimat2">Yeaayy! </p>
       <p id="kalimatb2">Tapi.. dalam hitungan ke: <b id="ctimer" style="font-size:24px">7</b></p>
       <p id="kalimatc2">Kita <b>PUTUS</b> lagi ya :(</p>

       <!-- Konten Jawaban 2 -->
       <p id="kalimat3">Canda, wkwk</p>
       <p id="kalimatb3">Akhirnya kita balikan &gt;&lt;</p>
       <p id="kalimatc3">sa sayang ko </p>
     </blockquote></div>

     <!-- Tombol Multifungsi -->
     <div id="Tombol">
       <a id="By" onClick="multifungsi()">
         <b id="tmbl">Boleh</b>
       </a>
       
       <a id="Bn" onClick="ditolak()">Gamau</a>
       <a id="Bn2" onClick="ditolak2()"></a>
     </div>
     
     <span id="pesanWA">Iyaa sa mau balikan kok, hehe</span>
     
   </div>

<!-- Jangan Edit Bagian Ini --><script>
  ftom=0;jikapr=1;ftganti=0;flag=1;flagg=1;fungsi=0;fungsiAwal=0;var aw=0,ngetika;ngetika=ket.innerHTML;ket.innerHTML="";function ngetikAwal() {if(aw<ngetika.length){ket.innerHTML += ngetika.charAt(aw);aw++;setTimeout(ngetikAwal,50);} if(aw==ngetika.length){fungsiAwal=1;}}
  function showDiv() {ngetikAwal();wallpaper.style="opacity:.2;";pesanwhatsapp = pesanWA.innerHTML;Content.style = "margin-top:8vh";Bn2.innerHTML=Bn.innerHTML;Bn2.style.display="none";}
  function memulai(){suratin.style="transition:all 1s ease;transform:scale(.1);opacity:0";ket.style="transition:all 1s ease;transform:scale(.1);opacity:0";setTimeout(mulaikonten,300)}
  function mulaikonten() {if(fungsiAwal==1){audio.play();setTimeout(mulaihitung,1000);fungsiAwal=0;otomatis();ket.style="display:none";Content.style = "opacity:1;margin-top:4vh";bodyblur.style="opacity:.6;animation:none";wallpaper.style="transform: scale(1);opacity:1;";fotoakhir.style="display:inline-flex;";setTimeout(ftmuncul,200);bq.style = "position:relative;opacity:1;visibility:visible;transform: scale(1);border-radius:var(--bingkai);margin-top:0";fungsi=1;}}
  
  function ftmuncul(){
    if(ftganti==0){fotoakhir.style="display:inline-flex;opacity:1;transform:scale(1)";}
    if(ftganti==1){fotoakhir.src = fotoakhir2.src;fotoakhir.style="display:inline-flex;opacity:1;transition:all .7s ease;transform:scale(1);";}
    if(ftganti==2){fotoakhir.src = fotoakhir3.src;fotoakhir.style="display:inline-flex;opacity:1;transition:all .7s ease;transform:scale(1);";}
  }
  function fthilang(){fotoakhir.style="display:inline-flex;opacity:1;transition:all .7s ease;transform:scale(.1)";}
  function jjfoto(){fotoakhir.style.animation="rto .8s infinite alternate";}
  
  function tombol(){Tombol.style="opacity:1;transform: scale(1);";Bn.style="margin:12px 0 12px 12px";ftom=1;}
  function multifungsi(){if(ftom==1){diterima();} if(ftom==5){menuju();}}
  async function menuju(){await swals.fire('OK!', 'Kirim pesan ke sa eh <3!', 'success');window.location = "https://api.whatsapp.com/send?phone=&text=" + pesanwhatsapp;Tombol.style="margin-top:15px;opacity:1;transform: scale(1);";} setTimeout(showDiv,100);

  const body = document.querySelector("body");const swalst = Swal.mixin({timer: 2777, allowOutsideClick: false, showConfirmButton: false, timerProgressBar: true, imageHeight: 100,}); audio = new Audio('' + linkmp3.innerHTML);const swals = Swal.mixin({allowOutsideClick: false, cancelButtonColor: '#FF0040', imageWidth: 100, imageHeight: 100,}); const style = document.createElement('style'); var today = new Date();var dd = String(today.getDate()).padStart(2, '0');var mm = String(today.getMonth() + 1).padStart(2, '0');var yyyy = today.getFullYear();const monthNames = ["Januari", "Februari", "Maret", "April", "Mei", "Juni", "Juli", "Agustus", "September", "Oktober", "November", "Desember"];today = dd + ' ' + monthNames[today.getMonth()] + ' ' + yyyy;

  function otomatis() {befanimkata();setTimeout(animkata,400);} 
  function befanimkata(){kalimat.style="transform:scale(.3);";kalimatb.style="transform:scale(.3);";} 
  function animkata() {kalimat.style="transform:scale(1);";kalimatb.style="transform:scale(1);";}
  
  var ah=0,ngetikh;ngetikh=kalimatc.innerHTML;kalimatc.innerHTML="";function ngetikC() {if(ah<ngetikh.length){kalimatc.innerHTML += ngetikh.charAt(ah);ah++;setTimeout(ngetikC,60);} if(ah==ngetikh.length){setTimeout(otomatisc2,1000);}}
  function otomatisc2() {befanimkatac();setTimeout(animkatac,400);} 
  function befanimkatac(){kalimat.style.opacity="0";kalimatb.style.opacity="0";kalimatc.style.opacity="0";skalimatc=kalimatc1.innerHTML;kalimatc.innerHTML="";} 
  function animkatac() {setTimeout(otomatiscc2,1700);kalimat.innerHTML = kalimat1.innerHTML;kalimatb.innerHTML = kalimatb1.innerHTML;kalimat.style.opacity="1";kalimatb.style.opacity="1";}
  function otomatiscc2(){setTimeout(tombol,1000);kalimatc.innerHTML = skalimatc;kalimatc.style.opacity="1";}

  function otomatis2() {befanimkata2();setTimeout(animkata2,400);} 
  function befanimkata2(){kalimat.style.opacity="0";kalimatb.style.opacity="0";kalimatc.style.opacity="0";} 
  function animkata2() {mulaict();kalimat.innerHTML = kalimat2.innerHTML;kalimatb.innerHTML = kalimatb2.innerHTML;kalimatc.innerHTML = kalimatc2.innerHTML;kalimat.style.opacity="1";kalimatb.style.opacity="1";kalimatc.style.opacity="1";}
  
  function otomatis3() {befanimkata3();setTimeout(animkata3,400);} 
  function befanimkata3(){kalimat.style.opacity="0";kalimatb.style.opacity="0";kalimatc.style.opacity="0";} 
  function animkata3() {kalimat.innerHTML = kalimat3.innerHTML;kalimatb.innerHTML = kalimatb3.innerHTML;kalimatc.innerHTML = kalimatc3.innerHTML;kalimat.style.opacity="1";kalimatb.style.opacity="1";kalimatc.style.opacity="1";}

  function fangka(){angka.innerHTML = Math.floor(Math.random() * 25) + 5;}
  function henti(){clearInterval(tmer);setTimeout(ngetikC,1200);}
  
  function mulaihitung(){
  	tmer = setInterval(fangka,200);
      setTimeout(henti,2000);
  }
  
  function sbakhir(){Bn.style.display="none";setTimeout(stakhir,500);} function stakhir(){tmbl.innerHTML=" Kirim";Tombol.style="margin-top:10px;opacity:1;transform: scale(1)";ftom=5;fungsi=0;}
  
  async function diterima(){
      fthilang();ftganti=1;
      setTimeout(ftmuncul,400);
      Bn2.style.display="none";
      wallpaper.style="transform: scale(1.5);opacity:1;";
      bq.style = "position:relative;opacity:1;visibility:visible;transform: scale(1);transition:all .7s ease;border-radius:var(--bingkai);margin-top:0;";
      Tombol.style="opacity:0;transition:all .5s ease;transform: scale(.1);";
      otomatis2();
   }

  flag=1;flagg=1;
  function ditolak(){
  	if(fungsi==1){
  	if(flagg==1){Bn.style="margin:12px 0 12px 12px;cursor:default;opacity:0;transition:all 0s ease;";flagg=2;
                 Bn2.style="width:auto;opacity:1;transition:all .3s ease;margin:160px 0 12px 140px;transform:rotate(-45deg);"}
  	}
   }
  function ditolak2(){
  	if(fungsi==1){
  	if(flagg==2){Bn2.style="width:auto;opacity:1;transition:all .3s ease;margin:190px 0 12px 12px;";flagg=3}
  	    else if(flagg==3){Bn2.style="width:auto;opacity:1;transition:all .3s ease;margin:160px 160px 12px 12px;transform:rotate(45deg);";flagg=4}
  		else if(flagg==4){Bn2.style="transition:all .3s ease;margin:12px 0 12px 12px;";Bn.style="margin:12px 0 12px 12px";flagg=1}
  	    }
   }

  function mulaict(){
    var timeleft = 7;
    var downloadTimer = setInterval(function(){
    timeleft--;
    document.getElementById("ctimer").textContent = timeleft;
    if(timeleft <= 0)
      clearInterval(downloadTimer);
      if(timeleft==0){
      wallpaper.style="transform: scale(1);opacity:1;";
      setInterval(createHeart,200);
      fthilang();ftganti=2;
      setTimeout(ftmuncul,400);otomatis3();
      setTimeout(sbakhir,2000);
      }
    },1000);
  }
  
   function createHeart() {const heart = document.createElement("div"); heart.className = "fas fa-heart"; heart.style.left = (Math.random() * 90)+"vw"; heart.style.animationDuration = (Math.random()*3)+2+"s"; body.appendChild(heart);} setInterval(function name(params) {var heartArr = document.querySelectorAll(".fa-heart"); if (heartArr.length > 100) {heartArr[0].remove()}},100);
</script>
<!-- Sampai Sini -->
</body>
</html>
