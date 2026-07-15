---
tag: travel
author: "Cindy Pan"
---

## mexico city
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
    --mex: #dcfce7;
    --mex-text: #166534;
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

  @keyframes pinIn {
    from { opacity: 0; transform: translateY(16px) scale(0.97); }
    to   { opacity: 1; transform: none; }
  }

  /* Photo area — natural aspect ratio, no cropping */
  .pin-img {
    width: 100%;
    display: block;
    background: var(--tag-bg);
    position: relative;
    overflow: hidden;
  }

  .pin-img img {
    width: 100%;
    height: auto;
    display: block;
  }

  /* Day section header */
  .day-header {
    font-size: 1.1rem;
    font-weight: 700;
    color: var(--text);
    padding: 28px 4px 14px;
    margin-bottom: 14px;
    max-width: 1200px;
    margin-left: auto;
    margin-right: auto;
  }
  .day-header:first-of-type {
    padding-top: 4px;
  }

  /* Pin body */
  .pin-body {
    padding: 12px 14px 14px;
  }
  .pin-title {
    font-size: 1rem;
    line-height: 1.3;
    color: var(--text);
    margin-bottom: 0;
  }
</style>
</head>
<body>

<div class="masonry-wrap">

  <!-- ══════════ MARCH 29 ══════════ -->
  <div class="day-header">March 29</div>
  <div class="masonry">
    <div class="pin" style="--d:0.04s">
      <div class="pin-img"><img src="/pictures/mexico/apt.jpeg"></div>
      <div class="pin-body"><div class="pin-title">I arrive in Mexico City with my spirits soaring. The Airbnb is really cute albeit the weird nail art</div></div>
    </div>
    <div class="pin" style="--d:0.08s">
      <div class="pin-img"><img src="/pictures/mexico/trees.jpeg"></div>
      <div class="pin-body"><div class="pin-title">I walk the streets in wonder. Trees towering over Spanish-style buildings and flowers all around</div></div>
    </div>
    <div class="pin" style="--d:0.12s">
      <div class="pin-img"><img src="/pictures/mexico/alone.jpeg"></div>
      <div class="pin-body"><div class="pin-title">I eat at Santa Habanero alone</div></div>
    </div>
    <div class="pin" style="--d:0.16s">
      <div class="pin-img"><img src="/pictures/mexico/monstera.jpeg"></div>
      <div class="pin-body"><div class="pin-title">I see monsteras thriving in the sub-tropical climate</div></div>
    </div>
    <div class="pin" style="--d:0.2s">
      <div class="pin-img"><img src="/pictures/mexico/churro.jpeg"></div>
      <div class="pin-body"><div class="pin-title">I am invited to eat my churro at a table of strangers. There is a strong language barrier</div></div>
    </div>

  </div><!-- /masonry -->

  <!-- ══════════ MARCH 30 ══════════ -->
  <div class="day-header">March 30</div>
  <div class="masonry">
    <div class="pin" style="--d:0.04s">
      <div class="pin-img"><img src="/pictures/mexico/purple.jpeg"></div>
      <div class="pin-body"><div class="pin-title">I go on a morning run exploring the beautiful streets of Roma Norte</div></div>
    </div>
    <div class="pin" style="--d:0.08s">
      <div class="pin-img"><img src="/pictures/mexico/street.jpeg"></div>
      <div class="pin-body"><div class="pin-title">It is shady and beautiful</div></div>
    </div>
    <div class="pin" style="--d:0.12s">
      <div class="pin-img"><img src="/pictures/mexico/house.jpeg"></div>
      <div class="pin-body"><div class="pin-title">But I suffer from the high altitude</div></div>
    </div>
    <div class="pin" style="--d:0.16s">
      <div class="pin-img"><img src="/pictures/mexico/us.jpeg"></div>
      <div class="pin-body"><div class="pin-title">Darshini finally arrives and we go to the famous Tacos Onrico</div></div>
    </div>
    <div class="pin" style="--d:0.2s">
      <div class="pin-img"><img src="/pictures/mexico/taco.JPG"></div>
        <div class="pin-body"><div class="pin-title">Unfortunately Darshini eats bacon</div></div>
    </div>
    <div class="pin" style="--d:0.24s">
      <div class="pin-img"><img src="/pictures/mexico/library.jpeg"></div>
      <div class="pin-body"><div class="pin-title">We visit the Interstellar museum. On our way there, we are kicked off the bus due to an Uber protest. We walk and take in the culture</div></div>
    </div>
    <div class="pin" style="--d:0.28s">
      <div class="pin-img"><img src="/pictures/mexico/selfie.JPG"></div>
            <div class="pin-body"><div class="pin-title">We are impressed by the museum</div></div>
    </div>
    <div class="pin" style="--d:0.32s">
      <div class="pin-img"><img src="/pictures/mexico/rest.JPG"></div>
       <div class="pin-body"><div class="pin-title">Darshini rests on the retro couch</div></div>
    </div>
    <div class="pin" style="--d:0.36s">
      <div class="pin-img"><img src="/pictures/mexico/pasta.JPG"></div>
      <div class="pin-body"><div class="pin-title">We eat pasta with Mexican flair</div></div>
    </div>
    <div class="pin" style="--d:0.4s">
      <div class="pin-img"><img src="/pictures/mexico/dinner1.JPG"></div>
            <div class="pin-body"><div class="pin-title">We decide normal pasta is better</div></div>
    </div>

  </div><!-- /masonry -->

  <!-- ══════════ MARCH 31 ══════════ -->
  <div class="day-header">March 31</div>
  <div class="masonry">
    <div class="pin" style="--d:0.04s">
      <div class="pin-img"><img src="/pictures/mexico/lush.jpeg"></div>
      <div class="pin-body"><div class="pin-title">I run through Condessa where it is lush and vibrant</div></div>
    </div>
    <div class="pin" style="--d:0.08s">
      <div class="pin-img"><img src="/pictures/mexico/office.jpeg"></div>
      <div class="pin-body"><div class="pin-title">I visit the DoorDash office. I observe the Mexican culture but do not speak to anyone</div></div>
    </div>
    <div class="pin" style="--d:0.12s">
      <div class="pin-img"><img src="/pictures/mexico/officefood.jpeg"></div>
      <div class="pin-body"><div class="pin-title">I eat catered Mexican lunch alone</div></div>
    </div>

    <div class="pin" style="--d:0.16s">
      <div class="pin-img"><img src="/pictures/mexico/park2.jpeg"></div>
      <div class="pin-body"><div class="pin-title">I walk through a neighboring park as I wait for Darshini to meet me from the Qualtrics office</div></div>
    </div>

    <div class="pin" style="--d:0.2s">
      <div class="pin-img"><img src="/pictures/mexico/tostada.JPG"></div>
      <div class="pin-body"><div class="pin-title">We go to a food market in Coyoacan and eat the famous tostadas with horchata</div></div>
    </div>

    <div class="pin" style="--d:0.24s">
      <div class="pin-img"><img src="/pictures/mexico/coyote.jpeg"></div>
      <div class="pin-body"><div class="pin-title">We go shopping in Coyoacan square and see the famous coyote fountain</div></div>
    </div>

    <div class="pin" style="--d:0.28s">
      <div class="pin-img"><img src="/pictures/mexico/yoga.jpeg"></div>
      <div class="pin-body"><div class="pin-title">We scurry to Gita yoga where they have a projector on the walls. The flow is orated in Spanish</div></div>
    </div>

  </div><!-- /masonry -->

  <!-- ══════════ APRIL 1 ══════════ -->
  <div class="day-header">April 1</div>
  <div class="masonry">
    <div class="pin" style="--d:0.04s">
      <div class="pin-img"><img src="/pictures/mexico/bagel.jpeg"></div>
      <div class="pin-body"><div class="pin-title">After I trap Darshini at home, we have the most life-changing bagel sandwiches. Darshini enthusiastically orders two</div></div>
    </div>

    <div class="pin" style="--d:0.08s">
      <div class="pin-img"><img src="/pictures/mexico/ramen.jpeg"></div>
      <div class="pin-body"><div class="pin-title">After work, we get amazing massages and then eat ramen in a very aesthetic restaurant</div></div>
    </div>
    <div class="pin" style="--d:0.12s">
      <div class="pin-img"><img src="/pictures/mexico/vibes.jpeg"></div>
      <div class="pin-body"><div class="pin-title">Mexico City has nailed dining in a way I've never seen before</div></div>
    </div>

  </div><!-- /masonry -->

  <!-- ══════════ APRIL 2 ══════════ -->
  <div class="day-header">April 2</div>
  <div class="masonry">
    <div class="pin" style="--d:0.04s">
      <div class="pin-img"><img src="/pictures/mexico/pools.jpeg"></div>
      <div class="pin-body"><div class="pin-title">Darshini and I have an insane day at the Tolantongo pools. We wake up at 4am to take a 4 hour shuttle to the middle of Mexico. Darshini sleeps one hour which worries me</div></div>
    </div>
    <div class="pin" style="--d:0.08s">
      <div class="pin-img"><img src="/pictures/mexico/swim.jpeg"></div>
      <div class="pin-body"><div class="pin-title">We frolick around the pools and have a photoshoot</div></div>
    </div>
    <div class="pin" style="--d:0.12s">
      <div class="pin-img"><img src="/pictures/mexico/crystal.jpeg"></div>
      <div class="pin-body"><div class="pin-title">We oogle at mineralized structures</div></div>
    </div>
    <div class="pin" style="--d:0.16s">
      <div class="pin-img"><img src="/pictures/mexico/breakfast.jpeg"></div>
      <div class="pin-body"><div class="pin-title">We eat breakfast at the resort</div></div>
    </div>
    <div class="pin" style="--d:0.2s">
      <div class="pin-img"><img src="/pictures/mexico/waterfall.jpeg"></div>
      <div class="pin-body"><div class="pin-title">After the pools, we are led to the waterfalls area. It is stunning</div></div>
    </div>
    <div class="pin" style="--d:0.24s">
      <div class="pin-img"><img src="/pictures/mexico/hole.jpeg"></div>
      <div class="pin-body"><div class="pin-title">We run through the freezing waterfall to enter a tunnel where it is hot and stuffy. It is dark, slippery, and full of people. At points we are chest deep in water. We reached the end of the tunnel on our second try</div></div>
    </div>
    <div class="pin" style="--d:0.04s"><div class="pin-img"><img src="/pictures/mexico/blue.jpeg"></div>
        <div class="pin-body"><div class="pin-title">After the tunnel, we swim in the cave which is filled with fresh, hot spring water. It is light blue and extremely pleasant</div>
    </div>
      </div>
      <div class="pin" style="--d:0.04s"><div class="pin-img"><img src="/pictures/mexico/stream.jpeg"></div>
        <div class="pin-body"><div class="pin-title">We play in the stream and put the mud on our faces</div>
    </div>
      </div>
    <div class="pin" style="--d:0.28s">
      <div class="pin-img"><img src="/pictures/mexico/indian.jpeg"></div>
      <div class="pin-body"><div class="pin-title">For dinner, we avoid Mexican food and eat at a delicious Indian restaurant</div></div>
    </div>

  </div><!-- /masonry -->

  <!-- ══════════ APRIL 3 ══════════ -->
  <div class="day-header">April 3</div>
  <div class="masonry">
    <div class="pin" style="--d:0.04s">
      <div class="pin-img"><img src="/pictures/mexico/lunch.JPG"></div>
      <div class="pin-body"><div class="pin-title">Since the line at Jenni's quesadilla place is too long, Darshini and I go to get some street food with no line and two reviews on Google</div></div>
    </div>
    <div class="pin" style="--d:0.08s">
      <div class="pin-img"><img src="/pictures/mexico/bigcup.JPG"></div>
      <div class="pin-body"><div class="pin-title">We feel like locals</div></div>
    </div>
    <div class="pin" style="--d:0.12s">
      <div class="pin-img"><img src="/pictures/mexico/pose.JPG"></div>
        <div class="pin-body"><div class="pin-title">Me and Darshini go shopping after work</div></div>
    </div>
    <div class="pin" style="--d:0.16s">
      <div class="pin-img"><img src="/pictures/mexico/pose2.JPG"></div>
              <div class="pin-body"><div class="pin-title">We take pictures</div></div>
    </div>
    <div class="pin" style="--d:0.2s">
      <div class="pin-img"><img src="/pictures/mexico/us2.JPG"></div>
                    <div class="pin-body"><div class="pin-title">We go to a rooftop bar</div></div>
    </div>
    <div class="pin" style="--d:0.24s">
      <div class="pin-img"><img src="/pictures/mexico/guac.JPG"></div>
                    <div class="pin-body"><div class="pin-title">We eat the worst guac of our lives</div></div>
    </div>
    <div class="pin" style="--d:0.28s">
      <div class="pin-img"><img src="/pictures/mexico/us3.JPG"></div>
      <div class="pin-body"><div class="pin-title">Our waiter takes our pic after convincing us to buy Topo Chicos to cleanse our palate between each sip of our cocktail</div></div>
    </div>
    <div class="pin" style="--d:0.36s">
      <div class="pin-img"><img src="/pictures/mexico/drinks.JPG"></div>
         <div class="pin-body"><div class="pin-title">We don't realize we were swindled until later</div></div>

    </div>
    <div class="pin" style="--d:0.32s">
      <div class="pin-img"><img src="/pictures/mexico/us4.jpeg"></div>
            <div class="pin-body"><div class="pin-title">We end up at a bar that reminds of us Still Liquor</div></div>

    </div>

  </div><!-- /masonry -->

  <!-- ══════════ APRIL 4 ══════════ -->
  <div class="day-header">April 4</div>
  <div class="masonry">
    <div class="pin" style="--d:0.04s"><div class="pin-img"><img src="/pictures/mexico/lepu2.JPG">
    <div class="pin-body"><div class="pin-title">We are back for the bagels</div></div></div></div>
    <div class="pin" style="--d:0.08s">
        <div class="pin-img"><img src="/pictures/mexico/shop.jpeg"></div>
        <div class="pin-body"><div class="pin-title">We go shopping in El Bazar Sábado</div></div>
    </div>
    <div class="pin" style="--d:0.12s"><div class="pin-img">
        <img src="/pictures/mexico/door.jpeg"></div>
        <div class="pin-body"><div class="pin-title">I love the doors in Mexico City</div></div>
    </div>
    <div class="pin" style="--d:0.16s"><div class="pin-img">
        <img src="/pictures/mexico/fancy.jpeg"></div>
        <div class="pin-body"><div class="pin-title">We visit another expensive rooftop bar</div></div>
    </div>
    <div class="pin" style="--d:0.2s">  
        <div class="pin-img"><img src="/pictures/mexico/chip.JPG"></div>
        <div class="pin-body"><div class="pin-title">We have a photoshoot with the chips</div></div>
    </div>
    <div class="pin" style="--d:0.24s"><div class="pin-img">
        <img src="/pictures/mexico/chip2.JPG"></div>
            <div class="pin-body"><div class="pin-title">There is no evidence but after dinner, we sing I Want It That Way by the Backstreet Boys at a karaoke bar frequented by locals. We think about this experience often</div></div></div>

    </div>

  </div><!-- /masonry -->

  <!-- ══════════ APRIL 5 ══════════ -->
  <div class="day-header">April 5</div>
  <div class="masonry">
    <div class="pin" style="--d:0.04s"><div class="pin-img"><img src="/pictures/mexico/chila.jpeg"></div>
    <div class="pin-body"><div class="pin-title">We eat chilaqualies for breakfast. I had not heard of this food before</div></div>
    </div>
    <div class="pin" style="--d:0.08s"><div class="pin-img"><img src="/pictures/mexico/airbnb.jpeg"></div>
    <div class="pin-body"><div class="pin-title">We arrive at our new Airbnb. We are not ready. The toilet doesn't flush. The front door lock is dysfunctional</div></div>
    </div>
    <div class="pin" style="--d:0.12s"><div class="pin-img"><img src="/pictures/mexico/bike.jpeg"></div>
    <div class="pin-body"><div class="pin-title">We rent bikes and bike through the city where they have bike only streets on Sundays</div></div>
    </div>
    <div class="pin" style="--d:0.16s"><div class="pin-img"><img src="/pictures/mexico/mural.jpeg"></div>
    <div class="pin-body"><div class="pin-title">We participate in a free walking tour and learn about Frida Kahlo's husband, Diego</div></div>
    </div>
    <div class="pin" style="--d:0.2s"><div class="pin-img"><img src="/pictures/mexico/rest.jpeg"></div>
    <div class="pin-body"><div class="pin-title">I crawl into Cafe de Tabuca exhuasted from the tour</div></div>
    </div>
    <div class="pin" style="--d:0.24s"><div class="pin-img"><img src="/pictures/mexico/ench.jpeg"></div>
    <div class="pin-body"><div class="pin-title">We eat enchiladas at last</div></div>
    </div>

  </div><!-- /masonry -->

  <!-- ══════════ APRIL 6 ══════════ -->
  <div class="day-header">April 6</div>
  <div class="masonry">
   <div class="pin" style="--d:0.04s">
        <div class="pin-body"><div class="pin-title">Preethi arrives!!! But the front door lock breaks again...</div></div>
    </div>
    <div class="pin" style="--d:0.04s"><div class="pin-img"><img src="/pictures/mexico/pastor.jpeg"></div>
        <div class="pin-body"><div class="pin-title">We walk around Roma Norte to show Preethi the neighborhood. We eat tacos</div></div>
    </div>
    <div class="pin" style="--d:0.08s"><div class="pin-img"><img src="/pictures/mexico/chur.jpeg"></div>
            <div class="pin-body"><div class="pin-title">And then a churro</div></div>
    </div>
    <div class="pin" style="--d:0.04s"><div class="pin-img"><img src="/pictures/mexico/bug.jpeg"></div>
        <div class="pin-body"><div class="pin-title">There is a cockroach issue at our Airbnb, but Preethi bravely defends us with a sword. The culprit turns out to be a rock</div>
    </div>
    </div>

  </div><!-- /masonry -->

  <!-- ══════════ APRIL 7 ══════════ -->
  <div class="day-header">April 7</div>
  <div class="masonry">
    <div class="pin" style="--d:0.04s"><div class="pin-img"><img src="/pictures/mexico/cafe.jpeg"></div>
                <div class="pin-body"><div class="pin-title">Preethi and I get coffee at Lardo</div></div>
    </div>
    <div class="pin" style="--d:0.08s"><div class="pin-img"><img src="/pictures/mexico/guava.jpeg"></div>
                <div class="pin-body"><div class="pin-title">And a guava pastry</div></div>
    </div>
    <div class="pin" style="--d:0.12s"><div class="pin-img"><img src="/pictures/mexico/prod.jpeg"></div>
                <div class="pin-body"><div class="pin-title">We pass a lively market on our way home</div></div>
    </div>
    <div class="pin" style="--d:0.16s"><div class="pin-img"><img src="/pictures/mexico/que.jpeg"></div>
                <div class="pin-body"><div class="pin-title">We take Darshini there for lunch </div></div>
    </div>
    <div class="pin" style="--d:0.04s"><div class="pin-img"><img src="/pictures/mexico/game.JPG"></div>
        <div class="pin-body"><div class="pin-title">After work, we get ready to experience some Mexican culture</div>
    </div>
    </div>
    <div class="pin" style="--d:0.2s"><div class="pin-img"><img src="/pictures/mexico/fight.jpeg"></div>
                    <div class="pin-body"><div class="pin-title">We meet Annie at the Luche Libra show</div></div>
    </div>
    <div class="pin" style="--d:0.04s"><div class="pin-img"><img src="/pictures/mexico/fighters.jpeg"></div>
        <div class="pin-body"><div class="pin-title">We are confused but amused</div>
    </div></div>
    

  </div><!-- /masonry -->

  <!-- ══════════ APRIL 8 ══════════ -->
  <div class="day-header">April 8</div>
  <div class="masonry">
    <div class="pin" style="--d:0.04s"><div class="pin-img"><img src="/pictures/mexico/cool.jpeg"></div>
        <div class="pin-body"><div class="pin-title">I go shopping. I buy a long linen dress</div></div>
    </div>
    <div class="pin" style="--d:0.08s"><div class="pin-img"><img src="/pictures/mexico/bestbar.jpeg"></div>
    <div class="pin-body"><div class="pin-title">We get cocktails at the best bar in the world but are disappointed</div></div>
    </div>

  </div><!-- /masonry -->

   <!-- ══════════ APRIL 8 ══════════ -->
  <div class="day-header">April 9</div>
  <div class="masonry">
   <div class="pin" style="--d:0.04s"><div class="pin-img"><img src="/pictures/mexico/dogs.jpeg"></div>
        <div class="pin-body"><div class="pin-title">I continue to go on runs and see mobs of dogs being walked</div>
    </div>
      </div>
    <div class="pin" style="--d:0.04s"><div class="pin-img"><img src="/pictures/mexico/boats.JPG"></div>
        <div class="pin-body"><div class="pin-title">After work we visit the Coyoacan canals</div>
    </div>
      </div>
      <div class="pin" style="--d:0.04s"><div class="pin-img"><img src="/pictures/mexico/guacer.jpeg"></div>
        <div class="pin-body"><div class="pin-title">Somehow we do not win the guac competition</div>
    </div>
      </div>
    <div class="pin" style="--d:0.04s"><div class="pin-img"><img src="/pictures/mexico/corn.JPG"></div>
        <div class="pin-body"><div class="pin-title">We purchase corn from a passing boat</div>
    </div>
      </div>
    <div class="pin" style="--d:0.04s"><div class="pin-img"><img src="/pictures/mexico/porc.jpeg"></div>
        <div class="pin-body"><div class="pin-title">Darshini holds a porcupine after seeing axolotl. Preethi is scared of snakes. Darshini later holds a small corn snake</div>
    </div>
      </div>
    <div class="pin" style="--d:0.04s"><div class="pin-img"><img src="/pictures/mexico/chine.jpeg"></div>
        <div class="pin-body"><div class="pin-title">We eat at a Chinese restuarant for dinner that is unexpectedly amazing</div>
    </div>
    </div>

  </div><!-- /masonry -->

  <!-- ══════════ APRIL 10 ══════════ -->
  <div class="day-header">April 10</div>
  <div class="masonry">
    <div class="pin" style="--d:0.16s"><div class="pin-img"><img src="/pictures/mexico/balloon.JPG"></div>
    <div class="pin-body"><div class="pin-title">We get up at 4am again and take a hot air balloon ride over the Teothihuacán pyramids</div>
    </div>
    </div>
     <div class="pin" style="--d:0.04s"><div class="pin-img"><img src="/pictures/mexico/self.JPG"></div>
        <div class="pin-body"><div class="pin-title">Many pictures are taken</div>
    </div>
      </div>
    <div class="pin" style="--d:0.2s"><div class="pin-img"><img src="/pictures/mexico/cave.jpeg"></div>
    <div class="pin-body"><div class="pin-title">We eat breakfast in a cave with some questionable Europeans</div>
    </div>
    </div>
    <div class="pin" style="--d:0.24s"><div class="pin-img"><img src="/pictures/mexico/group.jpeg"></div>
    <div class="pin-body"><div class="pin-title">We take a picture before Darshini and I make a TikTok dance and Preethi has to distance herself</div>
    </div>
    </div>
    <div class="pin" style="--d:0.04s"><div class="pin-img"><img src="/pictures/mexico/lastdin.jpeg"></div>
    <div class="pin-body"><div class="pin-title">We eat our final dinner</div>
    </div>
    </div>
    <div class="pin" style="--d:0.08s"><div class="pin-img"><img src="/pictures/mexico/lastde.jpeg"></div>
    <div class="pin-body"><div class="pin-title">And share an alcoholic-tasting tres leches</div>
    </div>
    </div>
    <div class="pin" style="--d:0.12s"><div class="pin-img"><img src="/pictures/mexico/swank.jpeg"></div>
    <div class="pin-body"><div class="pin-title">We get drinks at an empty bar</div>
    </div>
    </div>

  </div><!-- /masonry -->

  <!-- ══════════ APRIL 11 ══════════ -->
  <div class="day-header">April 11</div>
  <div class="masonry">
    <div class="pin" style="--d:0.04s"><div class="pin-img"><img src="/pictures/mexico/lepu3.jpeg"></div>
        <div class="pin-body"><div class="pin-title">We nervously take Preethi, now a New Yorker, to our favorite bagel spot</div>
    </div>
  </div>

  <div class="pin" style="--d:0.04s">
        <div class="pin-body"><div class="pin-title">And then I go to the airport and reminisce on the exhilarating two weeks I got to spend in Mexico with my best friends!!!</div>
    </div>
  </div>

  </div><!-- /masonry -->

  </body>
  </html>
