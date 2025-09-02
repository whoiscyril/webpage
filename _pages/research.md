---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

<style>
.research-coming-soon {
  text-align: center;
  padding: 50px 20px;
  font-family: 'Arial', sans-serif;
}

.atom-animation {
  width: 150px;
  height: 150px;
  margin: 30px auto;
  position: relative;
}

.nucleus {
  width: 20px;
  height: 20px;
  background: #ff6b35;
  border-radius: 50%;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  box-shadow: 0 0 20px #ff6b35;
}

.orbit {
  position: absolute;
  border: 2px solid #0066cc;
  border-radius: 50%;
  opacity: 0.7;
}

.orbit-1 {
  width: 80px;
  height: 80px;
  top: 35px;
  left: 35px;
  animation: rotate 2s linear infinite;
}

.orbit-2 {
  width: 120px;
  height: 120px;
  top: 15px;
  left: 15px;
  animation: rotate 3s linear infinite reverse;
}

.orbit-3 {
  width: 140px;
  height: 140px;
  top: 5px;
  left: 5px;
  animation: rotate 4s linear infinite;
}

.electron {
  width: 8px;
  height: 8px;
  background: #00d4ff;
  border-radius: 50%;
  position: absolute;
  box-shadow: 0 0 10px #00d4ff;
}

.electron-1 {
  top: -4px;
  left: 36px;
}

.electron-2 {
  top: 56px;
  left: -4px;
}

.electron-3 {
  top: -4px;
  left: 66px;
}

@keyframes rotate {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}

.glow-text {
  animation: glow 2s ease-in-out infinite alternate;
  font-size: 3em;
  color: #0066cc;
  margin: 20px 0;
}

@keyframes glow {
  from { text-shadow: 0 0 10px #0066cc, 0 0 20px #0066cc; }
  to { text-shadow: 0 0 20px #0066cc, 0 0 30px #0066cc, 0 0 40px #0066cc; }
}

.molecular-formula {
  font-family: 'Times New Roman', serif;
  font-size: 1.5em;
  color: #333;
  margin: 20px 0;
  animation: fadeInOut 3s ease-in-out infinite;
}

@keyframes fadeInOut {
  0%, 100% { opacity: 0.5; }
  50% { opacity: 1; }
}
</style>

<div class="research-coming-soon">
  <h1 class="glow-text">✨ Research Coming Soon!</h1>
  
  <div class="atom-animation">
    <div class="nucleus"></div>
    <div class="orbit orbit-1">
      <div class="electron electron-1"></div>
    </div>
    <div class="orbit orbit-2">
      <div class="electron electron-2"></div>
    </div>
    <div class="orbit orbit-3">
      <div class="electron electron-3"></div>
    </div>
  </div>
  
</div>
