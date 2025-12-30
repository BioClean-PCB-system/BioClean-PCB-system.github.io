<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BioClean PCB System</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap');
        body { font-family: 'Montserrat', sans-serif; margin: 0; padding: 0; background-color: #f0f8ff; }
        header { background-color: #0077b6; color: white; padding: 30px 20px; text-align: center; }
        nav { background-color: #023e8a; display: flex; justify-content: center; padding: 10px; }
        nav button { color: white; margin: 0 10px; padding: 10px 15px; border: none; border-radius: 5px; cursor: pointer; font-weight: bold; background-color: #0077b6; transition: background 0.3s; }
        nav button:hover { background-color: #0096c7; }
        section { display: none; padding: 20px; }
        section.active { display: block; }
        h2 { color: #0077b6; font-weight: 700; font-size: 1.8em; margin-bottom: 15px; }
        .features { display: flex; gap: 20px; flex-wrap: wrap; margin-top: 15px; }
        .feature { background-color: #caf0f8; padding: 15px; border-radius: 10px; flex: 1; min-width: 250px; }
        .dashboard { background-color: #90e0ef; padding: 15px; border-radius: 10px; margin-top: 20px; }
        footer { background-color: #0077b6; color: white; text-align: center; padding: 15px; margin-top: 30px; }
    </style>
    <script>
        function showTab(tabId) {
            const sections = document.querySelectorAll('section');
            sections.forEach(section => section.classList.remove('active'));
            document.getElementById(tabId).classList.add('active');
        }
        window.onload = function() {
            showTab('about'); // About tab is the starting point
        }
    </script>
</head>
<body>

<header>
    <h1>BioClean PCB System</h1>
    <p>Innovative PCB Cleanup for a Safer Passaic River</p>
</header>

<nav>
    <button onclick="showTab('about')">About</button>
    <button onclick="showTab('how-it-works')">How It Works</button>
    <button onclick="showTab('impact')">Impact</button>
    <button onclick="showTab('research')">Research</button>
    <button onclick="showTab('future')">Future</button>
    <button onclick="showTab('contact')">Contact</button>
</nav>

<section id="about">
    <h2>About</h2>
    <p>The BioClean PCB System is an in-situ solution to remove PCBs from contaminated sediment and soil using natural microbes, enzymes, and reactive caps with real-time monitoring.</p>
</section>

<section id="how-it-works">
    <h2>How It Works</h2>
    <div class="features">
        <div class="feature">
            <h3>Microbes & Enzymes</h3>
            <p>Specialized bacteria and enzymes break down PCBs into harmless compounds.</p>
        </div>
        <div class="feature">
            <h3>Reactive Caps</h3>
            <p>Activated carbon and biochar layers trap remaining PCBs to prevent contamination.</p>
        </div>
        <div class="feature">
            <h3>Real-Time Monitoring</h3>
            <p>Sensors track PCB levels, oxygen, and pH for optimized cleanup.</p>
        </div>
    </div>
</section>

<section id="impact">
    <h2>Impact & Benefits</h2>
    <ul>
        <li>Reduces PCB levels efficiently and safely.</li>
        <li>Restores river ecosystems for wildlife.</li>
        <li>Protects public health and supports recreation.</li>
        <li>Boosts tourism and local property values.</li>
        <li>Creates cleanup-related jobs in the community.</li>
    </ul>
    <div class="dashboard">
        <h3>Live Monitoring Dashboard</h3>
        <p>Current PCB levels: <strong>0.12 ppm</strong></p>
        <p>Microbial activity: <strong>High</strong></p>
        <p>Oxygen levels: <strong>7.8 mg/L</strong></p>
    </div>
</section>

<section id="research">
    <h2>Research & Evidence</h2>
    <p>Scientific studies show microbial and enzymatic PCB degradation reduces contamination by up to 90%. Ongoing research monitors ecological recovery and community health improvements.</p>
</section>

<section id="future">
    <h2>Future Plans</h2>
    <p>The system aims to restore the Passaic River fully, support safe recreation, expand sensor networks, and provide educational outreach for local communities.</p>
</section>

<section id="contact">
    <h2>Contact</h2>
    <p>Email: info@biocleanpcb.org</p>
    <p>Phone: (555) 123-4567</p>
    <p>Follow us on social media: Facebook | Instagram</p>
</section>

<footer>
    &copy; 2025 BioClean PCB System. All rights reserved.
</footer>

</body>
</html>
