<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>NUJES – Free JAMB Support Portal</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f4f7f9;
      color: #222;
      line-height: 1.6;
    }

    header {
      background: #0a7d3b;
      color: white;
      padding: 25px;
      text-align: center;
    }

    header h1 { margin: 0; }

    .toggle-btn {
      margin-top: 10px;
      padding: 8px 15px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      background: white;
      color: #0a7d3b;
      font-weight: bold;
    }

    section {
      padding: 20px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      margin-bottom: 20px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    h2 { color: #0a7d3b; }

    .subjects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
    }

    .subject {
      background: #e9f5ee;
      padding: 15px;
      border-radius: 8px;
      font-weight: bold;
    }

    a {
      color: #0a7d3b;
      text-decoration: none;
    }

    a:hover { text-decoration: underline; }

    input, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 8px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }

    button.submit {
      background: #0a7d3b;
      color: white;
      border: none;
      padding: 10px;
      margin-top: 10px;
      border-radius: 5px;
      cursor: pointer;
      width: 100%;
    }

    footer {
      background: #0a7d3b;
      color: white;
      text-align: center;
      padding: 15px;
      font-size: 14px;
    }
  </style>
</head>

<body>

<header>
  <h1 id="title">NUJES Free JAMB Support Portal</h1>
  <p id="subtitle">Helping Jama’are Emirate Students Prepare for JAMB – 100% Free</p>
  <button class="toggle-btn" onclick="toggleLang()">Hausa / English</button>
</header>

<section class="card">
  <h2 id="aboutTitle">About This Platform</h2>
  <p id="aboutText">
    This platform is created by the National Union of Jama’are Emirate Students (NUJES)
    to support students and parents with free JAMB past questions, free books,
    guidance, and trusted educational resources.
  </p>
</section>

<section class="card">
  <h2>📘 JAMB Subjects</h2>

  <h3>🧪 Science</h3>
  <div class="subjects">
    <div class="subject">Mathematics</div>
    <div class="subject">English</div>
    <div class="subject">Physics</div>
    <div class="subject">Chemistry</div>
    <div class="subject">Biology</div>
  </div>

  <h3>🌍 Social Science</h3>
  <div class="subjects">
    <div class="subject">Economics</div>
    <div class="subject">Government</div>
    <div class="subject">Geography</div>
    <div class="subject">CRS / IRS</div>
  </div>

  <h3>🎨 Arts</h3>
  <div class="subjects">
    <div class="subject">Literature</div>
    <div class="subject">Hausa</div>
    <div class="subject">Arabic</div>
    <div class="subject">History</div>
    <div class="subject">Fine Arts</div>
  </div>
</section>

<section class="card">
  <h2>📥 Free JAMB Past Questions & Books</h2>

  <ul>
    <li>
      📘 <strong>All Subjects – Past Questions</strong><br>
      <a href="https://myschool.ng/classroom/jamb" target="_blank">
        Myschool (Free JAMB Past Questions)
      </a>
    </li><br>

    <li>
      🧪 <strong>CBT Practice Questions</strong><br>
      <a href="https://pass.ng/jamb" target="_blank">
        Pass.ng Free CBT Practice
      </a>
    </li><br>

    <li>
      📄 <strong>Past Question PDFs</strong><br>
      <a href="https://exampastquestions.com.ng/jamb-past-questions/" target="_blank">
        Download Free PDFs
      </a>
    </li><br>

    <li>
      📚 <strong>Free Study Books</strong><br>
      <a href="https://openlibrary.org" target="_blank">
        Open Library – Free Textbooks
      </a>
    </li>
  </ul>

  <p style="font-size:14px;">
    ⚠️ NUJES does not sell or own these materials. All links are free educational resources.
  </p>
</section>

<section class="card">
  <h2>🎯 JAMB Guidance</h2>
  <ul>
    <li>How to prepare for JAMB effectively</li>
    <li>Correct subject combinations</li>
    <li>Common mistakes students make</li>
    <li>How to manage time in CBT exams</li>
    <li>Study tips for scoring 250+</li>
  </ul>
</section>

<section class="card">
  <h2>🗣 Feedback & Support</h2>
  <form action="https://formspree.io/f/yourFormID" method="POST">
    <input type="text" name="name" placeholder="Your Name" required>
    <input type="email" name="email" placeholder="Your Email" required>
    <textarea name="message" placeholder="Your Message"></textarea>
    <button class="submit">Send Message</button>
  </form>
</section>

<footer>
  © 2026 NUJES | Free Educational Support | Not Officially Affiliated with JAMB
</footer>

<script>
  let hausa = false;

  function toggleLang() {
    hausa = !hausa;

    document.getElementById("title").innerText =
      hausa ? "Shafin Tallafin JAMB na NUJES (Kyauta)" : "NUJES Free JAMB Support Portal";

    document.getElementById("subtitle").innerText =
      hausa ? "Tallafa wa Daliban Masarautar Jama’are Kyauta" :
              "Helping Jama’are Emirate Students Prepare for JAMB – 100% Free";

    document.getElementById("aboutTitle").innerText =
      hausa ? "Game da Wannan Shafi" : "About This Platform";

    document.getElementById("aboutText").innerText =
      hausa
        ? "NUJES ta kirkiro wannan shafi domin taimaka wa dalibai da iyaye da past questions, littattafai da shawarwari kyauta."
        : "This platform is created by the National Union of Jama’are Emirate Students (NUJES) to support students and parents with free resources.";
  }
</script>

</body>
</html>
