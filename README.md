<center><h3>Twitter Video Downloader Tool</h3><center>


<iframe src="https://mp3downy.com/twitter-video-downloader?apikey=&color=17a2b8&bg=ffffff" style="width:100%;min-height:250px;height:auto;" ></iframe></center></center>

<br />

<center><h3>Facebook video Downloader Tool</h3><center>

<iframe src="https://mp3downy.com/facebook-video-downloader?apikey=&color=17a2b8&bg=ffffff" style="width:100%;min-height:250px;height:auto;" ></iframe></center></center>

<center><h3>Youtube Downloader Tool</h3><center>

<iframe src="https://mp3downy.com/MP3-converter?apikey=1234567890&color=17a2b8&bg=ffffff" style="width:100%;min-height:250px;height:auto;" ></iframe></center></center>

<link rel="stylesheet" href="style.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"/>
</head>
<body>
<style type="text/css">
   *{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}
html,body{
  display: grid;
  height: 100%;
  place-items: center;
  background: #000;
}
.icons{
  display: inline-flex;
}
.icons a{
  margin: 0 25px;
  text-decoration: none;
  color: #fff;
  display: block;
  position: relative;
}
.icons a .layer{
  width: 55px;
  height: 55px;
  transition: transform 0.3s;
}
.icons a:hover .layer{
  transform: rotate(-35deg) skew(20deg);
}
.icons a .layer span{
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  border: 1px solid #fff;
  border-radius: 5px;
  transition: all 0.3s;
}
.icons a .layer span.fab{
  font-size: 30px;
  line-height: 55px;
  text-align: center;
}
.icons a:hover .layer span:nth-child(1){
  opacity: 0.2;
}
.icons a:hover .layer span:nth-child(2){
  opacity: 0.4;
  transform: translate(5px, -5px);
}
.icons a:hover .layer span:nth-child(3){
  opacity: 0.6;
  transform: translate(10px, -10px);
}
.icons a:hover .layer span:nth-child(4){
  opacity: 0.8;
  transform: translate(15px, -15px);
}
.icons a:hover .layer span:nth-child(5){
  opacity: 1;
  transform: translate(20px, -20px);
}
.icons a:nth-child(1) .layer span,
.icons a:nth-child(1) .text{
  color: #4267B2;
  border-color: #4267B2;
}
.icons a:nth-child(2) .layer span,
.icons a:nth-child(2) .text{
  color: #1DA1F2;
  border-color: #1DA1F2;
}
.icons a:nth-child(3) .layer span,
.icons a:nth-child(3) .text{
  color: #E1306C;
  border-color: #E1306C;
}
.icons a:nth-child(4) .layer span,
.icons a:nth-child(4) .text{
  color: #2867B2;
  border-color: #2867B2;
}
.icons a:nth-child(5) .layer span,
.icons a:nth-child(5) .text{
  color: #ff0000;
  border-color: #ff0000;
}
.icons a:hover:nth-child(1) .layer span{
  box-shadow: -1px 1px 3px #4267B2;
}
.icons a:hover:nth-child(2) .layer span{
  box-shadow: -1px 1px 3px #1DA1F2;
}
.icons a:hover:nth-child(3) .layer span{
  box-shadow: -1px 1px 3px #E1306C;
}
.icons a:hover:nth-child(4) .layer span{
  box-shadow: -1px 1px 3px #2867B2;
}
.icons a:hover:nth-child(5) .layer span{
  box-shadow: -1px 1px 3px #ff0000;
}
.icons a .text{
  position: absolute;
  left: 50%;
  bottom: -5px;
  opacity: 0;
  font-weight: 500;
  transform: translateX(-50%);
  transition: bottom 0.3s ease, opacity 0.3s ease;
}
.icons a:hover .text{
  bottom: -35px;
  opacity: 1;
}

</style>
<style>
input {
display: inline-block;
width: 30%;
max-width: 30%;
max-width: calc(100% - 8em);
min-height: 2.8em;
padding: 0.5em;
margin: 0.5em 0;
background: yellow;
border-color: red;
border-width: 1px;
color: #212121;
transition: all 500ms ease;
}
input:focus, input:hover {
border-color: #208bfd;
transition: all 500ms ease;
}
.dummyData{
display:none;
}
.search {
display: inline-block;
padding: 0 1em;
text-align: center;
min-width: 2.8em;
height: 2.8em;
margin: 0;
background: #208bfd;
border: 2px solid #212121;
color: #f9f9f9;
transition: all 500ms ease;
}
.search:focus, .search:hover {
background: #212121;
border-color: #f9f9f9;
cursor: pointer;
transition: all 500ms ease;
}
.gajabwapdata {
margin: 0 auto;
padding: 4em 1em;
max-width: 40em;
}
.gajabwapdata video, .gajabwapdata img {
width: calc(100% - 4em);
margin: 2em;
}
.gajabwapdata .download {
text-decoration: none;
display: inline-block;
padding: 0.5em 1em;
background: blue;
border-color: #208bfd;
border-width: 1px;
color: #f9f9f9;
transition: all 500ms ease;
}
.gajabwapdata .download:focus, .gajabwapdata .download:hover {
background: #208bfd;
border-color: #f9f9f9;
cursor: pointer;
transition: all 500ms ease;
}

.image-placeholder {
margin: auto;
width: 89%;
max-width: 500px;
display: block;
height: 380px;
background-repeat: no-repeat;
background-size: cover;
background-position: center center;
background-image: url(https://cdn.shopify.com/s/files/1/0533/2089/files/placeholder-images-image_large.png?format=jpg&quality=90&v=1530129081);
}

body {
margin: 0;
padding: 0;
font-family: "consolas",monospace;
font-size: 14px;
line-height: 1.5;
background: #f9f9f9;
color: #333;
}
.love {
padding:2em;
box-shadow:0 5px 15px rgba(0,0,0,.16);
border-radius:5px;
margin-top:1em;
background:#fff;
text-align:left
}

.pasterlink{
top: 0;
left: 0;
width: 100%;
height: 4em;
background: brown;
margin: 0 auto;
text-align: center;
color: green;
}
::placeholder {
color: black;
}
</style>

<!--Instagram Downloader-->



 <center> <h3>Instagram image Video Download </h3></center>
<div class='pasterlink'>
<input id="visittechnicalarp" placeholder='Paste link here...' type='url' value='' />
<button class='download btn-outline' type="submit" onclick='getMedia()'>Download</button>
<div class="love container">
     


<br />
<br />
<br /><br />

   
   </div>
<br />
</div>

    
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<section class='gajabwapdata'>
<br />

</section>

            
<div class="dummyData">NO Data</div>
  <div class='main no-items section' id='main'></div>

</centre>
<div class="icons">
         <a href="http://Wa.me//+923456745713">
            <div class="layer">
               <span></span>
               <span></span>
               <span></span>
               <span></span>
               <span class="fab fa-WhatsApp"></span>
            </div>
            <div class="text">
               WhatsApp Contact
            </div>
         </a>
         <a href="https://facebook.com/JUNGi.TV/">
            <div class="layer">
               <span></span>
               <span></span>
               <span></span>
               <span></span>
               <span class="fab fa-facebook-f"></span>
            </div>
            <div class="text">
               Facebook Page Follow
            </div>
         </a>
         <a href="https://t.me/ajdon607">
            <div class="layer">
               <span></span>
               <span></span>
               <span></span>
               <span></span>
               <span class="fab fa-telegram"></span>
            </div>
            <div class="text">
               Telegram Channel Join
            </div>
         </a>

<!-- Theme Functions JS by Technical Arp-->
<script>
 const render = document.querySelector('.gajabwapdata');
  const sonu = document.querySelector('.dummyData');
 
//Get Data - Sorry Encrypted Because it was already encryted - We Just Changed UI of it. 

const createVideo = (_0xd7b7x2) => {
    let _0xd7b7x3 = document['createElement']('video');
    _0xd7b7x3['id'] = 'instavideo';
    _0xd7b7x3['src'] = _0xd7b7x2['content'];
    _0xd7b7x3['controls'] = true;
    _0xd7b7x3['autoplay'] = true;
    console['log']('Inside Video');
    let _0xd7b7x4 = document['createElement']('p');
    _0xd7b7x4['textContent'] = 'Click the right button on video and select save as.';
    render['innerHTML'] = '';
    render['appendChild'](_0xd7b7x3);
    render['appendChild'](_0xd7b7x4)
};
const createImg = (_0xd7b7x2) => {
    let _0xd7b7x6 = document['createElement']('img');
    _0xd7b7x6['id'] = 'instaImg';
    _0xd7b7x6['src'] = _0xd7b7x2['content'];
    console['log']('Inside Img');
    let _0xd7b7x4 = document['createElement']('p');
    _0xd7b7x4['textContent'] = 'Click the right button on the image and select save image..';
    render['innerHTML'] = '';
    render['appendChild'](_0xd7b7x6);
    render['appendChild'](_0xd7b7x4)
}

var _0x52b7 = ["\x68\x74\x74\x70\x73\x3A\x2F\x2F\x77\x77\x77\x2E\x69\x6E\x73\x74\x61\x67\x72\x61\x6D\x2E\x63\x6F\x6D\x2F\x28\x2E\x2B\x3F\x29", "\x69\x6E\x6E\x65\x72\x48\x54\x4D\x4C", "\x3C\x64\x69\x76\x20\x63\x6C\x61\x73\x73\x3D\x27\x69\x6D\x61\x67\x65\x2D\x70\x6C\x61\x63\x65\x68\x6F\x6C\x64\x65\x72\x27\x3E\x3C\x2F\x64\x69\x76\x3E", "\x76\x61\x6C\x75\x65", "\x23\x76\x69\x73\x69\x74\x74\x65\x63\x68\x6E\x69\x63\x61\x6C\x61\x72\x70", "\x71\x75\x65\x72\x79\x53\x65\x6C\x65\x63\x74\x6F\x72", "\x6C\x6F\x67", "\x6D\x61\x74\x63\x68", "\x49\x6E\x73\x69\x64\x65\x20\x50\x61\x74\x74\x65\x72\x6E", "\x49\x6E\x73\x69\x64\x65\x20\x55\x52\x4C", "\x49\x6E\x73\x69\x64\x65\x20\x46\x65\x74\x63", "\x6D\x65\x74\x61\x5B\x70\x72\x6F\x70\x65\x72\x74\x79\x3D\x22\x6F\x67\x3A\x76\x69\x64\x65\x6F\x22\x5D", "\x6D\x65\x74\x61\x5B\x70\x72\x6F\x70\x65\x72\x74\x79\x3D\x22\x6F\x67\x3A\x69\x6D\x61\x67\x65\x22\x5D", "\x70\x6C\x61\x63\x65\x68\x6F\x6C\x64\x65\x72", "\x49\x6E\x76\x61\x6C\x69\x64\x20\x61\x64\x64\x72\x65\x73\x73\x2C\x20\x75\x73\x65\x20\x61\x20\x70\x72\x6F\x70\x65\x72\x20\x49\x6E\x73\x61\x67\x72\x61\x6D\x20\x6C\x69\x6E\x6B", "\x73\x65\x74\x41\x74\x74\x72\x69\x62\x75\x74\x65", "\x76\x69\x73\x69\x74\x74\x65\x63\x68\x6E\x69\x63\x61\x6C\x61\x72\x70", "\x67\x65\x74\x45\x6C\x65\x6D\x65\x6E\x74\x42\x79\x49\x64", "", "\x66\x6F\x63\x75\x73", "\x45\x72\x72\x6F\x72\x20\x65\x78\x74\x72\x61\x63\x74\x69\x6E\x67\x20\x49\x6E\x73\x74\x61\x67\x72\x61\x6D\x20\x69\x6D\x61\x67\x65\x20\x2F\x20\x76\x69\x64\x65\x6F\x2E", "\x74\x68\x65\x6E", "\x74\x65\x78\x74"];
const getMedia = () => {
    var _0x572bx2 = new RegExp(_0x52b7[0]);
    render[_0x52b7[1]] = _0x52b7[2];
    let _0x572bx3 = document[_0x52b7[5]](_0x52b7[4])[_0x52b7[3]];
    console[_0x52b7[6]](_0x572bx3);
    if (_0x572bx3[_0x52b7[7]](_0x572bx2)) {
        console[_0x52b7[6]](_0x52b7[8]);
        if (_0x572bx3) {
            console[_0x52b7[6]](_0x52b7[9]);
            fetch(_0x572bx3)[_0x52b7[21]]((_0x572bx4) => _0x572bx4[_0x52b7[22]]())[_0x52b7[21]]((_0x572bx4) => {
                sonu[_0x52b7[1]] = _0x572bx4;
                console[_0x52b7[6]](_0x52b7[10]);
                let _0x572bx5 = setTimeout(() => {
                    let _0x572bx6 = document[_0x52b7[5]](_0x52b7[11]);
                    if (_0x572bx6) {
                        createVideo(_0x572bx6)
                    } else {
                        let _0x572bx7 = document[_0x52b7[5]](_0x52b7[12]);
                        if (_0x572bx7) {
                            createImg(_0x572bx7)
                        } else {
                            document[_0x52b7[5]](_0x52b7[4])[_0x52b7[15]](_0x52b7[13], _0x52b7[14]);
                            document[_0x52b7[17]](_0x52b7[16])[_0x52b7[3]] = _0x52b7[18];
                            document[_0x52b7[17]](_0x52b7[16])[_0x52b7[19]]();
                            alert(_0x52b7[20])
                        }
                    };
                    clearTimeout(_0x572bx5)
                }, 200)
            })
        }
    } else {
        document[_0x52b7[5]](_0x52b7[4])[_0x52b7[15]](_0x52b7[13], _0x52b7[14]);
        document[_0x52b7[17]](_0x52b7[16])[_0x52b7[3]] = _0x52b7[18];
        document[_0x52b7[17]](_0x52b7[16])[_0x52b7[19]]()
    }
}
</script>
