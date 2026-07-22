<link rel="stylesheet" href="{{ '/assets/css/positioning.css' | relative_url }}">

<div class="positioning-page">
  <div class="page-shell">

<aside class="profile-sidebar" aria-label="Profile">
  <img src="{{ '/assets/img/profile.JPG' | relative_url }}" alt="Portrait of Hyunsoo Lee" class="profile-image">

  <div class="profile-copy">
    <h1>Hyunsoo Lee</h1>
    <p class="profile-role">Research Assistant Professor</p>
    <p>KAIST School of Computing<br>Graduate School of Information Security</p>
    <p class="profile-appointment">
      Incoming Visiting Scholar<br>
      UC Berkeley EECS<br>
      Oct 2026–Sep 2027
    </p>
  </div>

  <nav class="profile-links" aria-label="Professional links">
    <a href="mailto:hslee90@kaist.ac.kr" aria-label="Email Hyunsoo Lee"><i class="fa-solid fa-envelope"></i></a>
    <a href="https://scholar.google.com/citations?user=ctglUjoAAAAJ&hl=en" target="_blank" rel="noopener noreferrer" aria-label="Google Scholar"><i class="fa-solid fa-graduation-cap"></i></a>
    <a href="https://x.com/hyunsoo820" target="_blank" rel="noopener noreferrer" aria-label="X profile"><i class="fa-brands fa-x-twitter"></i></a>
    <a href="{{ '/assets/cv/CV(Hyunsoo Lee_260510).pdf' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Curriculum vitae"><span class="cv-label">CV</span></a>
  </nav>
</aside>

<main class="main-content">
  <section class="hero" aria-labelledby="hero-title">
    <p class="section-label">HUMAN-CENTERED PRIVACY, SECURITY, AND SAFETY</p>
    <h2 id="hero-title">Designing systems that preserve human agency and meaningful control.</h2>

    <p class="hero-lead">
      I study how people understand, negotiate, and retain meaningful control over data-driven and increasingly autonomous systems. My research combines empirical HCI, usable security, and interactive system design to develop privacy, security, and safety mechanisms that work in everyday life.
    </p>

    <p class="current-focus">
      <strong>Current focus:</strong> relational privacy in sensor-rich environments, usable risk communication, and human-centered guardrails for AI and autonomous systems.
    </p>

    <div class="hero-actions">
      <a class="button button-primary" href="{{ '/assets/pdf/research statement.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">Research Statement</a>
      <a class="button" href="{{ '/assets/cv/CV(Hyunsoo Lee_260510).pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">CV</a>
      <a class="button" href="https://scholar.google.com/citations?user=ctglUjoAAAAJ&hl=en" target="_blank" rel="noopener noreferrer">Google Scholar</a>
      <a class="button" href="mailto:hslee90@kaist.ac.kr">Email</a>
    </div>
  </section>

  <section id="research-agenda" class="content-section">
    <header class="section-header">
      <p class="section-label">RESEARCH AGENDA</p>
      <h2>One agenda across privacy, security, and safety</h2>
      <p>My work examines how people can understand risk, negotiate data practices, and intervene in the behavior of increasingly intelligent systems.</p>
    </header>

    <div class="agenda-grid">
      <article class="agenda-card">
        <span class="card-number">01</span>
        <h3>Relational Privacy and Data Governance</h3>
        <p class="agenda-question">How can people understand and negotiate privacy when data is continuously sensed, inferred, and shared across multiple people?</p>
        <p class="agenda-projects">PriviAware · FamilyScope · OurData · Dynamic Consent · Group Privacy</p>
      </article>

      <article class="agenda-card">
        <span class="card-number">02</span>
        <h3>Usable Security and Risk Understanding</h3>
        <p class="agenda-question">How can security and privacy risks become understandable and actionable in everyday and AI-mediated systems?</p>
        <p class="agenda-projects">Mind the SIM · LLM-Driven Privacy Attacks · Mental Models · Risk Communication</p>
      </article>

      <article class="agenda-card agenda-card-emerging">
        <span class="card-number">03 · EMERGING DIRECTION</span>
        <h3>Human-Centered Safety and Oversight</h3>
        <p class="agenda-question">How can people meaningfully supervise, contest, and intervene when AI systems influence decisions or act autonomously?</p>
        <p class="agenda-projects">AI Guardrails · Relational Safety · Agentic AI · Physical AI · Human Oversight</p>
      </article>
    </div>
  </section>

  <section id="selected-research" class="content-section">
    <header class="section-header section-header-row">
      <div>
        <p class="section-label">SELECTED RESEARCH</p>
        <h2>Representative contributions</h2>
      </div>
      <a class="section-link" href="{{ '/publications.html' | relative_url }}">View all publications →</a>
    </header>

    <div class="research-grid">
      <article class="research-card">
        <div class="research-visual" aria-hidden="true"><span>OurData</span></div>
        <div class="research-body">
          <p class="research-tags">Relational Privacy · Multi-User Data · Smart Homes</p>
          <h3>Rethinking privacy for relationally entangled data</h3>
          <p>Introduces a sociotechnical framework for understanding and governing sensor data that implicates multiple household members.</p>
          <div class="research-links"><a href="{{ '/assets/pdf/ourdata.pdf' | relative_url }}">Paper</a></div>
        </div>
      </article>

      <article class="research-card">
        <div class="research-visual" aria-hidden="true"><span>PriviAware</span></div>
        <div class="research-body">
          <p class="research-tags">Usable Privacy · Dynamic Consent · Visualization</p>
          <h3>Making continuous sensing visible and controllable</h3>
          <p>Designs contextual visualization and filtering mechanisms that help people inspect and adjust mobile sensing data collection.</p>
          <div class="research-links">
            <a href="{{ '/assets/pdf/priviaware.pdf' | relative_url }}">Paper</a>
            <a href="{{ '/assets/pdf/chi24.pdf' | relative_url }}">Slides</a>
          </div>
        </div>
      </article>

      <article class="research-card">
        <div class="research-visual" aria-hidden="true"><span>Mind the SIM</span></div>
        <div class="research-body">
          <p class="research-tags">Usable Security · Mental Models · Risk Communication</p>
          <h3>Understanding security awareness in everyday infrastructure</h3>
          <p>Examines how users understand SIM-related threats and where mental-model gaps undermine risk recognition and protective action.</p>
          <div class="research-links"><a href="{{ '/assets/pdf/mindthesim.pdf' | relative_url }}">Paper</a></div>
        </div>
      </article>

      <article class="research-card">
        <div class="research-visual" aria-hidden="true"><span>FamilyScope</span></div>
        <div class="research-body">
          <p class="research-tags">Family Informatics · Social Sensing · Reflection</p>
          <h3>Supporting shared reflection on family sensor data</h3>
          <p>Explores how families interpret affective and social sensing data together, revealing both opportunities and tensions in shared reflection.</p>
          <div class="research-links">
            <a href="{{ '/assets/pdf/familyscope.pdf' | relative_url }}">Paper</a>
            <a href="{{ '/assets/pdf/cscw24.pdf' | relative_url }}">Slides</a>
          </div>
        </div>
      </article>

      <article class="research-card research-card-current">
        <div class="research-visual" aria-hidden="true"><span>AI Guardrails</span></div>
        <div class="research-body">
          <p class="research-tags">Current Research · AI Safety · Human Oversight</p>
          <h3>Designing guardrails for increasingly autonomous AI</h3>
          <p>Investigates how people can recognize risk, contest system behavior, and exercise meaningful control in generative, agentic, and physical AI systems.</p>
        </div>
      </article>
    </div>
  </section>

  <section id="current-projects" class="content-section">
    <header class="section-header">
      <p class="section-label">CURRENT / EMERGING PROJECTS</p>
      <h2>Extending the agenda toward autonomous systems</h2>
    </header>

    <div class="project-list">
      <article class="project-item">
        <p class="project-status">CURRENT RESEARCH</p>
        <h3>Human-Centered AI Guardrails</h3>
        <p>Designing and evaluating intervention, escalation, explanation, and recovery mechanisms that support meaningful human control over AI behavior.</p>
      </article>

      <article class="project-item">
        <p class="project-status">NATIONAL POC PROJECT</p>
        <h3>Collaborative Intelligence and Physical AI</h3>
        <p>Examining privacy, security, safety, oversight, and governance when intelligent systems move from recommendation to physical action.</p>
      </article>

      <article class="project-item">
        <p class="project-status">EMERGING DIRECTION</p>
        <h3>Privacy and Safety in AI-Mediated Interaction</h3>
        <p>Studying relational and psychological risks in human–AI interaction, including inappropriate reliance, manipulation, dependency, and delusion-related harm.</p>
      </article>
    </div>
  </section>

  <section id="teaching-mentoring" class="content-section">
    <header class="section-header">
      <p class="section-label">TEACHING &amp; MENTORING</p>
      <h2>Building research and educational capacity</h2>
    </header>

    <div class="teaching-grid">
      <article class="teaching-card">
        <p class="teaching-term">SPRING 2026 · KAIST</p>
        <h3>CS374: Introduction to Human–Computer Interaction</h3>
        <p>User-centered design, prototyping, empirical evaluation, and the responsible development of interactive systems.</p>
        <!-- Optional public metric: <p class="teaching-metric">Course evaluation: 4.85 / 5.00</p> -->
      </article>

      <article class="teaching-card">
        <p class="teaching-term">FALL 2025 · KAIST</p>
        <h3>CS492: Human-Centered Security &amp; Privacy</h3>
        <p>Usable security and privacy, human factors in security, risk communication, privacy design, and emerging AI-related challenges.</p>
      </article>
    </div>

    <div class="mentoring-block">
      <h3>Mentoring</h3>
      <p>I mentor students in empirical HCI, usable privacy and security, ubiquitous computing, sensor-based systems, and human-centered AI research—from problem formulation and study design to system development and publication.</p>
      <p class="leadership-note"><strong>Research leadership:</strong> corresponding author and faculty mentor on CHI 2026 and IMWUT/UbiComp 2025 publications.</p>
    </div>
  </section>

  <section id="selected-news" class="content-section">
    <header class="section-header">
      <p class="section-label">SELECTED NEWS</p>
      <h2>Recent updates</h2>
    </header>

    <div class="news-list">
      <div class="news-item"><time>Oct 2026</time><p>Joining UC Berkeley EECS as a visiting scholar for a one-year research visit.</p></div>
      <div class="news-item"><time>Apr 2026</time><p><i>OurData</i>, introducing a relational framework for family privacy in sensor-rich homes, was accepted to IMWUT/UbiComp 2026.</p></div>
      <div class="news-item"><time>Mar 2026</time><p>Teaching <strong>CS374: Introduction to Human–Computer Interaction</strong> at KAIST School of Computing.</p></div>
      <div class="news-item"><time>Jan 2026</time><p>Two papers were accepted to CHI 2026: <i>Mind the SIM</i> and <i>Why Stressed, Mom?</i></p></div>
      <div class="news-item"><time>Sep 2025</time><p>Joined a national proof-of-concept project on collaborative intelligence and Physical AI.</p></div>
    </div>

    <details class="news-archive">
      <summary>Earlier news</summary>
      <div class="news-item"><time>Oct 2025</time><p>Research on home IoT for emotional wellbeing was featured in multiple media outlets. <a href="https://www.mk.co.kr/news/it/11446938" target="_blank" rel="noopener noreferrer">Coverage</a></p></div>
      <div class="news-item"><time>Sep 2025</time><p>Taught <strong>CS492: Human-Centered Security &amp; Privacy</strong> at KAIST School of Computing.</p></div>
      <div class="news-item"><time>Jul 2025</time><p>A mentored paper on home IoT and emotional wellbeing was accepted to IMWUT/UbiComp 2025. <a href="{{ '/assets/pdf/lifepensieve.pdf' | relative_url }}">Preprint</a></p></div>
      <div class="news-item"><time>Jul 2025</time><p>Gave an early-career researcher talk at KCC 2025. <a href="{{ '/assets/pdf/kcc2025.pdf' | relative_url }}">Slides</a></p></div>
      <div class="news-item"><time>Feb 2025</time><p>Gave a talk on LLM-driven privacy attacks and privacy-risk assessment at IEEE BigComp 2025.</p></div>
    </details>
  </section>

  <section id="selected-publications" class="content-section publications-preview">
    <header class="section-header section-header-row">
      <div>
        <p class="section-label">SELECTED PUBLICATIONS</p>
        <h2>Recent peer-reviewed work</h2>
      </div>
      <a class="section-link" href="{{ '/publications.html' | relative_url }}">Complete list →</a>
    </header>

    <div class="publication-item">
      <h3>OurData: Understanding Family Privacy in Sensor-Rich Homes</h3>
      <p class="publication-authors"><strong>Hyunsoo Lee</strong>, Reza Ghaiumy Anaraky, Oded Nov, Uichin Lee</p>
      <p class="publication-venue">IMWUT/UbiComp 2026</p>
      <a href="{{ '/assets/pdf/ourdata.pdf' | relative_url }}">PDF</a>
    </div>

    <div class="publication-item publication-leadership">
      <h3>Why Stressed, Mom? Exploring Family Reflection on Social and Emotional Sensor Data</h3>
      <p class="publication-authors">Hyesoo Park, Sueun Jang, <strong>Hyunsoo Lee*</strong>, Gahee Kim, Uichin Lee</p>
      <p class="publication-venue">CHI 2026 · <strong>*Corresponding author / Faculty mentor</strong></p>
      <a href="{{ '/assets/pdf/selad.pdf' | relative_url }}">PDF</a>
    </div>

    <div class="publication-item publication-leadership">
      <h3>Harnessing Home IoT for Self-Tracking Emotional Wellbeing</h3>
      <p class="publication-authors">Youngji Koh, Chanhee Lee, Eunki Joung, <strong>Hyunsoo Lee*</strong>, Uichin Lee</p>
      <p class="publication-venue">IMWUT/UbiComp 2025 · <strong>*Corresponding author / Faculty mentor</strong></p>
      <a href="{{ '/assets/pdf/pensieve.pdf' | relative_url }}">PDF</a>
    </div>
  </section>
</main>
  </div>
</div>

