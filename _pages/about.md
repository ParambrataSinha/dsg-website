---
title: "About Us"
permalink: /about/
layout: splash
---

<style>
.about-hero {
  text-align: center;
  padding: 4rem 20px;
  background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
  border-radius: 16px;
  margin-bottom: 3rem;
}

.about-hero img {
  width: 100%;
  max-width: 800px;
  border-radius: 12px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.1);
  margin-bottom: 2rem;
}

.about-hero p {
  font-size: 1.15rem;
  color: #4a5568;
  max-width: 900px;
  margin: 0 auto;
  line-height: 1.8;
}

.year-section {
  margin-bottom: 4rem;
}

.year-header {
  font-size: 2rem;
  color: #2c3e50;
  border-bottom: 3px solid #007acc;
  padding-bottom: 10px;
  margin-bottom: 2rem;
  display: inline-block;
}

.member-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
  gap: 30px;
}

.member-card {
  background: #ffffff;
  padding: 16px;
  border-radius: 16px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.06);
  text-align: center;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  border: 1px solid #f1f3f5;
  display: block;
  text-decoration: none !important;
  color: inherit;
  cursor: pointer;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
  transform: translateZ(0);
  will-change: transform;
}

.member-card,
.member-card:hover,
.member-card:focus,
.member-card:visited,
.member-card *,
.member-card:hover * {
  text-decoration: none !important;
}

.layout--splash .page__content a.member-card,
.layout--splash .page__content a.member-card:hover,
.page__content a.member-card,
.page__content a.member-card:hover {
  text-decoration: none !important;
}

.member-card:hover {
  transform: translateY(-8px) translateZ(0);
  box-shadow: 0 12px 25px rgba(0,0,0,0.1);
}

.member-card img {
  width: 100%;
  aspect-ratio: 1 / 1;
  object-fit: cover;
  border-radius: 12px;
  margin-bottom: 1rem;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
  transform: translateZ(0);
}

.member-card h3 {
  margin: 0;
  font-size: 1.15rem;
  font-weight: 600;
  color: #2c3e50;
  transition: color 0.2s ease;
  text-decoration: none !important;
}

.member-card:hover h3 {
  color: #007acc;
  text-decoration: none !important;
}
</style>

<div class="about-hero">
  <img src="{{ site.baseurl }}/assets/images/dsgteam25.jpeg" alt="Data Science Group Team">
  <p>We are Data Science Group, IIT Roorkee. A student organization, part of the umbrella organization Software Development Section. We aim to work on innovative open source projects in the domain of Machine Learning, Deep Learning & Reinforcement Learning, bridging the gap between research and industry. In the process, we fulfill our mission of cultivating and evolving the technical community at IIT Roorkee by organizing lectures, workshops, hackathons spanning the field of Data Science and AI.</p>
</div>

<div class="team-container">
  <h1 style="text-align: center; font-size: 3rem; margin-bottom: 3rem;">Our Team</h1>

  <!-- 4TH Year (Y24) -->
  <div class="year-section">
    <h2 class="year-header">4th Year (Y24)</h2>
    <div class="member-grid">
      <a href="{{ site.baseurl }}/members/abhivanshgupta/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y24/abhivansh.jpeg" alt="Abhivansh Gupta" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Abhivansh Gupta</h3>
      </a>
      <a href="{{ site.baseurl }}/members/abhinavkumar/" class="member-card">         
      <img src="{{ site.baseurl }}/assets/images/members/y24/abhinav.png" alt="Abhinav Kumar" 
        onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Abhinav Kumar</h3>
      </a>
      <a href="{{ site.baseurl }}/members/advika/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y24/advika.jpeg" alt="Advika Sinha" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Advika Sinha</h3>
      </a>
      <a href="{{ site.baseurl }}/members/amritanshu/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y24/amritanshu.png" alt="Amritanshu Tiwari" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Amritanshu Tiwari</h3>
      </a>
      <a href="{{ site.baseurl }}/members/atharvmittal/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y24/otterv.webp" alt="Atharv Mittal" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Atharv Mittal</h3>
      </a>
      <a href="{{ site.baseurl }}/members/cherishpuniani/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y24/cp.jpeg" alt="Cherish Puniani" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Cherish Puniani</h3>
      </a>
      <a href="{{ site.baseurl }}/members/JheelMaheshwari/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y24/jheelmaheshwari.png" alt="Jheel Maheshwari" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Jheel Maheshwari</h3>
      </a>
      <a href="{{ site.baseurl }}/members/kaustubhsharma/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y24/kaustubh.jpg" alt="Kaustubh Sharma" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Kaustubh Sharma</h3>
      </a>
      <a href="{{ site.baseurl }}/members/ojasvanema/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y24/ojasv.jpg" alt="Ojasva Nema" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Ojasva Nema</h3>
      </a>
      <a href="{{ site.baseurl }}/members/SargamGoyal/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y24/sargam.jpg" alt="Sargam Goyal" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Sargam Goyal</h3>
      </a>
      <a href="{{ site.baseurl }}/members/Tushar/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y24/tushar.jpeg" alt="Tushar" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Tushar</h3>
      </a>
    </div>
  </div>

  <!-- 3rd Year (Y25) -->
  <div class="year-section">
    <h2 class="year-header">3nd Year (Y25)</h2>
    <div class="member-grid">
      <a href="{{ site.baseurl }}/members/aarush/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y25/aarush.jpg" alt="Aarush Aggarwal" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Aarush Aggarwal</h3>
      </a>
      <a href="{{ site.baseurl }}/members/adityachauhan/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y25/adityachauhan.jpg" alt="Aditya Chauhan" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Aditya Chauhan</h3>
      </a>
      <a href="{{ site.baseurl }}/members/akshat/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y25/akshat_tomar.jpg" alt="Akshat Tomar" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Akshat Tomar</h3>
      </a>
      <a href="{{ site.baseurl }}/members/arnav/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y25/arnav.png" alt="Arnav Bendre" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Arnav Bendre</h3>
      </a>
      <a href="{{ site.baseurl }}/members/gaurav/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y25/gaurav.jpg" alt="Gaurav Kumar" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Gaurav Kumar</h3>
      </a>
      <a href="{{ site.baseurl }}/members/gowri/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y25/gowri.jpg" alt="Gowri D V" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Gowri D V</h3>
      </a>
      <a href="{{ site.baseurl }}/members/laabhanvi/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y25/laabhanvi.jpg" alt="Laabhanvi Jain" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Laabhanvi Jain</h3>
      </a>
      <a href="{{ site.baseurl }}/members/manjot/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y25/manjot.jpg" alt="Manjot Singh" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Manjot Singh</h3>
      </a>
      <a href="{{ site.baseurl }}/members/raj/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y25/raj.jpg" alt="Raj Shekhar Singh" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Raj Shekhar Singh</h3>
      </a>
      <a href="{{ site.baseurl }}/members/shreyansh/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y25/shreyansh.jpg" alt="Shreyansh Modi" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Shreyansh Modi</h3>
      </a>
      <a href="{{ site.baseurl }}/members/soham/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y25/soham.png" alt="Soham Gawand" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Soham Gawand</h3>
      </a>
      <a href="{{ site.baseurl }}/members/srijan/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y25/srijan.jpg" alt="Srijan Tiwari" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Srijan Tiwari</h3>
      </a>
    </div>
  </div>

  <!-- 2nd Year (Y26) -->
  <div class="year-section">
    <h2 class="year-header">2nd Year (Y26)</h2>
    <div class="member-grid">
      <!-- Add Y26 members here. Example:
      <a href="{{ site.baseurl }}/members/examplename/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y26/example.jpg" alt="Member Name" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Member Name</h3>
      </a>
      -->
      <a href="{{ site.baseurl }}/members/harshit_agrawal/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y26/harshit_agrawal.jpeg" alt="Harshit Agrawal" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Harshit Agrawal</h3>
      </a>
      <a href="{{ site.baseurl }}/members/kavish/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y26/kavish_grover.jpeg" alt="Kavish Grover" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Kavish Grover</h3>
      </a>
      <a href="{{ site.baseurl }}/members/parambrata/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y26/parambrata.png" alt="Parambrata Sinha" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Parambrata Sinha</h3>
      </a>
      <a href="{{ site.baseurl }}/members/parth_brijpuria/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y26/parth_brijpuria.jpeg" alt="Parth Brijpuria" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Parth Brijpuria</h3>
      </a>
      <a href="{{ site.baseurl }}/members/kandpal/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y26/rishita_kandpal.jpg" alt="Rishita Kandpal" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Rishita Kandpal</h3>
      </a>
      <a href="{{ site.baseurl }}/members/Sarthak/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y26/Sarthak.jpeg" alt="Sarthak Bhatia" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Sarthak Bhatia</h3>
      </a>
      <a href="{{ site.baseurl }}/members/tanush_gupta/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y26/tanush_gupta.jpg" alt="Tanush Gupta" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Tanush Gupta</h3>
      </a>
      <a href="{{ site.baseurl }}/members/vedansh/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y26/vedanshSethi.png" alt="Vedansh Sethi" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Vedansh Sethi</h3>
      </a>
    </div>

  </div>

  <!-- Alumni (Y22 & Earlier) -->
  <div class="year-section">
    <h2 class="year-header">Alumni</h2>
    <div class="member-grid">
      <a href="{{ site.baseurl }}/members/aakashkrsingh/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y23/aakash.jpeg" alt="Aakash Kr Singh" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Aakash Kumar Singh (Y23)</h3>
      </a>
      <a href="{{ site.baseurl }}/members/aayanyadav/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y23/aayan.jpeg" alt="Aayan Yadav" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Aayan Yadav (Y23)</h3>
      </a>
      <a href="{{ site.baseurl }}/members/agampandey/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y23/Agam_PFP.png" alt="Agam Pandey" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Agam Pandey (Y23)</h3>
      </a>
      <a href="{{ site.baseurl }}/members/anantjain/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y23/anantjain.png" alt="Anant Jain" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Anant Jain (Y23)</h3>
      </a>
      <a href="{{ site.baseurl }}/members/anupriyakkumari/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y23/anupriya_image.jpg" alt="Anupriya Kumari" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Anupriya Kumari (Y23)</h3>
      </a>
      <a href="{{ site.baseurl }}/members/barathchandran/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y23/Screenshot 2025-03-28 175712.png" alt="Barath Chandran" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Barath Chandran (Y23)</h3>
      </a>
      <a href="{{ site.baseurl }}/members/parthbadgujar/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y23/parth.jpg" alt="Parth Badgujar" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Parth Badgujar (Y23)</h3>
      </a>
      <a href="{{ site.baseurl }}/members/shoryasinghal/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y23/shorya.jpg" alt="Shorya Singhal" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Shorya Singhal (Y23)</h3>
      </a>
      <a href="{{ site.baseurl }}/members/shreesinghi/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y23/shree.jpeg" alt="Shree Singhi" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Shree Singhi (Y23)</h3>
      </a>
      <a href="{{ site.baseurl }}/members/sukritjindal/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y23/sukrit.JPG" alt="Sukrit Jindal" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Sukrit Jindal (Y23)</h3>
      </a>
      <a href="{{ site.baseurl }}/members/swadeshswain/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y23/swadesh.png" alt="Swadesh Swain" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Swadesh Swain (Y23)</h3>
      </a>
      <a href="{{ site.baseurl }}/members/aasthakhaitan/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y22/aasthakhaitan.jpeg" alt="Aastha Khaitan" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Aastha Khaitan (Y22)</h3>
      </a>
      <a href="{{ site.baseurl }}/members/vedumrajkar/" class="member-card">
        <img src="{{ site.baseurl }}/assets/images/members/y22/vedumrajkar.jpeg" alt="Ved Umrajkar" onerror="this.onerror=null;this.src='{{ site.baseurl }}/assets/images/placeholder.jpeg';">
        <h3>Ved Umrajkar (Y22)</h3>
      </a>
    </div>
  </div>

</div>
