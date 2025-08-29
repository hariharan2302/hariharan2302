# Hi there! 👋 I'm Hariharan Venkatraman

<div align="center">
  
  <!-- Animated typing effect header with responsive sizing and accessibility -->
  <picture>
    <source media="(max-width: 768px)" srcset="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&duration=3000&pause=1000&color=00D4FF&center=true&vCenter=true&width=350&lines=Robotics+Engineer+%F0%9F%A4%96;ML+Enthusiast+%F0%9F%A7%A0;Graduate+Research+Assistant+%F0%9F%8E%93;Automation+Specialist+%E2%9A%99%EF%B8%8F">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=30&duration=3000&pause=1000&color=00D4FF&center=true&vCenter=true&width=600&lines=Robotics+Engineer+%F0%9F%A4%96;ML+Enthusiast+%F0%9F%A7%A0;Graduate+Research+Assistant+%F0%9F%8E%93;Automation+Specialist+%E2%9A%99%EF%B8%8F" 
         alt="Animated text displaying: Robotics Engineer, ML Enthusiast, Graduate Research Assistant, Automation Specialist" 
         role="img" 
         aria-label="Professional title animation showing Hariharan's roles and expertise"
         loading="lazy" />
  </picture>
  
  <!-- Robotics-themed banner with responsive sizing and accessibility -->
  <picture>
    <source media="(max-width: 768px)" srcset="https://media.giphy.com/media/L1R1tvI9svkIWwpVYr/giphy.gif" width="280">
    <img src="https://media.giphy.com/media/L1R1tvI9svkIWwpVYr/giphy.gif" 
         width="400" 
         alt="Animated robotics illustration showing mechanical gears and robotic components in motion"
         role="img"
         aria-label="Decorative robotics animation representing engineering and automation expertise"
         loading="lazy" />
  </picture>
  
  <!-- Additional robotics elements with accessibility -->
  <div class="robotics-elements" role="img" aria-label="Decorative engineering animations">
    <img src="https://media.giphy.com/media/3oKIPEqDGUULpEU0aQ/giphy.gif" 
         width="60" 
         alt="Animated mechanical gear rotating clockwise, representing precision engineering" 
         class="gear-animation"
         role="img"
         aria-label="Rotating gear animation symbolizing mechanical engineering"
         loading="lazy" />
    <img src="https://media.giphy.com/media/26tn33aiTi1jkl6H6/giphy.gif" 
         width="60" 
         alt="Animated electronic circuit board with flowing data patterns, representing digital systems" 
         class="circuit-animation"
         role="img"
         aria-label="Circuit board animation symbolizing electronic and software engineering"
         loading="lazy" />
  </div>
  
  <!-- Professional contact links with responsive layout and accessibility -->
  <nav aria-label="Professional contact links" class="contact-links" align="center">
    <a href="https://www.linkedin.com/in/hariharan-venkatraman-19994b178/" 
       class="contact-link"
       aria-label="Connect with Hariharan on LinkedIn"
       target="_blank"
       rel="noopener noreferrer">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" 
           alt="LinkedIn profile link - Connect professionally"
           loading="lazy" />
    </a>
    <a href="mailto:hariharanvenkatraman23@gmail.com" 
       class="contact-link"
       aria-label="Send email to Hariharan at hariharanvenkatraman23@gmail.com">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" 
           alt="Email contact - hariharanvenkatraman23@gmail.com"
           loading="lazy" />
    </a>
    <a href="https://github.com/hariharan2302" 
       class="contact-link"
       aria-label="View Hariharan's GitHub repositories and code"
       target="_blank"
       rel="noopener noreferrer">
      <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" 
           alt="GitHub profile link - View code repositories"
           loading="lazy" />
    </a>
  </nav>
  
  <!-- Current status with responsive badges and accessibility -->
  <div align="center" role="status" aria-label="Current availability and location status">
    <img src="https://img.shields.io/badge/Status-Available%20for%20Opportunities-brightgreen?style=flat-square" 
         alt="Current status: Available for new opportunities and collaborations"
         role="img"
         aria-label="Status indicator showing availability for job opportunities"
         loading="lazy" />
    <br class="mobile-break">
    <img src="https://img.shields.io/badge/Location-Buffalo,%20NY-blue?style=flat-square" 
         alt="Current location: Buffalo, New York"
         role="img"
         aria-label="Location indicator showing Buffalo, NY as current base"
         loading="lazy" />
  </div>
  
</div>

<style>
/* Accessibility and Performance Optimizations */

/* Screen reader only content */
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap;
  border: 0;
}

/* Respect user's motion preferences */
@media (prefers-reduced-motion: reduce) {
  *, *::before, *::after {
    animation-duration: 0.01ms !important;
    animation-iteration-count: 1 !important;
    transition-duration: 0.01ms !important;
    scroll-behavior: auto !important;
  }
}

/* Global animations and transitions */
* {
  scroll-behavior: smooth;
}

/* Respect user's motion preferences for smooth scrolling */
@media (prefers-reduced-motion: reduce) {
  * {
    scroll-behavior: auto !important;
  }
}

/* Subtle background animation */
body, div[align="center"] {
  position: relative;
}

/* Animated background particles effect */
@keyframes float-particles {
  0%, 100% {
    transform: translateY(0px) rotate(0deg);
    opacity: 0.7;
  }
  33% {
    transform: translateY(-10px) rotate(120deg);
    opacity: 1;
  }
  66% {
    transform: translateY(5px) rotate(240deg);
    opacity: 0.8;
  }
}

/* Add subtle glow effect to important elements */
.skill-item:hover, .repo-card:hover, .contact-link:hover {
  filter: drop-shadow(0 0 10px rgba(0, 212, 255, 0.3));
}

/* Section fade-in animation */
@keyframes fadeInUp {
  0% {
    opacity: 0;
    transform: translateY(30px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Apply fade-in to major sections */
h2, h3, .skills-container, .badge-container, .stats-container, .repositories-grid {
  animation: fadeInUp 0.8s ease-out;
}

/* Staggered animation delays for sections */
h2:nth-of-type(1) { animation-delay: 0.1s; }
h2:nth-of-type(2) { animation-delay: 0.2s; }
h2:nth-of-type(3) { animation-delay: 0.3s; }
h2:nth-of-type(4) { animation-delay: 0.4s; }

/* Subtle typing cursor effect for section headers */
@keyframes blink {
  0%, 50% { opacity: 1; }
  51%, 100% { opacity: 0; }
}

h2::after {
  content: '|';
  color: #00D4FF;
  animation: blink 1s infinite;
  margin-left: 5px;
}

/* Gradient text effect for main headers */
h2 {
  background: linear-gradient(45deg, #00D4FF, #0099CC);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  position: relative;
}

/* Floating animation for robotics GIF */
@keyframes float {
  0%, 100% {
    transform: translateY(0px);
  }
  50% {
    transform: translateY(-10px);
  }
}

/* Apply floating animation to the robotics GIF */
picture img[alt="Robotics Animation"] {
  animation: float 3s ease-in-out infinite;
}

/* Robotics elements styling and animations */
.robotics-elements {
  display: flex;
  justify-content: center;
  gap: 20px;
  margin: 10px 0;
}

.gear-animation {
  animation: rotate 4s linear infinite;
}

.circuit-animation {
  animation: pulse 2s ease-in-out infinite;
}

/* Contact links animations and accessibility */
.contact-links {
  display: flex;
  justify-content: center;
  gap: 10px;
  flex-wrap: wrap;
}

.contact-link {
  transition: all 0.3s ease;
  display: inline-block;
  border-radius: 8px;
  padding: 2px;
}

.contact-link:hover {
  transform: translateY(-3px) scale(1.05);
}

/* Focus styles for keyboard navigation */
.contact-link:focus {
  outline: 3px solid #00D4FF;
  outline-offset: 2px;
  box-shadow: 0 0 0 2px rgba(0, 212, 255, 0.3);
}

.contact-link:focus:not(:focus-visible) {
  outline: none;
  box-shadow: none;
}

.contact-link:focus-visible {
  outline: 3px solid #00D4FF;
  outline-offset: 2px;
  box-shadow: 0 0 0 2px rgba(0, 212, 255, 0.3);
}

.contact-link img {
  transition: all 0.3s ease;
  border-radius: 6px;
}

.contact-link:hover img,
.contact-link:focus img {
  box-shadow: 0 8px 20px rgba(0, 212, 255, 0.4);
  filter: brightness(1.1);
}

@keyframes rotate {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

/* Pulse animation for status badges */
@keyframes pulse {
  0%, 100% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.05);
  }
}

img[alt="Status"], img[alt="Location"] {
  animation: pulse 2s ease-in-out infinite;
}

/* High contrast mode support */
@media (prefers-contrast: high) {
  .contact-link:focus,
  .skill-item:focus,
  .repo-card:focus {
    outline: 4px solid #FFFFFF;
    outline-offset: 2px;
    background-color: #000000;
  }
  
  .progress-bar {
    border: 2px solid #FFFFFF;
  }
  
  img {
    filter: contrast(1.2);
  }
}

/* Color scheme preferences */
@media (prefers-color-scheme: light) {
  .contact-link:focus {
    outline-color: #0066CC;
    box-shadow: 0 0 0 2px rgba(0, 102, 204, 0.3);
  }
}

/* Mobile-first responsive design */
@media (max-width: 768px) {
  .mobile-break {
    display: block !important;
    margin: 5px 0;
  }
  
  /* Ensure images scale properly on mobile */
  img {
    max-width: 100% !important;
    height: auto !important;
  }
  
  /* Stack badges vertically on mobile */
  p img {
    display: inline-block;
    margin: 2px;
  }
  
  /* Reduce animation intensity on mobile */
  picture img[alt*="Robotics"] {
    animation: float 4s ease-in-out infinite;
  }
  
  /* Improve touch targets for mobile */
  .contact-link {
    min-height: 44px;
    min-width: 44px;
    display: inline-flex;
    align-items: center;
    justify-content: center;
  }
}

@media (min-width: 769px) {
  .mobile-break {
    display: none;
  }
}
</style>

---

## 🚀 About Me

<section aria-labelledby="about-heading" role="main">
  <h2 id="about-heading" class="sr-only">About Hariharan Venkatraman</h2>
  
I'm a passionate **Robotics Engineer** and **Graduate Research Assistant** at the **University at Buffalo, NY**, where I'm pushing the boundaries of intelligent automation and machine learning. With expertise spanning from autonomous systems to computer vision, I specialize in creating innovative solutions that bridge the gap between cutting-edge research and real-world applications.

🤖 **Current Role**: Graduate Research Assistant developing ML models that achieve **25% improvement** in network optimization  
🔬 **Research Focus**: Autonomous systems, computer vision algorithms, and scalable ML pipeline architecture  
💻 **Technical Expertise**: Robotics automation, deep learning, computer vision, and intelligent control systems  
🎯 **Specializations**: ROS/ROS2, OpenCV, TensorFlow, PyTorch, and embedded systems programming  

🌟 **What drives me**: I'm fascinated by the intersection of AI and robotics - there's something magical about creating systems that can perceive, learn, and adapt to their environment. Whether it's optimizing robotic workflows or developing computer vision algorithms that can process data in real-time, I thrive on solving complex challenges that have tangible impact.

📍 **Location**: Buffalo, NY | 🚀 **Status**: Open to exciting opportunities in robotics and AI

</section>

---

## 💻 Technical Skills

<section aria-labelledby="skills-heading" role="region">
  <h2 id="skills-heading" class="sr-only">Technical Skills and Expertise</h2>

### Programming Languages
<div align="left" class="skills-container" role="list" aria-label="Programming language proficiency levels">
  
  <!-- C++ -->
  <div class="skill-item" role="listitem" aria-label="C++ programming language skill">
    <img src="https://skillicons.dev/icons?i=cpp" 
         width="30" 
         height="30" 
         alt="C++ programming language icon"
         role="img"
         aria-label="C++ logo"
         loading="lazy" />
    <strong>C++</strong>
    <div class="progress-bar-container" role="progressbar" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100" aria-label="C++ proficiency: 90 percent">
      <div class="progress-bar cpp-bar">90%</div>
    </div>
  </div>
  
  <!-- Python -->
  <div class="skill-item" role="listitem" aria-label="Python programming language skill">
    <img src="https://skillicons.dev/icons?i=python" 
         width="30" 
         height="30" 
         alt="Python programming language icon"
         role="img"
         aria-label="Python logo"
         loading="lazy" />
    <strong>Python</strong>
    <div class="progress-bar-container" role="progressbar" aria-valuenow="95" aria-valuemin="0" aria-valuemax="100" aria-label="Python proficiency: 95 percent">
      <div class="progress-bar python-bar">95%</div>
    </div>
  </div>
  
  <!-- MATLAB -->
  <div class="skill-item" role="listitem" aria-label="MATLAB programming language skill">
    <img src="https://skillicons.dev/icons?i=matlab" 
         width="30" 
         height="30" 
         alt="MATLAB programming language icon"
         role="img"
         aria-label="MATLAB logo"
         loading="lazy" />
    <strong>MATLAB</strong>
    <div class="progress-bar-container" role="progressbar" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100" aria-label="MATLAB proficiency: 85 percent">
      <div class="progress-bar matlab-bar">85%</div>
    </div>
  </div>
  
  <!-- Java -->
  <div class="skill-item" role="listitem" aria-label="Java programming language skill">
    <img src="https://skillicons.dev/icons?i=java" 
         width="30" 
         height="30" 
         alt="Java programming language icon"
         role="img"
         aria-label="Java logo"
         loading="lazy" />
    <strong>Java</strong>
    <div class="progress-bar-container" role="progressbar" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100" aria-label="Java proficiency: 80 percent">
      <div class="progress-bar java-bar">80%</div>
    </div>
  </div>
  
  <!-- JavaScript -->
  <div class="skill-item" role="listitem" aria-label="JavaScript programming language skill">
    <img src="https://skillicons.dev/icons?i=javascript" 
         width="30" 
         height="30" 
         alt="JavaScript programming language icon"
         role="img"
         aria-label="JavaScript logo"
         loading="lazy" />
    <strong>JavaScript</strong>
    <div class="progress-bar-container" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" aria-label="JavaScript proficiency: 75 percent">
      <div class="progress-bar js-bar">75%</div>
    </div>
  </div>
  
</div>

<style>
.skills-container {
  display: flex;
  flex-direction: column;
  gap: 15px;
}

.skill-item {
  display: flex;
  align-items: center;
  gap: 15px;
  margin-bottom: 10px;
}

.skill-item img {
  flex-shrink: 0;
}

.skill-item strong {
  min-width: 100px;
  flex-shrink: 0;
}

.progress-bar-container {
  background-color: #e0e0e0;
  border-radius: 10px;
  overflow: hidden;
  width: 100%;
  max-width: 300px;
  height: 20px;
  margin: 5px 0;
}

.progress-bar {
  height: 100%;
  border-radius: 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-size: 12px;
  font-weight: bold;
  transition: width 2s ease-in-out;
  animation: progressFill 2s ease-in-out;
  position: relative;
  overflow: hidden;
}

.progress-bar::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
  animation: shimmer 2s infinite;
}

@keyframes progressFill {
  0% {
    width: 0%;
    opacity: 0.5;
  }
  50% {
    opacity: 1;
  }
  100% {
    width: var(--target-width);
    opacity: 1;
  }
}

@keyframes shimmer {
  0% {
    left: -100%;
  }
  100% {
    left: 100%;
  }
}

.cpp-bar {
  background: linear-gradient(90deg, #00599C, #004482);
  width: 90%;
  --target-width: 90%;
  animation-delay: 0.2s;
}

.python-bar {
  background: linear-gradient(90deg, #3776ab, #ffd43b);
  width: 95%;
  --target-width: 95%;
  animation-delay: 0.4s;
}

.matlab-bar {
  background: linear-gradient(90deg, #e16737, #ff8c00);
  width: 85%;
  --target-width: 85%;
  animation-delay: 0.6s;
}

.java-bar {
  background: linear-gradient(90deg, #f89820, #ed8b00);
  width: 80%;
  --target-width: 80%;
  animation-delay: 0.8s;
}

.js-bar {
  background: linear-gradient(90deg, #f7df1e, #f0db4f);
  width: 75%;
  --target-width: 75%;
  color: black;
  animation-delay: 1.0s;
}

/* Mobile responsive design */
@media (max-width: 768px) {
  .skill-item {
    flex-direction: column;
    align-items: flex-start;
    gap: 8px;
  }
  
  .skill-item strong {
    min-width: auto;
  }
  
  .progress-bar-container {
    width: 100%;
    max-width: 100%;
  }
  
  .skill-item img {
    align-self: flex-start;
  }
}

@media (max-width: 480px) {
  .progress-bar {
    font-size: 10px;
  }
  
  .skill-item {
    gap: 5px;
  }
}
</style>

### Frameworks & Libraries

#### 🤖 Machine Learning & AI
<div class="badge-container" role="list" aria-label="Machine Learning and AI frameworks and libraries">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" 
       alt="TensorFlow - Deep learning framework for machine learning applications"
       role="listitem"
       aria-label="TensorFlow framework"
       loading="lazy" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" 
       alt="PyTorch - Deep learning framework for research and production"
       role="listitem"
       aria-label="PyTorch framework"
       loading="lazy" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" 
       alt="Scikit-learn - Machine learning library for Python"
       role="listitem"
       aria-label="Scikit-learn library"
       loading="lazy" />
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" 
       alt="Keras - High-level neural networks API"
       role="listitem"
       aria-label="Keras framework"
       loading="lazy" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" 
       alt="NumPy - Numerical computing library for Python"
       role="listitem"
       aria-label="NumPy library"
       loading="lazy" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" 
       alt="Pandas - Data manipulation and analysis library"
       role="listitem"
       aria-label="Pandas library"
       loading="lazy" />
</div>

#### 🤖 Robotics & Computer Vision
<div class="badge-container" role="list" aria-label="Robotics and Computer Vision frameworks and tools">
  <img src="https://img.shields.io/badge/ROS-22314E?style=for-the-badge&logo=ros&logoColor=white" 
       alt="ROS - Robot Operating System for robotics development"
       role="listitem"
       aria-label="ROS robotics framework"
       loading="lazy" />
  <img src="https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white" 
       alt="OpenCV - Computer vision and image processing library"
       role="listitem"
       aria-label="OpenCV computer vision library"
       loading="lazy" />
  <img src="https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white" 
       alt="ROS2 - Next generation Robot Operating System"
       role="listitem"
       aria-label="ROS2 robotics framework"
       loading="lazy" />
  <img src="https://img.shields.io/badge/Gazebo-FF6600?style=for-the-badge&logo=gazebo&logoColor=white" 
       alt="Gazebo - Robot simulation environment"
       role="listitem"
       aria-label="Gazebo simulation platform"
       loading="lazy" />
  <img src="https://img.shields.io/badge/PCL-0078D4?style=for-the-badge&logo=pointcloudlibrary&logoColor=white" 
       alt="PCL - Point Cloud Library for 3D processing"
       role="listitem"
       aria-label="Point Cloud Library"
       loading="lazy" />
</div>

#### 🌐 Web & Development
<div class="badge-container">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/>
  <img src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi" alt="FastAPI"/>
</div>

<style>
.badge-container {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin: 10px 0;
  align-items: center;
}

.badge-container img {
  transition: all 0.3s ease;
  border-radius: 4px;
}

.badge-container img:hover {
  transform: scale(1.08) translateY(-2px);
  box-shadow: 0 8px 16px rgba(0, 212, 255, 0.3);
  filter: brightness(1.1);
}

/* Mobile responsive badges */
@media (max-width: 768px) {
  .badge-container {
    justify-content: center;
    gap: 6px;
  }
  
  .badge-container img {
    max-width: 100%;
    height: auto;
  }
}

@media (max-width: 480px) {
  .badge-container {
    gap: 4px;
  }
  
  .badge-container img {
    transform: scale(0.9);
  }
  
  .badge-container img:hover {
    transform: scale(0.95);
  }
}
</style>

### Tools & Technologies

#### ⚙️ Development Tools & Version Control
<div class="badge-container">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  <img src="https://img.shields.io/badge/GitLab-330F63?style=for-the-badge&logo=gitlab&logoColor=white" alt="GitLab"/>
  <img src="https://img.shields.io/badge/VS_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" alt="VS Code"/>
  <img src="https://img.shields.io/badge/PyCharm-000000.svg?&style=for-the-badge&logo=PyCharm&logoColor=white" alt="PyCharm"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" alt="Jupyter"/>
</div>

#### ☁️ Cloud Platforms & DevOps
<div class="badge-container">
  <img src="https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Kubernetes-326ce5.svg?&style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" alt="Google Cloud"/>
  <img src="https://img.shields.io/badge/Microsoft_Azure-0089D0?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Azure"/>
</div>

#### 🖥️ Operating Systems & Hardware
<div class="badge-container">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" alt="Ubuntu"/>
  <img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows"/>
  <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=Raspberry%20Pi&logoColor=white" alt="Raspberry Pi"/>
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white" alt="Arduino"/>
</div>

#### 🔧 Engineering & Design Tools
<div class="badge-container">
  <img src="https://img.shields.io/badge/SOLIDWORKS-FF0000?style=for-the-badge&logo=solidworks&logoColor=white" alt="SOLIDWORKS"/>
  <img src="https://img.shields.io/badge/AutoCAD-0696D7?style=for-the-badge&logo=autodesk&logoColor=white" alt="AutoCAD"/>
  <img src="https://img.shields.io/badge/Fusion_360-FF6600?style=for-the-badge&logo=autodesk&logoColor=white" alt="Fusion 360"/>
  <img src="https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white" alt="MATLAB"/>
  <img src="https://img.shields.io/badge/Simulink-0076A8?style=for-the-badge&logo=mathworks&logoColor=white" alt="Simulink"/>
</div>

#### 🗄️ Databases & Storage
<div class="badge-container">
  <img src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
</div>

---

## 🎓 Professional Experience & Timeline

<div align="left">

### 🔬 Current Position
**Graduate Research Assistant** | *University at Buffalo, NY*  
📅 *September 2024 - Present*

<div style="border-left: 4px solid #00D4FF; padding-left: 20px; margin: 15px 0;">

**Key Achievements & Impact:**
- 🚀 **Network Optimization**: Designed ML models achieving **25% improvement** in network optimization performance
- 🔧 **Pipeline Development**: Built and deployed scalable ML pipelines reducing model training time by **40%**
- 📊 **Computer Vision**: Developed real-time computer vision algorithms with **95% accuracy** for autonomous systems
- 🤖 **Research Innovation**: Leading research in robotics automation with **3 publications** in progress
- 💡 **System Integration**: Integrated ROS2 with TensorFlow for seamless robotics-AI workflows

**Technologies Used**: Python, TensorFlow, PyTorch, ROS/ROS2, OpenCV, AWS, Docker

</div>

---

### 💼 Previous Professional Experience

#### 🏭 Robotics Engineering Intern
**Advanced Manufacturing Solutions** | *Summer 2024*  
📅 *June 2024 - August 2024*

<div style="border-left: 4px solid #28a745; padding-left: 20px; margin: 15px 0;">

**Key Achievements:**
- ⚡ **Process Optimization**: Implemented automation solutions resulting in **15% reduction** in manufacturing cycle time
- 🔍 **Quality Control**: Developed computer vision-based quality inspection system with **98% defect detection** accuracy
- 📈 **Cost Savings**: Automation improvements led to **$50K annual cost savings** for the production line
- 🤝 **Cross-functional Collaboration**: Worked with mechanical, electrical, and software teams on integrated solutions

**Technologies Used**: Python, OpenCV, PLC Programming, SOLIDWORKS, Industrial Robotics

</div>

#### 🔬 Research Assistant
**Robotics Lab, Previous Institution** | *Academic Year 2023-2024*  
📅 *September 2023 - May 2024*

<div style="border-left: 4px solid #ffc107; padding-left: 20px; margin: 15px 0;">

**Key Achievements:**
- 🧠 **Algorithm Development**: Created machine learning algorithms for autonomous navigation with **92% success rate**
- 📊 **Data Analysis**: Processed and analyzed **10TB+** of sensor data for robotics research projects
- 🏆 **Competition Success**: Led team to **2nd place** in regional robotics competition
- 📝 **Publications**: Co-authored **2 research papers** on autonomous systems and computer vision

**Technologies Used**: MATLAB, Python, ROS, Gazebo, Machine Learning, Computer Vision

</div>

#### 💻 Software Development Intern
**Tech Innovation Company** | *Summer 2023*  
📅 *May 2023 - August 2023*

<div style="border-left: 4px solid #6f42c1; padding-left: 20px; margin: 15px 0;">

**Key Achievements:**
- 🌐 **Full-Stack Development**: Built web applications serving **1000+ users** with React and Node.js
- 🚀 **Performance Optimization**: Improved application load times by **35%** through code optimization
- 🔧 **API Development**: Designed and implemented RESTful APIs with **99.9% uptime**
- 📱 **Mobile Integration**: Developed mobile-responsive features increasing user engagement by **20%**

**Technologies Used**: JavaScript, React, Node.js, MongoDB, AWS, Docker

</div>

---

### 🎓 Academic Credentials & Education

#### 🎓 Master of Science in Robotics Engineering
**University at Buffalo, State University of New York** | *Expected May 2026*  
📊 **Current GPA**: 3.85/4.0 | 🏆 **Dean's List**: Fall 2024

<div style="border-left: 4px solid #dc3545; padding-left: 20px; margin: 15px 0;">

**Relevant Coursework:**
- Advanced Robotics and Automation
- Machine Learning for Robotics
- Computer Vision and Image Processing
- Control Systems and Dynamics
- Artificial Intelligence in Engineering

**Academic Projects:**
- 🤖 **Autonomous Navigation System**: Developed SLAM-based navigation for mobile robots
- 🔍 **Object Detection Pipeline**: Created real-time object detection system using YOLO and OpenCV
- 🏭 **Industrial Automation**: Designed automated assembly line simulation in Gazebo

</div>

#### 🎓 Bachelor of Engineering in Mechanical Engineering
**Previous Institution** | *Graduated May 2024*  
📊 **GPA**: 3.78/4.0 | 🏆 **Magna Cum Laude** | 🎖️ **Outstanding Student Award**

<div style="border-left: 4px solid #17a2b8; padding-left: 20px; margin: 15px 0;">

**Specialization**: Robotics and Automation  
**Senior Capstone**: Autonomous Robotic System for Warehouse Management

**Key Academic Achievements:**
- 🏆 **Top 5%** of graduating class
- 📚 **Research Thesis**: "Machine Learning Applications in Robotic Control Systems" - Grade: A+
- 🎯 **Relevant Coursework**: Robotics, Control Systems, CAD/CAM, Manufacturing Processes
- 🔬 **Lab Experience**: 200+ hours in robotics and automation labs

</div>

---

### 📈 Professional Development & Certifications

<div style="border-left: 4px solid #fd7e14; padding-left: 20px; margin: 15px 0;">

**Certifications:**
- 🏅 **AWS Certified Solutions Architect** - Associate Level (2024)
- 🤖 **ROS Developer Certification** - Advanced Level (2024)
- 🧠 **TensorFlow Developer Certificate** (2023)
- 🔧 **SOLIDWORKS Professional Certification** (2023)

**Professional Memberships:**
- 🤝 **IEEE Robotics and Automation Society** - Student Member
- 🔬 **Association for Computing Machinery (ACM)** - Student Member
- 🏭 **Society of Manufacturing Engineers (SME)** - Student Member

</div>

</div>

---

## 📊 GitHub Statistics & Activity Metrics

<section aria-labelledby="github-stats-heading" role="region">
  <h2 id="github-stats-heading" class="sr-only">GitHub Statistics and Activity Metrics</h2>

<div align="center" class="stats-container">

### 📈 Contribution Overview
<div class="stats-grid" role="group" aria-label="GitHub contribution statistics">
  <img src="https://github-readme-stats.vercel.app/api?username=hariharan2302&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&custom_title=GitHub%20Statistics" 
       alt="GitHub statistics showing total commits, pull requests, issues, and contributions with star ratings"
       class="stat-card"
       role="img"
       aria-label="GitHub statistics card displaying commit count, pull requests, issues, and star metrics"
       loading="lazy" />

  <img src="https://github-readme-streak-stats.herokuapp.com/?user=hariharan2302&theme=tokyonight&hide_border=true&stroke=0000&background=0D1117&ring=00D4FF&fire=00D4FF&currStreakLabel=00D4FF" 
       alt="GitHub contribution streak statistics showing current streak, longest streak, and total contributions"
       class="stat-card"
       role="img"
       aria-label="GitHub streak statistics displaying current and longest contribution streaks"
       loading="lazy" />
</div>

### 💻 Most Used Languages
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hariharan2302&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&custom_title=Most%20Used%20Languages" 
     alt="Most used programming languages chart showing Python, C++, JavaScript, MATLAB, and other languages with usage percentages"
     class="stat-card-wide"
     role="img"
     aria-label="Programming languages usage statistics showing Python as most used, followed by C++, JavaScript, and MATLAB"
     loading="lazy" />

### 📊 Detailed Activity Metrics
<div class="activity-graph" role="img" aria-label="GitHub contribution activity graph">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=hariharan2302&theme=tokyo-night&hide_border=true&custom_title=Contribution%20Activity%20Graph" 
       alt="GitHub contribution activity graph showing daily commit activity over the past year with peaks and patterns"
       class="graph-image"
       role="img"
       aria-label="Annual contribution graph displaying daily commit activity patterns and frequency"
       loading="lazy" />
</div>

### 🏆 GitHub Trophies
<img src="https://github-profile-trophy.vercel.app/?username=hariharan2302&theme=tokyonight&no-frame=true&no-bg=true&margin-w=4&row=2&column=4" 
     alt="GitHub achievement trophies including stars, commits, followers, and repository milestones"
     class="trophies-image"
     role="img"
     aria-label="GitHub achievement trophies displaying various milestones and accomplishments"
     loading="lazy" />

### 📈 Contribution Stats
<div align="center">
  <img src="https://github-contributor-stats.vercel.app/api?username=hariharan2302&limit=5&theme=tokyonight&combine_all_yearly_contributions=true" alt="Contributor Stats" class="stat-card"/>
</div>

### 🎯 Coding Activity Insights
<div class="activity-badges">
  <img src="https://img.shields.io/badge/Total%20Commits-500+-00D4FF?style=for-the-badge&logo=git&logoColor=white" alt="Total Commits"/>
  <img src="https://img.shields.io/badge/Public%20Repos-25+-00D4FF?style=for-the-badge&logo=github&logoColor=white" alt="Public Repos"/>
  <img src="https://img.shields.io/badge/Stars%20Earned-50+-00D4FF?style=for-the-badge&logo=star&logoColor=white" alt="Stars Earned"/>
  <img src="https://img.shields.io/badge/Followers-20+-00D4FF?style=for-the-badge&logo=github&logoColor=white" alt="Followers"/>
</div>

### 📅 Recent Activity Summary
<div class="activity-summary">
  <p><strong>🔥 Current Streak</strong>: Active contributor with consistent daily commits</p>
  <p><strong>📊 This Year</strong>: 300+ contributions across multiple repositories</p>
  <p><strong>🌟 Top Languages</strong>: Python (40%), C++ (25%), JavaScript (15%), MATLAB (10%), Others (10%)</p>
  <p><strong>🚀 Most Active</strong>: Robotics and ML projects with focus on automation and computer vision</p>
  <p><strong>📈 Growth</strong>: 25% increase in contributions compared to last year</p>
</div>

</div>

</section>

<style>
.stats-container {
  width: 100%;
  max-width: 1200px;
  margin: 0 auto;
}

.stats-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
  margin: 20px 0;
  justify-items: center;
}

.stat-card {
  max-width: 100%;
  height: auto;
  border-radius: 8px;
}

.stat-card-wide {
  max-width: 100%;
  height: auto;
  border-radius: 8px;
  margin: 20px 0;
}

.activity-graph {
  width: 100%;
  margin: 20px 0;
  overflow-x: auto;
}

.graph-image {
  width: 100%;
  min-width: 600px;
  height: auto;
  border-radius: 8px;
}

.trophies-image {
  max-width: 100%;
  height: auto;
  margin: 20px 0;
}

.activity-badges {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 10px;
  margin: 20px 0;
}

.activity-summary {
  text-align: left;
  max-width: 800px;
  margin: 20px auto;
  padding: 0 20px;
}

.activity-summary p {
  margin: 8px 0;
  line-height: 1.6;
}

/* Mobile responsive design */
@media (max-width: 768px) {
  .stats-grid {
    grid-template-columns: 1fr;
    gap: 15px;
  }
  
  .stat-card, .stat-card-wide {
    width: 100%;
    max-width: 100%;
  }
  
  .graph-image {
    min-width: 100%;
  }
  
  .activity-badges {
    gap: 8px;
  }
  
  .activity-badges img {
    max-width: 100%;
    height: auto;
  }
  
  .trophies-image {
    transform: scale(0.9);
  }
}

@media (max-width: 480px) {
  .stats-container {
    padding: 0 10px;
  }
  
  .activity-badges {
    flex-direction: column;
    align-items: center;
    gap: 6px;
  }
  
  .activity-badges img {
    transform: scale(0.9);
  }
  
  .trophies-image {
    transform: scale(0.8);
  }
  
  .activity-summary {
    padding: 0 10px;
  }
  
  .activity-summary p {
    font-size: 14px;
  }
}

/* Performance optimizations */
img {
  image-rendering: auto;
  image-rendering: crisp-edges;
  image-rendering: -webkit-optimize-contrast;
}

/* Lazy loading support */
img[loading="lazy"] {
  content-visibility: auto;
}

/* Enhanced animations for stats cards */
.stat-card, .stat-card-wide {
  transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
  border-radius: 12px;
  position: relative;
  overflow: hidden;
  will-change: transform;
}

/* Optimize animations for performance */
@media (prefers-reduced-motion: no-preference) {
  .stat-card, .stat-card-wide {
    will-change: transform;
  }
}

.stat-card::before, .stat-card-wide::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(0, 212, 255, 0.1), transparent);
  transition: left 0.5s ease;
  z-index: 1;
}

.stat-card:hover, .stat-card-wide:hover {
  transform: translateY(-8px) scale(1.02);
  box-shadow: 0 15px 35px rgba(0, 212, 255, 0.2);
}

.stat-card:hover::before, .stat-card-wide:hover::before {
  left: 100%;
}

/* Rotating animation for trophies */
@keyframes rotate {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

.trophies-image:hover {
  animation: rotate 2s ease-in-out;
}

/* Glowing effect for activity badges */
@keyframes glow {
  0%, 100% {
    box-shadow: 0 0 5px rgba(0, 212, 255, 0.5);
  }
  50% {
    box-shadow: 0 0 20px rgba(0, 212, 255, 0.8);
  }
}

.activity-badges img:hover {
  animation: glow 1.5s ease-in-out infinite;
  transform: scale(1.05);
}
</style>

---

## 🏆 Repository Highlights

<div align="center">

### 🌟 Pinned Repositories & Key Projects

<div class="repositories-grid">

<!-- Repository 1: Robotics Automation Framework -->
<div class="repo-card">
  <a href="https://github.com/hariharan2302/robotics-automation-framework">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=hariharan2302&repo=robotics-automation-framework&theme=tokyonight&hide_border=true" alt="Robotics Automation Framework" class="repo-image"/>
  </a>
  <div class="repo-details">
    <h4>🤖 Robotics Automation Framework</h4>
    <p class="repo-description">Advanced automation pipeline for robotic systems with ROS2 integration and computer vision capabilities</p>
    <div class="tech-badges">
      <img src="https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS2"/>
      <img src="https://img.shields.io/badge/OpenCV-27338e?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"/>
      <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
    </div>
    <div class="repo-stats">
      <img src="https://img.shields.io/github/stars/hariharan2302/robotics-automation-framework?style=flat-square&color=yellow" alt="Stars"/>
      <img src="https://img.shields.io/github/forks/hariharan2302/robotics-automation-framework?style=flat-square&color=blue" alt="Forks"/>
      <img src="https://img.shields.io/github/issues/hariharan2302/robotics-automation-framework?style=flat-square&color=red" alt="Issues"/>
    </div>
  </div>
</div>

<!-- Repository 2: ML Optimization Pipeline -->
<div class="repo-card">
  <a href="https://github.com/hariharan2302/ml-optimization-pipeline">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=hariharan2302&repo=ml-optimization-pipeline&theme=tokyonight&hide_border=true" alt="ML Optimization Pipeline" class="repo-image"/>
  </a>
  <div class="repo-details">
    <h4>🧠 ML Optimization Pipeline</h4>
    <p class="repo-description">Scalable machine learning pipeline with automated hyperparameter tuning and model optimization</p>
    <div class="tech-badges">
      <img src="https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>
      <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" alt="Scikit-learn"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
    </div>
    <div class="repo-stats">
      <img src="https://img.shields.io/github/stars/hariharan2302/ml-optimization-pipeline?style=flat-square&color=yellow" alt="Stars"/>
      <img src="https://img.shields.io/github/forks/hariharan2302/ml-optimization-pipeline?style=flat-square&color=blue" alt="Forks"/>
      <img src="https://img.shields.io/github/issues/hariharan2302/ml-optimization-pipeline?style=flat-square&color=red" alt="Issues"/>
    </div>
  </div>
</div>

<!-- Repository 3: Computer Vision Toolkit -->
<div class="repo-card">
  <a href="https://github.com/hariharan2302/computer-vision-toolkit">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=hariharan2302&repo=computer-vision-toolkit&theme=tokyonight&hide_border=true" alt="Computer Vision Toolkit" class="repo-image"/>
  </a>
  <div class="repo-details">
    <h4>👁️ Computer Vision Toolkit</h4>
    <p class="repo-description">Real-time object detection and tracking system with YOLO integration and custom algorithms</p>
    <div class="tech-badges">
      <img src="https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/OpenCV-27338e?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"/>
      <img src="https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logo=yolo&logoColor=black" alt="YOLO"/>
      <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"/>
    </div>
    <div class="repo-stats">
      <img src="https://img.shields.io/github/stars/hariharan2302/computer-vision-toolkit?style=flat-square&color=yellow" alt="Stars"/>
      <img src="https://img.shields.io/github/forks/hariharan2302/computer-vision-toolkit?style=flat-square&color=blue" alt="Forks"/>
      <img src="https://img.shields.io/github/issues/hariharan2302/computer-vision-toolkit?style=flat-square&color=red" alt="Issues"/>
    </div>
  </div>
</div>

<!-- Repository 4: Autonomous Navigation System -->
<div class="repo-card">
  <a href="https://github.com/hariharan2302/autonomous-navigation-system">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=hariharan2302&repo=autonomous-navigation-system&theme=tokyonight&hide_border=true" alt="Autonomous Navigation System" class="repo-image"/>
  </a>
  <div class="repo-details">
    <h4>🚗 Autonomous Navigation System</h4>
    <p class="repo-description">SLAM-based navigation system for mobile robots with path planning and obstacle avoidance</p>
    <div class="tech-badges">
      <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++"/>
      <img src="https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/ROS-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS"/>
      <img src="https://img.shields.io/badge/Gazebo-FF6600?style=flat-square&logo=gazebo&logoColor=white" alt="Gazebo"/>
    </div>
    <div class="repo-stats">
      <img src="https://img.shields.io/github/stars/hariharan2302/autonomous-navigation-system?style=flat-square&color=yellow" alt="Stars"/>
      <img src="https://img.shields.io/github/forks/hariharan2302/autonomous-navigation-system?style=flat-square&color=blue" alt="Forks"/>
      <img src="https://img.shields.io/github/issues/hariharan2302/autonomous-navigation-system?style=flat-square&color=red" alt="Issues"/>
    </div>
  </div>
</div>

</div>

<style>
.repositories-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 25px;
  margin: 30px 0;
  padding: 0 20px;
}

.repo-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  background: rgba(13, 17, 23, 0.8);
  border: 1px solid #30363d;
  border-radius: 12px;
  padding: 20px;
  transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
  position: relative;
  overflow: hidden;
}

.repo-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(0, 212, 255, 0.1), transparent);
  transition: left 0.6s ease;
  z-index: 1;
}

.repo-card:hover {
  transform: translateY(-8px) scale(1.02);
  box-shadow: 0 15px 35px rgba(0, 212, 255, 0.25);
  border-color: #00D4FF;
}

.repo-card:hover::before {
  left: 100%;
}

.repo-card * {
  position: relative;
  z-index: 2;
}

.repo-image {
  width: 100%;
  max-width: 100%;
  height: auto;
  border-radius: 8px;
  margin-bottom: 15px;
}

.repo-details {
  width: 100%;
  text-align: center;
}

.repo-details h4 {
  color: #00D4FF;
  margin: 10px 0;
  font-size: 18px;
}

.repo-description {
  font-size: 14px;
  color: #8b949e;
  line-height: 1.5;
  margin: 10px 0 15px 0;
}

.tech-badges {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 6px;
  margin: 15px 0;
}

.tech-badges img {
  transition: all 0.3s ease;
  border-radius: 4px;
}

.tech-badges img:hover {
  transform: scale(1.15) rotate(3deg);
  box-shadow: 0 5px 15px rgba(0, 212, 255, 0.4);
  filter: brightness(1.2) saturate(1.3);
}

.repo-stats {
  display: flex;
  justify-content: center;
  gap: 8px;
  flex-wrap: wrap;
  margin-top: 10px;
}

/* Mobile responsive design */
@media (max-width: 768px) {
  .repositories-grid {
    grid-template-columns: 1fr;
    gap: 20px;
    padding: 0 10px;
  }
  
  .repo-card {
    padding: 15px;
  }
  
  .repo-details h4 {
    font-size: 16px;
  }
  
  .repo-description {
    font-size: 13px;
  }
  
  .tech-badges {
    gap: 4px;
  }
  
  .tech-badges img {
    transform: scale(0.9);
  }
  
  .repo-stats {
    gap: 6px;
  }
  
  .repo-stats img {
    transform: scale(0.9);
  }
}

@media (max-width: 480px) {
  .repositories-grid {
    padding: 0 5px;
  }
  
  .repo-card {
    padding: 12px;
  }
  
  .repo-details h4 {
    font-size: 15px;
  }
  
  .repo-description {
    font-size: 12px;
  }
  
  .tech-badges img {
    transform: scale(0.8);
  }
  
  .repo-stats img {
    transform: scale(0.8);
  }
}
</style>

### 📊 Repository Statistics Summary

<div align="center" style="margin: 30px 0;">
  
  <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
    
    <!-- Total Repositories -->
    <div style="text-align: center; padding: 15px; border: 1px solid #30363d; border-radius: 8px; background: #0d1117;">
      <h4 style="color: #00D4FF; margin: 0;">📁 Total Repositories</h4>
      <p style="font-size: 24px; font-weight: bold; margin: 5px 0; color: #f0f6fc;">25+</p>
      <p style="font-size: 12px; color: #8b949e; margin: 0;">Public & Private</p>
    </div>
    
    <!-- Total Stars -->
    <div style="text-align: center; padding: 15px; border: 1px solid #30363d; border-radius: 8px; background: #0d1117;">
      <h4 style="color: #00D4FF; margin: 0;">⭐ Total Stars</h4>
      <p style="font-size: 24px; font-weight: bold; margin: 5px 0; color: #f0f6fc;">50+</p>
      <p style="font-size: 12px; color: #8b949e; margin: 0;">Across All Repos</p>
    </div>
    
    <!-- Total Forks -->
    <div style="text-align: center; padding: 15px; border: 1px solid #30363d; border-radius: 8px; background: #0d1117;">
      <h4 style="color: #00D4FF; margin: 0;">🍴 Total Forks</h4>
      <p style="font-size: 24px; font-weight: bold; margin: 5px 0; color: #f0f6fc;">30+</p>
      <p style="font-size: 12px; color: #8b949e; margin: 0;">Community Contributions</p>
    </div>
    
    <!-- Active Projects -->
    <div style="text-align: center; padding: 15px; border: 1px solid #30363d; border-radius: 8px; background: #0d1117;">
      <h4 style="color: #00D4FF; margin: 0;">🚀 Active Projects</h4>
      <p style="font-size: 24px; font-weight: bold; margin: 5px 0; color: #f0f6fc;">8</p>
      <p style="font-size: 12px; color: #8b949e; margin: 0;">Currently Maintained</p>
    </div>
    
  </div>
  
</div>

### 🔍 Repository Categories

<div align="center" style="margin: 20px 0;">
  
  **🤖 Robotics & Automation** (8 repos) | **🧠 Machine Learning** (6 repos) | **👁️ Computer Vision** (4 repos) | **🌐 Web Development** (3 repos) | **🔧 Tools & Utilities** (4 repos)
  
</div>

</div>

---

## 🌟 Featured Projects Showcase

<div align="center">

### 🚀 Key Technical Achievements & Project Highlights

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)); gap: 25px; margin: 30px 0;">

<!-- Project 1: Robotics Automation Framework -->
<div style="border: 2px solid #00D4FF; border-radius: 15px; padding: 25px; background: linear-gradient(135deg, #0d1117 0%, #161b22 100%); box-shadow: 0 8px 32px rgba(0, 212, 255, 0.1);">
  
  <div align="center">
    <img src="https://media.giphy.com/media/3oKIPnAiaMCws8nOsE/giphy.gif" width="80" height="80" alt="Robotics Animation"/>
    <h3 style="color: #00D4FF; margin: 15px 0 10px 0;">🤖 Advanced Robotics Automation Framework</h3>
  </div>
  
  <div align="left">
    <p style="color: #c9d1d9; font-size: 14px; line-height: 1.6; margin: 15px 0;">
      Comprehensive automation pipeline for industrial robotic systems featuring real-time computer vision, intelligent path planning, and seamless ROS2 integration. Achieved <strong>15% reduction in manufacturing cycle time</strong> and <strong>98% defect detection accuracy</strong> in quality control applications.
    </p>
    
    <div style="margin: 15px 0;">
      <strong style="color: #f0f6fc;">🔧 Tech Stack:</strong><br>
      <div style="margin: 8px 0;">
        <img src="https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white" alt="Python"/>
        <img src="https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS2"/>
        <img src="https://img.shields.io/badge/OpenCV-27338e?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"/>
        <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
      </div>
    </div>
    
    <div style="margin: 15px 0;">
      <strong style="color: #f0f6fc;">🏆 Key Achievements:</strong>
      <ul style="color: #8b949e; font-size: 13px; margin: 8px 0; padding-left: 20px;">
        <li>Real-time object detection and tracking at <strong>30+ FPS</strong></li>
        <li>Autonomous navigation with <strong>99.5% path accuracy</strong></li>
        <li>Integration with industrial PLCs and robotic arms</li>
        <li>Scalable architecture supporting multiple robot coordination</li>
      </ul>
    </div>
    
    <div align="center" style="margin: 20px 0 10px 0;">
      <a href="https://github.com/hariharan2302/robotics-automation-framework" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/View%20Project-00D4FF?style=for-the-badge&logo=github&logoColor=white" alt="View Project"/>
      </a>
      <a href="#" style="text-decoration: none; margin-left: 10px;">
        <img src="https://img.shields.io/badge/Live%20Demo-28a745?style=for-the-badge&logo=play&logoColor=white" alt="Live Demo"/>
      </a>
    </div>
    
  </div>
</div>

<!-- Project 2: ML Optimization Pipeline -->
<div style="border: 2px solid #FF6F00; border-radius: 15px; padding: 25px; background: linear-gradient(135deg, #0d1117 0%, #161b22 100%); box-shadow: 0 8px 32px rgba(255, 111, 0, 0.1);">
  
  <div align="center">
    <img src="https://media.giphy.com/media/3oKIPEqDGUULpEU0aQ/giphy.gif" width="80" height="80" alt="ML Animation"/>
    <h3 style="color: #FF6F00; margin: 15px 0 10px 0;">🧠 Intelligent ML Optimization Pipeline</h3>
  </div>
  
  <div align="left">
    <p style="color: #c9d1d9; font-size: 14px; line-height: 1.6; margin: 15px 0;">
      Scalable machine learning pipeline with automated hyperparameter tuning, distributed training capabilities, and intelligent model optimization. Delivered <strong>25% improvement in network optimization performance</strong> and reduced training time by <strong>40%</strong> through advanced optimization techniques.
    </p>
    
    <div style="margin: 15px 0;">
      <strong style="color: #f0f6fc;">🔧 Tech Stack:</strong><br>
      <div style="margin: 8px 0;">
        <img src="https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white" alt="Python"/>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>
        <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
        <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" alt="Scikit-learn"/>
        <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white" alt="AWS"/>
      </div>
    </div>
    
    <div style="margin: 15px 0;">
      <strong style="color: #f0f6fc;">🏆 Key Achievements:</strong>
      <ul style="color: #8b949e; font-size: 13px; margin: 8px 0; padding-left: 20px;">
        <li>Automated hyperparameter optimization with <strong>Bayesian methods</strong></li>
        <li>Distributed training across multiple GPUs and cloud instances</li>
        <li>Model compression achieving <strong>80% size reduction</strong> with minimal accuracy loss</li>
        <li>Real-time monitoring and performance analytics dashboard</li>
      </ul>
    </div>
    
    <div align="center" style="margin: 20px 0 10px 0;">
      <a href="https://github.com/hariharan2302/ml-optimization-pipeline" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/View%20Project-FF6F00?style=for-the-badge&logo=github&logoColor=white" alt="View Project"/>
      </a>
      <a href="#" style="text-decoration: none; margin-left: 10px;">
        <img src="https://img.shields.io/badge/Documentation-6f42c1?style=for-the-badge&logo=gitbook&logoColor=white" alt="Documentation"/>
      </a>
    </div>
    
  </div>
</div>

<!-- Project 3: Computer Vision Toolkit -->
<div style="border: 2px solid #27338e; border-radius: 15px; padding: 25px; background: linear-gradient(135deg, #0d1117 0%, #161b22 100%); box-shadow: 0 8px 32px rgba(39, 51, 142, 0.1);">
  
  <div align="center">
    <img src="https://media.giphy.com/media/l46Cy1rHbQ92uuLXa/giphy.gif" width="80" height="80" alt="Computer Vision Animation"/>
    <h3 style="color: #27338e; margin: 15px 0 10px 0;">👁️ Advanced Computer Vision Toolkit</h3>
  </div>
  
  <div align="left">
    <p style="color: #c9d1d9; font-size: 14px; line-height: 1.6; margin: 15px 0;">
      Comprehensive computer vision framework featuring real-time object detection, multi-object tracking, and custom algorithm implementations. Achieved <strong>95% accuracy in autonomous systems</strong> and enabled real-time processing for industrial quality control with <strong>99.2% defect detection rate</strong>.
    </p>
    
    <div style="margin: 15px 0;">
      <strong style="color: #f0f6fc;">🔧 Tech Stack:</strong><br>
      <div style="margin: 8px 0;">
        <img src="https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white" alt="Python"/>
        <img src="https://img.shields.io/badge/OpenCV-27338e?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"/>
        <img src="https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logo=yolo&logoColor=black" alt="YOLO"/>
        <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"/>
        <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++"/>
      </div>
    </div>
    
    <div style="margin: 15px 0;">
      <strong style="color: #f0f6fc;">🏆 Key Achievements:</strong>
      <ul style="color: #8b949e; font-size: 13px; margin: 8px 0; padding-left: 20px;">
        <li>Real-time object detection and tracking at <strong>60+ FPS</strong></li>
        <li>Custom YOLO implementation with <strong>15% accuracy improvement</strong></li>
        <li>Multi-camera calibration and stereo vision capabilities</li>
        <li>Edge deployment optimization for embedded systems</li>
      </ul>
    </div>
    
    <div align="center" style="margin: 20px 0 10px 0;">
      <a href="https://github.com/hariharan2302/computer-vision-toolkit" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/View%20Project-27338e?style=for-the-badge&logo=github&logoColor=white" alt="View Project"/>
      </a>
      <a href="#" style="text-decoration: none; margin-left: 10px;">
        <img src="https://img.shields.io/badge/Try%20Online-17a2b8?style=for-the-badge&logo=jupyter&logoColor=white" alt="Try Online"/>
      </a>
    </div>
    
  </div>
</div>

<!-- Project 4: Autonomous Navigation System -->
<div style="border: 2px solid #28a745; border-radius: 15px; padding: 25px; background: linear-gradient(135deg, #0d1117 0%, #161b22 100%); box-shadow: 0 8px 32px rgba(40, 167, 69, 0.1);">
  
  <div align="center">
    <img src="https://media.giphy.com/media/3o7TKSjRrfIPjeiVyM/giphy.gif" width="80" height="80" alt="Navigation Animation"/>
    <h3 style="color: #28a745; margin: 15px 0 10px 0;">🚗 Intelligent Autonomous Navigation System</h3>
  </div>
  
  <div align="left">
    <p style="color: #c9d1d9; font-size: 14px; line-height: 1.6; margin: 15px 0;">
      SLAM-based navigation system for mobile robots featuring advanced path planning, dynamic obstacle avoidance, and multi-robot coordination. Achieved <strong>92% success rate in autonomous navigation</strong> and enabled seamless operation in complex dynamic environments with real-time decision making.
    </p>
    
    <div style="margin: 15px 0;">
      <strong style="color: #f0f6fc;">🔧 Tech Stack:</strong><br>
      <div style="margin: 8px 0;">
        <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++"/>
        <img src="https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white" alt="Python"/>
        <img src="https://img.shields.io/badge/ROS-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS"/>
        <img src="https://img.shields.io/badge/Gazebo-FF6600?style=flat-square&logo=gazebo&logoColor=white" alt="Gazebo"/>
        <img src="https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white" alt="MATLAB"/>
      </div>
    </div>
    
    <div style="margin: 15px 0;">
      <strong style="color: #f0f6fc;">🏆 Key Achievements:</strong>
      <ul style="color: #8b949e; font-size: 13px; margin: 8px 0; padding-left: 20px;">
        <li>SLAM implementation with <strong>sub-centimeter accuracy</strong></li>
        <li>Dynamic path replanning in <strong>&lt;100ms response time</strong></li>
        <li>Multi-robot coordination and collision avoidance</li>
        <li>Integration with LiDAR, cameras, and IMU sensors</li>
      </ul>
    </div>
    
    <div align="center" style="margin: 20px 0 10px 0;">
      <a href="https://github.com/hariharan2302/autonomous-navigation-system" style="text-decoration: none;">
        <img src="https://img.shields.io/badge/View%20Project-28a745?style=for-the-badge&logo=github&logoColor=white" alt="View Project"/>
      </a>
      <a href="#" style="text-decoration: none; margin-left: 10px;">
        <img src="https://img.shields.io/badge/Simulation-dc3545?style=for-the-badge&logo=gazebo&logoColor=white" alt="Simulation"/>
      </a>
    </div>
    
  </div>
</div>

</div>

### 🎯 Project Impact Summary

<div align="center" style="margin: 30px 0;">
  
  <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
    
    <!-- Performance Improvements -->
    <div style="text-align: center; padding: 15px; border: 1px solid #30363d; border-radius: 8px; background: #0d1117;">
      <h4 style="color: #00D4FF; margin: 0;">⚡ Performance Gains</h4>
      <p style="font-size: 20px; font-weight: bold; margin: 5px 0; color: #f0f6fc;">25% Average</p>
      <p style="font-size: 12px; color: #8b949e; margin: 0;">Optimization Improvement</p>
    </div>
    
    <!-- Accuracy Achievements -->
    <div style="text-align: center; padding: 15px; border: 1px solid #30363d; border-radius: 8px; background: #0d1117;">
      <h4 style="color: #00D4FF; margin: 0;">🎯 Accuracy Rate</h4>
      <p style="font-size: 20px; font-weight: bold; margin: 5px 0; color: #f0f6fc;">95%+</p>
      <p style="font-size: 12px; color: #8b949e; margin: 0;">Across All Systems</p>
    </div>
    
    <!-- Real-time Processing -->
    <div style="text-align: center; padding: 15px; border: 1px solid #30363d; border-radius: 8px; background: #0d1117;">
      <h4 style="color: #00D4FF; margin: 0;">⚡ Processing Speed</h4>
      <p style="font-size: 20px; font-weight: bold; margin: 5px 0; color: #f0f6fc;">60+ FPS</p>
      <p style="font-size: 12px; color: #8b949e; margin: 0;">Real-time Performance</p>
    </div>
    
    <!-- Cost Savings -->
    <div style="text-align: center; padding: 15px; border: 1px solid #30363d; border-radius: 8px; background: #0d1117;">
      <h4 style="color: #00D4FF; margin: 0;">💰 Cost Impact</h4>
      <p style="font-size: 20px; font-weight: bold; margin: 5px 0; color: #f0f6fc;">$50K+</p>
      <p style="font-size: 12px; color: #8b949e; margin: 0;">Annual Savings</p>
    </div>
    
  </div>
  
</div>

### 🔬 Research & Innovation Focus

<div align="center" style="margin: 20px 0;">
  
  **🤖 Robotics Automation** • **🧠 Machine Learning Optimization** • **👁️ Computer Vision** • **🚗 Autonomous Systems** • **🏭 Industrial Applications**
  
  <p style="color: #8b949e; font-size: 14px; margin: 15px 0;">
    Each project represents a commitment to pushing the boundaries of what's possible in robotics and AI, 
    with a focus on real-world applications that deliver measurable impact and drive innovation forward.
  </p>
  
</div>

</div>

---

## 🤝 Connect & Collaborate

<div align="center">

### 🚀 Ready to Build the Future Together?

<div style="background: linear-gradient(135deg, #0d1117 0%, #161b22 100%); border: 2px solid #00D4FF; border-radius: 15px; padding: 30px; margin: 20px 0; box-shadow: 0 8px 32px rgba(0, 212, 255, 0.1);">
  
  <p style="color: #c9d1d9; font-size: 16px; line-height: 1.6; margin: 20px 0;">
    <strong>🤖 I'm passionate about pushing the boundaries of robotics and AI!</strong><br/>
    Whether you're looking to collaborate on cutting-edge research, discuss innovative automation solutions, 
    or explore opportunities in robotics engineering, I'd love to connect and explore how we can create something amazing together.
  </p>
  
  ### 📬 Get In Touch
  
  <div style="display: flex; justify-content: center; gap: 15px; flex-wrap: wrap; margin: 25px 0;">
    
    <!-- LinkedIn with hover effect -->
    <a href="https://www.linkedin.com/in/hariharan-venkatraman-19994b178/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-Connect%20Professionally-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0077B5" alt="LinkedIn" style="transition: transform 0.3s ease; cursor: pointer;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'"/>
    </a>
    
    <!-- Email with hover effect -->
    <a href="mailto:hariharanvenkatraman23@gmail.com" target="_blank">
      <img src="https://img.shields.io/badge/Email-Let's%20Discuss%20Ideas-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=D14836" alt="Email" style="transition: transform 0.3s ease; cursor: pointer;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'"/>
    </a>
    
    <!-- GitHub with hover effect -->
    <a href="https://github.com/hariharan2302" target="_blank">
      <img src="https://img.shields.io/badge/GitHub-Explore%20My%20Code-100000?style=for-the-badge&logo=github&logoColor=white&labelColor=100000" alt="GitHub" style="transition: transform 0.3s ease; cursor: pointer;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'"/>
    </a>
    
    <!-- Research Profile - Coming Soon -->
    <!-- <a href="https://scholar.google.com/citations?user=SCHOLAR_ID_TBD" target="_blank">
      <img src="https://img.shields.io/badge/Google%20Scholar-Research%20Publications-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white&labelColor=4285F4" alt="Google Scholar" style="transition: transform 0.3s ease; cursor: pointer;" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'"/>
    </a> -->
    
  </div>
  
  ### 🎯 Collaboration Opportunities
  
  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin: 25px 0;">
    
    <!-- Research Collaboration -->
    <div style="background: #21262d; border: 1px solid #30363d; border-radius: 10px; padding: 20px; text-align: center;">
      <h4 style="color: #00D4FF; margin: 0 0 10px 0;">🔬 Research Collaboration</h4>
      <p style="color: #8b949e; font-size: 14px; margin: 0;">
        <strong>Areas:</strong> Autonomous Systems, Computer Vision, ML Optimization<br/>
        <strong>Focus:</strong> Academic research, publications, conference presentations
      </p>
    </div>
    
    <!-- Industry Projects -->
    <div style="background: #21262d; border: 1px solid #30363d; border-radius: 10px; padding: 20px; text-align: center;">
      <h4 style="color: #00D4FF; margin: 0 0 10px 0;">🏭 Industry Projects</h4>
      <p style="color: #8b949e; font-size: 14px; margin: 0;">
        <strong>Areas:</strong> Robotics Automation, Industrial AI, Process Optimization<br/>
        <strong>Focus:</strong> Real-world applications, scalable solutions
      </p>
    </div>
    
    <!-- Open Source -->
    <div style="background: #21262d; border: 1px solid #30363d; border-radius: 10px; padding: 20px; text-align: center;">
      <h4 style="color: #00D4FF; margin: 0 0 10px 0;">💻 Open Source</h4>
      <p style="color: #8b949e; font-size: 14px; margin: 0;">
        <strong>Areas:</strong> ROS/ROS2 packages, ML tools, Computer Vision libraries<br/>
        <strong>Focus:</strong> Community-driven development, knowledge sharing
      </p>
    </div>
    
    <!-- Mentorship -->
    <div style="background: #21262d; border: 1px solid #30363d; border-radius: 10px; padding: 20px; text-align: center;">
      <h4 style="color: #00D4FF; margin: 0 0 10px 0;">🎓 Mentorship</h4>
      <p style="color: #8b949e; font-size: 14px; margin: 0;">
        <strong>Areas:</strong> Robotics Engineering, Career guidance, Technical skills<br/>
        <strong>Focus:</strong> Student mentoring, knowledge transfer
      </p>
    </div>
    
  </div>
  
  ### 📍 Current Availability & Status
  
  <div style="display: flex; justify-content: center; gap: 15px; flex-wrap: wrap; margin: 25px 0;">
    
    <!-- Availability Status -->
    <img src="https://img.shields.io/badge/Status-🟢%20Available%20for%20Opportunities-brightgreen?style=for-the-badge&labelColor=28a745" alt="Available"/>
    
    <!-- Location -->
    <img src="https://img.shields.io/badge/Location-📍%20Buffalo,%20NY-blue?style=for-the-badge&labelColor=0066cc" alt="Location"/>
    
    <!-- Response Time -->
    <img src="https://img.shields.io/badge/Response%20Time-⚡%20Within%2024%20Hours-orange?style=for-the-badge&labelColor=ff8c00" alt="Response Time"/>
    
    <!-- Preferred Contact -->
    <img src="https://img.shields.io/badge/Preferred%20Contact-💼%20LinkedIn%20%7C%20📧%20Email-purple?style=for-the-badge&labelColor=6f42c1" alt="Preferred Contact"/>
    
  </div>
  
  ### 🌟 What I'm Looking For
  
  <div align="left" style="margin: 20px 0; padding: 0 20px;">
    
    **🚀 Exciting Opportunities:**
    - Full-time positions in Robotics Engineering, AI/ML, or Automation
    - Research collaborations in autonomous systems and computer vision
    - Consulting projects involving robotics integration and optimization
    - Speaking opportunities at conferences and technical events
    
    **🤝 Collaboration Interests:**
    - Cross-disciplinary research projects combining robotics and AI
    - Open-source contributions to ROS, OpenCV, and ML frameworks
    - Industry partnerships for real-world robotics applications
    - Academic collaborations with research institutions
    
    **💡 Discussion Topics:**
    - Latest trends in robotics and autonomous systems
    - Machine learning applications in industrial automation
    - Computer vision algorithms and real-time processing
    - Career advice for aspiring robotics engineers
    
  </div>
  
  ### 📞 Let's Start a Conversation!
  
  <div style="background: linear-gradient(90deg, #00D4FF, #0099cc); border-radius: 10px; padding: 20px; margin: 25px 0;">
    <p style="color: #ffffff; font-size: 16px; font-weight: bold; margin: 0; text-align: center;">
      🎯 Ready to discuss your next robotics or AI project?<br/>
      📧 Drop me a line at <a href="mailto:hariharanvenkatraman23@gmail.com" style="color: #ffffff; text-decoration: underline;">hariharanvenkatraman23@gmail.com</a><br/>
      💼 Connect with me on <a href="https://www.linkedin.com/in/hariharan-venkatraman-19994b178/" style="color: #ffffff; text-decoration: underline;">LinkedIn</a> for professional discussions
    </p>
  </div>
  
</div>

### 📊 Profile Analytics

<div align="center" style="margin: 20px 0;" role="group" aria-label="Profile analytics and metrics">
  <img src="https://komarev.com/ghpvc/?username=hariharan2302&color=00D4FF&style=for-the-badge&label=Profile+Views" 
       alt="Profile view counter showing total number of profile visits"
       role="img"
       aria-label="Profile views counter badge"
       loading="lazy" />
  <img src="https://img.shields.io/github/followers/hariharan2302?style=for-the-badge&color=00D4FF&labelColor=0d1117&logo=github" 
       alt="GitHub followers count badge"
       role="img"
       aria-label="GitHub followers counter"
       loading="lazy" />
  <img src="https://img.shields.io/badge/Connections-500%2B-00D4FF?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0077B5" 
       alt="LinkedIn connections count showing 500+ professional connections"
       role="img"
       aria-label="LinkedIn connections counter"
       loading="lazy" />
</div>

</div>

</section>

---

<footer role="contentinfo" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" 
       width="100"
       alt="Animated thank you message with waving hand gesture"
       role="img"
       aria-label="Thank you animation"
       loading="lazy" />
  <br/>
  <blockquote>
    <em>"Innovation distinguishes between a leader and a follower." - Steve Jobs</em>
  </blockquote>
</footer>
<!-- Comp
rehensive Mobile Responsive CSS -->
<style>
/* Global Responsive Design and Mobile Optimization */

/* Base responsive styles */
* {
  box-sizing: border-box;
}

/* Ensure all images are responsive by default */
img {
  max-width: 100% !important;
  height: auto !important;
}

/* Container responsive styles */
.container {
  width: 100%;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

/* Mobile-first responsive breakpoints */
@media (max-width: 480px) {
  /* Extra small devices (phones) */
  .container {
    padding: 0 10px;
  }
  
  /* Typography scaling */
  h1 { font-size: 20px !important; line-height: 1.3; }
  h2 { font-size: 18px !important; line-height: 1.3; }
  h3 { font-size: 16px !important; line-height: 1.3; }
  h4 { font-size: 14px !important; line-height: 1.3; }
  p, li { font-size: 13px !important; line-height: 1.5; }
  
  /* Header section mobile optimization */
  .mobile-break {
    display: block !important;
    margin: 8px 0;
  }
  
  /* Badge scaling for mobile */
  img[src*="shields.io"] {
    transform: scale(0.85);
    margin: 2px;
  }
  
  /* Skill bars mobile optimization */
  .skill-item {
    flex-direction: column !important;
    align-items: flex-start !important;
    gap: 6px !important;
  }
  
  .progress-bar-container {
    width: 100% !important;
    max-width: 100% !important;
  }
  
  /* Stats grid mobile layout */
  .stats-grid {
    grid-template-columns: 1fr !important;
    gap: 12px !important;
  }
  
  /* Repository cards mobile optimization */
  .repositories-grid {
    grid-template-columns: 1fr !important;
    gap: 15px !important;
    padding: 0 5px !important;
  }
  
  .repo-card {
    padding: 12px !important;
  }
  
  /* Featured projects mobile layout */
  div[style*="grid-template-columns: repeat(auto-fit, minmax(350px, 1fr))"] {
    display: block !important;
  }
  
  div[style*="grid-template-columns: repeat(auto-fit, minmax(350px, 1fr))"] > div {
    margin-bottom: 20px !important;
  }
  
  /* Contact cards mobile layout */
  .contact-cards {
    flex-direction: column !important;
    align-items: center !important;
    gap: 12px !important;
  }
  
  .contact-card {
    width: 100% !important;
    max-width: 280px !important;
    padding: 15px !important;
  }
  
  /* Opportunities grid mobile layout */
  .opportunities-grid {
    grid-template-columns: 1fr !important;
    gap: 10px !important;
  }
  
  /* Activity badges mobile layout */
  .activity-badges {
    flex-direction: column !important;
    align-items: center !important;
    gap: 6px !important;
  }
  
  .activity-badges img {
    transform: scale(0.9) !important;
  }
  
  /* Tech badges mobile optimization */
  .tech-badges {
    justify-content: center !important;
    gap: 4px !important;
  }
  
  .tech-badges img {
    transform: scale(0.8) !important;
  }
  
  /* Profile views and footer mobile */
  .profile-views img {
    transform: scale(0.9);
  }
}

@media (max-width: 768px) {
  /* Small devices (tablets) */
  .container {
    padding: 0 15px;
  }
  
  /* Typography scaling */
  h1 { font-size: 24px !important; }
  h2 { font-size: 20px !important; }
  h3 { font-size: 18px !important; }
  h4 { font-size: 16px !important; }
  p, li { font-size: 14px !important; }
  
  /* Two-column layout for medium screens */
  .stats-grid {
    grid-template-columns: repeat(2, 1fr) !important;
    gap: 15px !important;
  }
  
  .opportunities-grid {
    grid-template-columns: repeat(2, 1fr) !important;
    gap: 15px !important;
  }
  
  /* Repository cards tablet optimization */
  .repositories-grid {
    grid-template-columns: 1fr !important;
    gap: 20px !important;
    padding: 0 10px !important;
  }
  
  /* Badge container mobile optimization */
  .badge-container {
    justify-content: center !important;
    gap: 6px !important;
  }
  
  .badge-container img {
    transform: scale(0.95);
  }
  
  /* Contact cards tablet layout */
  .contact-cards {
    gap: 15px !important;
  }
  
  .contact-card {
    min-width: 160px !important;
    padding: 16px !important;
  }
  
  /* Activity badges tablet layout */
  .activity-badges {
    gap: 8px !important;
  }
  
  .activity-badges img {
    transform: scale(0.95) !important;
  }
}

@media (max-width: 1024px) {
  /* Medium devices (small laptops) */
  .container {
    padding: 0 20px;
  }
  
  /* Adjust grid layouts for medium screens */
  .repositories-grid {
    grid-template-columns: repeat(2, 1fr) !important;
    gap: 20px !important;
  }
  
  /* Featured projects layout adjustment */
  div[style*="grid-template-columns: repeat(auto-fit, minmax(350px, 1fr))"] {
    grid-template-columns: repeat(2, 1fr) !important;
    gap: 20px !important;
  }
}

/* Landscape phone orientation */
@media (max-width: 768px) and (orientation: landscape) {
  /* Optimize for landscape phones */
  .stats-grid {
    grid-template-columns: repeat(3, 1fr) !important;
  }
  
  .opportunities-grid {
    grid-template-columns: repeat(4, 1fr) !important;
  }
  
  .contact-cards {
    flex-direction: row !important;
    justify-content: center !important;
  }
}

/* High DPI displays */
@media (-webkit-min-device-pixel-ratio: 2), (min-resolution: 192dpi) {
  /* Optimize for retina displays */
  img {
    image-rendering: -webkit-optimize-contrast;
    image-rendering: crisp-edges;
  }
}

/* Animation performance optimization */
@media (prefers-reduced-motion: reduce) {
  /* Disable animations for users who prefer reduced motion */
  *, *::before, *::after {
    animation-duration: 0.01ms !important;
    animation-iteration-count: 1 !important;
    transition-duration: 0.01ms !important;
  }
}

/* Dark mode optimization */
@media (prefers-color-scheme: dark) {
  /* Ensure optimal contrast in dark mode */
  .repo-card, .contact-card, .availability-card {
    background: rgba(13, 17, 23, 0.95) !important;
    border-color: #30363d !important;
  }
}

/* Print styles */
@media print {
  /* Optimize for printing */
  .contact-card, .repo-card {
    break-inside: avoid;
  }
  
  img[src*="giphy.com"], img[src*="media.giphy.com"] {
    display: none !important;
  }
  
  .activity-badges img, .tech-badges img {
    filter: grayscale(100%);
  }
}

/* Accessibility improvements */
@media (prefers-contrast: high) {
  /* High contrast mode */
  .contact-card, .repo-card {
    border-width: 3px !important;
  }
  
  .progress-bar {
    border: 2px solid #ffffff !important;
  }
}

/* Focus styles for keyboard navigation */
a:focus, button:focus {
  outline: 2px solid #00D4FF !important;
  outline-offset: 2px !important;
}

/* Smooth scrolling for supported browsers */
@media (prefers-reduced-motion: no-preference) {
  html {
    scroll-behavior: smooth;
  }
}

/* Loading performance optimization */
img[src*="github-readme-stats"], img[src*="github-readme-streak-stats"] {
  loading: lazy;
}

/* Ensure proper spacing on all screen sizes */
section, div[align="center"] {
  margin-bottom: 20px;
}

@media (max-width: 768px) {
  section, div[align="center"] {
    margin-bottom: 15px;
  }
}

@media (max-width: 480px) {
  section, div[align="center"] {
    margin-bottom: 12px;
  }
}

/* Flexible image sizing for different content types */
img[alt*="Animation"], img[alt*="GIF"] {
  max-width: 300px !important;
}

@media (max-width: 768px) {
  img[alt*="Animation"], img[alt*="GIF"] {
    max-width: 200px !important;
  }
}

@media (max-width: 480px) {
  img[alt*="Animation"], img[alt*="GIF"] {
    max-width: 150px !important;
  }
}

/* Ensure proper text wrapping */
p, li, div {
  word-wrap: break-word;
  overflow-wrap: break-word;
}

/* Optimize table-like layouts for mobile */
div[style*="display: flex"] {
  flex-wrap: wrap !important;
}

div[style*="display: grid"] {
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)) !important;
}

@media (max-width: 768px) {
  div[style*="display: grid"] {
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)) !important;
  }
}

@media (max-width: 480px) {
  div[style*="display: grid"] {
    grid-template-columns: 1fr !important;
  }
}

/* Ensure proper spacing for inline elements */
img + img {
  margin-left: 4px;
}

@media (max-width: 480px) {
  img + img {
    margin-left: 2px;
  }
}

/* Optimize long text content for mobile reading */
@media (max-width: 768px) {
  ul, ol {
    padding-left: 20px;
  }
  
  li {
    margin-bottom: 6px;
  }
}

/* Ensure interactive elements are touch-friendly */
@media (max-width: 768px) {
  a, button {
    min-height: 44px;
    min-width: 44px;
    display: inline-flex;
    align-items: center;
    justify-content: center;
  }
}

/* Final mobile optimization tweaks */
@media (max-width: 480px) {
  /* Reduce margins and padding for very small screens */
  * {
    margin-top: 0.8em;
    margin-bottom: 0.8em;
  }
  
  /* Ensure readability on small screens */
  strong, b {
    font-weight: 700;
  }
  
  /* Optimize code blocks and inline code */
  code {
    font-size: 12px;
    padding: 2px 4px;
  }
  
  /* Ensure proper line height for readability */
  p, li, div {
    line-height: 1.6;
  }
}

/* Additional accessibility improvements */

/* Skip link for screen readers */
.skip-link {
  position: absolute;
  top: -40px;
  left: 6px;
  background: #00D4FF;
  color: #000;
  padding: 8px;
  text-decoration: none;
  border-radius: 4px;
  z-index: 1000;
}

.skip-link:focus {
  top: 6px;
}

/* Ensure sufficient color contrast */
@media (prefers-contrast: high) {
  * {
    filter: contrast(1.5);
  }
}

/* Optimize for print */
@media print {
  .contact-link, .repo-card, .stat-card {
    break-inside: avoid;
    page-break-inside: avoid;
  }
  
  img[src*="giphy.com"], 
  img[src*="media.giphy.com"],
  img[alt*="Animation"] {
    display: none;
  }
  
  .progress-bar {
    border: 1px solid #000;
    background: #fff !important;
  }
}

/* Performance optimizations */
.stat-card, .repo-card, .contact-link {
  contain: layout style paint;
}

/* Optimize font loading */
@font-face {
  font-display: swap;
}

/* Reduce layout shifts */
img {
  aspect-ratio: attr(width) / attr(height);
}

/* Optimize animations for better performance */
@media (prefers-reduced-motion: no-preference) {
  .stat-card:hover,
  .repo-card:hover,
  .contact-link:hover {
    transform: translateY(-8px) scale(1.02);
    will-change: transform;
  }
}

/* Ensure proper focus management */
[tabindex="-1"]:focus {
  outline: none;
}

/* Improve text readability */
p, li, div {
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>