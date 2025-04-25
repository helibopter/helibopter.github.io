<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Course Catalog | M.O.R.E.</title>
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v6.1.1/css/all.css"/>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: #f8f9fa;
      color: #333;
    }
    header {
      background: #1b365d;
      color: white;
      padding: 1.5rem;
      text-align: center;
    }
    .catalog-container {
      max-width: 1100px;
      margin: 0 auto;
      padding: 2rem;
    }
    .catalog-title {
      text-align: center;
      margin-bottom: 2rem;
    }
    .course-listing {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      justify-content: center;
    }
    .course-card {
      background: white;
      border: 1px solid #ddd;
      border-radius: 8px;
      width: 320px;
      padding: 1.5rem;
      box-shadow: 0 2px 6px rgba(0,0,0,0.05);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }
    .course-card h3 {
      color: #1b365d;
      font-size: 1.25rem;
      margin-bottom: 1rem;
    }
    .course-card ul {
      padding-left: 1rem;
      margin: 0 0 1rem 0;
    }
    .course-card li {
      margin-bottom: 0.5rem;
    }
    .course-card a {
      margin-top: auto;
      text-decoration: none;
      color: #ffffff;
      background: #61ad00;
      padding: 0.5rem 1rem;
      text-align: center;
      border-radius: 5px;
      transition: background 0.3s ease;
    }
    .course-card a:hover {
      background: #4e8700;
    }
  </style>
</head>
<body>

  <header>
    <h1>M.O.R.E. Course Catalog</h1>
    <p>Explore our programs designed for middle and high school learners</p>
  </header>

  <div class="catalog-container">
    <h2 class="catalog-title">Academic Year Courses</h2>

    <div class="course-listing">

      <!-- Course 1 -->
      <div class="course-card">
        <h3>1-on-1 English Tutoring</h3>
        <ul>
          <li>Flexible, personalized scheduling</li>
          <li>Help with essays and school writing</li>
          <li>Tailored to individual needs</li>
        </ul>
        <a href="/courses/1-on-1-english-tutoring/">Learn More</a>
      </div>

      <!-- Course 2 -->
      <div class="course-card">
        <h3>English Workshops</h3>
        <ul>
          <li>Free, monthly deep dives</li>
          <li>Each workshop explores one specific topic</li>
          <li>Live Zoom instruction with slides & PDFs</li>
        </ul>
        <a href="/courses/english-workshops/">Learn More</a>
      </div>

      <!-- Course 3 -->
      <div class="course-card">
        <h3>Yearlong Language Arts</h3>
        <ul>
          <li>Free, full-year program</li>
          <li>Weekly classes + curriculum & breaks</li>
          <li>Great for advanced or honors prep</li>
        </ul>
        <a href="/courses/yearlong-language-arts/">Learn More</a>
      </div>

    </div>
  </div>

</body>
</html>
