<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Koushik - Full Stack Developer | AI/ML | Blockchain Security</title>
  <style>
    /* Basic reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Arial', sans-serif;
      background: #121212;
      color: #ffffff;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
    }

    /* Container */
    .container {
      text-align: center;
      max-width: 800px;
      padding: 20px;
      background: linear-gradient(135deg, #1E2A47, #2C3D66);
      border-radius: 15px;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
      animation: fadeIn 2s ease-out;
    }

    /* Heading Styling */
    h1 {
      font-size: 3rem;
      color: #4e9af1;
      margin-bottom: 20px;
      animation: slideIn 1s ease-out;
    }

    h2 {
      font-size: 1.5rem;
      color: #a3c4f3;
      margin-bottom: 20px;
    }

    p {
      font-size: 1rem;
      color: #d1d1d1;
      margin: 10px 0;
    }

    .cta-buttons a {
      padding: 10px 20px;
      margin: 5px;
      color: #fff;
      background-color: #3498db;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      transition: background-color 0.3s ease-in-out;
    }

    .cta-buttons a:hover {
      background-color: #2c87c8;
    }

    /* Tech Stack Grid */
    .tech-stack {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      margin-top: 30px;
    }

    .tech-stack div {
      background: #2c3e50;
      padding: 20px;
      border-radius: 8px;
      transition: transform 0.3s ease-in-out;
    }

    .tech-stack div:hover {
      transform: scale(1.1);
    }

    /* Animation keyframes */
    @keyframes fadeIn {
      0% {
        opacity: 0;
      }
      100% {
        opacity: 1;
      }
    }

    @keyframes slideIn {
      0% {
        transform: translateY(-30px);
      }
      100% {
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Hello, I'm <span style="color:#3498db">Koushik</span></h1>
    <h2>Full Stack Developer | AI/ML Enthusiast | Blockchain Security</h2>
    <p>Welcome to my GitHub Profile! I am passionate about creating efficient, scalable, and secure solutions using modern technologies.</p>
    
    <div class="cta-buttons">
      <a href="https://github.com/your-username" target="_blank">GitHub</a>
      <a href="https://www.linkedin.com/in/your-profile" target="_blank">LinkedIn</a>
      <a href="mailto:your-email@example.com">Email</a>
    </div>

    <section class="tech-stack">
      <div>React</div>
      <div>Node.js</div>
      <div>Next.js</div>
      <div>Express</div>
      <div>TailwindCSS</div>
      <div>Python</div>
      <div>Docker</div>
      <div>Kubernetes</div>
    </section>
  </div>

  <script>
    // Example of adding animation for the CTA Buttons
    const ctaButtons = document.querySelectorAll('.cta-buttons a');
    ctaButtons.forEach(button => {
      button.addEventListener('mouseover', () => {
        button.style.transform = 'scale(1.1)';
      });
      button.addEventListener('mouseout', () => {
        button.style.transform = 'scale(1)';
      });
    });
  </script>
</body>
</html>
