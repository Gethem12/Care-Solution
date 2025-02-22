<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Care Solutions | Employee Care Coordination</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #F7F9FC;
            color: #1E4D92;
        }
        header {
            background-color: #1E4D92;
            padding: 15px 20px;
            color: white;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo img {
            height: 50px;
        }
        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }
        nav ul li {
            display: inline;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        #hero {
            text-align: center;
            padding: 50px;
            background: #28A9E0;
            color: white;
            animation: fadeIn 2s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        section {
            padding: 40px;
            max-width: 1000px;
            margin: auto;
        }
        button {
            background-color: #F4A261;
            border: none;
            padding: 10px 20px;
            color: white;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
            transition: transform 0.3s;
        }
        button:hover {
            transform: scale(1.1);
        }
        form {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        input, textarea {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            background: #1E4D92;
            color: white;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
    <script>
        function showAlert() {
            alert('Thank you for your interest! We will get back to you soon.');
        }
    </script>
</head>
<body>
    <header>
        <div class="logo">
            <img src="/mnt/data/veritey-healthcare-horizontal-logo-medium-blue-cmyk-900px-w-300ppi.jpg" alt="Veritey Healthcare Logo">
        </div>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#employers">For Employers</a></li>
                <li><a href="#employees">For Employees</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="hero">
        <h1>Empowering Businesses to Support Caregivers</h1>
        <p>Reducing absenteeism, increasing productivity, and improving employee well-being.</p>
        <button onclick="showAlert()">Request a Demo</button>
    </section>
    
    <section id="about">
        <h2>About Us</h2>
        <p>Care Solutions is a B2B wellness and care coordination service designed to integrate home health navigation, mental health support, and elder care coordination into Employee Assistance Programs (EAPs).</p>
    </section>
    
    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>🏡 Home Health Navigation</li>
            <li>🧠 Mental Health Support</li>
            <li>👵🏽 Elder Care Coordination</li>
            <li>📊 Technology-Driven Solutions</li>
        </ul>
    </section>
    
    <section id="employers">
        <h2>For Employers</h2>
        <p>Why partner with Care Solutions?</p>
        <ul>
            <li>Reduce absenteeism by 30%</li>
            <li>Increase employee retention by 25%</li>
            <li>Improve productivity by 20%</li>
            <li>Get a 3x ROI through cost savings</li>
        </ul>
        <button onclick="showAlert()">Get a Free Business Assessment</button>
    </section>
    
    <section id="employees">
        <h2>For Employees</h2>
        <p>Access personalized caregiving support through your EAP portal.</p>
        <button onclick="showAlert()">Access Your Portal</button>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <form onsubmit="showAlert(); return false;">
            <label>Name</label>
            <input type="text" name="name" required>
            <label>Email</label>
            <input type="email" name="email" required>
            <label>Message</label>
            <textarea name="message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>
    
    <footer>
        <p>&copy; 2025 Care Solutions. All Rights Reserved.</p>
    </footer>
</body>
</html>
