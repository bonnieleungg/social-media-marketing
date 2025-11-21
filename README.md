# social-media-marketing
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Creative Social Media Marketing Agency</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap');

  /* Reset & Base */
  * {
    box-sizing: border-box;
  }
  body {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    background: linear-gradient(135deg, #667eea, #764ba2);
    color: #fff;
    line-height: 1.6;
  }

  /* Header */
  header {
    background: rgba(0, 0, 0, 0.5);
    padding: 3rem 1rem;
    text-align: center;
    backdrop-filter: blur(6px);
  }
  header h1 {
    font-weight: 600;
    font-size: 3rem;
    margin-bottom: 0.3rem;
    letter-spacing: 2px;
    text-transform: uppercase;
  }
  header p {
    font-weight: 300;
    font-size: 1.3rem;
    letter-spacing: 1px;
    font-style: italic;
  }

  /* Navigation */
  nav {
    background: #2a1f4a;
    display: flex;
    justify-content: center;
    padding: 1rem 0;
    box-shadow: 0 4px 6px rgba(0,0,0,0.3);
  }
  nav a {
    color: #d3d0f7;
    margin: 0 20px;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 1.5px;
    text-decoration: none;
    padding: 0.5rem 1rem;
    border-radius: 25px;
    transition: background-color 0.3s ease, color 0.3s ease;
  }
  nav a:hover,
  nav a:focus {
    background-color: #967bce;
    color: #fff;
  }

  /* Content Container */
  section {
    max-width: 900px;
    background: rgba(255, 255, 255, 0.1);
    margin: 3rem auto;
    padding: 2rem 3rem;
    border-radius: 15px;
    box-shadow: 0 8px 30px rgba(100, 100, 150, 0.4);
    backdrop-filter: blur(10px);
  }
  section h2 {
    font-size: 2rem;
    border-left: 8px solid #967bce;
    padding-left: 0.7rem;
    margin-bottom: 1rem;
  }

  /* Previous Work Cards */
  .work-item {
    background: #8669b2;
    border-radius: 12px;
    padding: 1rem 1.5rem;
    margin-bottom: 1.5rem;
    box-shadow: 0 2px 15px rgba(0, 0, 0, 0.3);
    transition: transform 0.3s ease;
  }
  .work-item:hover {
    transform: translateY(-8px);
    box-shadow: 0 8px 25px rgba(0, 0, 0, 0.5);
  }
  .work-item h3 {
    font-weight: 600;
    margin-bottom: 0.5rem;
  }
  .work-item p {
    font-weight: 300;
    font-size: 1.1rem;
  }

  /* Services grid */
  #services {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1.5rem;
  }
  .service {
    background: #7c63b8;
    padding: 1.5rem 2rem;
    border-radius: 15px;
    box-shadow: 0 3px 18px rgba(0,0,0,0.3);
    transition: background-color 0.3s ease;
  }
  .service:hover {
    background: #967bce;
  }
  .service h3 {
    margin-bottom: 0.7rem;
    font-weight: 600;
  }
  .service p {
    font-weight: 300;
  }

  /* Pricing Table */
  .pricing-table {
    width: 100%;
    border-collapse: separate;
    border-spacing: 0 15px;
  }
  .pricing-table th,
  .pricing-table td {
    text-align: center;
    padding: 1rem 1.5rem;
    font-weight: 600;
    border-radius: 12px;
  }
  .pricing-table th {
    background: #503c7b;
    color: #e0d9ff;
  }
  .pricing-table td {
    background: #7661b2;
    color: #f0e9ff;
    transition: background-color 0.3s ease;
  }
  tr:hover td {
    background-color: #a89de5;
    color: #2a0a66;
  }

  /* Contact Form */
  form {
    display: flex;
    flex-direction: column;
    max-width: 450px;
    margin: auto;
  }
  input, textarea {
    background: rgba(255, 255, 255, 0.15);
    border: none;
    border-radius: 10px;
    padding: 12px 18px;
    margin-bottom: 1rem;
    color: #fff;
    font-weight: 300;
    font-size: 1rem;
    transition: background 0.3s ease;
  }
  input::placeholder,
  textarea::placeholder {
    color: #e5dcff;
    font-style: italic;
  }
  input:focus, textarea:focus {
    outline: none;
    background: rgba(255, 255, 255, 0.35);
  }
  button {
    background: #967bce;
    padding: 14px;
    font-weight: 600;
    border: none;
    border-radius: 25px;
    cursor: pointer;
    transition: background-color 0.4s ease;
    font-size: 1.1rem;
    color: #fff;
  }
  button:hover {
    background: #bfaaff;
  }

  /* Footer */
  footer {
    text-align: center;
    padding: 2rem 1rem;
    background: #1c1432;
    font-size: 0.9rem;
    letter-spacing: 1.5px;
    color: #a494d3;
  }

  /* Responsive */
  @media (max-width: 600px) {
    header h1 {
      font-size: 2rem;
    }
    nav {
      flex-wrap: wrap;
    }
    nav a {
      margin: 8px 12px;
    }
  }
</style>
</head>
<body>
<header>
  <h1>Creative Social Media Marketing</h1>
  <p>Driving Growth with Innovative Campaigns & Designs</p>
</header>
<nav>
  <a href="#previous-work">Previous Work</a>
  <a href="#services">Services</a>
  <a href="#pricing">Pricing</a>
  <a href="#contact">Contact</a>
</nav>

<section id="previous-work">
  <h2>Previous Work</h2>
  <div class="work-item">
    <h3>Red Bull Social Campaign</h3>
    <p>Executed a multi-platform campaign resulting in a 40% increase in engagement.</p>
  </div>
  <div class="work-item">
    <h3>Ocean Park Digital Strategy</h3>
    <p>Developed targeted content that boosted social followers by 25%.</p>
  </div>
  <div class="work-item">
    <h3>Startup Launch Marketing</h3>
    <p>Launched social presence for a fintech startup reaching 50K followers in 3 months.</p>
  </div>
</section>

<section id="services">
  <h2>Our Services</h2>
  <div class="service">
    <h3>Social Media Strategy</h3>
    <p>Customized strategies to grow your brand’s social presence.</p>
  </div>
  <div class="service">
    <h3>Content Creation</h3>
    <p>High-quality posts, videos, and graphics tailored for your audience.</p>
  </div>
  <div class="service">
    <h3>Social Media Management</h3>
    <p>End-to-end management of your social profiles with consistent engagement.</p>
  </div>
  <div class="service">
    <h3>Analytics & Reporting</h3>
    <p>Detailed performance reports to optimize your social media campaigns.</p>
  </div>
</section>

<section id="pricing">
  <h2>Pricing</h2>
  <table class="pricing-table">
    <tr>
      <th>Package</th>
      <th>Services Included</th>
      <th>Price (HKD)</th>
    </tr>
    <tr>
      <td>Basic</td>
      <td>Social Media Strategy + Monthly Reporting</td>
      <td>5,000</td>
    </tr>
    <tr>
      <td>Standard</td>
      <td>Strategy + Content Creation + Management</td>
      <td>12,000</td>
    </tr>
    <tr>
      <td>Premium</td>
      <td>All Services + Dedicated Account Manager</td>
      <td>20,000</td>
    </tr>
  </table>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <form action="mailto:info@mymarketingagency.com" method="post" enctype="text/plain">
    <input type="text" name="name" placeholder="Your Name" required />
    <input type="email" name="email" placeholder="Your Email" required />
    <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
    <button type="submit">Send Message</button>
  </form>
</section>

<footer>
  &copy; 2025 Creative Social Media Marketing Agency. All rights reserved.
</footer>
</body>
</html>
