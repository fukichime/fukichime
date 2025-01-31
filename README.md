<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Page Title</title>
  <style>
    body {
      font-family: sans-serif; /* Use a default font */
      margin: 0; /* Remove default body margins */
    }
    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .typing-svg {
      margin-bottom: 20px;
    }
    .main-content {
      display: flex;
      width: 100%; /* Or a specific width */
      margin-bottom: 20px;
    }
    .text-column {
      width: 50%;
      padding: 20px;
      display: flex;
      flex-direction: column;
    }
    .gif-column {
      width: 50%;
      padding: 20px;
      display: flex;
      justify-content: flex-end; /* Align GIF to right */
      align-items: flex-start; /* Align GIF to top */
    }
    .gif-image {
      max-width: 360px; /* Limit GIF width */
    }
    .social-links {
      display: flex;
      margin-top: 10px;
    }
    .social-links img {
      width: 40px;
      height: 40px;
      margin-right: 10px;
    }
    .stats-graphs {
      display: flex;
      margin-bottom: 20px;
    }
    .stats-graphs img {
      height: 150px;
      margin: 0 10px; /* Add some space between graphs */
    }
    .kirby-gif {
      width: 250px;
    }
  </style>
</head>
<body>

<div class="container">

  <div class="typing-svg">
    <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=40&pause=1000&color=84BEF7&width=435&height=60&lines=hello!+I'm+Esra!" alt="Typing SVG" /></a>
  </div>

  <div class="main-content">
    <div class="text-column">
      <p>
        >> I'm a Computer Engineering graduate from Bahçeşehir University.<br>
        >> Currently focused on expanding my skillset in software and related technologies.<br>
        >> Feel free to reach out through my socials if you share similar interests or have any exciting projects in mind.<br>
        >> <a href="mailto:aygn.esranur@gmail.com"><b>email</b></a>
      </p>
      <div class="social-links">
        <a href="https://www.linkedin.com/in/esranur-ayg%C3%BCn-22056418b/" target="_blank"><img src="assets/download.png" alt="linkedin logo" /></a>
        <a href="https://www.hackerrank.com/profile/Katszura" target="_blank"><img src="assets/imageshackerrank.png" alt="hackerrank logo" /></a>
        <a href="https://leetcode.com/u/fukichime/" target="_blank"><img src="assets/images.png" alt="leetcode logo" /></a>
      </div>
    </div>
    <div class="gif-column">
      <img src="assets/rekall.gif" class="gif-image" alt="Rekall GIF">
    </div>
  </div>

  <div class="stats-graphs">
    <img src="https://github-readme-stats.vercel.app/api?username=fukichime&hide_title=true&hide_rank=true&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=material-palenight&locale=en&hide_border=false&order=1&custom_title=Stats" alt="stats graph" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs?username=fukichime&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=material-palenight&hide_border=false&order=2" alt="languages graph" />
  </div>

  <div>
    <img src="assets/kirby-dance-kirby-victory.gif" class="kirby-gif" alt="Kirby GIF">
  </div>

</div>

</body>
</html>
