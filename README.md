<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ashok Enterprises - Services</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" crossorigin="anonymous">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Orbitron', sans-serif;
      background: url('https://cdn.pixabay.com/photo/2023/01/13/17/29/space-7716166_1280.jpg') no-repeat center center fixed;
      background-size: cover;
      color: #fff;
    }
    header {
      background: rgba(0, 0, 0, 0.7);
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 { color: #0ff; font-size: 1.5rem; }
    nav a {
      color: #fff;
      margin-left: 1rem;
      text-decoration: none;
      transition: color 0.3s;
    }
    nav a:hover { color: #0ff; }
    section { padding: 2rem; background: rgba(0,0,0,0.5); }
    h2.section-title { color: #0ff; text-align: center; margin-bottom: 2rem; }
    .services-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1rem;
    }
    .service-item {
      background: rgba(0, 0, 0, 0.6);
      border: 1px solid #0ff;
      padding: 1rem;
      border-radius: 10px;
      display: flex;
      align-items: center;
      gap: 0.75rem;
      text-decoration: none;
      color: white;
      transition: all 0.3s ease;
    }
    .service-item:hover {
      background: rgba(0, 255, 255, 0.2);
      transform: scale(1.05);
      color: #0ff;
    }
    .service-item i { color: #0ff; transition: transform 0.3s; }
    .service-item:hover i { transform: scale(1.2); }
    footer {
      text-align: center;
      background: rgba(0, 0, 0, 0.8);
      padding: 1rem;
      font-size: 0.8rem;
    }
    #contact {
      padding: 2rem;
      background: rgba(0,0,0,0.6);
      text-align: center;
    }
    #contact h2 { color: #0ff; margin-bottom: 1rem; }
    #contact p, #contact a {
      color: white;
      margin: 0.5rem 0;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Ashok Enterprises</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>  <section id="services">
    <h2 class="section-title">Government & Utility Services</h2>
    <div class="services-list">
      <a href="https://uidai.gov.in" class="service-item" target="_blank"><i class="fas fa-id-card"></i> Aadhar Services</a>
      <a href="https://www.npci.org.in/what-we-do/aeps/product-overview" class="service-item" target="_blank"><i class="fas fa-fingerprint"></i> AePS</a>
      <a href="https://www.npci.org.in/what-we-do/aadhaar-pay/product-overview" class="service-item" target="_blank"><i class="fas fa-id-badge"></i> Aadhar Pay</a>
      <a href="https://www.onlineservices.nsdl.com/paam/endUserRegisterContact.html" class="service-item" target="_blank"><i class="fas fa-id-badge"></i> PAN Card (NSDL)</a>
      <a href="https://www.pan.utiitsl.com" class="service-item" target="_blank"><i class="fas fa-id-badge"></i> PAN Card (UTI)</a>
      <a href="https://sarathi.parivahan.gov.in" class="service-item" target="_blank"><i class="fas fa-car"></i> Driving Licence</a>
      <a href="https://voters.eci.gov.in" class="service-item" target="_blank"><i class="fas fa-vote-yea"></i> Voter ID</a>
      <a href="https://www.onlineservices.nsdl.com/paam/endUserRegisterContact.html" class="service-item" target="_blank"><i class="fas fa-credit-card"></i> Credit Card Apply</a>
      <a href="https://incometax.gov.in" class="service-item" target="_blank"><i class="fas fa-file-invoice"></i> Income Tax Return</a>
      <a href="https://www.gst.gov.in" class="service-item" target="_blank"><i class="fas fa-file-contract"></i> GST Services</a>
      <a href="https://www.irctc.co.in" class="service-item" target="_blank"><i class="fas fa-train"></i> Train Booking</a>
      <a href="https://www.licindia.in" class="service-item" target="_blank"><i class="fas fa-file-invoice-dollar"></i> LIC Bill Payment</a>
      <a href="https://www.bharatbillpay.com" class="service-item" target="_blank"><i class="fas fa-bolt"></i> Electricity Bill</a>
      <a href="https://www.irctc.co.in" class="service-item" target="_blank"><i class="fas fa-bus"></i> Bus Booking</a>
      <a href="https://www.igiaviationdelhi.com/air-ticket-booking.html" class="service-item" target="_blank"><i class="fas fa-plane"></i> Flight Booking</a>
      <a href="https://www.hotelbooking.com" class="service-item" target="_blank"><i class="fas fa-hotel"></i> Hotel Booking</a>
      <a href="https://www.bankofbaroda.in" class="service-item" target="_blank"><i class="fas fa-university"></i> Bank of Baroda</a>
      <a href="https://www.indiapost.gov.in/vas/Pages/IndiaPostHome.aspx" class="service-item" target="_blank"><i class="fas fa-piggy-bank"></i> India Post Payments Bank</a>
      <a href="https://www.pay1.in" class="service-item" target="_blank"><i class="fas fa-wallet"></i> Pay 1</a>
      <a href="https://www.india.gov.in" class="service-item" target="_blank"><i class="fas fa-landmark"></i> More Govt Services</a>
    </div>
  </section>  <section id="digitalseva">
    <h2 class="section-title">CSC Digital Seva</h2>
    <div class="services-list">
      <a href="https://digitalseva.csc.gov.in" class="service-item" target="_blank"><i class="fas fa-globe"></i> Digital Seva Portal</a>
    </div>
  </section>  <section id="contact">
    <h2>Contact Us</h2>
    <p><i class="fas fa-map-marker-alt"></i> Ashok Enterprise front on Radha Swami Aashram, Kalapur, Pilibhit Road, Bareilly</p>
    <p><i class="fas fa-phone"></i> 9761294444</p>
    <p><i class="fas fa-envelope"></i> <a href="mailto:ashokenterprises109@gmail.com">ashokenterprises109@gmail.com</a></p>
    <p><i class="fab fa-whatsapp"></i> WhatsApp Available</p>
  </section>  <footer>
    &copy; 2025 Ashok Enterprises | All rights reserved.
  </footer>
</body>
</html># A
