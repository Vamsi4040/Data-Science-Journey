---
layout: default
title: "About Me"
permalink: /about/
---

# About Me
<div id="slider" style="position: relative; width: 100%; height: 400px; overflow: hidden;">
  <img src="{{ 'assets/slide1.JPG' | relative_url }}" alt="Slide 2" class="slide" style="position: absolute; width: 100%; height: 100%; object-fit: contain; object-position: center; display: none;">
  <img src="{{ 'assets/slide2.jpg' | relative_url }}" alt="Slide 3" class="slide" style="position: absolute; width: 100%; height: 100%; object-fit: contain; object-position: center; display: none;">
</div>

<script>
  let slides = document.querySelectorAll('#slider .slide');
  let currentSlide = 0;
  setInterval(() => {
    slides[currentSlide].style.display = 'none';
    currentSlide = (currentSlide + 1) % slides.length;
    slides[currentSlide].style.display = 'block';
  }, 2000);
</script>


Hello, my name is Ganga Vamsik Sanipinidi. I am currently pursuing a Master’s in Data Science at the University of New Haven with an expected graduation in May 2025. My academic journey has equipped me with a robust skill set to solve real-world data challenges. I have executed projects in Natural Language Processing and Deep Learning and am presently tackling complex problems in Computer Vision. With an undergraduate background in Mechanical Engineering, I bring an interdisciplinary perspective that enriches my approach to data science. Additionally, as a Data Science Intern at Colaberry, I manage APIs while actively learning and contributing to the company’s culture. I also hold a certification in Azure Machine Learning, further enhancing my expertise in cloud-based machine learning solutions. I am passionate about leveraging data-driven insights to drive innovation and create transformative solutions.

---
## Interests & Hobbies

- I enjoy watching documentaries.
- I keep up with the news.
- I follow stock market trends.
- I love web surfing.
- I am learning Spanish.
- I enjoy travelling to different places.

---
## Passions & Pursuits

- **Student Chapter IEI (2020 – 2022)**  
  - Key member in Student Chapter, Conducted and participated in various mechanical engineering events during undergraduate.

- **Event Data Analyst**  
  - Evaluated crowd density and identified participation trends during a technical fest *Tech*(March 2022).

- **Rally Car Design Challenge**  
  - Participated in the Rally Car Design Challenge organized by AMZ Automotive at IIIT Nuzvid, representing RGUKT Srikakulam.

- **CATIA Phase-I Workshop (APSSDC)**  
  - Participated in the CATIA (Computer Aided Three-Dimensional Interactive Application) Phase-I Workshop 2019-2020, which is a computer-aided design (CAD) software for creating 3D models and product designs conducted by the Andhra Pradesh State Skill Development Corporation.

- **Automobile & IC Engine Design Workshop (IIT Hyderabad)**  
  - Participated in the Automobile & IC Engine Design Workshop conducted by Auto-Freak India at IIT Hyderabad in October 2018.

- **Cricket Enthusiast**  
  - Represented the Mechanical Engineering Department in Department Premier League (2018 – 2021), winning the championship for three consecutive years.

- **Community Service Program (Ignited Minds)**
  - Actively participated in the Six Days Community Services Program with Ignited Minds Organisation (May 2022).
 
- **Volunteer: “Save A Soul” Initiative (2018 – 2022)**  
  - Distributed food to orphanages, honing leadership and community engagement.

---
## Languages

- **Telugu:** Native
- **English:** Professional
- **Hindi:** Fluent
- **Spanish:** Basic

---

## Contact & Location Details

<div style="display: flex; flex-wrap: wrap;">

  <!-- Contact Details Section -->
  <div style="flex: 1; min-width: 300px; margin-right: 20px;">
    <strong><u>Contact Details</u></strong><br><br>
    <div style="margin-bottom: 10px;">
      <strong>Email:</strong> 
      <a href="mailto:contacttovamsi@gmail.com" target="_blank">contacttovamsi@gmail.com</a>
    </div>
    <div style="margin-bottom: 10px;">
      <strong>Phone:</strong> (860) 380-6189
    </div>
    <div style="margin-bottom: 10px;">
      <strong>LinkedIn:</strong> 
      <a href="https://www.linkedin.com/in/sgvamsik/" target="_blank">Ganga Vamsik S</a>
    </div>
    <!-- Social Links Section -->
<div style="margin-top: 20px;">
  <a href="https://github.com/Vamsi4040" target="_blank" style="margin-right: 10px;"><img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub" style="width: 40px; height: 40px; object-fit: contain;"/></a>
  <a href="https://www.linkedin.com/in/sgvamsik/" target="_blank" style="margin-right: 10px;"><img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn" style="width: 40px; height: 40px; object-fit: contain;"/></a>
  <a href="mailto:contacttovamsi@gmail.com" target="_blank" style="margin-right: 10px;"><img src="{{ '/assets/mail-logo.jpg' | relative_url }}" alt="Email" style="width: 40px; height: 40px; object-fit: contain;"/></a>
  <a href="https://www.kaggle.com/work/overview" target="_blank" style="margin-right: 10px;"><img src="{{ '/assets/kaggle-logo.png' | relative_url }}" alt="Kaggle" style="width: 40px; height: 40px; object-fit: contain;"/></a>
  <a href="https://www.quora.com/profile/Vamsi-Roy-2" target="_blank" style="margin-right: 10px;"><img src="{{ '/assets/quora-logo.png' | relative_url }}" alt="Quora" style="width: 42px; height: 45px; object-fit: contain;"/></a>
  <a href="https://grabcad.com/vamsi.s-1" target="_blank" style="margin-right: 10px;"><img src="{{ '/assets/Grabcad-logo.png' | relative_url }}" alt="GrabCAD" style="width: 42px; height: 42px; object-fit: contain;"/></a>
</div>
  </div>

  <!-- Map Section -->
  <div style="flex: 1; min-width: 300px;">
    <strong><u>Location</u></strong><br>
    194 Washington St, Hartford, Connecticut, 06106<br><br>
    <iframe 
      width="400" 
      height="250" 
      style="border:0;" 
      loading="lazy" 
      allowfullscreen 
      src="https://www.google.com/maps?q=194+Washington+Street,+Hartford,+CT&output=embed">
    </iframe>
  </div>
</div>



---

> *Feel free to reach out via LinkedIn or Email. I’m always excited to connect with fellow professionals and discuss data science!*
