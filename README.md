<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Aswin Raj Sivaprakash | Portfolio</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-white text-gray-800">
  <!-- Header -->
  <header class="bg-green-600 text-white p-6">
    <div class="container mx-auto flex flex-col md:flex-row items-center justify-between">
      <div class="flex items-center space-x-4">      
        <img src="https://raw.githubusercontent.com/Ash-Impactco/Portofolio-2/main/1746453347734.jpg" alt="Aswin Raj Sivaprakash" class="w-44 h-44 rounded-full border-2 border-white" />
        <div>
          <h1 class="text-4xl font-bold">Aswin Raj Sivaprakash</h1>
          <p class="text-lg mt-1">Clean Tech Marketer | Environmental Strategist | CRM Specialist</p>
        </div>
      </div>
      <div class="mt-4 md:mt-0 text-right">
        <p>📍 Porto, Portugal</p>
        <p>📞 +351 938816822</p>
        <p>✉️ <a href="mailto:aswinr63@gmail.com" class="underline">aswinr63@gmail.com</a></p>
        <p>🔗 <a href="https://linkedin.com/in/aswin-sivaprakash" target="_blank" class="underline">linkedin.com/in/aswin-sivaprakash</a></p>
      </div>
    </div>
  </header>

  <!-- Main Content -->
  <main class="container mx-auto px-4 py-10">
    <!-- Hero -->
    <section class="text-center px-4">
      <h2 class="text-5xl font-bold text-gray-800 mb-4">Hey, I'm Aswin 👋</h2>
      <p class="text-lg text-gray-600 max-w-xl mx-auto">
        A passionate clean tech marketer and sustainability specialist with 5+ years driving CRM, digital strategy, and ESG communications across global markets.
      </p>
      <div class="flex justify-center gap-4 mt-6">
        <!-- Resume link updated for direct download -->
        <a href="https://github.com/Ash-Impactco/Portofolio-2/raw/main/Aswin%20Resume%20.pdf" class="bg-green-600 text-white px-5 py-2 rounded-xl hover:bg-green-700 transition" download>
          📄 Download Resume
        </a>
        <a href="https://linkedin.com/in/aswin-sivaprakash" target="_blank" class="bg-blue-600 text-white px-5 py-2 rounded-xl hover:bg-blue-700 transition">
          🔗 LinkedIn
        </a>
      </div>
    </section>

    <!-- About -->
    <section id="about" class="py-16 px-4 bg-gray-100 text-gray-800">
      <div class="max-w-3xl mx-auto">
        <h2 class="text-3xl font-bold mb-4">About Me</h2>
        <p class="text-lg">
          I blend market expertise and sustainability passion to craft high-impact marketing strategies for clean technology and environmental initiatives. Skilled in CRM (HubSpot & Salesforce), digital campaigns, and stakeholder engagement, I deliver measurable results that support both business growth and environmental impact.
        </p>
      </div>
    </section>

    <!-- Experience -->
    <section id="experience" class="py-16 px-4 bg-white text-gray-800">
      <div class="max-w-4xl mx-auto">
        <h2 class="text-3xl font-bold mb-6 text-center">Experience</h2>
        <ul class="space-y-6">
          <li>
            <button onclick="toggle('exp1')" class="w-full text-left px-4 py-2 rounded bg-green-500 text-white hover:bg-green-600 transition">Freelance Clean Tech Marketer - Cleantech GrowthLab (Jun 2024 – Present)</button>
            <div id="exp1" class="hidden mt-2 ml-4">
              <ul class="list-disc pl-6">
                <li>Designed CRM workflows to nurture leads and improve SQL generation (10× increase).</li>
                <li>Sustained 44% average open rate on nurture emails.</li>
                <li>Developed digital strategy and content for social campaigns, boosting engagement by 30%.</li>
              </ul>
              <a href="#crm-cleantech" class="text-blue-600 underline mt-2 block">View CRM Campaign Details</a>
            </div>
          </li>
          <li>
            <button onclick="toggle('exp2')" class="w-full text-left px-4 py-2 rounded bg-blue-500 text-white hover:bg-blue-600 transition">Customer Success & Marketing Specialist - Scores &amp; Levels (Jun 2024 – Present)</button>
            <div id="exp2" class="hidden mt-2 ml-4">
              <ul class="list-disc pl-6">
                <li>Managed multi-channel campaigns, improving user retention by 25%.</li>
                <li>Developed onboarding flows in HubSpot, enhancing customer satisfaction by 20%.</li>
              </ul>
            </div>
          </li>
          <li>
            <button onclick="toggle('exp3')" class="w-full text-left px-4 py-2 rounded bg-blue-500 text-white hover:bg-blue-600 transition">Business Development Manager - National Chromatography Inco (Oct 2022 – May 2024)</button>
            <div id="exp3" class="hidden mt-2 ml-4">
              <ul class="list-disc pl-6">
                <li>Led international sales of chromatography equipment worth $35k+</li>
                <li>Onboarded 50+ clients via RFPs and cold outreach (80% quota).</li>
                <li>Boosted lead conversion by 13% with Salesforce CRM.</li>
              </ul>
              <a href="#crm-chromo" class="text-blue-600 underline mt-2 block">View CRM Campaign Details</a>
            </div>
          </li>
          <li>
            <button onclick="toggle('exp4')" class="w-full text-left px-4 py-2 rounded bg-green-500 text-white hover:bg-green-600 transition">Environmental Consultant - MGK Aqua Inco (Nov 2020 – Aug 2021)</button>
            <div id="exp4" class="hidden mt-2 ml-4">
              <ul class="list-disc pl-6">
                <li>Assembled DPRs for sustainability, energy efficiency, and GHG management projects.</li>
                <li>Executed water treatment solutions for housing & corporate projects.</li>
                <li>Implemented rainwater harvesting and wastewater treatment plans.</li>
              </ul>
            </div>
          </li>
          <li>
            <button onclick="toggle('exp5')" class="w-full text-left px-4 py-2 rounded bg-green-500 text-white hover:bg-green-600 transition">Project Assistant – UNICEF WASH (Jul 2018 – Jun 2019)</button>
            <div id="exp5" class="hidden mt-2 ml-4">
              <ul class="list-disc pl-6">
                <li>Streamlined water testing and installed solar stoves for 10k+ residents.</li>
                <li>Coordinated with government on solar stove & water pump projects.</li>
                <li>Modernized honeycomb toilet designs across 16 tea estates.</li>
              </ul>
            </div>
          </li>
        </ul>
      </div>
    </section>

    <!-- CRM Campaign Summary Table -->
    <h4 class="text-xl font-semibold mb-4 text-center">CRM Campaign Summary</h4>
    <table class="table-auto w-full border-collapse border border-gray-300 text-sm">
      <thead>
        <tr class="bg-gray-200">
          <th class="border border-gray-300 px-4 py-2">Campaign</th>
          <th class="border border-gray-300 px-4 py-2">Audience</th>
          <th class="border border-gray-300 px-4 py-2">Tools Used</th>
          <th class="border border-gray-300 px-4 py-2">Results</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td class="border border-gray-300 px-4 py-2">Cleantech GrowthLab</td>
          <td class="border border-gray-300 px-4 py-2">SMEs, Sustainability Teams, Investors</td>
          <td class="border border-gray-300 px-4 py-2">HubSpot CRM, Mailchimp, Google Analytics</td>
          <td class="border border-gray-300 px-4 py-2">10× SQL Growth, $X Revenue Generated</td>
        </tr>
        <tr>
          <td class="border border-gray-300 px-4 py-2">iGaming Platforms</td>
          <td class="border border-gray-300 px-4 py-2">Dormant, VIP, New Players</td>
          <td class="border border-gray-300 px-4 py-2">Salesforce CRM, Mailchimp, Twilio</td>
          <td class="border border-gray-300 px-4 py-2">25% Reactivation, 20% VIP Retention, +20% LTV</td>
        </tr>
        <tr>
          <td class="border border-gray-300 px-4 py-2">National Chromatography Inco</td>
          <td class="border border-gray-300 px-4 py-2">Pharma R&D, QC Labs, Universities</td>
          <td class="border border-gray-300 px-4 py-2">Salesforce Pardot, Mailchimp, LinkedIn</td>
          <td class="border border-gray-300 px-4 py-2">$35k Revenue, 13% Lead-to-Opportunity Conversion</td>
        </tr>
      </tbody>
    </table>
  </div>
</section>

    <!-- Projects -->
    <section id="projects" class="py-16 px-4 bg-gray-100 text-gray-800">
      <div class="max-w-5xl mx-auto">
        <h2 class="text-3xl font-bold mb-6 text-center">Projects</h2>
        <div class="space-y-8">
          <div class="bg-green-50 p-6 rounded-xl">
            <h3 class="text-xl font-semibold">Upcoming Geothermal Heat Grid Case Study – Leeuwarden, NL (Feb 2022 – Apr 2022)</h3>
            <p class="mt-2">Collected qualitative data from 100 respondents on geothermal integration using DESSIN-ESS. Findings published by <a href="https://www.omropfryslan.nl/nl/nieuws/1144457/internationale-studenten-duurzame-aanpak-in-fryslan-is-mogelijk" class="underline text-blue-600" target="_blank">Omrop</a>.</p>
          </div>
          <div class="bg-green-50 p-6 rounded-xl">
            <h3 class="text-xl font-semibold">Coral Bleaching Status – Andaman Islands, India (Dec 2017 – Feb 2018)</h3>
            <p class="mt-2">Identified 1°C SST increase causing symbiosis degradation. Assessed thermal stress via CBAS. Presented findings to ANET, Indian Wildlife Dept. & Coast Guard.</p>
          </div>
          <div class="bg-green-50 p-6 rounded-xl">
            <h3 class="text-xl font-semibold">Municipal Solid Waste Management – Erode, India (Sep 2016 – Nov 2016)</h3>
            <p class="mt-2">Monitored 10k kWh/day electricity from 135 tonnes waste gasification. Segregated waste into 6 categories including hazardous and E-waste.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- CRM Campaign Details -->
    <section id="crm-cleantech" class="py-16 px-4 bg-green-50 text-gray-800">
      <div class="max-w-4xl mx-auto">
        <h2 class="text-3xl font-bold mb-4">CRM Campaign – Cleantech GrowthLab</h2>
        <p>Developed a multi-stage nurture campaign to convert clean tech leads:</p>
        <ul class="list-disc pl-6 mt-2">
          <li>Segments: SMEs, corporate sustainability teams, investors.</li>
          <li>Workflow: Welcome email → educational series → case study highlight → demo invite.</li>
          <li>Tools: HubSpot workflows, behavior scoring, dynamic content.</li>
          <li>Results: 10× SQL growth, 44% open rate, 8% demo-to-contract conversion.</li>
        </ul>
      </div>
    </section>
    <section id="crm-igaming" class="py-16 px-4 bg-yellow-50 text-gray-800">
      <div class="max-w-4xl mx-auto">
        <h2 class="text-3xl font-bold mb-4">CRM Campaign – iGaming Platforms</h2>
        <p>Reactivation and retention strategy across multiple markets:</p>
        <ul class="list-disc pl-6 mt-2">
          <li>Audience: Dormant players, VIP segments, new registrants.</li>
          <li>Channels: Email, in-app notifications, SMS.</li>
          <li>Sequence: Re-engagement drip → VIP loyalty boost → exclusive offers.</li>
          <li>Outcomes: +20% LTV, 25% reactivation rate of dormant users.</li>
        </ul>
      </div>
    </section>
    <section id="crm-chromo" class="py-16 px-4 bg-blue-50 text-gray-800">
      <div class="max-w-4xl mx-auto">
        <h2 class="text-3xl font-bold mb-4">CRM Campaign – National Chromatography Inco</h2>
        <p>Targeted outreach for chromatography equipment adoption:</p>
        <ul class="list-disc pl-6 mt-2">
          <li>Prospecting: Pharma R&D, QC labs, universities.</li>
          <li>Email series: Product intro → ROI-focused case studies → personalized demos.</li>
          <li>Automation: Salesforce Pardot, lead scoring, triggered follow-ups.</li>
          <li>Impact: 13% lead-to-opportunity conversion, \$35k in closed deals.</li>
        </ul>
      </div>
    </section>

    <!-- Certifications & Courses -->
    <section id="certifications" class="py-16 px-4 bg-white text-gray-800">
      <div class="max-w-3xl mx-auto">
        <h2 class="text-3xl font-bold mb-6 text-center">Certifications & Courses</h2>
        <ul class="space-y-4">
          <li><strong>Salesforce Marketing Cloud Certification</strong> (Feb 2023)</li>
          <li><strong>Google Analytics Certification</strong> (Nov 2021)</li>
          <li><strong>HubSpot CRM Certified</strong> (Oct 2021)</li>
          <li><strong>LinkedIn Learning: Digital Marketing Strategy</strong> (Jul 2020)</li>
        </ul>
      </div>
    </section>

  </main>

  <!-- Footer -->
  <footer class="bg-gray-900 text-white py-8 text-center">
    <p>&copy; 2025 Aswin Raj Sivaprakash. All Rights Reserved.</p>
  </footer>

  <!-- Toggle Function for Experience Details -->
  <script>
    function toggle(id) {
      const element = document.getElementById(id);
      element.classList.toggle("hidden");
    }
  </script>
</body>
</html>

# Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aswin's | Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Aswin Raj Sivaprkash</h1>
    
  </header>
  <script src="script.js"></script>
</body>
</html>

body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
}
header {
  background: #f4f4f4;
  padding: 2rem;
  text-align: center;
}
}
import Hero from "@/components/Hero";
import About from "@/components/About";
import Projects from "@/components/Projects";
import Contact from "@/components/Contact";

export default function Home() {
  return (
    <main>
      <Hero />
      <About />
      <Projects />
      <Contact />
    </main>
  );
}
components/Hero.tsx – for your intro
export default function Hero() {
  return (
    <section className="min-h-screen flex flex-col items-center justify-center bg-white text-center px-4">
      <h1 className="text-5xl font-bold text-gray-800 mb-4">Hey, I'm Aswin 👋</h1>
      <p className="text-lg text-gray-600 max-w-xl">
        A passionate web developer building fast, modern websites using Next.js, React & Tailwind CSS.
      </p>
    </section>
  );
}

components/About.tsx
export default function About() {
  return (
    <section className="py-20 px-4 bg-gray-100 text-gray-800">
      <div className="max-w-3xl mx-auto">
        <h2 className="text-3xl font-bold mb-4">About Me</h2>
        <p className="text-lg">
          I'm a developer with a strong focus on building clean, accessible, and high-performing websites.
          I love turning ideas into digital experiences that are both beautiful and functional.
        </p>
      </div>
    </section>
  );
}

components/Projects.tsx
export default function Projects() {
  return (
    <section className="py-20 px-4 bg-white text-gray-800">
      <div className="max-w-5xl mx-auto">
        <h2 className="text-3xl font-bold mb-8">Projects</h2>
        <div className="grid gap-8 md:grid-cols-2">
          <div className="p-6 border rounded-xl shadow-sm hover:shadow-md transition">
            <h3 className="text-xl font-semibold mb-2">Project One</h3>
            <p className="text-gray-600">A cool project description goes here.</p>
          </div>
          <div className="p-6 border rounded-xl shadow-sm hover:shadow-md transition">
            <h3 className="text-xl font-semibold mb-2">Project Two</h3>
            <p className="text-gray-600">Another awesome project description.</p>
          </div>
        </div>
      </div>
    </section>
  );
}

components/Contact.tsx
export default function Contact() {
  return (
    <section className="py-20 px-4 bg-gray-100 text-gray-800">
      <div className="max-w-xl mx-auto text-center">
        <h2 className="text-3xl font-bold mb-4">Get In Touch</h2>
        <p className="text-lg mb-6">Have a project in mind or just want to say hi? Let’s connect!</p>
        <a
          href="mailto:youremail@example.com"
          className="inline-block bg-blue-600 text-white py-3 px-6 rounded-xl hover:bg-blue-700 transition"
        >
          Say Hello
        </a>
      </div>
    </section>
  );
}


