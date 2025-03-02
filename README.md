<!-- Contribution Graph - Professional Tech-Themed Animated Version -->
<h2 align="center">
  <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> 
  My GitHub Contributions
  <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30">
</h2>

<div align="center">
  <!-- Custom SVG for animated contribution graph -->
  <svg width="800" height="300" viewBox="0 0 800 300" xmlns="http://www.w3.org/2000/svg">
    <style>
      .grid { stroke: #1a1a2e; stroke-width: 0.5; }
      .axis { stroke: #4a4e69; stroke-width: 1; }
      .label { fill: #ff5678; font-family: 'Courier New', monospace; font-size: 12px; }
      .title { fill: #ff5678; font-family: 'Courier New', monospace; font-size: 20px; font-weight: bold; }
      .data-line { fill: none; stroke: #00ffff; stroke-width: 3; filter: drop-shadow(0 0 6px #00ffff); }
      .data-point { fill: #ff5678; r: 5; filter: drop-shadow(0 0 4px #ff5678); }
      .data-point-highlight { fill: #ffffff; r: 7; filter: drop-shadow(0 0 8px #ffffff); }
      .data-value { fill: #ffffff; font-family: 'Courier New', monospace; font-size: 10px; }
      
      @keyframes pulse {
        0% { opacity: 0.7; r: 5; }
        50% { opacity: 1; r: 6; }
        100% { opacity: 0.7; r: 5; }
      }
      
      @keyframes glow {
        0% { filter: drop-shadow(0 0 3px #00ffff); }
        50% { filter: drop-shadow(0 0 8px #00ffff); }
        100% { filter: drop-shadow(0 0 3px #00ffff); }
      }
      
      @keyframes highlight {
        0% { filter: drop-shadow(0 0 5px #ffffff); }
        50% { filter: drop-shadow(0 0 15px #ffffff); }
        100% { filter: drop-shadow(0 0 5px #ffffff); }
      }
      
      .data-point {
        animation: pulse 2s infinite;
      }
      
      .data-line {
        animation: glow 3s infinite;
      }
      
      .data-point-highlight {
        animation: highlight 2s infinite;
      }
    </style>
    
    <!-- Background -->
    <rect width="800" height="300" fill="#0d1117" rx="10" ry="10" />
    
    <!-- Grid lines -->
    <g class="grid">
      <!-- Horizontal grid lines -->
      <line x1="50" y1="50" x2="750" y2="50" />
      <line x1="50" y1="75" x2="750" y2="75" />
      <line x1="50" y1="100" x2="750" y2="100" />
      <line x1="50" y1="125" x2="750" y2="125" />
      <line x1="50" y1="150" x2="750" y2="150" />
      <line x1="50" y1="175" x2="750" y2="175" />
      <line x1="50" y1="200" x2="750" y2="200" />
      <line x1="50" y1="225" x2="750" y2="225" />
      <line x1="50" y1="250" x2="750" y2="250" />
      
      <!-- Vertical grid lines -->
      <line x1="75" y1="50" x2="75" y2="250" />
      <line x1="100" y1="50" x2="100" y2="250" />
      <line x1="125" y1="50" x2="125" y2="250" />
      <line x1="150" y1="50" x2="150" y2="250" />
      <line x1="175" y1="50" x2="175" y2="250" />
      <line x1="200" y1="50" x2="200" y2="250" />
      <line x1="225" y1="50" x2="225" y2="250" />
      <line x1="250" y1="50" x2="250" y2="250" />
      <line x1="275" y1="50" x2="275" y2="250" />
      <line x1="300" y1="50" x2="300" y2="250" />
      <line x1="325" y1="50" x2="325" y2="250" />
      <line x1="350" y1="50" x2="350" y2="250" />
      <line x1="375" y1="50" x2="375" y2="250" />
      <line x1="400" y1="50" x2="400" y2="250" />
      <line x1="425" y1="50" x2="425" y2="250" />
      <line x1="450" y1="50" x2="450" y2="250" />
      <line x1="475" y1="50" x2="475" y2="250" />
      <line x1="500" y1="50" x2="500" y2="250" />
      <line x1="525" y1="50" x2="525" y2="250" />
      <line x1="550" y1="50" x2="550" y2="250" />
      <line x1="575" y1="50" x2="575" y2="250" />
      <line x1="600" y1="50" x2="600" y2="250" />
      <line x1="625" y1="50" x2="625" y2="250" />
      <line x1="650" y1="50" x2="650" y2="250" />
      <line x1="675" y1="50" x2="675" y2="250" />
      <line x1="700" y1="50" x2="700" y2="250" />
      <line x1="725" y1="50" x2="725" y2="250" />
    </g>
    
    <!-- Axes -->
    <g class="axis">
      <line x1="50" y1="250" x2="750" y2="250" />
      <line x1="50" y1="50" x2="50" y2="250" />
    </g>
    
    <!-- Y-axis labels -->
    <g class="label">
      <text x="35" y="250" text-anchor="end">0</text>
      <text x="35" y="225" text-anchor="end">2</text>
      <text x="35" y="200" text-anchor="end">4</text>
      <text x="35" y="175" text-anchor="end">6</text>
      <text x="35" y="150" text-anchor="end">8</text>
      <text x="35" y="125" text-anchor="end">10</text>
      <text x="35" y="100" text-anchor="end">12</text>
      <text x="35" y="75" text-anchor="end">14</text>
      <text x="35" y="50" text-anchor="end">16</text>
    </g>
    
    <!-- X-axis labels (days) -->
    <g class="label">
      <text x="75" y="270" text-anchor="middle">1</text>
      <text x="125" y="270" text-anchor="middle">5</text>
      <text x="175" y="270" text-anchor="middle">9</text>
      <text x="225" y="270" text-anchor="middle">13</text>
      <text x="275" y="270" text-anchor="middle">17</text>
      <text x="325" y="270" text-anchor="middle">21</text>
      <text x="375" y="270" text-anchor="middle">25</text>
      <text x="425" y="270" text-anchor="middle">29</text>
      <text x="475" y="270" text-anchor="middle">2</text>
      <text x="525" y="270" text-anchor="middle">6</text>
      <text x="575" y="270" text-anchor="middle">10</text>
      <text x="625" y="270" text-anchor="middle">14</text>
      <text x="675" y="270" text-anchor="middle">18</text>
      <text x="725" y="270" text-anchor="middle">22</text>
    </g>
    
    <!-- Title -->
    <text x="400" y="30" text-anchor="middle" class="title">Sakhr Wahib's Contribution Graph</text>
    
    <!-- Data line -->
    <path class="data-line" d="M75,250 L100,250 L125,250 L150,250 L175,250 L200,250 L225,250 L250,250 L275,250 L300,250 L325,250 L350,250 L375,250 L400,250 L425,250 L450,250 L475,250 L500,250 L525,250 L550,250 L575,225 L600,150 L625,250 L650,100 L675,250 L700,200 L725,250" />
    
    <!-- Data points -->
    <g>
      <circle cx="75" cy="250" class="data-point" />
      <circle cx="100" cy="250" class="data-point" />
      <circle cx="125" cy="250" class="data-point" />
      <circle cx="150" cy="250" class="data-point" />
      <circle cx="175" cy="250" class="data-point" />
      <circle cx="200" cy="250" class="data-point" />
      <circle cx="225" cy="250" class="data-point" />
      <circle cx="250" cy="250" class="data-point" />
      <circle cx="275" cy="250" class="data-point" />
      <circle cx="300" cy="250" class="data-point" />
      <circle cx="325" cy="250" class="data-point" />
      <circle cx="350" cy="250" class="data-point" />
      <circle cx="375" cy="250" class="data-point" />
      <circle cx="400" cy="250" class="data-point" />
      <circle cx="425" cy="250" class="data-point" />
      <circle cx="450" cy="250" class="data-point" />
      <circle cx="475" cy="250" class="data-point" />
      <circle cx="500" cy="250" class="data-point" />
      <circle cx="525" cy="250" class="data-point" />
      <circle cx="550" cy="250" class="data-point" />
      <circle cx="575" cy="225" class="data-point" />
      <circle cx="600" cy="150" class="data-point-highlight" />
      <circle cx="625" cy="250" class="data-point" />
      <circle cx="650" cy="100" class="data-point-highlight" />
      <circle cx="675" cy="250" class="data-point" />
      <circle cx="700" cy="200" class="data-point" />
      <circle cx="725" cy="250" class="data-point" />
    </g>
    
    <!-- Data values for highlighted points -->
    <g class="data-value">
      <text x="575" y="215" text-anchor="middle">3</text>
      <text x="600" y="140" text-anchor="middle">10</text>
      <text x="650" y="90" text-anchor="middle">14</text>
      <text x="700" y="190" text-anchor="middle">4</text>
    </g>
    
    <!-- Y-axis label -->
    <text x="20" y="150" text-anchor="middle" class="label" transform="rotate(-90, 20, 150)">Contributions</text>
    
    <!-- X-axis label -->
    <text x="400" y="290" text-anchor="middle" class="label">Days</text>
  </svg>
</div>

<!-- Alternative Animated Contribution Graph using GitHub's API -->
<div align="center">
  <br>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=SakhrWahib&bg_color=0d1117&color=00ffff&line=ff5678&point=ffffff&area=true&hide_border=true" width="95%" alt="Contribution Graph">
  
  <style>
    img[alt="Contribution Graph"] {
      border-radius: 10px;
      box-shadow: 0 0 15px #00ffff;
      animation: border-glow 3s infinite;
    }
    
    @keyframes border-glow {
      0% { box-shadow: 0 0 5px #00ffff; }
      50% { box-shadow: 0 0 20px #00ffff, 0 0 30px #ff5678; }
      100% { box-shadow: 0 0 5px #00ffff; }
    }
  </style>
</div>

<!-- Tech-themed animated contribution calendar -->
<div align="center">
  <br>
  <h3>
    <img src="https://media.giphy.com/media/3oKIPtjEDeyIUTxO6I/giphy.gif" width="25"> 
    Contribution Calendar
    <img src="https://media.giphy.com/media/3oKIPtjEDeyIUTxO6I/giphy.gif" width="25">
  </h3>
  
  <img src="https://github-contribution-graph.ez4o.com/?username=SakhrWahib&theme=matrix&weeks=30&gap=1&point_border=none&stroke=1&frame=true" width="95%" alt="Contribution Calendar">
  
  <style>
    img[alt="Contribution Calendar"] {
      border-radius: 10px;
      box-shadow: 0 0 15px #00ff00;
      animation: calendar-pulse 4s infinite;
    }
    
    @keyframes calendar-pulse {
      0% { filter: brightness(0.9) hue-rotate(0deg); }
      50% { filter: brightness(1.1) hue-rotate(30deg); }
      100% { filter: brightness(0.9) hue-rotate(0deg); }
    }
  </style>
</div>

<!-- 3D Contribution Stats -->
<div align="center">
  <br>
  <h3>
    <img src="https://media.giphy.com/media/l46Cy1rHbQ92uuLXa/giphy.gif" width="25"> 
    3D Contribution Stats
    <img src="https://media.giphy.com/media/l46Cy1rHbQ92uuLXa/giphy.gif" width="25">
  </h3>
  
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=SakhrWahib&theme=radical&hide_border=true&background=0D1117&stroke=00FFFF&ring=FF5678&fire=FF5678&currStreakNum=FFFFFF&sideNums=00FFFF&currStreakLabel=FF5678&sideLabels=00FFFF&dates=FFFFFF" alt="GitHub Streak Stats" />
  
  <style>
    img[alt="GitHub Streak Stats"] {
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(255, 86, 120, 0.5);
      transform: perspective(1000px) rotateX(5deg);
      transition: transform 0.3s;
      animation: float 6s ease-in-out infinite;
    }
    
    img[alt="GitHub Streak Stats"]:hover {
      transform: perspective(1000px) rotateX(0deg) scale(1.02);
    }
    
    @keyframes float {
      0% { transform: perspective(1000px) rotateX(5deg) translateY(0px); }
      50% { transform: perspective(1000px) rotateX(5deg) translateY(-10px); }
      100% { transform: perspective(1000px) rotateX(5deg) translateY(0px); }
    }
  </style>
</div>
