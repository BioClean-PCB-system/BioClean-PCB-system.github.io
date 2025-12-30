
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
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
    <p>The BioClean PCB System is an in-situ solution to remove PCBs from contaminated sediment and soil using natural microbes, enzymes, and reactive caps with real-time monitoring. It works by using anaerobic and aerobic bacteria to break down PCBs into non-toxic compounds, while the reactive caps prevent the spread of remaining contaminants. Continuous monitoring allows for timely adjustments, ensuring maximum degradation efficiency and minimizing environmental impact.

 </p>
 <h2>
     Problem
 </h2>
 <p>
     In many communities there is a growing problem in the pollution in an area. Specifically polychlorinated biphenyls (PCBs) are highly stable, man-made chemicals that resist natural degradation, allowing them to persist in soil, sediment, and water for decades. They bioaccumulate in the food chain, concentrating in fish, wildlife, and humans, and can cause serious health problems such as cancer, liver damage, immune system suppression, endocrine disruption, and developmental delays in children exposed during critical growth periods.
 </p>
</section>

<section id="how-it-works">
    <h2>How It Works</h2>
    <div class="features">
        <div class="feature">
            <h3>Microbes & Enzymes</h3>
            <p>Specialized bacteria and enzymes break down PCBs into harmless compounds. Anaerobic bacteria, such as Dehalococcoides and other organohalide-respiring microbes, begin PCB degradation by removing chlorine atoms in a process called dechlorination, which makes the molecules less resistant to breakdown. After this step, aerobic bacteria including Burkholderia, Pseudomonas, Rhodococcus, Alcaligenes, and Comamonas use enzymes like biphenyl dioxygenase to oxidize the PCB rings, opening them up for further breakdown. These reactions convert PCBs into simpler, non-toxic compounds like chlorobenzoates, which can eventually be fully mineralized. Together, these microbial and enzymatic processes offer an efficient and natural method for detoxifying persistent PCB pollution.</p>
        </div>
        <div class="feature">
            <h3>Reactive Caps</h3>
            <p>Activated carbon and biochar layers trap remaining PCBs to prevent contamination. Reactive caps are engineered layers placed over contaminated sediments to prevent pollutants like PCBs and dioxins from spreading into surrounding water. They contain reactive materials in this case activated carbon or biochar that chemically bind or break down contaminants, reducing their toxicity and mobility while providing a stable surface for sediment and aquatic life.</p>
        </div>
        <div class="feature">
            <h3>Real-Time Monitoring</h3>
            <p>Sensors track PCB levels, oxygen, and pH for optimized cleanup. Specifically, IoT-enabled sensors track PCB concentrations, oxygen, pH, and microbial activity, allowing engineers to adjust nutrient delivery or oxygen levels to maximize cleanup efficiency.
 </p>
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
        <li>
            Microbes metabolize PCBs, transforming highly toxic compounds into non-toxic substances, reducing chemical exposure in water, sediment, and soil.

        </li>
        <li>
        Reactive caps stop remaining PCBs from entering the river, protecting wildlife and local communities.

        </li>
        <li>
         Sensors allow real-time monitoring so cleanup can be adjusted based on conditions, increasing safety and efficiency.

        </li>
    </ul>
   
</section>

<section id="research">
    <h2>Research & Evidence</h2>
    <p>Scientific studies show microbial and enzymatic PCB degradation reduces contamination by up to 90%. Ongoing research monitors ecological recovery and community health improvements.</p>
    <p>
        Researchers at Oak Ridge National Laboratory (ORNL) have developed innovative methods using natural bacteria to eliminate polychlorinated biphenyls (PCBs) from contaminated soil. Their approach relies on a two-stage biodegradation process involving both anaerobic (without oxygen) and aerobic (with oxygen) conditions. In the first stage, anaerobic bacteria target highly chlorinated PCBs, removing chlorine atoms and breaking them down into less toxic forms. In the second stage, aerobic bacteria further degrade these partially dechlorinated compounds into harmless substances such as carbon dioxide and water. This method can reduce PCB concentrations in soil by up to 70% and has the added advantage of working directly in contaminated soil without the need to add external sediments or chemicals, making it an environmentally friendly solution.

    </p>
    <p>
    The breakdown of PCBs relies on specialized microorganisms and enzymes that perform different chemical processes depending on oxygen availability. Anaerobic bacteria, such as Dehalococcoides and other organohalide-respiring microbes, remove chlorine atoms from PCBs through a process called dechlorination. This step is crucial because highly chlorinated PCBs are much more resistant to degradation. Once the molecules are less chlorinated, aerobic bacteria, including Burkholderia, Pseudomonas, Rhodococcus, Alcaligenes, and Comamonas can oxidatively break down the PCB molecules. Key enzymes in this aerobic process, such as biphenyl dioxygenase and other biphenyl-catabolic enzymes, introduce oxygen into the biphenyl rings of PCBs. This reaction opens the chemical rings, allowing the molecules to be further converted into simpler, non-toxic compounds like chlorobenzoates, which can then be fully mineralized. Together, these microbial and enzymatic processes offer a promising natural solution to one of the most persistent forms of environmental pollution.

    </p>
</section>

<section id="future">
    <h2>Future Plans</h2>
    
    <p>The system aims to restore the Passaic River fully, support safe recreation, expand sensor networks, and provide educational outreach for local communities.</p>
    <p>
    Continuous monitoring allows for timely adjustments to maximize degradation efficiency and minimize environmental impact. Future plans include expanding the system to larger contaminated sites, integrating advanced sensor technology for more precise tracking of microbial activity and PCB levels, and exploring genetically optimized microbes or enzyme cocktails to accelerate breakdown. Long-term goals also involve combining BioClean with ecological restoration projects to fully rehabilitate affected waterways and soils, making the environment safe for wildlife and local communities.
    </p>
 <img href=https://www.gdrc.org/oceans/rivers/photo-3.jpg>
    
</section>

<section id="contact">
    <h2>Help</h2>
    <p>Donate to local charities to help fix this problem in the real world</p>
    <div class="features">
        <div class="feature">
            <h3>CCI Camera Project </h3>
           
        </div>
        <div class="feature">
            <h3>Earth Month and Days of Service</h3>
        </div>
        <div class="feature">
            <h3>Community Growth through Tabling Events</h3>
            
        </div>
    </div>
</section>

<footer>
    &copy; 2025 BioClean PCB System. All rights reserved.
</footer>

</body>
</html>
