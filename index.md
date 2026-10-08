<style>
@import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,500;0,600;1,500&family=Inter:wght@400;500&display=swap');

body { background: #f5f4ec; color: #2e2f26; font-family: 'Inter', sans-serif; line-height: 1.75; }
.markdown-body, .container-lg { max-width: 760px; }
h2 { font-family: 'Cormorant Garamond', serif; color: #3f4a22; border: none !important; font-weight: 600; font-size: 2em; margin: 0 0 18px; }
a { color: #5e6b2c; }
p { margin: 0 0 14px; }

.label { font-size: 0.72em; letter-spacing: 0.18em; text-transform: uppercase; color: #8a9361; margin-top: 70px; }

.hero { display: flex; align-items: center; gap: 36px; flex-wrap: wrap; padding: 40px 0 10px; }
.hero img { width: 170px; height: 170px; object-fit: cover; border-radius: 50%; border: 6px solid #fff; box-shadow: 0 6px 24px rgba(63,74,34,0.15); }
.hero > div { flex: 1; min-width: 260px; }
.hero-name { font-family: 'Cormorant Garamond', serif; font-size: 3.2em; line-height: 1.05; color: #3f4a22; font-weight: 600; margin: 0; }
.hero-sub { color: #6f705f; margin: 10px 0 18px; }
.btn { display: inline-block; padding: 7px 20px; border-radius: 30px; text-decoration: none !important; font-size: 0.9em; margin-right: 8px; }
.btn-fill { background: #5e6b2c; color: #fff !important; }
.btn-line { border: 1px solid #5e6b2c; color: #5e6b2c !important; }

.quote { font-family: 'Cormorant Garamond', serif; font-style: italic; font-size: 1.6em; line-height: 1.4; color: #4f5a2c; border-left: 2px solid #a5ad7f; padding-left: 22px; margin: 50px 0 0; }

.timeline { margin-left: 8px; padding-left: 28px; border-left: 1px solid #c9cdb0; }
.step { position: relative; margin-bottom: 24px; }
.step::before { content: ""; position: absolute; left: -34px; top: 8px; width: 11px; height: 11px; border-radius: 50%; background: #f5f4ec; border: 2px solid #5e6b2c; }
.step .when { font-size: 0.8em; letter-spacing: 0.08em; color: #8a9361; text-transform: uppercase; }
.step .what { font-family: 'Cormorant Garamond', serif; font-size: 1.4em; color: #3f4a22; font-weight: 600; line-height: 1.3; }
.step .desc { color: #5c5d50; font-size: 0.95em; }

.cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(160px, 1fr)); gap: 14px; }
.card { background: #fff; border-radius: 14px; padding: 18px 20px; box-shadow: 0 2px 12px rgba(63,74,34,0.07); }
.card b { display: block; font-family: 'Cormorant Garamond', serif; font-size: 1.35em; color: #3f4a22; }
.card span { font-size: 0.88em; color: #5c5d50; }

.gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(160px, 1fr)); gap: 12px; }
.gallery figure { margin: 0; }
.gallery img { width: 100%; height: 170px; object-fit: cover; border-radius: 12px; display: block; }
.gallery figcaption { font-size: 0.8em; color: #8a8b7a; margin-top: 6px; }

.footer { text-align: center; color: #9a9b8a; font-size: 0.85em; margin: 80px 0 30px; }
</style>

<div class="hero">
  <img src="me.jpg" alt="Sana" onerror="this.style.display='none'">
  <div>
    <p class="hero-name">Sana Fathima<br>Srambicool</p>
    <p class="hero-sub">BIPM student at HWR Berlin</p>
    <a class="btn btn-fill" href="https://www.linkedin.com/in/YOUR-LINKEDIN">LinkedIn</a>
    <a class="btn btn-line" href="https://github.com/sananazim27-star">GitHub</a>
  </div>
</div>

<p class="quote">Grew up in Dubai, found my way to Germany, and now back in Berlin with a matcha in hand.</p>

<p class="label">My journey</p>

## How I got here

<div class="timeline">
  <div class="step"><div class="when">Where it started</div><div class="what">Dubai</div><div class="desc">Sunshine, school, and my first job</div></div>
  <div class="step"><div class="when">2021</div><div class="what">Berlin</div><div class="desc">Moved to Germany, new language, first real winter</div></div>
  <div class="step"><div class="when">2022 – 2026</div><div class="what">Schweinfurt</div><div class="desc">Bachelor's at THWS, small town, great friends</div></div>
  <div class="step"><div class="when">2025 – 2026</div><div class="what">Stuttgart</div><div class="desc">Working at Bosch</div></div>
  <div class="step"><div class="when">2026</div><div class="what">Berlin again</div><div class="desc">Master's at HWR, the next chapter</div></div>
</div>

<p class="label">Pictures</p>

## Places that shaped me

<div class="gallery">
  <figure><img src="dubai.jpg" alt="Dubai" onerror="this.parentElement.style.display='none'"><figcaption>Dubai</figcaption></figure>
  <figure><img src="schweinfurt.jpg" alt="Schweinfurt" onerror="this.parentElement.style.display='none'"><figcaption>Schweinfurt</figcaption></figure>
  <figure><img src="stuttgart.jpg" alt="Stuttgart" onerror="this.parentElement.style.display='none'"><figcaption>Stuttgart</figcaption></figure>
  <figure><img src="berlin.jpg" alt="Berlin" onerror="this.parentElement.style.display='none'"><figcaption>Berlin</figcaption></figure>
</div>

<p class="label">Off the clock</p>

## Things I love

<div class="cards">
  <div class="card"><b>Baking</b><span>Cakes, cookies, and the occasional disaster</span></div>
  <div class="card"><b>Matcha &amp; cafés</b><span>Always hunting for the best one in town</span></div>
  <div class="card"><b>Movies</b><span>Happy to watch anything once</span></div>
  <div class="card"><b>Long walks</b><span>Best way to get to know a new city</span></div>
</div>

<p style="margin-top:28px">I speak English, Hindi, Malayalam and some German. Matcha recommendations in Berlin are always welcome.</p>

<p class="footer">Sana · BIPM, HWR Berlin · 2026</p>
