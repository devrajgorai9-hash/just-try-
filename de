
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Devraj | Photographer Portfolio</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  background: #101010;
  color: #fff;
  font-family: Arial, sans-serif;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 25px 8%;
  border-bottom: 1px solid #292929;
}

.logo {
  font-size: 24px;
  font-weight: bold;
  letter-spacing: 2px;
}

nav a {
  color: #fff;
  text-decoration: none;
  margin-left: 24px;
  font-size: 14px;
}

nav a:hover {
  color: #c9a96e;
}

.hero {
  min-height: 80vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 80px 8%;
  background:
    linear-gradient(90deg, #101010 10%, #101010bb 55%, #10101033),
    url("https://images.unsplash.com/photo-1516035069371-29a1b244cc32?auto=format&fit=crop&w=1800&q=90")
    center/cover;
}

.hero p {
  color: #c9a96e;
  letter-spacing: 4px;
  text-transform: uppercase;
  margin-bottom: 20px;
}

.hero h1 {
  font-size: clamp(45px, 8vw, 95px);
  line-height: 1.05;
  max-width: 750px;
}

.hero h1 span {
  color: #c9a96e;
}

.hero .description {
  color: #ddd;
  letter-spacing: 0;
  line-height: 1.8;
  margin: 25px 0;
  max-width: 480px;
}

.btn {
  display: inline-block;
  width: fit-content;
  padding: 14px 25px;
  border: 1px solid #c9a96e;
  color: #c9a96e;
  text-decoration: none;
  transition: .3s;
}

.btn:hover {
  background: #c9a96e;
  color: #101010;
}

section {
  padding: 85px 8%;
}

.section-title {
  font-size: 38px;
  margin-bottom: 15px;
}

.section-subtitle {
  color: #aaa;
  margin-bottom: 35px;
  line-height: 1.7;
}

.filters {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin-bottom: 30px;
}

.filters button {
  padding: 10px 18px;
  background: transparent;
  border: 1px solid #444;
  color: white;
  cursor: pointer;
}

.filters button.active,
.filters button:hover {
  background: #c9a96e;
  color: #101010;
  border-color: #c9a96e;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 18px;
}

.photo {
  height: 300px;
  overflow: hidden;
  cursor: pointer;
  background: #222;
}

.photo img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: .5s;
}

.photo:hover img {
  transform: scale(1.07);
}

.about {
  display: grid;
  grid-template-columns: 1fr 1fr;
  align-items: center;
  gap: 50px;
}

.about img {
  width: 100%;
  max-height: 500px;
  object-fit: cover;
}

.about p {
  color: #bbb;
  line-height: 1.9;
  margin: 20px 0;
}

.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}

.service {
  padding: 30px;
  border: 1px solid #333;
  transition: .3s;
}

.service:hover {
  border-color: #c9a96e;
  transform: translateY(-5px);
}

.service h3 {
  color: #c9a96e;
  margin-bottom: 15px;
}

.service p {
  color: #aaa;
  line-height: 1.8;
}

.contact {
  text-align: center;
  background: #181818;
}

.contact p {
  color: #bbb;
  margin: 20px 0 30px;
  line-height: 1.8;
}

footer {
  text-align: center;
  padding: 25px;
  color: #888;
  border-top: 1px solid #292929;
  font-size: 13px;
}

.lightbox {
  display: none;
  position: fixed;
  inset: 0;
  z-index: 100;
  background: #000e;
  justify-content: center;
  align-items: center;
  padding: 20px;
}

.lightbox img {
  max-width: 95%;
  max-height: 90vh;
  object-fit: contain;
}

.lightbox.show {
  display: flex;
}

.close {
  position: absolute;
  top: 20px;
  right: 30px;
  color: white;
  font-size: 40px;
  cursor: pointer;
}

@media (max-width: 800px) {
  nav {
    padding: 20px 5%;
  }

  nav a {
    margin-left: 10px;
    font-size: 12px;
  }

  .hero {
    padding: 70px 6%;
  }

  section {
    padding: 60px 6%;
  }

  .gallery {
    grid-template-columns: repeat(2, 1fr);
  }

  .about {
    grid-template-columns: 1fr;
  }

  .services {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 480px) {
  .logo {
    font-size: 18px;
  }

  nav a {
    margin-left: 8px;
    font-size: 11px;
  }

  .gallery {
    grid-template-columns: 1fr;
  }

  .photo {
    height: 320px;
  }
}
</style>
</head>

<body>

<nav>
  <div class="logo">DEVRAJ<span style="color:#c9a96e">.</span></div>
  <div>
    <a href="#home">Home</a>
    <a href="#work">Work</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<header class="hero" id="home">
  <p>Photographer & Visual Artist</p>
  <h1>Capturing<br>Moments,<br><span>Creating Art.</span></h1>
  <p class="description">
    Every picture tells a story. I capture emotions,
    people and unforgettable moments through my lens.
  </p>
  <a href="#work" class="btn">EXPLORE MY WORK ↗</a>
</header>

<section id="work">
  <h2 class="section-title">Selected Works.</h2>
  <p class="section-subtitle">
    A collection of moments, stories and perspectives.
  </p>

  <div class="filters">
    <button class="active" data-filter="all">All Work</button>
    <button data-filter="portrait">Portrait</button>
    <button data-filter="wedding">Wedding</button>
    <button data-filter="nature">Nature</button>
  </div>

  <div class="gallery">

    <div class="photo" data-category="portrait">
      <img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=900&q=85" alt="Portrait photography">
    </div>

    <div class="photo" data-category="nature">
      <img src="https://images.unsplash.com/photo-1470770841072-f978cf4d019e?auto=format&fit=crop&w=900&q=85" alt="Nature photography">
    </div>

    <div class="photo" data-category="wedding">
      <img src="https://images.unsplash.com/photo-1519741497674-611481863552?auto=format&fit=crop&w=900&q=85" alt="Wedding photography">
    </div>

    <div class="photo" data-category="portrait">
      <img src="https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?auto=format&fit=crop&w=900&q=85" alt="Portrait photo">
    </div>

    <div class="photo" data-category="nature">
      <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?auto=format&fit=crop&w=900&q=85" alt="Landscape photography">
    </div>

    <div class="photo" data-category="wedding">
      <img src="https://images.unsplash.com/photo-1537633552985-df8429e8048b?auto=format&fit=crop&w=900&q=85" alt="Wedding couple">
    </div>

  </div>
</section>

<section id="about">
  <div class="about">
    <img src="https://images.unsplash.com/photo-1452587925148-ce544e77e70d?auto=format&fit=crop&w=1000&q=85" alt="Photographer with camera">

    <div>
      <h2 class="section-title">Behind The Lens.</h2>
      <p>
        Hello, I'm Devraj — a photographer passionate about
        storytelling through beautiful images.
      </p>
      <p>
        From portraits to weddings and natural landscapes,
        I believe every moment has a unique story worth
        preserving. My goal is to turn ordinary moments
        into extraordinary memories.
      </p>
      <a href="#contact" class="btn">LET'S CONNECT ↗</a>
    </div>
  </div>
</section>

<section id="services">
  <h2 class="section-title">What I Do.</h2>
  <p class="section-subtitle">
    Photography services tailored to your story.
  </p>

  <div class="services">
    <div class="service">
      <h3>01 / Portraits</h3>
      <p>Personal portraits, fashion shoots and creative expressions.</p>
    </div>

    <div class="service">
      <h3>02 / Weddings</h3>
      <p>Authentic emotions and beautiful memories from your special day.</p>
    </div>

    <div class="service">
      <h3>03 / Nature</h3>
      <p>Landscapes, travel photography and the beauty of the natural world.</p>
    </div>
  </div>
</section>

<section class="contact" id="contact">
  <h2 class="section-title">Let's Create Something.</h2>
  <p>
    Have a project or special moment in mind?<br>
    Let's discuss your photography needs.
  </p>
  <a href="mailto:your-email@example.com" class="btn">EMAIL ME ↗</a>
  <br><br>
  <a href="https://www.instagram.com/" class="btn" target="_blank" rel="noopener">INSTAGRAM ↗</a>
</section>

<footer>
  © 2026 Devraj Photography. All Rights Reserved.
</footer>

<div class="lightbox" id="lightbox">
  <span class="close" id="closeLightbox">&times;</span>
  <img id="lightboxImage" src="" alt="Expanded photograph">
</div>

<script>
const filterButtons = document.querySelectorAll(".filters button");
const photos = document.querySelectorAll(".photo");

filterButtons.forEach(button => {
  button.addEventListener("click", () => {
    filterButtons.forEach(item => item.classList.remove("active"));
    button.classList.add("active");

    const filter = button.dataset.filter;

    photos.forEach(photo => {
      photo.style.display =
        filter === "all" || photo.dataset.category === filter
          ? "block"
          : "none";
    });
  });
});

const lightbox = document.getElementById("lightbox");
const lightboxImage = document.getElementById("lightboxImage");

photos.forEach(photo => {
  photo.addEventListener("click", () => {
    lightboxImage.src = photo.querySelector("img").src;
    lightbox.classList.add("show");
  });
});

document.getElementById("closeLightbox").addEventListener("click", () => {
  lightbox.classList.remove("show");
});

lightbox.addEventListener("click", event => {
  if (event.target === lightbox) {
    lightbox.classList.remove("show");
  }
});

document.addEventListener("keydown", event => {
  if (event.key === "Escape") {
    lightbox.classList.remove("show");
  }
});
</script>

</body>
</html>
