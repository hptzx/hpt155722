<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f9f9f9;
    }

    .center {
        display: flex;
        justify-content: center;
        flex-direction: column;
        align-items: center;
    }

    .languageButton {
        background-color: #99b5dc;
        padding: 5px 10px;
        border-radius: 10px;
        color: white;
        font-weight: bold;
        margin: 5px;
    }

    .tagContainer {
        display: flex;
        flex-wrap: wrap;
        margin: 10px 0;
    }

    .websiteRow {
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .websiteContainer {
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 5px;
    }

    .portfolio {
        font-size: medium;
        text-align: right;
        margin: 0;
        padding: 0;
    }

    .webLink {
        background-color: #99b5dc;
        padding: 10px 15px;
        border-radius: 10px;
        color: white;
        text-decoration: none;
    }

    .webLink:hover {
        color: #ffe2f0;
        text-decoration: none !important;
    }

    .webLink:hover {
        text-decoration: underline;
    }

    .iframeContainer {
        display: flex;
        justify-content: center;
        gap: 20px;
    }

    iframe {
        border: 4px solid #3a3749;
        border-radius: 10px;
        width: 47%;
        height: 250; /* Set a fixed height for consistency */
    }

    img {
        width: 200px;
    }
</style>
</head>
<body>
  <div class="center">
      <img src="mongmong1.gif" />
      <h1>Hi, I'm Jinn ᯓ ⭑.ᐟ</h1>
  </div>

  <br>
  <h2># - Languages and Tools ─ !!</h2>
  <div class="tagContainer">
      <div class="languageButton">C++</div>
      <div class="languageButton">HTML</div>
      <div class="languageButton">CSS</div>
      <div class="languageButton">JavaScript</div>
      <div class="languageButton">PHP</div>
      <div class="languageButton">mySQL</div>
      <div class="languageButton">Node.js</div>
  </div>

  <br>
  <h2># - My Portfolio ─ !!</h2>
  <div class = 'websiteRow'>
    <img src="mongmong5.gif"/>
    <div class="websiteContainer">
        <h2>
            <a class="webLink" href="http://jinnha.com" target="_blank">jinnha.com</a>
        </h2>
    </div>

  </div>

  <h2># - My GitHub Stats ─ !!</h2>
  <div class="iframeContainer">
      <iframe src="https://github-readme-stats.vercel.app/api/top-langs/?username=hpt155722&theme=buefy&show_icons=true&hide_border=true&layout=compact" frameborder="0"></iframe>
      <iframe src="https://github-readme-streak-stats.herokuapp.com/?user=hpt155722&theme=buefy&hide_border=true" frameborder="0"></iframe>
  </div>
</body>
