<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>20/10 – Tặng Nguyễn Hương Giang</title>
  <meta name="description" content="Trang web nhỏ xinh tặng Nguyễn Hương Giang nhân ngày 20/10 – Tình yêu bắt đầu từ 16/02/2023." />
  <style>
    :root{
      --bg:#fff6f8;--primary:#e91e63;--primary-dark:#c2185b;--ink:#231942;--muted:#6c6a7a;
      --card:#ffffff;--shadow:0 12px 30px rgba(0,0,0,.12);--radius:18px;--container:1100px;
    }
    *{box-sizing:border-box} html{scroll-behavior:smooth}
    body{margin:0;font-family:"Inter",system-ui,-apple-system,"Segoe UI",Roboto,Arial,sans-serif;background:var(--bg);color:var(--ink);line-height:1.6}
    img{max-width:100%;display:block}

    .wrap{max-width:var(--container);margin:0 auto;padding:24px}
    .hero{position:relative;overflow:hidden;background:linear-gradient(135deg,#fff0f5,#ffe4ea);border-radius:var(--radius);box-shadow:var(--shadow);padding:48px 24px}
    .hero h1{margin:0;font-size:clamp(28px,5vw,40px);color:var(--primary)}
    .subtitle{color:var(--muted);margin-top:8px}
    .badges{display:flex;flex-wrap:wrap;gap:10px;margin-top:18px}
    .badge{background:#fff;padding:8px 12px;border-radius:999px;box-shadow:0 6px 18px rgba(233,30,99,.18);font-weight:600;color:var(--primary-dark)}
    .hero-grid{display:grid;grid-template-columns:1.2fr .8fr;gap:24px;align-items:center}
    @media (max-width:860px){.hero-grid{grid-template-columns:1fr}}

    .card{background:var(--card);border-radius:var(--radius);box-shadow:var(--shadow);padding:22px}
    .cards{display:grid;grid-template-columns:1fr 1fr 1fr;gap:18px;margin-top:24px}
    @media (max-width:1024px){.cards{grid-template-columns:1fr 1fr}}
    @media (max-width:640px){.cards{grid-template-columns:1fr}}

    .kpi{display:flex;align-items:center;gap:14px}
    .kpi .num{font-size:clamp(28px,4.5vw,36px);font-weight:800;color:var(--primary)}
    .kpi .label{color:var(--muted)}
    .btn{appearance:none;border:0;border-radius:14px;background:var(--primary);color:#fff;padding:14px 18px;font-weight:700;cursor:pointer;box-shadow:0 10px 24px rgba(233,30,99,.35);transition:.2s transform,.2s box-shadow}
    .btn:hover{transform:translateY(-1px);box-shadow:0 16px 32px rgba(233,30,99,.45)}

    .section{margin-top:36px}
    .section h2{margin:0 0 12px;font-size:clamp(22px,3.5vw,28px)}
    .lead{color:var(--muted)}

    .gallery{display:grid;grid-template-columns:2fr 1fr 1fr;gap:14px}
    .gallery img{width:100%;height:240px;object-fit:cover;border-radius:14px}
    @media (max-width:860px){.gallery{grid-template-columns:1fr 1fr}.gallery img{height:200px}}
    @media (max-width:520px){.gallery{grid-template-columns:1fr}.gallery img{height:220px}}

    .timeline{position:relative;padding-left:24px}
    .timeline::before{content:'';position:absolute;left:8px;top:0;bottom:0;width:2px;background:#ffd1de}
    .ti{position:relative;margin:12px 0;background:#fff;border-radius:12px;padding:12px 14px;box-shadow:0 6px 16px rgba(0,0,0,.06)}
    .ti::before{content:'❤';position:absolute;left:-16px;top:10px;color:var(--primary)}

    .hearts{pointer-events:none;position:fixed;inset:0;overflow:hidden;z-index:10}
    .heart{position:absolute;font-size:16px;animation:floatUp 6s linear forwards;opacity:.9;filter:drop-shadow(0 6px 12px rgba(233,30,99,.35))}
    @keyframes floatUp{from{transform:translateY(20vh) scale(.8)}to{transform:translateY(-110vh) scale(1.3);opacity:0}}

    .footer{margin:32px 0 10px;text-align:center;color:#8b8996}

    .yt-holder{width:320px;max-width:100%}
    .yt-aspect{position:relative;width:100%;padding-top:56.25%;border-radius:12px;overflow:hidden;box-shadow:0 6px 16px rgba(0,0,0,.08);background:#000}
    .yt-aspect iframe{position:absolute;inset:0;width:100%;height:100%;border:0}
    .small{font-size:14px;color:var(--muted)}
  </style>
</head>
<body>
  <div class="hearts" id="hearts"></div>
  <div class="wrap">
    <header class="hero">
      <div class="hero-grid">
        <div>
          <h1>Chúc mừng 20/10, <span style="white-space:nowrap">Nguyễn Hương Giang</span> 💐</h1>
          <p class="subtitle">Từ ngày <strong>16/02/2023</strong> đến hôm nay, chúng ta đã cùng nhau viết nên thật nhiều điều dễ thương.</p>

          <div class="badges">
            <span class="badge">❤ Mãi bên nhau</span>
            <span class="badge">🌷 Em là cô gái tuyệt vời nhất</span>
            <span class="badge">🎀 20/10 vui vẻ nhé!</span>
          </div>

          <div class="cards">
            <div class="card kpi"><div class="num" id="daysTogether">0</div><div class="label">ngày bên nhau</div></div>
            <div class="card kpi"><div class="num" id="hoursTogether">0</div><div class="label">giờ yêu thương</div></div>
            <div class="card kpi"><div class="num" id="till2010">00:00:00</div><div class="label">đếm ngược tới 20/10</div></div>
          </div>

          <div style="display:flex;gap:12px;align-items:center;margin-top:16px;flex-wrap:wrap">
            <button class="btn" id="flowerBtn">Bấm để nhận hoa 🌸</button>

            <!-- Player YouTube -->
            <div class="yt-holder">
              <div class="yt-aspect"><div id="yt-player"></div></div>
            </div>
          </div>
        </div>

        <div>
          <div class="gallery">
            <img src="./image/4.jpg" alt="Kỷ niệm 1" />
            <img src="./image/5.jpg" alt="Kỷ niệm 2" />
            <img src="./image/6.jpg" alt="Kỷ niệm 3" />
          </div>
        </div>
      </div>
    </header>

    <section class="section">
      <h2>Gửi Giang yêu dấu</h2>
      <div class="card">
        <p>Em là món quà tuyệt vời nhất mà anh có được. Mỗi ngày trôi qua kể từ <strong>16/02/2023</strong>, anh càng thấy biết ơn vì có em bên cạnh. Chúc em 20/10 thật rạng rỡ, luôn vui vẻ, khoẻ mạnh và hạnh phúc. Anh hứa sẽ cố gắng để xứng đáng với tình yêu của chúng mình.</p>
        <p>Thương em nhiều ❤</p>
      </div>
    </section>

    <section class="section">
      <h2>Dòng thời gian nho nhỏ</h2>
      <div class="timeline">
        <div class="ti"><strong>16/02/2023</strong> – Chính thức yêu nhau. Bắt đầu hành trình đẹp nhất. 🥰</div>
        <div class="ti"><strong>20/10/2023</strong> – 20/10 đầu tiên bên nhau, em cười rất xinh. 💐</div>
        <div class="ti"><strong>2024</strong> – Cùng nhau qua thêm nhiều dấu mốc đáng nhớ. 📸</div>
        <div class="ti"><strong>2025</strong> – Viết tiếp câu chuyện của chúng mình. ✨</div>
      </div>
    </section>

    <section class="section">
      <h2>Album kỷ niệm</h2>
      <p class="lead">Kéo xuống để xem thêm ảnh (thay link ảnh bằng ảnh thật của hai đứa nhé).</p>
      <div class="gallery">
        <img src="./image/2.jpg" alt="Couple 1" />
        <img src="./image/3.jpg" alt="Couple 2" />
        <img src="./image/1.jpg" alt="Couple 3" />
      </div>
    </section>

    <p class="footer">Made with ❤ dành tặng <strong>Nguyễn Hương Giang</strong> – 20/10</p>
  </div>

  <!-- YouTube IFrame API -->
  <script src="https://www.youtube.com/iframe_api"></script>
  <script>
    // ===== Helpers =====
    const pad = (n)=>String(n).padStart(2,'0');
    function calcSince(dateStr){const s=new Date(dateStr), n=new Date(), d=n-s;return {days:Math.floor(d/86400000),hours:Math.floor(d/3600000)}}
    function nextOct20(){const n=new Date(), y=n.getFullYear();let t=new Date(y,9,20,0,0,0);if(n>t)t=new Date(y+1,9,20,0,0,0);return t}
    const startLove='2023-02-16T00:00:00+07:00';
    function tick(){const {days,hours}=calcSince(startLove);document.getElementById('daysTogether').textContent=days.toLocaleString('vi-VN');document.getElementById('hoursTogether').textContent=hours.toLocaleString('vi-VN');const t=nextOct20(), n=new Date(), r=t-n, h=Math.floor(r/3600000), m=Math.floor((r%3600000)/60000), s=Math.floor((r%60000)/1000);document.getElementById('till2010').textContent=`${pad(h)}:${pad(m)}:${pad(s)}`}
    tick(); setInterval(tick,1000);

    // ===== Tim bay =====
    const hearts=document.getElementById('hearts');
    function spawnHeart(x,emoji='❤'){const el=document.createElement('div');el.className='heart';el.textContent=emoji;const size=14+Math.random()*22;el.style.left=(x??Math.random()*100)+'vw';el.style.bottom='-10vh';el.style.fontSize=size+'px';el.style.animationDuration=(4+Math.random()*3)+'s';hearts.appendChild(el);setTimeout(()=>el.remove(),7000)}
    setInterval(()=>spawnHeart(),900);

    // ===== Hoa + phát nhạc =====
    const flowerBtn=document.getElementById('flowerBtn');
    const flowers=['🌸','🌷','🌹','💮','🌺','💐','🌻'];
    function burst(e){
      const rect=e.target.getBoundingClientRect(), centerX=rect.left+rect.width/2;
      for(let i=0;i<24;i++){setTimeout(()=>{spawnHeart((100*(centerX+(Math.random()-0.5)*220)/window.innerWidth),flowers[i%flowers.length])},i*60)}
      if(ytReady && ytPlayer) ytPlayer.playVideo();
    }
    flowerBtn.addEventListener('click', burst);

    // ===== YouTube Player =====
    let ytPlayer=null, ytReady=false;
    const YT_VIDEO_ID='f-VsoLm4i5c'; // ID video

    function onYouTubeIframeAPIReady(){
      ytPlayer=new YT.Player('yt-player',{
        videoId: YT_VIDEO_ID,
        playerVars:{
          autoplay:0,controls:1,loop:1,playlist:YT_VIDEO_ID,
          modestbranding:1,rel:0,playsinline:1,origin:window.location.origin
        },
        events:{'onReady':()=>{ytReady=true;}}
      });
    }

    document.addEventListener('touchstart',()=>{}, {passive:true});
  </script>
</body>
</html>
