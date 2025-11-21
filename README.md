# social-media-marketing
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Social Media Marketing Agency</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f8f9fa; }
        header { background-color: #007bff; color: white; padding: 20px; text-align: center; }
        nav { background-color: #0056b3; padding: 10px; text-align: center; }
        nav a { color: white; text-decoration: none; margin: 0 15px; font-weight: bold; }
        nav a:hover { text-decoration: underline; }
        section { padding: 20px; max-width: 960px; margin: auto; }
        h2 { color: #007bff; border-bottom: 2px solid #007bff; padding-bottom: 5px; }
        .service, .work-item { margin-bottom: 15px; }
        .pricing-table { width: 100%; border-collapse: collapse; margin: 20px 0; }
        .pricing-table th, .pricing-table td { border: 1px solid #ddd; padding: 10px; text-align: center; }
        .pricing-table th { background-color: #007bff; color: white; }
        footer { background-color: #343a40; color: white; text-align: center; padding: 15px; margin-top: 40px; }
        form { max-width: 400px; margin: auto; display: flex; flex-direction: column; }
        form input, form textarea { margin-bottom: 10px; padding: 10px; border: 1px solid #ccc; border-radius: 4px; }
        form button { background-color: #007bff; color: white; border: none; padding: 10px; border-radius: 4px; cursor: pointer; }
        form button:hover { background-color: #0056b3; }
    </style>
</head>
<body>
    <header>
        <h1>My Social Media Marketing Agency</h1>
        <p>Driving Growth through Strategic Social Media Solutions</p>
    </header>
    <nav>
        <a href="#previous-work">Previous Work</a>
        <a href="#services">Services</a>
        <a href="#pricing">Pricing</a>
        <a href="#contact">Contact Us</a>
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
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 My Social Media Marketing Agency. All rights reserved.</p>
    </footer>
</body>
</html>
