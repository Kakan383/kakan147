# kakan147
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Shree Mobile Care | Mobile Repair Center</title>u

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            background: #050505;
            color: white;
        }

        /* NAVBAR */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            padding: 18px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: rgba(0,0,0,0.85);
            backdrop-filter: blur(10px);
            z-index: 999;
            border-bottom: 1px solid #00ff88;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #00ff88;
            text-shadow: 0 0 15px #00ff88;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 25px;
            transition: .3s;
        }

        nav a:hover {
            color: #00ff88;
        }

        /* HERO */
        .hero {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 100px 20px 50px;
            background:
                radial-gradient(circle at center, #07351f 0%, #050505 55%);
        }

        .hero h1 {
            font-size: clamp(42px, 8vw, 90px);
            color: #00ff88;
            text-shadow:
                0 0 10px #00ff88,
                0 0 30px #00ff88;
            animation: glow 2s infinite alternate;
        }

        .hero h2 {
            margin-top: 15px;
            font-size: 25px;
        }

        .hero p {
            margin: 20px auto;
            max-width: 650px;
            color: #bbb;
            line-height: 1.7;
        }

        .btn {
            display: inline-block;
            margin: 10px;
            padding: 14px 28px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            transition: .3s;
        }

        .btn-green {
            background: #00ff88;
            color: black;
            box-shadow: 0 0 20px #00ff88;
        }

        .btn-green:hover {
            transform: scale(1.08);
        }

        .btn-outline {
            border: 1px solid #00ff88;
            color: #00ff88;
        }

        .btn-outline:hover {
            background: #00ff88;
            color: black;
        }

        /* SECTIONS */
        section {
            padding: 90px 8%;
        }

        .title {
            text-align: center;
            margin-bottom: 50px;
        }

        .title h2 {
            font-size: 40px;
            color: #00ff88;
            text-shadow: 0 0 15px #00ff88;
        }

        .title p {
            color: #999;
            margin-top: 10px;
        }

        /* SERVICES */
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 25px;
        }

        .card {
            background: #0c0c0c;
            border: 1px solid #164b34;
            padding: 30px;
            text-align: center;
            border-radius: 15px;
            transition: .4s;
        }

        .card:hover {
            transform: translateY(-10px);
            border-color: #00ff88;
            box-shadow: 0 0 25px rgba(0,255,136,.3);
        }

        .icon {
            font-size: 50px;
            margin-bottom: 20px;
        }

        .card h3 {
            color: #00ff88;
            margin-bottom: 12px;
        }

        .card p {
            color: #999;
            line-height: 1.6;
        }

        /* ABOUT */
        .about {
            max-width: 900px;
            margin: auto;
            text-align: center;
            color: #bbb;
            line-height: 1.9;
            font-size: 17px;
        }

        /* CONTACT */
        .contact-box {
            max-width: 700px;
            margin: auto;
            text-align: center;
            background: #0c0c0c;
            padding: 40px;
            border-radius: 20px;
            border: 1px solid #164b34;
        }

        .contact-box p {
            margin: 15px;
            color: #ccc;
        }

        /* FOOTER */
        footer {
            text-align: center;
            padding: 30px;
            border-top: 1px solid #164b34;
            color: #777;
        }

        footer span {
            color: #00ff88;
        }

        @keyframes glow {
            from {
                text-shadow: 0 0 10px #00ff88;
            }
            to {
                text-shadow:
                    0 0 20px #00ff88,
                    0 0 40px #00ff88;
            }
        }

        @media(max-width: 700px) {
            nav {
                padding: 15px 5%;
            }

            nav .links {
                display: none;
            }

            section {
                padding: 70px 5%;
            }

            .hero h2 {
                font-size: 20px;
            }
        }
    </style>
</head>

<body>

    <!-- NAVBAR -->
    <nav>
        <div class="logo">SHREE MOBILE</div>

        <div class="links">
            <a href="#home">Home</a>
            <a href="#services">Services</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>


    <!-- HERO -->
    <section class="hero" id="home">

        <div>
            <h1>SHREE MOBILE CARE</h1>

            <h2>⚡ Professional Mobile Repair Center ⚡</h2>

            <p>
                আপনার মোবাইলের যেকোনো সমস্যা নিয়ে চিন্তা করবেন না।
                Display, Battery, Charging, Software এবং Hardware সমস্যার
                জন্য আমাদের অভিজ্ঞ টেকনিশিয়ানদের সাথে যোগাযোগ করুন।
            </p>

            <a href="#services" class="btn btn-green">
                Explore Services
            </a>

            <a href="#contact" class="btn btn-outline">
                Contact Us
            </a>
        </div>

    </section>


    <!-- SERVICES -->
    <section id="services">

        <div class="title">
            <h2>Our Services</h2>
            <p>Fast • Professional • Reliable</p>
        </div>

        <div class="services">

            <div class="card">
                <div class="icon">📱</div>
                <h3>Display Repair</h3>
                <p>
                    Broken বা damaged display replacement
                    এবং touch সমস্যা সমাধান।
                </p>
            </div>

            <div class="card">
                <div class="icon">🔋</div>
                <h3>Battery Service</h3>
                <p>
                    Battery backup কমে গেলে নতুন battery
                    replacement service।
                </p>
            </div>

            <div class="card">
                <div class="icon">⚡</div>
                <h3>Charging Repair</h3>
                <p>
                    Charging port, charging IC এবং charging
                    related সমস্যা সমাধান।
                </p>
            </div>

            <div class="card">
                <div class="icon">💻</div>
                <h3>Software Service</h3>
                <p>
                    Software update, reset, hang, bootloop
                    এবং software সমস্যা সমাধান।
                </p>
            </div>

            <div class="card">
                <div class="icon">🔧</div>
                <h3>Hardware Repair</h3>
                <p>
                    Motherboard এবং অন্যান্য hardware
                    সমস্যার professional repair।
                </p>
            </div>

            <div class="card">
                <div class="icon">🛡️</div>
                <h3>Phone Protection</h3>
                <p>
                    আপনার প্রিয় ফোনের জন্য বিভিন্ন protection
                    ও maintenance service।
                </p>
            </div>

        </div>

    </section>


    <!-- ABOUT -->
    <section id="about">

        <div class="title">
            <h2>About Us</h2>
        </div>

        <div class="about">

            <p>
                <strong style="color:#00ff88;">
                    Shree Mobile Care
                </strong>
                একটি professional mobile servicing center।
                আমরা বিভিন্ন brand-এর smartphone-এর software
                এবং hardware সমস্যার সমাধান করার চেষ্টা করি।
            </p>

            <br>

            <p>
                আমাদের লক্ষ্য হলো দ্রুত, যত্নসহকারে এবং
                customer-friendly service প্রদান করা।
                আপনার ফোন আমাদের কাছে নিরাপদে repair করার
                জন্য জমা দিতে পারেন।
            </p>

        </div>

    </section>


    <!-- CONTACT -->
    <section id="contact">

        <div class="title">
            <h2>Contact Us</h2>
            <p>আপনার মোবাইলের সমস্যা নিয়ে যোগাযোগ করুন</p>
        </div>

        <div class="contact-box">

            <p>📞 <strong>Phone:</strong> 01XXXXXXXXX</p>

            <p>💬 <strong>WhatsApp:</strong> 01XXXXXXXXX</p>

            <p>📍 <strong>Address:</strong> Your Shop Address</p>

            <a
                href="https://wa.me/8801XXXXXXXXX"
                class="btn btn-green"
                target="_blank">
                WhatsApp Now
            </a>

        </div>

    </section>


    <!-- FOOTER -->
    <footer>

        © 2026
        <span>Shree Mobile Care</span>
        — All Rights Reserved.

    </footer>

</body>
</html>