<?xml version="1.0" encoding="UTF-8"?>
<svg width="1200" height="320" viewBox="0 0 1200 320" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#141321">
        <animate attributeName="stop-color" values="#141321;#1f1b3a;#141321" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#1f1b3a">
        <animate attributeName="stop-color" values="#1f1b3a;#141321;#1f1b3a" dur="8s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#fe428e"/>
      <stop offset="100%" stop-color="#00d8ff"/>
    </linearGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <rect width="1200" height="320" rx="18" fill="url(#bgGrad)"/>
  <rect x="2" y="2" width="1196" height="316" rx="18" fill="none" stroke="url(#textGrad)" stroke-width="1.5" opacity="0.5"/>

  <!-- floating particles -->
  
    <circle cx="1074" cy="283" r="2.7" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="283;-19" dur="6.5s" begin="-8.6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.35;0" dur="6.5s" begin="-8.6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="978" cy="282" r="2.0" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="282;17" dur="5.2s" begin="-7.8s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.55;0" dur="5.2s" begin="-7.8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="447" cy="297" r="2.6" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="297;-8" dur="9.2s" begin="-5.8s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.52;0" dur="9.2s" begin="-5.8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="704" cy="305" r="1.2" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="305;35" dur="9.8s" begin="-3.0s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.47;0" dur="9.8s" begin="-3.0s" repeatCount="indefinite"/>
    </circle>
    <circle cx="579" cy="286" r="1.9" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="286;28" dur="5.6s" begin="-9.0s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.72;0" dur="5.6s" begin="-9.0s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1038" cy="288" r="1.3" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="288;31" dur="7.8s" begin="-8.8s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.76;0" dur="7.8s" begin="-8.8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="500" cy="297" r="2.9" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="297;-2" dur="8.7s" begin="-1.4s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.59;0" dur="8.7s" begin="-1.4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1141" cy="282" r="2.5" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="282;-18" dur="9.6s" begin="-0.1s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.73;0" dur="9.6s" begin="-0.1s" repeatCount="indefinite"/>
    </circle>
    <circle cx="523" cy="292" r="2.1" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="292;-3" dur="10.0s" begin="-8.4s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.48;0" dur="10.0s" begin="-8.4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1106" cy="288" r="3.1" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="288;24" dur="8.9s" begin="-3.9s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.39;0" dur="8.9s" begin="-3.9s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1166" cy="287" r="2.1" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="287;-10" dur="6.6s" begin="-0.7s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.64;0" dur="6.6s" begin="-0.7s" repeatCount="indefinite"/>
    </circle>
    <circle cx="644" cy="301" r="2.9" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="301;0" dur="9.7s" begin="-7.7s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.32;0" dur="9.7s" begin="-7.7s" repeatCount="indefinite"/>
    </circle>
    <circle cx="743" cy="292" r="1.3" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="292;-3" dur="10.5s" begin="-4.3s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.66;0" dur="10.5s" begin="-4.3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="637" cy="300" r="2.0" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="300;11" dur="10.5s" begin="-5.4s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.43;0" dur="10.5s" begin="-5.4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="672" cy="303" r="2.3" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="303;15" dur="9.5s" begin="-5.7s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.59;0" dur="9.5s" begin="-5.7s" repeatCount="indefinite"/>
    </circle>
    <circle cx="790" cy="287" r="2.2" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="287;-12" dur="5.5s" begin="-9.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.35;0" dur="5.5s" begin="-9.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1062" cy="285" r="2.6" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="285;30" dur="8.6s" begin="-6.2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.6;0" dur="8.6s" begin="-6.2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="899" cy="296" r="3.1" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="296;-4" dur="10.2s" begin="-9.9s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.66;0" dur="10.2s" begin="-9.9s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1118" cy="308" r="2.7" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="308;14" dur="9.6s" begin="-6.6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.45;0" dur="9.6s" begin="-6.6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="581" cy="294" r="3.1" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="294;-20" dur="10.3s" begin="-7.4s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.55;0" dur="10.3s" begin="-7.4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="602" cy="296" r="1.4" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="296;38" dur="8.8s" begin="-1.6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.55;0" dur="8.8s" begin="-1.6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="623" cy="284" r="2.7" fill="#a9fef7" opacity="0">
      <animate attributeName="cy" values="284;3" dur="8.2s" begin="-2.2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.57;0" dur="8.2s" begin="-2.2s" repeatCount="indefinite"/>
    </circle>

  <!-- neural network -->
  
    <line x1="70" y1="90" x2="180" y2="60" stroke="#fe428e" stroke-width="1.4"
          stroke-dasharray="6 10" opacity="0.55">
      <animate attributeName="stroke-dashoffset" values="16;0" dur="1.2s" begin="0.0s" repeatCount="indefinite"/>
    </line>
    <line x1="70" y1="90" x2="180" y2="125" stroke="#fe428e" stroke-width="1.4"
          stroke-dasharray="6 10" opacity="0.55">
      <animate attributeName="stroke-dashoffset" values="16;0" dur="1.2s" begin="0.12s" repeatCount="indefinite"/>
    </line>
    <line x1="70" y1="90" x2="180" y2="195" stroke="#fe428e" stroke-width="1.4"
          stroke-dasharray="6 10" opacity="0.55">
      <animate attributeName="stroke-dashoffset" values="16;0" dur="1.2s" begin="0.24s" repeatCount="indefinite"/>
    </line>
    <line x1="70" y1="90" x2="180" y2="260" stroke="#fe428e" stroke-width="1.4"
          stroke-dasharray="6 10" opacity="0.55">
      <animate attributeName="stroke-dashoffset" values="16;0" dur="1.2s" begin="0.36s" repeatCount="indefinite"/>
    </line>
    <line x1="70" y1="160" x2="180" y2="60" stroke="#fe428e" stroke-width="1.4"
          stroke-dasharray="6 10" opacity="0.55">
      <animate attributeName="stroke-dashoffset" values="16;0" dur="1.2s" begin="0.12s" repeatCount="indefinite"/>
    </line>
    <line x1="70" y1="160" x2="180" y2="125" stroke="#fe428e" stroke-width="1.4"
          stroke-dasharray="6 10" opacity="0.55">
      <animate attributeName="stroke-dashoffset" values="16;0" dur="1.2s" begin="0.24s" repeatCount="indefinite"/>
    </line>
    <line x1="70" y1="160" x2="180" y2="195" stroke="#fe428e" stroke-width="1.4"
          stroke-dasharray="6 10" opacity="0.55">
      <animate attributeName="stroke-dashoffset" values="16;0" dur="1.2s" begin="0.36s" repeatCount="indefinite"/>
    </line>
    <line x1="70" y1="160" x2="180" y2="260" stroke="#fe428e" stroke-width="1.4"
          stroke-dasharray="6 10" opacity="0.55">
      <animate attributeName="stroke-dashoffset" values="16;0" dur="1.2s" begin="0.48s" repeatCount="indefinite"/>
    </line>
    <line x1="70" y1="230" x2="180" y2="60" stroke="#fe428e" stroke-width="1.4"
          stroke-dasharray="6 10" opacity="0.55">
      <animate attributeName="stroke-dashoffset" values="16;0" dur="1.2s" begin="0.24s" repeatCount="indefinite"/>
    </line>
    <line x1="70" y1="230" x2="180" y2="125" stroke="#fe428e" stroke-width="1.4"
          stroke-dasharray="6 10" opacity="0.55">
      <animate attributeName="stroke-dashoffset" values="16;0" dur="1.2s" begin="0.36s" repeatCount="indefinite"/>
    </line>
    <line x1="70" y1="230" x2="180" y2="195" stroke="#fe428e" stroke-width="1.4"
          stroke-dasharray="6 10" opacity="0.55">
      <animate attributeName="stroke-dashoffset" values="16;0" dur="1.2s" begin="0.48s" repeatCount="indefinite"/>
    </line>
    <line x1="70" y1="230" x2="180" y2="260" stroke="#fe428e" stroke-width="1.4"
          stroke-dasharray="6 10" opacity="0.55">
      <animate attributeName="stroke-dashoffset" values="16;0" dur="1.2s" begin="0.6s" repeatCount="indefinite"/>
    </line>
    <line x1="180" y1="60" x2="290" y2="125" stroke="#00d8ff" stroke-width="1.4"
          stroke-dasharray="6 10" opacity="0.55">
      <animate attributeName="stroke-dashoffset" values="16;0" dur="1.2s" begin="0.5s" repeatCount="indefinite"/>
    </line>
    <line x1="180" y1="60" x2="290" y2="195" stroke="#00d8ff" stroke-width="1.4"
          stroke-dasharray="6 10" opacity="0.55">
      <animate attributeName="stroke-dashoffset" values="16;0" dur="1.2s" begin="0.62s" repeatCount="indefinite"/>
    </line>
    <line x1="180" y1="125" x2="290" y2="125" stroke="#00d8ff" stroke-width="1.4"
          stroke-dasharray="6 10" opacity="0.55">
      <animate attributeName="stroke-dashoffset" values="16;0" dur="1.2s" begin="0.62s" repeatCount="indefinite"/>
    </line>
    <line x1="180" y1="125" x2="290" y2="195" stroke="#00d8ff" stroke-width="1.4"
          stroke-dasharray="6 10" opacity="0.55">
      <animate attributeName="stroke-dashoffset" values="16;0" dur="1.2s" begin="0.74s" repeatCount="indefinite"/>
    </line>
    <line x1="180" y1="195" x2="290" y2="125" stroke="#00d8ff" stroke-width="1.4"
          stroke-dasharray="6 10" opacity="0.55">
      <animate attributeName="stroke-dashoffset" values="16;0" dur="1.2s" begin="0.74s" repeatCount="indefinite"/>
    </line>
    <line x1="180" y1="195" x2="290" y2="195" stroke="#00d8ff" stroke-width="1.4"
          stroke-dasharray="6 10" opacity="0.55">
      <animate attributeName="stroke-dashoffset" values="16;0" dur="1.2s" begin="0.86s" repeatCount="indefinite"/>
    </line>
    <line x1="180" y1="260" x2="290" y2="125" stroke="#00d8ff" stroke-width="1.4"
          stroke-dasharray="6 10" opacity="0.55">
      <animate attributeName="stroke-dashoffset" values="16;0" dur="1.2s" begin="0.86s" repeatCount="indefinite"/>
    </line>
    <line x1="180" y1="260" x2="290" y2="195" stroke="#00d8ff" stroke-width="1.4"
          stroke-dasharray="6 10" opacity="0.55">
      <animate attributeName="stroke-dashoffset" values="16;0" dur="1.2s" begin="0.98s" repeatCount="indefinite"/>
    </line>
  
    <circle cx="70" cy="90" r="7" fill="#00d8ff" opacity="0.85">
      <animate attributeName="r" values="7;10;7" dur="2.4s" begin="0.0s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;1;0.5" dur="2.4s" begin="0.0s" repeatCount="indefinite"/>
    </circle>
    <circle cx="70" cy="160" r="7" fill="#00d8ff" opacity="0.85">
      <animate attributeName="r" values="7;10;7" dur="2.4s" begin="0.15s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;1;0.5" dur="2.4s" begin="0.15s" repeatCount="indefinite"/>
    </circle>
    <circle cx="70" cy="230" r="7" fill="#00d8ff" opacity="0.85">
      <animate attributeName="r" values="7;10;7" dur="2.4s" begin="0.3s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;1;0.5" dur="2.4s" begin="0.3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="180" cy="60" r="7" fill="#fe428e" opacity="0.85">
      <animate attributeName="r" values="7;10;7" dur="2.4s" begin="0.3s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;1;0.5" dur="2.4s" begin="0.3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="180" cy="125" r="7" fill="#fe428e" opacity="0.85">
      <animate attributeName="r" values="7;10;7" dur="2.4s" begin="0.44999999999999996s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;1;0.5" dur="2.4s" begin="0.44999999999999996s" repeatCount="indefinite"/>
    </circle>
    <circle cx="180" cy="195" r="7" fill="#fe428e" opacity="0.85">
      <animate attributeName="r" values="7;10;7" dur="2.4s" begin="0.6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;1;0.5" dur="2.4s" begin="0.6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="180" cy="260" r="7" fill="#fe428e" opacity="0.85">
      <animate attributeName="r" values="7;10;7" dur="2.4s" begin="0.75s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;1;0.5" dur="2.4s" begin="0.75s" repeatCount="indefinite"/>
    </circle>
    <circle cx="290" cy="125" r="9" fill="#f8d847" opacity="0.85">
      <animate attributeName="r" values="9;12;9" dur="2.4s" begin="0.8s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;1;0.5" dur="2.4s" begin="0.8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="290" cy="195" r="9" fill="#f8d847" opacity="0.85">
      <animate attributeName="r" values="9;12;9" dur="2.4s" begin="0.9500000000000001s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;1;0.5" dur="2.4s" begin="0.9500000000000001s" repeatCount="indefinite"/>
    </circle>

  <!-- text -->
  <text x="420" y="155" font-family="Segoe UI, Helvetica, Arial, sans-serif" font-size="56" font-weight="700"
        fill="url(#textGrad)" filter="url(#glow)" letter-spacing="1">
    Aniket Yadav
  </text>
  <text x="420" y="195" font-family="Fira Code, Consolas, monospace" font-size="19" fill="#a9fef7" opacity="0.9">
    AI Explorer • Robotics Tinkerer • Forever Learning
  </text>
  <text x="420" y="225" font-family="Fira Code, Consolas, monospace" font-size="14" fill="#f8d847" opacity="0.8">
    &lt;/&gt; turning curiosity into code, one commit at a time
  </text>
</svg>h 

   
# 💫 Hi 👋, I'm Aniket:
💻 Code • Create • Innovate<br>🤖 AI | Robotics | Emerging Tech Explore<br>🧠 Fueled by curiosity & driven by innovation<br>🌱 Forever curious, forever learning
## 🌐 Socials:
[![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white)](https://discord.com/users/1333782637533204490) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aniket-yadav-569995302) [![Mastodon](https://img.shields.io/badge/-MASTODON-%232B90D9?logo=mastodon&logoColor=white)](https://mastodon.social/@Anii) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:aniketyvd@gmail.com) 
# 💻 Tech Stack:
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Netlify](https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7) ![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white) ![AmazonDynamoDB](https://img.shields.io/badge/Amazon%20DynamoDB-4053D6?style=for-the-badge&logo=Amazon%20DynamoDB&logoColor=white)
<!-- Snake Game Repo View -->

<div align="center">
  <img src="https://profile-readme-generator.com/assets/snake.svg" alt="Snake animation" />
</div>

# 📊 GitHub Stats:
![](https://github-readme-stats.shion.dev/api?username=Anixen&theme=radical&hide_border=true&include_all_commits=false&count_private=false)<br/>
![](https://streak-stats.demolab.com/?user=Anixen&theme=radical&hide_border=true)<br/>
![](https://github-readme-stats.shion.dev/api/top-langs/?username=Anixen&theme=radical&hide_border=true&include_all_commits=false&count_private=false&layout=compact)
## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=Anixen&theme=radical&no-frame=false&no-bg=true&margin-w=4)
### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)
### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=Anixen&limit=5&theme=dark&combine_all_yearly_contributions=true)
---
[![](https://komarev.com/ghpvc/?username=Anixen&icon=0&color=0)](https://visitcount.itsvg.in)
