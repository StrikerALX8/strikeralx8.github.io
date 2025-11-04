<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>striker alx — projects</title>
  <style>
    body {
      background-color: #0d1117;
      color: #e6edf3;
      font-family: "Segoe UI", Arial, sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
    }
    header {
      text-align: center;
      padding: 80px 20px 40px;
    }
    header h1 {
      font-size: 2.5em;
      margin-bottom: 0.2em;
      color: #58a6ff;
    }
    header p {
      max-width: 700px;
      margin: 0 auto;
      color: #8b949e;
      font-size: 1.1em;
    }
    main {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
    }
    section h2 {
      font-size: 1.6em;
      border-bottom: 1px solid #30363d;
      padding-bottom: 5px;
      margin-bottom: 20px;
      color: #58a6ff;
    }
    ul.projects {
      list-style: none;
      padding: 0;
    }
    ul.projects li {
      background: #161b22;
      border: 1px solid #30363d;
      padding: 20px;
      border-radius: 10px;
      margin-bottom: 15px;
      transition: border 0.2s, background 0.2s;
    }
    ul.projects li:hover {
      border-color: #58a6ff;
      background: #1c2128;
    }
    ul.projects a {
      color: #58a6ff;
      font-size: 1.2em;
      text-decoration: none;
    }
    ul.projects p {
      margin-top: 8px;
      color: #8b949e;
      font-size: 0.95em;
    }
    footer {
      text-align: center;
      color: #8b949e;
      font-size: 0.9em;
      padding: 30px 0;
      border-top: 1px solid #30363d;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>striker alx</h1>
    <p>
      welcome to my project hub. this is where i post things i've worked on, experiments i've built, and random ideas that turned into something interesting. most of it’s just for fun, but some of it might actually be useful.
    </p>
  </header>

  <main>
    <section>
      <h2>projects</h2>
      <ul class="projects">
        <li>
          <a href="sab-visualizer.html">Steal a Brainrot Visualizer</a>
          <p>
            a fan-made visualizer that lets you choose any brainrot and mutation to see what it looks like. made for players who enjoy experimenting with different combinations and visual effects.
          </p>
        </li>

        <li>
          <a href="#">Another Project</a>
          <p>
            description for a future project. maybe something experimental or a small game mechanic test.
          </p>
        </li>

        <li>
          <a href="#">Small Utility Tool</a>
          <p>
            a lightweight script i made to automate or simplify something repetitive.
          </p>
        </li>
      </ul>
    </section>
  </main>

  <footer>
    © 2025 striker alx — all rights reserved
  </footer>
</body>
</html>
