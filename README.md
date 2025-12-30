# BioClean-PCB-system.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BioClean PCB System</title>
    <style>
        body { font-family: 'Roboto', sans-serif; margin: 0; padding: 0; background-color: #f0f8ff; }
        header { background-color: #0077b6; color: white; padding: 20px; text-align: center; }
        nav { background-color: #023e8a; padding: 10px; }
        nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
        section { padding: 20px; }
        h2 { color: #0077b6; }
        .features { display: flex; gap: 20px; flex-wrap: wrap; }
        .feature { background-color: #caf0f8; padding: 15px; border-radius: 10px; flex: 1; min-width: 250px; }
        footer { background-color: #0077b6; color: white; text-align: center; padding: 15px; }
        .dashboard { background-color: #90e0ef; padding: 15px; border-radius: 10px; margin-top: 20px; }
        .tabs { display: flex; gap: 10px; margin-top: 10px; }
        .tab { background-color: #48cae4; padding: 10px 15px; border-radius: 5px; cursor: pointer; color: white; font-weight: bold; }
        .tab-content { display: none; margin-top: 20px; background-color: #ade8f4; padding: 15px; border-radius: 10px; }
        .active { display: block; }
    </style>
    <script>
        function openTab(tabId) {
            const contents = document.querySelectorAll('.tab-content');
            contents.forEach(c => c.classList.remove('active'));
            document.getElementById(tabId).classList.add('active');
        }
    </script>
    <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
</head>
<body>

<header>
    <h1>BioClean PCB System</h1>
    <p>Cleaning the Passaic River Safely and Effectively</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#how-it-works">How It Works</a>
    <a href="#impact">Impact</a>
    <a href="#research">Research</a>
    <a href="#future">Future</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About BioClean PCB System</h2>
    <p>The BioClean PCB System is an innovative, in-situ solution designed to remove PCBs from contaminated river sediment and soil using natural microbes, enzymes, and reactive caps while monitoring cleanup progress in real time.</p>
</section>

<section id="how-it-works">
    <h2>How It Works</h2>
    <div class="features">
        <div class="feature">
            <h3>Microbes & Enzymes</h3>
            <p>Specialized bacteria and enzymes chemically break down PCBs into harmless compounds.</p>
        </div>
        <div class="feature">
            <h3>Reactive Caps</h3>
            <p>Activated carbon and biochar layers trap remaining PCBs to prevent further contamination.</p>
        </div>
        <div class="feature">
            <h3>Real-Time Monitoring</h3>
            <p>Sensors track PCB levels, oxygen, and pH, allowing engineers to optimize the cleanup process.</p>
        </div>
    </div>
</section>

<section id="impact">
    <h2>Impact & Benefits</h2>
    <ul>
        <li>Reduces PCB levels safely and efficiently.</li>
        <li>Restores river ecosystems for fish, plants, and wildlife.</li>
        <li>Protects public health and supports safe recreation.</li>
        <li>Boosts local tourism and property values.</li>
        <li>Supports local economy by creating cleanup-related jobs.</li>
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
    <p>The BioClean PCB System is backed by scientific studies showing microbial and enzymatic PCB degradation reduces contamination in sediments by up to 90%. Ongoing research monitors long-term ecological recovery and community health improvements.</p>
</section>

<section id="future">
    <h2>Future Plans</h2>
    <p>The system aims to restore the Passaic River ecosystem fully, support safe recreation, and provide long-term environmental monitoring. Plans include expanding sensor networks, adaptive management strategies, and educational outreach programs for local communities.</p>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@biocleanpcb.org</p>
    <p>Phone: (555) 123-4567</p>
    <p>Follow us on social media for updates: Facebook | Instagram</p>
</section>

<footer>
    &copy; 2025 BioClean PCB System. All rights reserved.
</footer>

</body>
</html>
