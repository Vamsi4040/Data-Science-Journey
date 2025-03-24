---
layout: default
title: "About Me"
permalink: /about/
---

# About Me
<div id="slider" style="position: relative; width: 100%; height: 400px; overflow: hidden;">
  <img src="{{ '/assets/my-picture.jpg' | relative_url }}" alt="Slide 1" class="slide" style="position: absolute; width: 100%; height: 100%; object-fit: contain; object-position: center;">
  <img src="{{ 'assets/emotion_distribution.png' | relative_url }}" alt="Slide 2" class="slide" style="position: absolute; width: 100%; height: 100%; object-fit: contain; object-position: center; display: none;">
  <img src="{{ '/assets/my-picture3.jpg' | relative_url }}" alt="Slide 3" class="slide" style="position: absolute; width: 100%; height: 100%; object-fit: contain; object-position: center; display: none;">
</div>

<script>
  let slides = document.querySelectorAll('#slider .slide');
  let currentSlide = 0;
  setInterval(() => {
    slides[currentSlide].style.display = 'none';
    currentSlide = (currentSlide + 1) % slides.length;
    slides[currentSlide].style.display = 'block';
  }, 1000);
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
## Contact Details

- **Email:** [your-email@example.com](contacttovamsi@gmail.com)
- **Phone:** (860) 380-6189 
- **LinkedIn:** [linkedin.com/in/yourprofile](https://www.linkedin.com/in/sgvamsik/)
- **Address:** 194 Washington Street, Hartford, Connecticut

---
## Languages

- **Telugu:** Native
- **Hindi:** Fluent
- **English:** Professional
- **Spanish:** Basic

---
## Links
- **GitHub:** [https://github.com/Vamsi4040](https://github.com/Vamsi4040)  
- **LinkedIn:** [Ganga Vamsik S](https://linkedin.com/in/YourLinkedInProfile)  
- **Email:** [contacttovamsi@gmail.com](mailto:contacttovamsi@gmail.com)  

---

## My Location & Contact

<div style="display: flex; flex-wrap: wrap;">

  <!-- Contact Details Section -->
  <div style="flex: 1; min-width: 300px; margin-right: 20px;">
    <strong><u>Contact Details</u></strong><br><br>
    <div style="margin-bottom: 10px;">
      <strong>GitHub:</strong> 
      <a href="https://github.com/Vamsi4040" target="_blank">github.com/Vamsi4040</a>
    </div>
    <div style="margin-bottom: 10px;">
      <strong>LinkedIn:</strong> 
      <a href="https://linkedin.com/in/YourLinkedInProfile" target="_blank">Ganga Vamsik S</a>
    </div>
    <div style="margin-bottom: 10px;">
      <strong>Quora:</strong>
      <a href="https://www.quora.com/profile/Vamsi-Roy-2" target="_blank">Vamsi Roy</a>
    </div>
    <div style="margin-bottom: 10px;">
      <strong>Email:</strong> 
      <a href="mailto:contacttovamsi@gmail.com" target="_blank">contacttovamsi@gmail.com</a>
    </div>
  </div>

  <!-- Map Section -->
  <div style="flex: 1; min-width: 300px;">
    <strong><u>Location</u></strong><br><br>
    Apt 109, 194 Washington Street, Hartford, Connecticut
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
