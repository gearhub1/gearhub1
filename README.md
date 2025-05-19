<svg width="120" height="120" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg" style="margin-bottom: 0.5rem;">
  <g transform="translate(100,100)">
    <circle r="60" fill="#0052cc" stroke="#000" stroke-width="5"/>
    <g>
      <!-- Gear teeth -->
      <g fill="#0052cc" stroke="#000" stroke-width="3">
        <circle r="75" fill="none"/>
        <g>
          <!-- Draw 20 teeth -->
          <g id="tooth">
            <rect x="-5" y="-80" width="10" height="15" />
          </g>
          <use href="#tooth" transform="rotate(18)"/>
          <use href="#tooth" transform="rotate(36)"/>
          <use href="#tooth" transform="rotate(54)"/>
          <use href="#tooth" transform="rotate(72)"/>
          <use href="#tooth" transform="rotate(90)"/>
          <use href="#tooth" transform="rotate(108)"/>
          <use href="#tooth" transform="rotate(126)"/>
          <use href="#tooth" transform="rotate(144)"/>
          <use href="#tooth" transform="rotate(162)"/>
          <use href="#tooth" transform="rotate(180)"/>
          <use href="#tooth" transform="rotate(198)"/>
          <use href="#tooth" transform="rotate(216)"/>
          <use href="#tooth" transform="rotate(234)"/>
          <use href="#tooth" transform="rotate(252)"/>
          <use href="#tooth" transform="rotate(270)"/>
          <use href="#tooth" transform="rotate(288)"/>
          <use href="#tooth" transform="rotate(306)"/>
          <use href="#tooth" transform="rotate(324)"/>
          <use href="#tooth" transform="rotate(342)"/>
        </g>
      </g>
    </g>
    <!-- Garage name inside -->
    <text x="0" y="5" text-anchor="middle" fill="white" font-size="14" font-family="Arial" font-weight="bold">GearHub</text>
    <text x="0" y="25" text-anchor="middle" fill="white" font-size="10" font-family="Arial">Auto Services</text>
  </g>
</svg>
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>GearHub Auto Services</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f7fc;
      color: #222;
    }
    header {
      background: linear-gradient(to right, #0052cc, #007bff);
      color: white;
      padding: 2rem 1rem;
      text-align: center;
      position: relative;
    }
    header img {
      max-width: 120px;
      margin-bottom: 1rem;
    }
    nav {
      background: #004bb5;
      display: flex;
      justify-content: center;
      padding: 1rem;
    }
    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
    }
    .section {
      padding: 2rem 1rem;
      max-width: 1000px;
      margin: auto;
    }
    .services, .reviews, .contact, .booking {
      background: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      margin-bottom: 2rem;
      padding: 1.5rem;
    }
    h2 {
      color: #0052cc;
    }
    ul {
      padding-left: 1.5rem;
    }
    .form-group {
      margin-bottom: 1rem;
    }
    input, textarea {
      width: 100%;
      padding: 0.75rem;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background: #0052cc;
      color: white;
      padding: 0.75rem 1.5rem;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .map iframe {
      width: 100%;
      border: none;
      border-radius: 10px;
      height: 300px;
    }
    .social {
      text-align: center;
      margin-top: 1rem;
    }
    .social a {
      margin: 0 0.5rem;
      display: inline-block;
    }
    .reviews blockquote {
      border-left: 4px solid #007bff;
      padding-left: 1rem;
      margin: 1rem 0;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #002e80;
      color: white;
    }
  </style>
</head>
<body>
  <header>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/33/Car_icon_blue.svg/2048px-Car_icon_blue.svg.png" alt="GearHub Logo">
    <h1>GearHub Auto Services</h1>
    <p>Leicester | 8C Asfordby Street, LE5 3QG</p>
  </header>
  <nav>
    <a href="#services">Services</a>
    <a href="#booking">Book</a>
    <a href="#contact">Contact</a>
    <a href="#reviews">Reviews</a>
  </nav>  <div class="section services" id="services">
    <h2>Our Services</h2>
    <ul>
      <li>🔧Engine Rebuild & General Services</li>
      <li>🛠Gearboxes</li>
      <li>Electric & Wiring</li>
      <li>🚗Clutches</li>
      <li>🚑Suspension</li>
      <li>Radiators</li>
      <li>Clutch Actuators (Recondition & Reprogramming)</li>
      <li>Tyre Services</li>
      <li>Timing Belts & Chains</li>
      <li>Exhausts</li>
      <li>Brakes & Discs</li>
    </ul>
  </div>  <div class="section booking" id="booking">
    <h2>Book an Appointment</h2>
    <form>
      <div class="form-group">
        <input type="text" placeholder="Full Name" required />
      </div>
      <div class="form-group">
        <input type="email" placeholder="Email" required />
      </div>
      <div class="form-group">
        <input type="tel" placeholder="Phone" required />
      </div>
      <div class="form-group">
        <textarea placeholder="Describe your issue/service needed"></textarea>
      </div>
      <button type="submit">Submit</button>
    </form>
    <div class="social">
      <a href="https://wa.me/447944121280" target="_blank">WhatsApp</a> |
      <a href="https://www.facebook.com/share/192qrkpp9z/" target="_blank">Facebook</a>
    </div>
  </div>  <div class="section contact" id="contact">
    <h2>Contact & Hours</h2>
    <p><strong>Phone:</strong> <a href="tel:+447944121280">07944 121280</a></p>
    <p><strong>Email:</strong> <a href="mailto:Gearhub111@gmail.com">Gearhub111@gmail.com</a></p>
    <p><strong>Hours:</strong> Mon-Fri: 7:30 AM - 6 PM, Sat: 7:30 AM - 4 PM, Sun: Closed</p>
  </div>  <div class="section reviews" id="reviews">
    <h2>Customer Reviews</h2>
    <blockquote>“Fantastic service. Highly professional and reliable.” – Adeel H.</blockquote>
    <blockquote>“Best garage in Leicester. Got my brakes fixed quickly.” – Sonia M.</blockquote>
    <blockquote>“Excellent diagnostics and fair pricing.” – James R.</blockquote>
    <blockquote>“Friendly staff and clean workshop. Highly recommended!” – Olivia K.</blockquote>
  </div>  <div class="section map">
    <h2>Find Us</h2>
    <iframe src="https://maps.google.com/maps?q=8C%20Asfordby%20St,%20Leicester&t=&z=13&ie=UTF8&iwloc=&output=embed"></iframe>
  </div>  <footer>
    &copy; 2025 GearHub Auto Services. All rights reserved.
  </footer>
</body>
</html>
