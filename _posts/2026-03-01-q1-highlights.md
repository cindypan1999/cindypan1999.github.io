---
tag: highlights
---

## best of jan - march!!!

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
  :root {
    --bg: #f9f7f5;
    --white: #ffffff;
    --text: #1c1917;
    --soft: #78716c;
    --border: #e8e3dc;
    --tag-bg: #f0ebe3;
    --jan: #fde8d8;
    --jan-text: #9a3412;
    --feb: #fce7f3;
    --feb-text: #9d174d;
    --mar: #dcfce7;
    --mar-text: #166534;
    --radius: 16px;
    --shadow: 0 2px 8px rgba(0,0,0,0.08), 0 1px 2px rgba(0,0,0,0.04);
    --shadow-hover: 0 12px 32px rgba(0,0,0,0.14), 0 4px 8px rgba(0,0,0,0.06);
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }

  /* ── MASONRY ── */
  .masonry-wrap {
    max-width: 1200px;
    margin: 0 auto;
    padding: 8px 16px 60px;
  }

  .masonry {
    columns: 4;
    column-gap: 14px;
  }

  @media (max-width: 1024px) { .masonry { columns: 3; } }
  @media (max-width: 680px)  { .masonry { columns: 2; } }
  @media (max-width: 400px)  { .masonry { columns: 1; } }

  /* ── PIN CARD ── */
  .pin {
    break-inside: avoid;
    margin-bottom: 14px;
    border-radius: var(--radius);
    background: var(--white);
    box-shadow: var(--shadow);
    overflow: hidden;
    cursor: pointer;
    transition: transform 0.25s ease, box-shadow 0.25s ease;
    position: relative;
    animation: pinIn 0.4s ease both;
    animation-delay: var(--d, 0s);
  }
  .pin:hover {
    transform: translateY(-4px) scale(1.01);
    box-shadow: var(--shadow-hover);
  }
  .pin:hover .pin-overlay { opacity: 1; }

  @keyframes pinIn {
    from { opacity: 0; transform: translateY(16px) scale(0.97); }
    to   { opacity: 1; transform: none; }
  }

  /* Photo area */
  .pin-img {
    width: 100%;
    display: block;
    background: var(--tag-bg);
    position: relative;
    overflow: hidden;
  }

  .pin-img img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

  .pin-img-inner {
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 6px;
    color: #b5aca0;
    font-size: 0.7rem;
    font-weight: 700;
    letter-spacing: 0.1em;
    padding: 20px;
  }
  .pin-img-inner .cam { font-size: 2rem; opacity: 0.5; }

  /* Month tag */
  .month-tag {
    position: absolute;
    top: 12px;
    left: 12px;
    font-size: 0.65rem;
    letter-spacing: 0.08em;
    padding: 4px 10px;
    border-radius: 20px;
    z-index: 2;
  }
  .tag-jan { background: var(--jan); color: var(--jan-text); }
  .tag-feb { background: var(--feb); color: var(--feb-text); }
  .tag-mar { background: var(--mar); color: var(--mar-text); }

  /* Pin body */
  .pin-body {
    padding: 12px 14px 14px;
  }
  .pin-title {
    font-size: 1rem;
    line-height: 1.3;
    color: var(--text);
    margin-bottom: 5px;
  }
  .pin-date {
    font-size: 0.72rem;
    color: var(--soft);
    margin-bottom: 6px;
  }
  .pin-desc {
    font-size: 0.82rem;
    color: #57534e;
    line-height: 1.55;
    font-weight: 400;
  }

  /* ── TEXT-ONLY PIN ── */
  .pin.text-pin .pin-img {
    background: linear-gradient(135deg, #fdf4ec, #fce4d0);
    min-height: 120px;
  }
  .pin.text-pin.feb-pin .pin-img {
    background: linear-gradient(135deg, #fdf2f8, #fce7f3);
  }
  .pin.text-pin.mar-pin .pin-img {
    background: linear-gradient(135deg, #f0fdf4, #dcfce7);
  }
  .text-pin-quote {
    font-style: italic;
    font-size: clamp(1rem, 2vw, 1.3rem);
    font-weight: 300;
    line-height: 1.4;
    color: var(--text);
    padding: 24px 20px;
    text-align: center;
  }

  /* ── HIDDEN state ── */
  .pin.filtered-out {
    display: none;
  }
</style>
</head>
<body>

<!-- MASONRY GRID -->
<div class="masonry-wrap">
<div class="masonry" id="grid">

  <!-- ── JANUARY ── -->
  <div class="pin" data-month="january" data-text="new year friends college philadelphia party" style="--d:0.04s">
    <div class="pin-img" style="height:260px">
      <img src="/pictures/q12026/nye.jpeg">
    </div>
    <div class="pin-body">
      <div class="pin-date">january 1</div>
      <div class="pin-title">rang in the ny w some college besties in the inspiring city of philly</div>
    </div>
  </div>

  <div class="pin" data-month="january" data-text="merlin birthday celebration" style="--d:0.08s">
    <div class="pin-img">
      <img src="/pictures/q12026/merlin.jpeg">
      
    </div>
    <div class="pin-body">
      <div class="pin-date">january 6</div>
      <div class="pin-title">celerated merlin's 4th birthday who was coincedentally born on 1/6/2021</div>
    </div>
  </div>

  <div class="pin" data-month="january" data-text="mom virginia corepower yoga asian food family" style="--d:0.12s">
    <div class="pin-img" style="height:200px">
      <img src="/pictures/q12026/mom.jpeg">
      
    </div>
    <div class="pin-body">
      <div class="pin-date">january 9</div>
      <div class="pin-title">hung out w mom in virginia, went to corepower & ate delicious asian food</div>
    </div>
  </div>

  <div class="pin" data-month="january" data-text="pickle" style="--d:0.12s">
    <div class="pin-img" style="height:200px">
      <img src="/pictures/q12026/pickle.jpeg">
      
    </div>
    <div class="pin-body">
      <div class="pin-date">january 9</div>
      <div class="pin-title">using awesome pickleball plate from sam's dad</div>
    </div>
  </div>

  <div class="pin text-pin" data-month="january" data-text="annie birthday celebrate friend" style="--d:0.16s">
    <div class="pin-img">
    <img src="/pictures/q12026/annie.jpeg">
      <div class="pin-overlay"></div>
      
    </div>
    <div class="pin-body">
      <div class="pin-date">january 16</div>
      <div class="pin-title">annie's bday! cozy vibes</div>
    </div>
  </div>

  <div class="pin" data-month="january" data-text="hair dye red color" style="--d:0.2s">
    <div class="pin-img">
      <img src="/pictures/q12026/hair.jpeg">
      
      
    </div>
    <div class="pin-body">
      <div class="pin-date">january 17</div>
      <div class="pin-title">dyed hair red</div>
    </div>
  </div>

  <div class="pin" data-month="january" data-text="sam anniversary date bar maripili cannon" style="--d:0.24s">
    <div class="pin-img" style="height:260px">
      <img src="/pictures/q12026/mari.jpeg">
      
      
    </div>
    <div class="pin-body">
      <div class="pin-date">january 23</div>
      <div class="pin-title">celebrated 4th anniversary!! @ canon & maripili bar</div>
    </div>
  </div>

  <div class="pin" data-month="january" data-text="ski skiing colorado mountains snow winter trip" style="--d:0.28s">
    <div class="pin-img" style="height:300px">
      <img src="/pictures/q12026/ski.jpeg">
      
      
    </div>
    <div class="pin-body">
      <div class="pin-date">january 31 - february 7</div>
      <div class="pin-title">skiied colorado w sam & co</div>
    </div>
  </div>

  <div class="pin" data-month="february" data-text="vday brunch" style="--d:0.2s">
    <div class="pin-img" style="height:210px">
      <img src="/pictures/q12026/brunch.jpeg">
      
      
    </div>
    <div class="pin-body">
      <div class="pin-date">february 8</div>
      <div class="pin-title">hosted a vday brunch</div>
    </div>
  </div>

  <div class="pin" data-month="february" data-text="vday brunch" style="--d:0.2s">
    <div class="pin-img" style="height:210px">
      <img src="/pictures/q12026/drink.jpg">
      
      
    </div>
    <div class="pin-body">
      <div class="pin-date">february 8</div>
      <div class="pin-title">pj party</div>
    </div>
  </div>

   <div class="pin" data-month="february" data-text="vday brunch" style="--d:0.2s">
    <div class="pin-img" style="height:210px">
      <img src="/pictures/q12026/pancake.jpg">
      
      
    </div>
    <div class="pin-body">
      <div class="pin-date">february 8</div>
      <div class="pin-title">brunch details</div>
    </div>
  </div>

  <div class="pin" data-month="february" data-text="galentines brunch super bowl friends football" style="--d:0.04s">
    <div class="pin-img" style="height:220px">
      <img src="/pictures/q12026/nfl.jpeg">
      
    </div>
    <div class="pin-body">
      <div class="pin-date">february 8</div>
      <div class="pin-title">super bowl viewing at zach & auddie's</div>
    </div>
  </div>

  <div class="pin" data-month="february" data-text="nfl parade football celebration" style="--d:0.08s">
    <div class="pin-img" style="height:240px">
      <img src="/pictures/q12026/parade.jpeg">
      
    </div>
    <div class="pin-body">
      <div class="pin-date">february 11</div>
      <div class="pin-title">nfl parade outside work</div>
    </div>
  </div>

  <div class="pin text-pin feb-pin" data-month="february" data-text="graysie birthday friend celebrate" style="--d:0.12s">
    <div class="pin-img" style="height:210px">
      <img src="/pictures/q12026/graysie.jpeg">
      
      
      <div class="text-pin-quote">graysie bday</div>
    </div>
    <div class="pin-body">
      <div class="pin-date">february 12</div>
      <div class="pin-title">ayca sushi for graysie's bday!</div>
    </div>
  </div>

  <div class="pin" data-month="february" data-text="hong kong bistro marlo birthday dinner big group" style="--d:0.16s">
    <div class="pin-img" style="height:250px">
      <img src="/pictures/q12026/hong.jpeg">
      
    </div>
    <div class="pin-body">
      <div class="pin-date">february 13</div>
      <div class="pin-title">huge dinner at hong kong bistro for marlo's bday</div>
    </div>
  </div>

  <div class="pin" data-month="february" style="--d:0.2s">
    <div class="pin-img" style="height:210px">
      <img src="/pictures/q12026/love.jpg">
      
      
    </div>
    <div class="pin-body">
      <div class="pin-date">february 14-16</div>
      <div class="pin-title">vday weekend in bellingham, skiing at artist's point</div>
    </div>
  </div>

  <div class="pin text-pin feb-pin" data-month="february" data-text="dumplings chinese new year food" style="--d:0.24s">
    <div class="pin-img" style="height:250px">
      <img src="/pictures/q12026/dumpling.jpg">
      
      
    </div>
    <div class="pin-body">
      <div class="pin-date">february 16</div>
      <div class="pin-title">homemade dumplings for cny</div>
    </div>
  </div>

  <div class="pin" data-month="february" data-text="kiki friend hangout visit" style="--d:0.28s">
    
    <div class="pin-body">
      <div class="pin-date">february 18</div>
      <div class="pin-title">swam with kiki who finally met sam</div>
    </div>
  </div>

  <div class="pin" data-month="february" data-text="palm springs desert trip travel vacation sun" style="--d:0.32s">
    <div class="pin-img" style="height:300px">
      <img src="/pictures/q12026/palm.jpeg">
      
      
    </div>
    <div class="pin-body">
      <div class="pin-date">february 19-23</div>
      <div class="pin-title">palm springs w annie & grace</div>
    </div>
  </div>

  <div class="pin" data-month="february" data-text="dumplings annie kay food friends" style="--d:0.36s">
    <div class="pin-img" style="height:200px">
      <img src="/pictures/q12026/kat.jpeg">
      
    </div>
    <div class="pin-body">
      <div class="pin-date">february 24</div>
      <div class="pin-title">belated cny dumplings w annie & kat</div>
    </div>
  </div>

  <div class="pin" data-month="february" data-text="belay climbing class allie gym" style="--d:0.4s">
    <div class="pin-img" style="height:220px">
      <img src="/pictures/q12026/climb.jpeg">
    </div>
    <div class="pin-body">
      <div class="pin-date">february 27</div>
      <div class="pin-title">belay class w allie & jordy</div>
    </div>
  </div>

  <div class="pin" data-month="february" data-text="ski alpental snow slopes winter" style="--d:0.44s">
    <div class="pin-img" style="height:250px">
       <img src="/pictures/q12026/al.jpeg">
      
      
    </div>
    <div class="pin-body">
      <div class="pin-date">february 28</div>
      <div class="pin-title">skied @ alpental</div>
    </div>
  </div>

  <!-- ── MARCH ── -->
  <div class="pin" data-month="march" data-text="salmon dinner food cooking" style="--d:0.04s">
    <div class="pin-img" style="height:240px">
      <img src="/pictures/q12026/salmon.jpeg">
      
     
    </div>
    <div class="pin-body">
      <div class="pin-date">march 1</div>
      <div class="pin-title">multicourse salmon dinner by sam & sebastian</div>
    </div>
  </div>

  <div class="pin" data-month="march" data-text="sam birthday dinner early celebrate" style="--d:0.08s">
    <div class="pin-img" style="height:220px">
      
      <img src="/pictures/q12026/lao.jpeg">
      
     
    </div>
    <div class="pin-body">
      <div class="pin-date">march 5</div>
      <div class="pin-title">early bday dinner for sam before his trip</div>
    </div>
  </div>

    <div class="pin" data-month="february" data-text="kiki friend hangout visit" style="--d:0.28s">
    
    <div class="pin-body">
      <div class="pin-date">march 6</div>
      <div class="pin-title">darshini & i win our first doubles match</div>
    </div>
  </div>

  <div class="pin" data-month="march" data-text="allie birthday out night bar friends" style="--d:0.12s">
    <div class="pin-img" style="height:250px">
      <img src="/pictures/q12026/allie.jpeg">
      
     
    </div>
    <div class="pin-body">
      <div class="pin-date">march 7</div>
      <div class="pin-title">allie's bday! yonder & still liquor</div>
    </div>
  </div>

  <div class="pin" data-month="march" data-text="sam birthday dinner early celebrate" style="--d:0.08s">
    <div class="pin-img" style="height:220px">
      
      <img src="/pictures/q12026/fondu.jpeg">
      
     
    </div>
    <div class="pin-body">
      <div class="pin-date">march 15</div>
      <div class="pin-title">fondu surprise dinner for sam</div>
    </div>
  </div>


  <div class="pin" data-month="march" data-text="sam birthday dinner early celebrate" style="--d:0.08s">
    <div class="pin-img" style="height:220px">
      
      <img src="/pictures/q12026/tempe.jpeg">
      
     
    </div>
    <div class="pin-body">
      <div class="pin-date">march 19-20</div>
      <div class="pin-title">work trip to tempe</div>
    </div>
  </div>

  <div class="pin" data-month="march" data-text="sam birthday dinner early celebrate" style="--d:0.08s">
    <div class="pin-img" style="height:220px">
      
      <img src="/pictures/q12026/bonfire.jpeg">
      
     
    </div>
    <div class="pin-body">
      <div class="pin-date">march 22</div>
      <div class="pin-title">belated bonfire celebration for sam</div>
    </div>
  </div>

  <div class="pin" data-month="march" data-text="sam birthday dinner early celebrate" style="--d:0.08s">
    <div class="pin-img" style="height:290px">
      
      <img src="/pictures/q12026/shoot.jpg">
      
     
    </div>
    <div class="pin-body">
      <div class="pin-date">march 25</div>
      <div class="pin-title">cherry blossom photoshoot where graysie showcases raw talent</div>
    </div>
  </div>

</div><!-- /masonry -->
</div><!-- /wrap -->

</body>
</html>