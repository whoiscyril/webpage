---
permalink: /software/
title: "Software"
---

<style>
.coming-soon {
  text-align: center;
  padding: 50px 20px;
  font-family: 'Arial', sans-serif;
}

.pulse {
  animation: pulse 2s infinite;
  font-size: 3em;
  color: #0066cc;
  margin: 20px 0;
}

.loading-dots {
  display: inline-block;
  position: relative;
  width: 80px;
  height: 80px;
}

.loading-dots div {
  position: absolute;
  top: 33px;
  width: 13px;
  height: 13px;
  border-radius: 50%;
  background: #0066cc;
  animation-timing-function: cubic-bezier(0, 1, 1, 0);
}

.loading-dots div:nth-child(1) {
  left: 8px;
  animation: lds1 0.6s infinite;
}

.loading-dots div:nth-child(2) {
  left: 8px;
  animation: lds2 0.6s infinite;
}

.loading-dots div:nth-child(3) {
  left: 32px;
  animation: lds2 0.6s infinite;
}

.loading-dots div:nth-child(4) {
  left: 56px;
  animation: lds3 0.6s infinite;
}

@keyframes pulse {
  0% { transform: scale(1); }
  50% { transform: scale(1.1); }
  100% { transform: scale(1); }
}

@keyframes lds1 {
  0% { transform: scale(0); }
  100% { transform: scale(1); }
}

@keyframes lds3 {
  0% { transform: scale(1); }
  100% { transform: scale(0); }
}

@keyframes lds2 {
  0% { transform: translate(0, 0); }
  100% { transform: translate(24px, 0); }
}

.code-animation {
  font-family: 'Courier New', monospace;
  background: #f4f4f4;
  padding: 20px;
  margin: 30px auto;
  max-width: 500px;
  border-radius: 8px;
  border-left: 4px solid #0066cc;
}

.typing {
  overflow: hidden;
  white-space: nowrap;
  margin: 0 auto;
  border-right: 2px solid #0066cc;
  animation: typing 3.5s steps(40, end), blink-caret 0.75s step-end infinite;
}

@keyframes typing {
  from { width: 0 }
  to { width: 100% }
}

@keyframes blink-caret {
  from, to { border-color: transparent }
  50% { border-color: #0066cc }
}
</style>

<div class="coming-soon">
  <h1 class="pulse">🚀 Coming Soon!</h1>
  
  <div class="loading-dots">
    <div></div>
    <div></div>
    <div></div>
    <div></div>
  </div>
  
  <div class="code-animation">
    <div class="typing">def building_awesome_software():</div>
  </div>
  
</div>
