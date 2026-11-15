# Magic-Beautician

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Amma's Beauty Studio | Home Beauty Services</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    font-family: 'Segoe UI', sans-serif;
    color: #49333b;
    background: #fff9fa;
}

header {
    background: white;
    padding: 18px 7%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: sticky;
    top: 0;
    z-index: 10;
    box-shadow: 0 3px 15px #00000010;
}

.logo {
    color: #b34e75;
    font-size: 23px;
    font-weight: bold;
}

nav a {
    text-decoration: none;
    color: #573b47;
    margin-left: 20px;
    font-weight: 600;
}

nav a:hover {
    color: #c34e7d;
}

.hero {
    min-height: 580px;
    padding: 80px 8%;
    display: flex;
    align-items: center;
    background:
    linear-gradient(90deg, #fff1f4 5%, #fff1f4dd 48%, #fff1f400 100%),
    url('https://images.unsplash.com/photo-1487412947147-5cebf100ffc2?w=1400')
    center/cover;
}

.hero-content {
    max-width: 550px;
}

.tag {
    color: #b34e75;
    letter-spacing: 3px;
    font-size: 13px;
    font-weight: bold;
}

.hero h1 {
    font-size: clamp(40px, 6vw, 65px);
    margin: 20px 0;
    color: #71394f;
    line-height: 1.1;
}

.hero p {
    font-size: 18px;
    line-height: 1.8;
    margin-bottom: 30px;
}

.btn {
    display: inline-block;
    background: #b94f79;
    color: white;
    padding: 15px 28px;
    border-radius: 30px;
    text-decoration: none;
    font-weight: bold;
    border: none;
    cursor: pointer;
}

.btn:hover {
    background: #883453;
}

section {
    padding: 75px 8%;
}

.section-title {
    text-align: center;
    margin-bottom: 40px;
}

.section-title h2 {
    color: #9f4568;
    font-size: 36px;
    margin-bottom: 12px;
}

.section-title p {
    color: #846d76;
}

.services {
    background: #fff;
}

.service-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(210px, 1fr));
    gap: 22px;
}

.service-card {
    background: #fff8fa;
    padding: 30px 20px;
    text-align: center;
    border-radius: 18px;
    border: 1px solid #f3dce5;
    transition: 0.3s;
}

.service-card:hover {
    transform: translateY(-7px);
    box-shadow: 0 10px 25px #a94c7018;
}

.service-card .emoji {
    font-size: 40px;
    margin-bottom: 15px;
}

.service-card h3 {
    color: #984765;
    margin-bottom: 10px;
}

.service-card p {
    color: #806d75;
    line-height: 1.6;
    font-size: 14px;
}

.about {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 45px;
    align-items: center;
    background: #fff0f4;
}

.about img {
    width: 100%;
    height: 390px;
    object-fit: cover;
    border-radius: 25px;
}

.about h2 {
    font-size: 36px;
    color: #9f4568;
    margin-bottom: 20px;
}

.about p {
    line-height: 1.9;
    margin-bottom: 15px;
}

.booking {
    background: #fff;
}

.booking-container {
    max-width: 650px;
    margin: auto;
    padding: 35px;
    background: #fff7f9;
    border-radius: 20px;
    border: 1px solid #f1dce4;
}

.booking-container input,
.booking-container select,
.booking-container textarea {
    width: 100%;
    padding: 14px;
    margin: 10px 0 18px;
    border: 1px solid #e6cbd5;
    border-radius: 10px;
    font-size: 15px;
    background: white;
}

.booking-container label {
    font-weight: 600;
    color: #754257;
}

.booking-container button {
    width: 100%;
    font-size: 16px;
}

.contact {
    text-align: center;
    background: #fce9ef;
}

.contact h2 {
    color: #984765;
    font-size: 35px;
    margin-bottom: 20px;
}

.contact p {
    line-height: 2;
    margin-bottom: 15px;
}

footer {
    background: #71394f;
    color: white;
    text-align: center;
    padding: 25px;
    line-height: 1.8;
}

.whatsapp {
    position: fixed;
    right: 20px;
    bottom: 20px;
    background: #25D366;
    color: white;
    padding: 15px 20px;
    border-radius: 40px;
    text-decoration: none;
    font-weight: bold;
    z-index: 20;
    box-shadow: 0 4px 15px #0003;
}

@media(max-width:750px) {
    header {
        flex-direction: column;
        gap: 15px;
    }

    nav a {
        margin: 0 7px;
        font-size: 13px;
    }

    .hero {
        background-position: 60% center;
        min-height: 500px;
    }

    .about {
        grid-template-columns: 1fr;
    }

    .about img {
        height: 280px;
    }

    section {
        padding: 55px 6%;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">🌸 Amma's Beauty Studio</div>
    <nav>
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#about">About</a>
        <a href="#booking">Booking</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<!-- HOME -->
<div class="hero" id="home">
    <div class="hero-content">
        <div class="tag">BEAUTY • CARE • CONFIDENCE</div>
        <h1>Feel Beautiful.<br>Feel Confident.</h1>
        <p>
            Professional beauty care at your doorstep.
            Enjoy beauty services in the comfort of your home.
        </p>
        <a class="btn" href="#booking">Book Your Appointment</a>
    </div>
</div>

<!-- SERVICES -->
<section class="services" id="services">
    <div class="section-title">
        <h2>Our Beauty Services</h2>
        <p>Beauty and personal care services at your convenience 🌷</p>
    </div>

    <div class="service-grid">

        <div class="service-card">
            <div class="emoji">✨</div>
            <h3>Facial</h3>
            <p>Relaxing facial and skin care treatments.</p>
        </div>

        <div class="service-card">
            <div class="emoji">🌸</div>
            <h3>Threading</h3>
            <p>Eyebrow shaping and facial threading.</p>
        </div>

        <div class="service-card">
            <div class="emoji">🧴</div>
            <h3>Waxing</h3>
            <p>Personal grooming and waxing services.</p>
        </div>

        <div class="service-card">
            <div class="emoji">💆‍♀️</div>
            <h3>Hair Care</h3>
            <p>Hair styling and hair care services.</p>
        </div>

        <div class="service-card">
            <div class="emoji">💅</div>
            <h3>Manicure</h3>
            <p>Hand and nail care treatments.</p>
        </div>

        <div class="service-card">
            <div class="emoji">🦶</div>
            <h3>Pedicure</h3>
            <p>Foot care and relaxation treatments.</p>
        </div>

        <div class="service-card">
            <div class="emoji">💄</div>
            <h3>Party Makeup</h3>
            <p>Beautiful makeup for special occasions.</p>
        </div>

        <div class="service-card">
            <div class="emoji">👰</div>
            <h3>Bridal Makeup</h3>
            <p>Bridal beauty and makeup services.</p>
        </div>

        <div class="service-card">
            <div class="emoji">🌺</div>
            <h3>Mehendi</h3>
            <p>Beautiful mehendi designs for occasions.</p>
        </div>

        <div class="service-card">
            <div class="emoji">🧖‍♀️</div>
            <h3>Cleanup</h3>
            <p>Refreshing skin cleansing and care.</p>
        </div>

    </div>
</section>

<!-- ABOUT -->
<section class="about" id="about">
    <div>
        <img
        src="https://images.unsplash.com/photo-1522337360788-8b13dee7a37e?w=900"
        alt="Beauty salon and hair care">
    </div>

    <div>
        <h2>Beauty Care At Your Home</h2>
        <p>
            Welcome to Amma's Beauty Studio!
            We provide beauty and personal care services
            with attention, care and comfort.
        </p>
        <p>
            No need to travel to a salon.
            Book your preferred service and enjoy
            beauty care at your doorstep.
        </p>
        <p>🌸 Personal care</p>
        <p>🌸 Convenient home appointments</p>
        <p>🌸 Friendly beauty service</p>
    </div>
</section>

<!-- BOOKING -->
<section class="booking" id="booking">
    <div class="section-title">
        <h2>Book An Appointment</h2>
        <p>Fill in your details. Your booking request will open in WhatsApp.</p>
    </div>

    <div class="booking-container">

        <form id="bookingForm">

            <label>Your Name</label>
            <input type="text" id="name"
            placeholder="Enter your name" required>

            <label>Phone Number</label>
            <input type="tel" id="phone"
            placeholder="Your contact number" required>

            <label>Select Service</label>
            <select id="service" required>
                <option value="">Choose a service</option>
                <option>Facial</option>
                <option>Threading</option>
                <option>Waxing</option>
                <option>Hair Care</option>
                <option>Manicure</option>
                <option>Pedicure</option>
                <option>Party Makeup</option>
                <option>Bridal Makeup</option>
                <option>Mehendi</option>
                <option>Cleanup</option>
            </select>

            <label>Preferred Date</label>
            <input type="date" id="date" required>

            <label>Home Address / Area</label>
            <input type="text" id="address"
            placeholder="Enter your location" required>

            <label>Additional Details</label>
            <textarea id="message" rows="4"
            placeholder="Any special requirements?"></textarea>

            <button class="btn" type="submit">
                Book Through WhatsApp
            </button>

        </form>
    </div>
</section>

<!-- CONTACT -->
<section class="contact" id="contact">
    <h2>Get In Touch 🌷</h2>

    <p>
        Have questions or want to book a beauty service?
        Contact us today!
    </p>

    <p>📍 Location: Kengeri, Bengaluru</p>

    <p>📞 Phone: 9353990947</p>

    <a class="btn"
    href="https://wa.me/919353990947?text=Hello%2C%20I%20want%20to%20book%20a%20beauty%20service."
    target="_blank">
        Chat With Us on WhatsApp
    </a>
</section>

<footer>
    <p>🌸 Amma's Beauty Studio</p>
    <p>Beauty Care At Your Doorstep</p>
    <p>© 2026 Amma's Beauty Studio. All Rights Reserved.</p>
</footer>

<a class="whatsapp"
href="https://wa.me/919353990947"
target="_blank">
    WhatsApp 💬
</a>

<script>
document.getElementById("bookingForm")
.addEventListener("submit", function(event) {

    event.preventDefault();

    const name = document.getElementById("name").value;
    const phone = document.getElementById("phone").value;
    const service = document.getElementById("service").value;
    const date = document.getElementById("date").value;
    const address = document.getElementById("address").value;
    const message = document.getElementById("message").value;

    const text =
        "Hello! I want to book a beauty appointment.%0A%0A" +
        "Name: " + encodeURIComponent(name) + "%0A" +
        "Phone: " + encodeURIComponent(phone) + "%0A" +
        "Service: " + encodeURIComponent(service) + "%0A" +
        "Preferred Date: " + encodeURIComponent(date) + "%0A" +
        "Address: " + encodeURIComponent(address) + "%0A" +
        "Additional Details: " + encodeURIComponent(message);

    window.open(
        "https://wa.me/919353990947?text=" + text,
        "_blank"
    );
});
</script>

</body>
</html
