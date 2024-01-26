link to the figma project: https://www.figma.com/file/hvQqxp2V9rtf2ibRrdoh0C/Untitled?type=design&mode=design&t=AmaWmT44lsZTwHF6-1


Target user profile:
With this project, I aimed to create a resume in a simple and visually appealing manner. Using Figma, I found an intuitive and easy-to-use tool that allows me to highlight my skills, work experience, and education. My user profile has primarily focused on updating my resume to reflect my current journey.

Information architecture:
Since this project focuses on creating a resume in Figma, information architecture is not a relevant element in this context. The Figma design platform provides us with an intuitive and flexible interface that allows us to create and organize content freely.

Visual design:
To visually design this project, a color palette reflecting professionalism and modernity will be used. I have employed a combination of neutral tones such as white and black, along with accents of a subtle color like blue, which adds a touch of freshness and vitality.

Regarding typography, I have used a clean and readable sans-serif font, in this case, Montserrat. This font is ideal for presenting information clearly and professionally.

As for the page layout, I aimed for a clean and organized structure that facilitates resume navigation and editing. I have divided the content into well-defined sections, such as Languages, Work Experience, Education, Skills, etc. This allows me to organize my information effectively and highlight my strengths.

For inspiration, I have reviewed similar projects on design platforms and online portfolios. I have also watched YouTube videos to get an idea of what constitutes good design.

<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Resume/CV Design</title>
	<link rel="stylesheet" href="CURRICULUM1.css">
	<script src="https://kit.fontawesome.com/b99e675b6e.js"></script>
</head>
<body>

<div class="resume">
   <div class="resume_left">
     <div class="resume_profile">
       <img src="foto-marc-lopez-vilchez.png" alt="profile_pic">
     </div>
     <div class="resume_content">
       <div class="resume_item resume_info">
         <div class="title">
           <p class="bold">Marc López Vílchez</p>
           <p class="regular">Computer Engineering student.</p>
         </div>
         <ul>
           <li>
             <div class="icon">
               <i class="fas fa-map"></i>
             </div>
             <div class="data">
               Sant Feliu de Guíxols, Girona <br /> Spain
             </div>
           </li>
           <li>
             <div class="icon">
               <i class="fas fa-mobile-alt"></i>
             </div>
             <div class="data">
               +34 608772976
             </div>
           </li>
           <li>
             <div class="icon">
               <i class="fas fa-envelope"></i>
             </div>
             <div class="data">
               marclopezvil@gmail.com
             </div>
           </li>
         </ul>
       </div>
       <div class="resume_item resume_skills">
         <div class="title">
           <p class="bold">Skills</p>
         </div>
         <ul>
           <li>
             <div class="skill_name">
               HTML
             </div>
             <div class="skill_progress">
               <span style="width: 80%;"></span>
             </div>
             <div class="skill_per">80%</div>
           </li>
           <li>
             <div class="skill_name">
               CSS
             </div>
             <div class="skill_progress">
               <span style="width: 70%;"></span>
             </div>
             <div class="skill_per">70%</div>
           </li>
           <li>
             <div class="skill_name">
               C++
             </div>
             <div class="skill_progress">
               <span style="width: 90%;"></span>
             </div>
             <div class="skill_per">90%</div>
           </li>
           <li>
             <div class="skill_name">
               JAVA
             </div>
             <div class="skill_progress">
               <span style="width: 80%;"></span>
             </div>
             <div class="skill_per">80%</div>
           </li>
           <li>
             <div class="skill_name">
               SQL
             </div>
             <div class="skill_progress">
               <span style="width: 65%;"></span>
             </div>
             <div class="skill_per">65%</div>
           </li>
           <li>
            <div class="skill_name">
              PHP
            </div>
            <div class="skill_progress">
              <span style="width: 60%;"></span>
            </div>
            <div class="skill_per">60%</div>
          </li>
          <li>
            <div class="skill_name">
              C
            </div>
            <div class="skill_progress">
              <span style="width: 85%;"></span>
            </div>
            <div class="skill_per">85%</div>
          </li>
          <li>
            <div class="skill_name">
              JS
            </div>
            <div class="skill_progress">
              <span style="width: 70%;"></span>
            </div>
            <div class="skill_per">70%</div>
          </li>
         </ul>
       </div>
       <div class="resume_item resume_languages">
         <div class="title">
           <p class="bold">Languages</p>
         </div>
         <ul>
          <li>
            <div class="skill_name">
              SPANISH
            </div>
            <div class="skill_progress">
              <span style="width: 100%;"></span>
            </div>
            <div class="skill_per">100%</div>
          </li>
          <li>
            <div class="skill_name">
              CATALAN
            </div>
            <div class="skill_progress">
              <span style="width: 100%;"></span>
            </div>
            <div class="skill_per">100%</div>
          </li>
          <li>
            <div class="skill_name">
              ENGLISH
            </div>
            <div class="skill_progress">
              <span style="width: 90%;"></span>
            </div>
            <div class="skill_per">90%</div>
          </li>
          <li>
            <div class="skill_name">
              FRENCH
            </div>
            <div class="skill_progress">
              <span style="width: 70%;"></span>
            </div>
            <div class="skill_per">70%</div>
          </li>
        </ul>
       </div>
     </div>
  </div>
  <div class="resume_right">
    <div class="resume_item resume_about">
        <div class="title">
           <p class="bold">About me</p>
         </div>
        <p>Hello! My name is Marc López Vílchez. I was born on 10/11/2003, and I have a strong interest in learning and being able to help in any way.</p>
    </div>
    <div class="resume_item resume_work">
        <div class="title">
           <p class="bold">Work Experience</p>
         </div>
        <ul>
            <li>
                <div class="date">2020</div> 
                <div class="info">
                     <p class="semi-bold">Grup Món Web SL (Informàtica Llagostera).</p> 
                  <p>Internship in computer-related tasks, web page design, and advertising.</p>
                </div>
            </li>
            <li>
              <div class="date">2021 (June-August)</div>
              <div class="info">
                     <p class="semi-bold">Hostal La Marina.</p> 
                  <p>Performing receptionist services.</p>
                </div>
            </li>
            <li>
              <div class="date">2022-2023 (June-September)</div>
              <div class="info">
                     <p class="semi-bold">Caprabo S.A.</p> 
                  <p>Performing sales (cashier) and restocking services.</p>
                </div>
            </li>
        </ul>
    </div>
    <div class="resume_item resume_education">
      <div class="title">
           <p class="bold">Education</p>
         </div>
      <ul>
            <li>
                <div class="date">2015 - 2019</div> 
                <div class="info">
                     <p class="semi-bold">ESO (HIGHSCHOOL SFG)</p> 
                  <p>Secondary education.</p>
                </div>
            </li>
            <li>
              <div class="date">2019 - 2021</div>
              <div class="info">
                     <p class="semi-bold">Batxillerat (HIGHSCHOOL SFG)</p> 
                  <p>Studies in Batxillerat, technological branch.</p>
                </div>
            </li>
            <li>
              <div class="date">2021 - Current date</div>
              <div class="info">
                     <p class="semi-bold">GEINF (UDG)</p> 
                  <p>Bachelor's degree studies in Computer Engineering.</p>
                </div>
            </li>
        </ul>
    </div>
    <div class="resume_item resume_hobby">
      <div class="title">
           <p class="bold">Hobbies</p>
         </div>
      <ul>
          <li>
              <div class="info">
                <p>Passionate about computer science, I dedicate my free time to exploring new technologies and developing computer projects. I am also enthusiastic about cybersecurity and solving algorithmic problems. My constant interest in learning and innovating is a standout feature in my professional profile. </p>
              </div>
          </li>
      </ul>
    </div>
  </div>
</div>

</body>
</html>
