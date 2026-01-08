[index_Version5.html](https://github.com/user-attachments/files/24509821/index_Version5.html)
<!doctype html>
<html lang="en" dir="ltr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>essenzaart</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="site-header">
    <div class="container">
      <h1 class="logo">emilyjohn</h1>
      <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container">
        <h2>Simple free website for online work</h2>
        <p>I offer online services for free — for example: graphic design, web development, virtual assistance.</p>
        <!-- Replace email and phone with your details -->
        <p class="cta">
          <a class="btn" href="mailto:emiluyjohn2519@gmail.com">Email me</a>
          <a class="btn outline" href="https://wa.me/03108809427">Chat on WhatsApp</a>
        </p>
      </div>
    </section>

    <section id="about" class="container section">
      <h3>About</h3>
      <p>Write a short introduction about yourself here — experience, skills, and the online services you provide.</p>
    </section>

    <section id="services" class="container section">
      <h3>Services</h3>
      <div class="grid">
        <div class="card">
          <h4>Service 1</h4>
          <p>Brief description of the service — e.g.: logo design, website development, etc.</p>
        </div>
        <div class="card">
          <h4>Service 2</h4>
          <p>Brief description of the service.</p>
        </div>
        <div class="card">
          <h4>Service 3</h4>
          <p>Brief description of the service.</p>
        </div>
      </div>
    </section>

    <section id="portfolio" class="container section">
      <h3>Portfolio</h3>
      <p>Show your projects or sample images/links here.</p>
      <div class="grid">
        <div class="card">Sample 1</div>
        <div class="card">Sample 2</div>
        <div class="card">Sample 3</div>
      </div>
    </section>

    <section id="contact" class="container section">
      <h3>Contact</h3>
      <p>Provide your email or WhatsApp number here. You can also use the form below — sign up at Formspree and replace the form action with your form ID.</p>

      <!-- Simple contact form (Formspree example) -->
      <form action="https://formspree.io/f/yourFormId" method="POST" class="contact-form">
        <label>Name
          <input type="text" name="name" required />
        </label>
        <label>Email
          <input type="email" name="email" required />
        </label>
        <label>Message
          <textarea name="message" required></textarea>
        </label>
        <button type="submit" class="btn">Send message</button>
      </form>

      <p class="small">If you don't want to use Formspree, use the Email or WhatsApp links above.</p>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© <span id="year"></span> emilyjohn — Online Services</p>
    </div>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
