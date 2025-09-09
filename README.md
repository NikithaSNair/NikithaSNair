<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nikitha S Nair | Portfolio</title>
  <!-- Tailwind CSS CDN for styling -->
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap');
body {
      font-family: 'Inter', sans-serif;
      background-color: #0D1117;
      color: #E2E8F0;
      overflow-x: hidden;
    }
   /* Starfield canvas background */
    #starfield {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: -1;
    }
/* Custom fade-in animations for a sleek entrance */
    .fade-in {
      opacity: 0;
      animation: fadeIn 1s ease-out forwards;
      animation-delay: var(--delay, 0s);
    }
    @keyframes fadeIn {
      to {
        opacity: 1;
      }
    }
    .slide-in-up {
      opacity: 0;
      transform: translateY(20px);
      animation: slideInUp 0.8s ease-out forwards;
      animation-delay: var(--delay, 0s);
    }
    @keyframes slideInUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    /* Floating text animation */
    .float-text {
      animation: float 4s ease-in-out infinite;
    }
    @keyframes float {
      0% { transform: translateY(0px); }
      50% { transform: translateY(-10px); }
      100% { transform: translateY(0px); }
    }
    /* Additional custom styles */
    .card {
      background-color: rgba(13, 17, 23, 0.7);
      border: 1px solid rgba(226, 232, 240, 0.1);
      backdrop-filter: blur(8px);
    }
    .line-divider {
      background-color: rgba(226, 232, 240, 0.2);
    }
    h1, h2, h3 {
      font-weight: 700;
    }
    .project-link:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body class="p-4 md:p-8">

<canvas id="starfield"></canvas>

<div class="max-w-4xl mx-auto space-y-12">


  <header class="text-center space-y-4 fade-in" style="--delay: 0.2s;">
    <h3 class="text-xl md:text-2xl font-semibold text-gray-300 float-text" align="center">It's Half code and half chaos.</h3>
    <p class="text-lg md:text-xl text-gray-400" align="center">Crafting on the web, scaling the cloud, and thriving in the unknown. 🌙👩‍💻☁️</p>
  </header>
  
  <div class="h-1 bg-gray-700 w-full rounded-full line-divider slide-in-up" style="--delay: 0.4s;"></div>


  <section class="card p-6 md:p-8 rounded-xl space-y-6 slide-in-up" style="--delay: 0.6s;">
    <h2 class="text-3xl font-bold">About Me</h2>
    <div class="space-y-4 text-lg">
      <p>🔭 I'm currently working on building projects that are out of this world.</p>
      <p>🌌 I'm always learning new technologies and exploring the digital frontier.</p>
      <p>💬 You can reach out to me via email at <a href="mailto:nikithasanthoshnair@gmail.com" class="text-indigo-400 hover:text-indigo-300 transition">nikithasanthoshnair@gmail.com</a></p>
      <p>✍ You can find my resume <a href="https://drive.google.com/file/d/1_s5sx7HmfF5Rq2Hap1cwrwXwHellFOeY/view?usp=drive_link" class="text-indigo-400 hover:text-indigo-300 transition" target="_blank">here↗</a></p>
    </div>
  </section>
  
  <div class="h-1 bg-gray-700 w-full rounded-full line-divider slide-in-up" style="--delay: 0.8s;"></div>

  
  <section class="card p-6 md:p-8 rounded-xl space-y-6 slide-in-up" style="--delay: 1s;">
    <h2 class="text-3xl font-bold">My Skills</h2>
    <p class="text-center">
      <img src="https://skillicons.dev/icons?i=python,java,html,react,css,js,vscode,tailwindcss,github,git,bash,npm,bun,netlify,notion,vite,postman,figma,java" alt="Skills" class="mx-auto" />
      <br>
      <p class="text-lg text-gray-400">🚀 More skills are on the way...</p>
    </p>
  </section>

  <div class="h-1 bg-gray-700 w-full rounded-full line-divider slide-in-up" style="--delay: 1.2s;"></div>

  
  <section class="card p-6 md:p-8 rounded-xl space-y-6 slide-in-up" style="--delay: 1.4s;">
    <h2 class="text-3xl font-bold">Project Glimpse</h2>
    
  <div class="space-y-4">
      <h4 class="text-2xl font-semibold">1. 🪐 First Project: Pokemon Team Builder</h4>
      <p class="text-lg text-gray-400">A Pokémon team builder application.</p>
      <ul class="list-disc list-inside space-y-2">
        <li><strong>Technologies used:</strong> <span class="bg-gray-700 px-2 py-1 rounded text-sm">Typescript</span>, <span class="bg-gray-700 px-2 py-1 rounded text-sm">HTML</span>, <span class="bg-gray-700 px-2 py-1 rounded text-sm">CSS</span>, <span class="bg-gray-700 px-2 py-1 rounded text-sm">JavaScript</span></li>
        <li><a href="https://pokemon-trn3.vercel.app/" class="text-indigo-400 hover:text-indigo-300 transition project-link" target="_blank"><strong>View Live Demo ↗</strong></a></li>
        <li><a href="https://github.com/NikithaSNair/Pokemon" class="text-indigo-400 hover:text-indigo-300 transition project-link" target="_blank"><strong>Project Repository</strong></a></li>
      </ul>
    </div>
    
   <div class="space-y-4">
      <h4 class="text-2xl font-semibold">2. 🌌 Second Project: Peek-A-Git</h4>
      <p class="text-lg text-gray-400">An application that displays the account details of a GitHub user.</p>
      <ul class="list-disc list-inside space-y-2">
        <li><strong>Technologies used:</strong> <span class="bg-gray-700 px-2 py-1 rounded text-sm">API</span>, <span class="bg-gray-700 px-2 py-1 rounded text-sm">React</span>, <span class="bg-gray-700 px-2 py-1 rounded text-sm">Typescript</span>, <span class="bg-gray-700 px-2 py-1 rounded text-sm">Vite</span></li>
        <li><a href="https://api-task-kappa.vercel.app/" class="text-indigo-400 hover:text-indigo-300 transition project-link" target="_blank"><strong>View Live Demo ↗</strong></a></li>
        <li><a href="https://github.com/NikithaSNair/API-task" class="text-indigo-400 hover:text-indigo-300 transition project-link" target="_blank"><strong>Project Repository</strong></a></li>
      </ul>
    </div>
  </section>

  <div class="h-1 bg-gray-700 w-full rounded-full line-divider slide-in-up" style="--delay: 1.6s;"></div>


  <div align="center" class="slide-in-up" style="--delay: 1.8s;">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/NikithaSNair/NikithaSNair/output/github-snake-dark.svg" />
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/NikithaSNair/NikithaSNair/output/github-snake.svg" />
      <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/NikithaSNair/NikithaSNair/output/github-snake.svg" class="mx-auto"/>
    </picture>
  </div>

  <div class="h-1 bg-gray-700 w-full rounded-full line-divider slide-in-up" style="--delay: 2s;"></div>

  <section class="card p-6 md:p-8 rounded-xl space-y-6 slide-in-up" style="--delay: 2.2s;">
    <h2 class="text-3xl font-bold text-center">GitHub Galaxy Stats</h2>
    <div class="flex flex-col md:flex-row items-center justify-center space-y-6 md:space-y-0 md:space-x-8">
      <div class="space-y-4 text-center">
        <img src="https://github-readme-stats.vercel.app/api?username=NikithaSNair&theme=midnight-purple&show_icons=true&count_private=true&include_all_commits=false" alt="Nikitha S Nair's GitHub stats" class="w-full h-auto rounded-lg"/>
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=NikithaSNair&theme=midnight-purple&hide_border=false" alt="GitHub Streaks" class="w-full h-auto rounded-lg"/>
      </div>
      <div>
        <img src="https://github-readme-stats.anuraghazra1.vercel.app/api/top-langs/?username=NikithaSNair&theme=midnight-purple&hide_border=false&no-bg=true&no-frame=true&langs_count=10" alt="Nikitha S Nair's Top Languages" class="w-full h-auto rounded-lg"/>
      </div>
    </div>
    
  <div align="center" class="w-full">
      <img width="868px" src="https://github-readme-activity-graph.vercel.app/graph?username=NikithaSNair&theme=react-dark" alt="Nikitha S Nair"/>
    </div>
  </section>

  <div class="h-1 bg-gray-700 w-full rounded-full line-divider slide-in-up" style="--delay: 2.4s;"></div>

  
  <section class="card p-6 md:p-8 rounded-xl space-y-6 slide-in-up" style="--delay: 2.6s;">
    <h2 class="text-3xl font-bold text-center" align="center">Connect with me</h2>
    <p class="flex justify-center space-x-4" align="center">
      <a href="https://www.linkedin.com/in/nikitha-s-nair-b111882b6" target="_blank" class="transition transform hover:scale-110">
        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge" />
      </a>
      <a href="https://www.instagram.com/nikitha_santhoshh?igsh=MWQ2MDhwM28zeWxweQ==" target="_blank" class="transition transform hover:scale-110">
        <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram Badge" />
      </a>
    </p>
  </section>

  <div class="h-1 bg-gray-700 w-full rounded-full line-divider slide-in-up" style="--delay: 2.8s;"></div>
</div>

<script>
  window.onload = function() {
    const canvas = document.getElementById('starfield');
    const ctx = canvas.getContext('2d');
    let stars = [];
    const numStars = 1500;
    const maxSpeed = 1.5;

    function resizeCanvas() {
      canvas.width = window.innerWidth;
      canvas.height = window.innerHeight;
      createStars();
    }

    function createStars() {
      stars = [];
      for (let i = 0; i < numStars; i++) {
        stars.push({
          x: Math.random() * canvas.width,
          y: Math.random() * canvas.height,
          size: Math.random() * 1.5,
          speed: Math.random() * maxSpeed + 0.1,
          opacity: Math.random() * 0.8 + 0.2
        });
      }
    }

    function animate() {
      ctx.clearRect(0, 0, canvas.width, canvas.height);
      ctx.fillStyle = '#0D1117';
      ctx.fillRect(0, 0, canvas.width, canvas.height);

      ctx.fillStyle = 'white';
      stars.forEach(star => {
        star.y += star.speed;
        if (star.y > canvas.height) {
          star.y = 0;
          star.x = Math.random() * canvas.width;
          star.size = Math.random() * 1.5;
          star.speed = Math.random() * maxSpeed + 0.1;
        }
        ctx.beginPath();
        ctx.arc(star.x, star.y, star.size, 0, Math.PI * 2);
        ctx.globalAlpha = star.opacity;
        ctx.fill();
      });

      requestAnimationFrame(animate);
    }

    window.addEventListener('resize', resizeCanvas);
    resizeCanvas();
    animate();
  };
</script>

</body>
</html>
