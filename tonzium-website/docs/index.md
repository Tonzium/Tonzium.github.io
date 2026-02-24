# Toni Kiuru

<div align="center">
  <img src="images/toni.jpg" width="250" style="border-radius: 50%; border: 2px solid #39ff14; box-shadow: 0 0 15px rgba(57, 255, 20, 0.3);">
  
  <h3>Materials Scientist | Applied AI Research | Computational Engineering</h3>
  
  <p>
    <em>"A curious lifelong learner from Finland. I find inspiration in building and developing impactful systems to drive growth."</em>
  </p>

  <!-- System Analytics Section -->
  <div class="data-dashboard">
    <div class="data-card">
      <div class="metric-text">Visitors</div>
      <img src="https://visitor-badge.laobi.icu/badge?page_id=Tonzium.tonzium.github.io&left_color=black&right_color=green&left_text=Visits" alt="visitor badge">
    </div>
    <div class="data-card">
       <div class="metric-text">SYSTEM STATUS</div>
       <span id="system-time" style="color: #39ff14; font-family: 'Share Tech Mono';">ONLINE</span>
    </div>
  </div>

  <div class="data-dashboard">
    <a href="https://github.com/Tonzium">
      <img class="data-card" align="center" src="https://github-readme-stats.vercel.app/api?username=Tonzium&show_icons=true&theme=dark&bg_color=0a0a0a&title_color=39ff14&text_color=fff&icon_color=39ff14&hide_border=true" alt="GitHub" />
    </a>
  </div>

  <script>
    // Simple script to update time - adds to the 'live' dashboard feel
    function updateTime() {
      const now = new Date();
      document.getElementById('system-time').innerText = "ONLINE | " + now.toISOString().split('T')[0] + " " + now.toLocaleTimeString();
    }
    setInterval(updateTime, 1000);
    updateTime();
  </script>
</div>

---

## About Me

Hi there! I'm Toni.

> **"I see research, engineering, and IT as the bridge between cutting-edge science and real-world impact."**

I hold a **Master’s degree in Materials Science from Aalto University**, where I developed a strong foundation in physics, chemistry, and data-driven problem solving. My academic focus included semiconductor physics and lithium-ion battery materials, combining theoretical understanding with experimental insight.

From early on, I was equally drawn to computational thinking. I chose **materials science** intentionally, recognizing that deep physical intuition provides the strongest basis for solving complex engineering problems. This background trained me to approach phenomena through first principles, structured modelling, and experimental validation.

After graduation, I deliberately expanded into **programming, data engineering, and machine learning**, viewing it as a long-term commitment rather than a short-term skill acquisition. I built my expertise systematically in neural networks, deep learning, and advanced analytics, applying these methods to real industrial material processes.

Currently, I am completing a **Bachelor’s Degree in Data and AI at KAMK** alongside my work to formalize and certify my existing expertise, while staying aligned with modern tools and expanding my professional network. My planned graduation year is 2027.

I'm a big fan of science fiction, and the classic green-on-black aesthetic of the genre inspired the theme of this website. When I'm outside, I enjoy riding my mountain bike through forest trails. Indoors, I keep building my digital Homelab and connecting the digital world to the real world with a 3D printer models, bringing ideas to life. This mix of outdoor adventure and creative work keeps me motivated and curious.

---

## Work Life & Mission


<div class="terminal-manifest">
```json
{
  "name": "Toni Kiuru",
  "role": "Process Engineer (Processes <-> Data <-> AI/ML )",
  "core_competencies": [
    "Predictive Systems",
    "Advanced Data Analysis",
    "Cross-functional Team Lead"
  ],
  "mission_vector": "Turning Physical Processes into Scalable, Intelligent Systems",
  "status": "In Progress"
}
```
</div>


### **What I Bring to the Team**

I have seen firsthand that innovation starts with bringing people together. Through active listening, I help teams formulate actionable steps to create transformative change. I help teams structure messy data, build machine learning models that actually work in production, and connect data insights with real physical understanding. For example, I've developed models to predict material behaviour from process data.

I enjoy shaping ideas into clear project plans, coordinating between R&D, IT, and production, and making sure every deliverable adds real value. I bring structured thinking, curiosity, and a collaborative mindset and I communicate results clearly, whether to researchers, operators, or management. I am a **native Finnish speaker** and work fluently in **English** in multicultural environments.

---

### **The Bridge: Materials-to-AI Pipeline**

In my work, I focus on multivariate modelling of complex material and process systems, where interactions between parameters are often non-linear and time-dependent. Rather than analysing signals independently, I design models that capture temporal evolution across full process runs, enabling more accurate representation of physical behaviour. I place strong emphasis on rigorous validation strategies, including careful dataset splitting, robustness testing, and monitoring of model generalization across process drifts. Addressing generalization challenges across tools, materials, and production conditions is a central part of my modelling philosophy.

*How I translate physical signals into industrial impact.*

<div class="mermaid">
graph LR
    subgraph "Physical Domain"
        A[Manufacturing Processes] --> B[Sensor & Tool Signals]
    end

    subgraph "Digital Domain"
        B --> C[Data Engineering & Feature Extraction]
        C --> D[Predictive AI / ML Models]
        D --> E[Decision Support & Process Control]
    end

    subgraph "Business Impact"
        E --> F[Yield & Quality Improvement]
        E --> G[Process Understanding & Insights]
        E --> H[Cost & Waste Reduction]
    end


    style A fill:#004400,stroke:#39ff14,color:#fff
    style D fill:#004400,stroke:#39ff14,color:#fff
    style F fill:#004400,stroke:#39ff14,color:#fff
    style G fill:#004400,stroke:#39ff14,color:#fff
    style B fill:#001a00,stroke:#39ff14,color:#fff
    style C fill:#001a00,stroke:#39ff14,color:#fff
    style E fill:#001a00,stroke:#39ff14,color:#fff
    style H fill:#004400,stroke:#39ff14,color:#fff
</div>

---

### **Where Data Meets Real World**
My background allows me to handle complex high-dimensional sensor data, not just as a mathematical exercise, but as a way to understand the physical phenomena behind material performance. 

*   **Applied AI/ML:** I work fluently with Python-based workflows (TensorFlow, PyTorch, Scikit-learn) to develop models for predictive material behaviour, quality control, anomaly detection, and predictive maintenance.
*   **Operational Integration:** I focus on deploying models as actual decision-support tools in operational environments, ensuring they remain physically meaningful and practically usable.

### **Innovation & Impact**
I thrive in environments where innovation is measured by results. My approach combines theoretical understanding with a data-driven mindset to solve complex manufacturing challenges.

!!! success "Example Highlights"
    *   **Yield Optimization:** I have led initiatives resulting in historically high yields and a **40% reduction in yield costs** within a single year.
    *   **Digital Transformation:** Pioneered data-driven quality systems, including the implementation of predictive maintenance pipelines and deep learning defect classification models.
    *   **Metrology Mastery:** Extensive experience with SEM, confocal/optical microscopy, and laser-based measurement systems to ensure data quality through MSA and Gage R&R.

### **Collaborative Leadership**
I believe that the best solutions are created through trust, clarity, and shared goals. I am comfortable bridging the gap between technical and operational teams. Whether it's sparring with equipment engineers, mentoring R&D teams, or building cross-functional material strategies with global suppliers.

---

## Experience

### **Sr. Process Engineer** @ Murata
*Vantaa, Finland (2022 – Present)*

**Silicon-Glass Fusion Process Ownership**

I manage product/process qualifications, optimization, cost reduction, and yield improvement projects. My role involves executing Engineer Change Notices (planning, validation, documentation, safe-launch, reporting) and ensuring robust process controls.

*   **Key Responsibilities:**
    *   Responsible of silicon-glass fusion process to ensure structural integrity and directing post-fusion workflows.
    *   Metrology tool controls (MSA, Gage R&R).
    *   Implementing process controls and continuous improvements (CI) to reduce variation.
    *   Leading root-cause investigations (FTA, 8D).
    *   Overseeing purchases and supplier quality projects.
    *   Financial assessments and ROI analyses.

*   **My Impact (Data & AI):**
    *   **Digital Transformation:** Spearheaded initiatives delivering end-to-end data solutions, from novel data-collection strategies to fully automated analytics.
    *   **AI Integration:** Developed novel process controls leveraging AI for predictive maintenance and smarter production workflows.
    *   **Visualization:** Created Power BI and JMP dashboards for enhanced analysis.
    *   **Mentorship:** Mentoring engineers in machine learning and deep-learning initiatives.

??? Click_to_see_Manufacturing_Processes
    Thermal glass-silicon fusion  
    Edgegrinding  
    Edgeprofilemeter  
    Grinding  
    Washing  
    Etching Processes  
    Thermal Relaxation Processes  
    Polishing Processes  
    Metrology Tools  


??? Click_to_see_Data_and_AI_Innovations
    Glass-Silicon Fusion Data and AI solution  
    Grinding Process Control via novel data innovations  
    High-impact feasibility studies with significant cost-reduction potential 
    Ownership and development of BI solutions
    Mentorship via Python

### **Thesis Worker** @ Aalto University
*Espoo, Finland (2021)*

*   Investigated the degradation of lithium-ion battery materials (NMC811 and graphite) for second-life applications.
*   Conducted extensive material characterization and data analysis as part of a Business Finland commission.

### **Process Operator** @ Okmetic
*Vantaa, Finland (2012 – 2017)*

*   Began my career in a cleanroom environment specializing in Double-Sided Polishing (DSP) of semiconductor wafers.
*   Operated precision equipment, performed maintenance, troubleshooting, and quality control.
*    utilized data to monitor processes and ensure quality standards were met.
*   Expanded role to include Single-Sided Polishing (Okamoto XLSSP) and wafer sorting, contributing to process development and loss minimization.

---

## Skills

| Category | Skills |
| :--- | :--- |
| **Materials Science** | MEMS, Semiconductor Technology, Microfabrication |
| **Machine Learning** | Classic ML, Deep learning, TensorFlow, PyTorch, Scikit-learn |
| **Data Engineering** | Python, SQL, ETL Pipelines, Data Analysis |
| **Tools & Platforms** | Git, SVN, Power BI, JMP, Linux |
| **Soft Skills** | Leadership, Team Collaboration, Communication, Problem Solving |

---

## Home Project examples

### [fintraffic_railway_data_pipeline](https://github.com/Tonzium/fintraffic_railway_data_pipeline)
This repository contains professional data platform setup for analyzing Finnish Railway data.

### [Q-learning-vs-ExpectedSarsa_in_cliff_world](https://github.com/Tonzium/Q-learning-vs-ExpectedSarsa_in_cliff_world)
In this repository visually shows the differences (trade-off) between two RL algorithms: Q-learning and Expected Sarsa.

### [Reinforcement Learning - Lunar Lander v3](https://github.com/Tonzium/ExpectedSarsaAgent_with_NeuralNetwork-LunarLander-v3)
This repository contains manual implementation of RL agent to play classic Lunar Lander v3 -game.

### [Snake Game - Click to play](https://tonzium.github.io/snakegame/)
A classic Snake game implementation where you can play against AI or a friend.

*   *Check out more on my [GitHub](https://github.com/Tonzium/).*
*   *School projects in internal [GitLab]*

---

## Education

**Master's Degree** | Aalto University (2021)
:   *Major:* Functional Materials
:   *Thesis:* Analysis of Lithium-Ion Battery Cathode-Anode Materials for Second-Life Applications

**Bachelor's Degree** | Kajaanin ammattikorkeakoulu KAMK (2025 – Present)
:   *Major:* Data and Artificial Intelligence

**Bachelor's Degree** | Aalto University (2015)
:   *Major:* Applied Materials Science
:   *Minor:* Industrial Engineering and Management

---

## Awards & Certifications
### Data adn AI
*   [Google Advanced Data Analytics](https://www.coursera.org/account/accomplishments/specialization/certificate/6SVDZET3MVQ8/) (Coursera)
*   [Data Scientist: NLP Specialist](https://www.codecademy.com/profiles/ToniKiuru/certificates/9c35fed4f15a487385d52456712e0da9/) (Codecademy)
*   [Intermediate Machine Learning](https://www.codecademy.com/profiles/ToniKiuru/certificates/964140ff91ae4cd7872f51207633413a/) (Codecademy)
*   [Data Scientist: Machine Learning](https://www.codecademy.com/profiles/ToniKiuru/certificates/8e9e59de3f924b33ad2371faf667129b/) (Codecademy)
*   [Business Intelligence Data Analyst](https://www.codecademy.com/profiles/ToniKiuru/certificates/d03c7391224540ef8f850f8807a2b72a/) (Codecademy)
*   [Reinforced Learning Specialization](https://www.coursera.org/account/accomplishments/specialization/certificate/B83VFZ99X6G2/) (Coursera)

### Other
*   [Kennesaw University - Six Sigma Green Belt](https://www.coursera.org/account/accomplishments/specialization/TD61UAN7UPYM) (Coursera)
*   [KAIST - Supply Chain Management](https://www.coursera.org/account/accomplishments/verify/NHRPZWSNL648) (Coursera)
*   [Darthmouth - Strategic Leadership - Part1](https://www.coursera.org/account/accomplishments/verify/N3B6H334QTE4) (Coursera)

---

## Contact

I am always open to discussing new opportunities, collaborations, or just chatting about tech and science.

[Email Toni!](mailto:toni.kiuru9@gmail.com){ .md-button }
[LinkedIn](https://www.linkedin.com/in/toni-k-46538b83/){ .md-button }
[Discord Tonzium](https://discordapp.com/users/Tonzium){ .md-button }
