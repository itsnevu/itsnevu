<div align="center">

<div class="hero-container">

  <div class="glow-bg"></div>

  <h1 class="logo">
    NEVU
  </h1>

  <p class="tagline">
    Serial Builder • Web3 Architect • Tech Hustler
  </p>

</div>

<style>

.hero-container {
  position: relative;
  padding: 90px 20px;
  border-radius: 18px;

  background:
    linear-gradient(
      135deg,
      rgba(0,0,0,0.95),
      rgba(20,20,20,0.95)
    );

  border: 1px solid rgba(255,255,255,0.08);

  box-shadow:

    0 0 60px rgba(88,166,255,0.15),
    inset 0 0 40px rgba(255,255,255,0.02);

  overflow: hidden;
}

.glow-bg {

  position: absolute;

  width: 800px;
  height: 800px;

  background:

    radial-gradient(
      circle,
      rgba(88,166,255,0.15),
      transparent 70%
    );

  animation:

    rotateGlow 18s linear infinite;

  top: -200px;
  left: -200px;

}

.logo {

  font-size: 110px;
  font-weight: 900;

  letter-spacing: 35px;

  font-family:

    'Poppins',
    sans-serif;

  text-transform: uppercase;

  margin: 0;

  background:

    linear-gradient(
      90deg,
      #ffffff,
      #58a6ff,
      #ffffff
    );

  background-size: 200% auto;

  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;

  animation:

    shine 3s linear infinite,
    float 4s ease-in-out infinite;

  text-shadow:

    0 0 20px rgba(88,166,255,0.5),
    0 0 40px rgba(88,166,255,0.3),
    0 0 80px rgba(88,166,255,0.2);

  position: relative;
  z-index: 2;
}

.tagline {

  font-size: 20px;

  color:

    rgba(255,255,255,0.7);

  margin-top: 30px;

  letter-spacing: 6px;

  text-transform: uppercase;

  font-weight: 300;

  font-family:

    'Poppins',
    sans-serif;

  position: relative;
  z-index: 2;

}

@keyframes shine {

  to {
    background-position: 200% center;
  }

}

@keyframes float {

  0% {
    transform: translateY(0px);
  }

  50% {
    transform: translateY(-8px);
  }

  100% {
    transform: translateY(0px);
  }

}

@keyframes rotateGlow {

  0% {
    transform: rotate(0deg);
  }

  100% {
    transform: rotate(360deg);
  }

}

/* Responsive */

@media (max-width: 768px) {

  .logo {

    font-size: 60px;
    letter-spacing: 18px;

  }

  .tagline {

    font-size: 14px;
    letter-spacing: 3px;

  }

}

</style>

</div>
