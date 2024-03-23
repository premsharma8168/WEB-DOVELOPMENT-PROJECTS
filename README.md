<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BRIJ PUBLIC SCHOOL</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
  <link href="style.css" rel="stylesheet" type="text/css" />
<style>    CSS Reset
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    /* Global Styles */
    body {
      font-family: 'Poppins', sans-serif;
      line-height: 1.6;
      color: #333;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* Header Styles */
    .header {
      background-color: #2c3e50;
      color: #fff;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .header h2 {
      font-weight: 700;
      padding: 0.5rem 0;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
    }
    .NAME{
      font-size: 35px;}
    .logo {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      margin-right: 30px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
      animation: logo-spin 2s linear infinite;
    }


    .nav {
      list-style: none;
      display: flex;
    }

    .nav li {
      margin-right: 20px;
      position: relative;
    }

    .nav li::before {
      content: "";
      position: absolute;
      bottom: -5px;
      left: 0;
      width: 0%;
      height: 2px;
      background-color: #e67e22;
      transition: width 0.8s ease;
    }

    .nav li:hover::before {
      width: 100%;
    }

    .nav li:last-child {
      margin-right: 0;
    }

    .nav a {
      color: #fff;
      transition: color 0.3s ease;
    }

    .nav a:hover {
      color: #e67e22;
    }

    /* Main Content Styles */
    .main {
      display: grid;
      grid-template-columns: 1fr 3fr;
      grid-gap: 30px;
      padding: 30px;
    }

    .sidebar {
      background-color: #f1f1f1;
      padding: 20px;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    .sidebar h3 {
      margin-bottom: 10px;
      color: #2c3e50;
      text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.2);
    }

    .sidebar ul {
      list-style: none;
    }

    .sidebar li {
      margin-bottom: 10px;
      padding: 10px;
      background-color: #fff;
      border-radius: 5px;
      box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
    }

    .sidebar li:hover {
      transform: translateY(-5px);
    }

    .sidebar a {
      color: #2c3e50;
      transition: color 0.3s ease;
      font-weight: 600;
    }

    .sidebar a:hover {
      color: #e67e22;
    }

    .sidebar p {
      margin-top: 5px;
      font-size: 0.9rem;
      color: #666;
    }

    .content {
      background-color: #f1f1f1;
      padding: 20px;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    /* Footer Styles */
    footer {
      background-color: #2c3e50;
      color: #fff;
      padding: 30px;
      text-align: center;
    }

    .footer-content {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      max-width: 1200px;
      margin: 0 auto 20px;
    }

    .footer-section {
      flex: 1;
      margin-bottom: 20px;
      text-align: left;
    }

    .footer-section h2 {
      margin-bottom: 10px;
      text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.2);
    }

    .footer-section ul {
      list-style: none;
      padding: 0;
    }

    .footer-section li {
      margin-bottom: 5px;
    }

    .footer-section a {
      color: #fff;
      transition: color 0.3s ease;
    }

    .footer-section a:hover {
      color: #e67e22;
    }

    .social-icons a {
      display: inline-block;
      margin-right: 10px;
      font-size: 20px;
      color: #fff;
      transition: color 0.3s ease;
    }

    .social-icons a:hover {
      color: #e67e22;
      transform: scale(1.2);
    }

    .footer2 {
      margin-bottom: 20px;
    }

    .footer2 a {
      background-color: #e67e22;
      color: #fff;
      padding: 10px 20px;
      border-radius: 5px;
      transition: background-color 0.3s ease;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
    }

    .footer2 a:hover {
      background-color: #d35400;
      transform: scale(1.1);
    }

</style>
</head>
<body>
  <div class="header">
    <div>
      <img src="bps.jpg" alt="School Logo" class="logo">
    </div>
    <div class="NAME"><h2>BRIJ PUBLIC SCHOOL</h2></div>
    <ul class="nav">
      <li><a href="https://www.icbse.com/schools/brij-public-school-hodal-3pv9q">HOME</a></li>
      <li><a href="https://www.justdial.com/Palwal/Brij-Public-School-YC-Mohalla-Hodal-Rural-Hodal/9999P1275-1275-190419124838-K4U2_BZDET">About</a></li>
      <li><a href="https://schools.org.in/palwal/06211705026/brij-public-school-hodal.html">Academics</a></li>
      <li><a href="https://vidhyant.com/schools/1113259/Brij-Public-School-Hodal">Admissions</a></li>
      <li>+919416477145</li>
    </ul>
  </div>
  <div class="main">
    <div class="sidebar">
      <h3>News and Events</h3>
      <ul>
        <li>
          <h4>Annual Day Celebration</h4>
          <p>Our annual day celebration is a grand event where students showcase their talents through various performances, including dance, music, and drama.</p>
        </li>
        <li>
          <h4>Sports Day</h4>
          <p>The sports day is an exciting event where students participate in various athletic competitions, fostering a spirit of sportsmanship and healthy competition.</p>
        </li>
        <li>
          <h4>Science Fair</h4>
          <p>The science fair provides a platform for students to showcase their scientific projects, experiments, and innovations, encouraging their curiosity and love for science.</p>
        </li>
        <li>
          <h4>Cultural Fest</h4>
          <p>The cultural fest celebrates the rich diversity of our student community, showcasing traditional dances, music, and art from various cultures.</p>
        </li>
        <li>
          <h4>Parent-Teacher Meeting</h4>
          <p>Regular parent-teacher meetings are organized to foster open communication and collaboration between parents and teachers, ensuring the holistic development of our students.</p>
        </li>
      </ul>
      <div class="ad">
        <a href="https://vidhyant.com/schools/1113259/Brij-Public-School-Hodal"><img src="ad.jpg" alt="Admition" class="logo"></a>
      </div>
    </div>
    <div class="content">
      <div id="home">
        <h2>Welcome to Brij Academics Council.</h2>
        <p>Brij Public School Hodal is a co-educational school located in Hodal Tehsil, Haryana, India. The school was established in 1997 and is managed by the UNIIN Pvt. Unaided. It offers education from grades 1 to 8 and has an attached pre-primary section. The school is dedicated to providing quality education to students of all ages and has highly qualified teachers who are committed to providing quality education to their students.</p>
      </div>
      <div id="about">
        <h2>About Us</h2>
        <p>At Brij Public School, we believe in nurturing well-rounded individuals who are not only academically sound but also socially conscious and emotionally resilient. Our holistic approach to education focuses on developing the mind, body, and spirit of each student, equipping them with the skills and values necessary to thrive in the rapidly evolving world.</p>
        <p>Our dedicated faculty members are passionate about their subjects and employ innovative teaching methodologies to make learning an engaging and enjoyable experience. We foster an environment that encourages curiosity, critical thinking, and creativity, empowering our students to become lifelong learners.</p>
      </div>
      <div id="academics">
        <h2>Academics</h2>
        <p>At Brij Public School, we offer a comprehensive academic curriculum that aligns with the latest educational standards. Our academic programs are designed to challenge and inspire students, fostering intellectual growth and a love for learning.</p>
        <h3>Curriculum Overview</h3>
        <ul>
          <li>Core subjects: Language, Mathematics, Science, Social Studies</li>
          <li>Enrichment programs: Art, Music, Physical Education, Computer Science</li>
          <li>Co-curricular activities: Clubs, projects, and competitions</li>
          <li>Personalized learning support: Tutorials and remedial classes</li>
        </ul>
      </div>
      <div id="admissions">
        <h2>Admissions</h2>
        <p>We welcome applications from families who share our vision and values. To apply for admission to the school, you can visit the school's website or contact the school directly to obtain the application form. The application form must be filled out completely and submitted along with the required documents and fees. The school will then review your application and notify you of the admission decision.</p>
        <h3>Admission Process</h3>
        <ol>
          <li>Fill out the online application form</li>
          <li>Submit required documents</li>
          <li>Pay the application fee</li>
          <li>Attend the admission interview (if applicable)</li>
          <li>Receive the admission decision</li>
        </ol>
      </div>
      <div id="testimonials">
        <h2>Testimonials</h2>
        <div class="testimonial">
          <blockquote>"Brij Public School has been an excellent choice for our child's education. The dedicated faculty and nurturing environment have helped our child blossom academically and personally."</blockquote>
          <cite>- Vivek and Shruti Bhardwaj, Parents</cite>
        </div>
        <div class="testimonial">
          <blockquote>"The school's emphasis on holistic development, coupled with a rigorous academic curriculum, has prepared me for success in my future endeavors."</blockquote>
          <cite>- Parv jain, Alumni</cite>
        </div>
      </div>
    </div>
  </div>
  <footer>
    <div class="footer2">
      <a href="form.html">REGISTER HERE!!!</a>
    </div>
    <div class="footer-content">
      <div class="footer-section">
        <h2>Quick Links</h2>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About Us</a></li>
          <li><a href="#academics">Academics</a></li>
          <li><a href="#admissions">Admissions</a></li>
          <li><a href="#contact">Contact Us</a></li>
        </ul>
      </div>
      <div class="footer-section">
        <h2>Programs</h2>
        <ul>
          <li><a href="#">Elementary School</a></li>
          <li><a href="#">Middle School</a></li>
          <li><a href="#">High School</a></li>
          <li><a href="#">Extracurriculars</a></li>
        </ul>
      </div>
      <div class="footer-section" id="contact">
        <h2>Contact Us</h2>
        <p>y-c colony<br>Hodal 121106, HARYANA<br>Email:brijpublicschoolhodal@gmail.com <br>Phone:+91 9416477145,<br>+91 8168926020</p>
      </div>
      <div class="footer-section">
        <h2>Follow Us</h2>
        <div class="social-icons">
          <a href="#" target="_blank"><i class="fab fa-facebook-f"></i></a>
          <a href="#" target="_blank"><i class="fab fa-twitter"></i></a>
          <a href="#" target="_blank"><i class="fab fa-instagram"></i></a>
        </div>
      </div>
    </div>
    <p>&copy; 2024 BRIJ PUBLIC SCHOOL {HODAL}. All rights reserved.</p>
  </footer>
</body>
</html>
