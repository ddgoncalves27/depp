// Random Template System
const placeholderTemplates = {
    comingSoon: [
        {
            name: "Cosmic Countdown",
            html: `<!DOCTYPE html>
<html><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>Coming Soon</title>
<style>
body{margin:0;height:100vh;display:flex;align-items:center;justify-content:center;background:linear-gradient(135deg,#667eea 0%,#764ba2 100%);color:#fff;font-family:system-ui;overflow:hidden}
.stars{position:fixed;width:100%;height:100%;top:0;left:0}
.star{position:absolute;width:2px;height:2px;background:#fff;border-radius:50%;animation:twinkle 3s infinite}
@keyframes twinkle{0%,100%{opacity:0}50%{opacity:1}}
h1{font-size:4rem;margin:0;text-shadow:0 0 20px rgba(255,255,255,0.5);z-index:1}
p{font-size:1.5rem;opacity:0.8;z-index:1}
.content{text-align:center;z-index:1}
</style></head><body>
<div class="stars" id="stars"></div>
<div class="content"><h1>Coming Soon</h1><p>Something amazing is on its way</p></div>
<script>
const s=document.getElementById('stars');
for(let i=0;i<100;i++){
  const star=document.createElement('div');
  star.className='star';
  star.style.left=Math.random()*100+'%';
  star.style.top=Math.random()*100+'%';
  star.style.animationDelay=Math.random()*3+'s';
  s.appendChild(star);
}
</` + `script></body></html>`
        },
        {
            name: "Neon Glow",
            html: `<!DOCTYPE html>
<html><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>Coming Soon</title>
<style>
body{margin:0;height:100vh;display:flex;align-items:center;justify-content:center;background:#0a0a0a;font-family:system-ui}
h1{font-size:5rem;margin:0;color:#fff;text-transform:uppercase;letter-spacing:0.1em;animation:neon 2s ease-in-out infinite alternate}
@keyframes neon{
  from{text-shadow:0 0 10px #fff,0 0 20px #fff,0 0 30px #e60073,0 0 40px #e60073,0 0 50px #e60073,0 0 60px #e60073,0 0 70px #e60073}
  to{text-shadow:0 0 20px #fff,0 0 30px #ff4da6,0 0 40px #ff4da6,0 0 50px #ff4da6,0 0 60px #ff4da6,0 0 70px #ff4da6,0 0 80px #ff4da6}
}
</style></head><body><h1>Coming Soon</h1></body></html>`
        },
        {
            name: "Gradient Wave",
            html: `<!DOCTYPE html>
<html><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>Coming Soon</title>
<style>
body{margin:0;height:100vh;display:flex;align-items:center;justify-content:center;background:linear-gradient(-45deg,#ee7752,#e73c7e,#23a6d5,#23d5ab);background-size:400% 400%;animation:gradient 15s ease infinite;font-family:system-ui;color:#fff}
@keyframes gradient{0%{background-position:0% 50%}50%{background-position:100% 50%}100%{background-position:0% 50%}}
.container{text-align:center;backdrop-filter:blur(10px);background:rgba(255,255,255,0.1);padding:3rem;border-radius:20px}
h1{font-size:3.5rem;margin-bottom:1rem}
</style></head><body>
<div class="container"><h1>Coming Soon</h1><p>We're working on something awesome</p></div>
</body></html>`
        }
    ],
    
    maintenance: [
        {
            name: "Circuit Board",
            html: `<!DOCTYPE html>
<html><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>Maintenance Mode</title>
<style>
body{margin:0;height:100vh;display:flex;align-items:center;justify-content:center;background:#1a1a1a;color:#00ff00;font-family:'Courier New',monospace;overflow:hidden}
.circuit{position:absolute;width:100%;height:100%;opacity:0.1;background-image:repeating-linear-gradient(0deg,transparent,transparent 50px,#00ff00 50px,#00ff00 51px),repeating-linear-gradient(90deg,transparent,transparent 50px,#00ff00 50px,#00ff00 51px)}
.terminal{background:#000;padding:2rem;border:2px solid #00ff00;border-radius:10px;box-shadow:0 0 20px #00ff00;text-align:center}
h1{margin:0;font-size:2rem}
.blink{animation:blink 1s infinite}
@keyframes blink{0%,50%{opacity:1}51%,100%{opacity:0}}
</style></head><body>
<div class="circuit"></div>
<div class="terminal">
<h1>SYSTEM MAINTENANCE</h1>
<p>Running diagnostics<span class="blink">_</span></p>
</div></body></html>`
        },
        {
            name: "Tech Grid",
            html: `<!DOCTYPE html>
<html><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>Under Maintenance</title>
<style>
body{margin:0;height:100vh;display:flex;align-items:center;justify-content:center;background:#000;font-family:system-ui;overflow:hidden}
.grid{position:absolute;width:100%;height:100%;background-image:linear-gradient(rgba(0,255,255,0.1) 1px,transparent 1px),linear-gradient(90deg,rgba(0,255,255,0.1) 1px,transparent 1px);background-size:50px 50px;animation:move 10s linear infinite}
@keyframes move{0%{transform:translate(0,0)}100%{transform:translate(50px,50px)}}
.content{text-align:center;z-index:1;color:#0ff}
h1{font-size:3rem;margin:0;text-shadow:0 0 20px #0ff}
</style></head><body>
<div class="grid"></div>
<div class="content"><h1>MAINTENANCE MODE</h1><p>We'll be back shortly</p></div>
</body></html>`
        }
    ],
    
    error404: [
        {
            name: "Space Lost",
            html: `<!DOCTYPE html>
<html><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>404 - Lost in Space</title>
<style>
body{margin:0;height:100vh;display:flex;align-items:center;justify-content:center;background:#000;color:#fff;font-family:system-ui;overflow:hidden}
.astronaut{font-size:5rem;animation:float 6s ease-in-out infinite}
@keyframes float{0%,100%{transform:translateY(0) rotate(-5deg)}50%{transform:translateY(-20px) rotate(5deg)}}
.content{text-align:center;z-index:1}
h1{font-size:8rem;margin:0;background:linear-gradient(45deg,#f093fb,#f5576c);-webkit-background-clip:text;-webkit-text-fill-color:transparent}
</style></head><body>
<div class="content">
<div class="astronaut">👨‍🚀</div>
<h1>404</h1>
<p>Houston, we have a problem</p>
</div></body></html>`
        },
        {
            name: "Glitch 404",
            html: `<!DOCTYPE html>
<html><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>404 Error</title>
<style>
body{margin:0;height:100vh;display:flex;align-items:center;justify-content:center;background:#000;color:#fff;font-family:monospace;overflow:hidden}
h1{font-size:8rem;margin:0;position:relative}
h1:before,h1:after{content:'404';position:absolute;top:0;left:0;right:0;background:#000;overflow:hidden}
h1:before{animation:glitch-1 0.5s infinite;color:#00ffff;z-index:-1}
h1:after{animation:glitch-2 0.5s infinite;color:#ff00ff;z-index:-2}
@keyframes glitch-1{0%{clip:rect(132px,auto,101px,30px)}5%{clip:rect(17px,auto,94px,0)}10%{clip:rect(40px,auto,66px,0)}15%{clip:rect(87px,auto,82px,0)}20%{clip:rect(137px,auto,61px,0)}25%{clip:rect(34px,auto,14px,0)}30%{clip:rect(133px,auto,74px,0)}35%{clip:rect(76px,auto,107px,0)}40%{clip:rect(59px,auto,130px,0)}45%{clip:rect(29px,auto,84px,0)}50%{clip:rect(22px,auto,67px,0)}55%{clip:rect(67px,auto,62px,0)}60%{clip:rect(10px,auto,105px,0)}65%{clip:rect(78px,auto,115px,0)}70%{clip:rect(105px,auto,13px,0)}75%{clip:rect(15px,auto,75px,0)}80%{clip:rect(66px,auto,39px,0)}85%{clip:rect(133px,auto,73px,0)}90%{clip:rect(36px,auto,128px,0)}95%{clip:rect(68px,auto,103px,0)}100%{clip:rect(14px,auto,100px,0)}}
@keyframes glitch-2{0%{clip:rect(129px,auto,36px,0)}5%{clip:rect(36px,auto,4px,0)}10%{clip:rect(85px,auto,66px,0)}15%{clip:rect(91px,auto,91px,0)}20%{clip:rect(148px,auto,138px,0)}25%{clip:rect(38px,auto,122px,0)}30%{clip:rect(69px,auto,54px,0)}35%{clip:rect(98px,auto,71px,0)}40%{clip:rect(146px,auto,34px,0)}45%{clip:rect(134px,auto,43px,0)}50%{clip:rect(102px,auto,80px,0)}55%{clip:rect(119px,auto,44px,0)}60%{clip:rect(106px,auto,99px,0)}65%{clip:rect(141px,auto,74px,0)}70%{clip:rect(20px,auto,78px,0)}75%{clip:rect(133px,auto,79px,0)}80%{clip:rect(78px,auto,52px,0)}85%{clip:rect(35px,auto,39px,0)}90%{clip:rect(67px,auto,70px,0)}95%{clip:rect(71px,auto,103px,0)}100%{clip:rect(83px,auto,40px,0)}}
</style></head><body>
<div><h1>404</h1><p>Page not found</p></div>
</body></html>`
        }
    ],
    
    construction: [
        {
            name: "Building Site",
            html: `<!DOCTYPE html>
<html><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>Under Construction</title>
<style>
body{margin:0;height:100vh;display:flex;align-items:center;justify-content:center;background:#ffd93d;font-family:system-ui;color:#333}
.container{text-align:center}
.icon{font-size:5rem;margin-bottom:1rem}
h1{font-size:3rem;margin:0}
.stripe{position:absolute;width:100%;height:80px;background:repeating-linear-gradient(45deg,#333,#333 20px,#ffd93d 20px,#ffd93d 40px);opacity:0.1}
</style></head><body>
<div class="stripe" style="top:0"></div>
<div class="stripe" style="bottom:0"></div>
<div class="container">
<div class="icon">🚧</div>
<h1>Under Construction</h1>
<p>We're building something great!</p>
</div></body></html>`
        }
    ],
    
    loading: [
        {
            name: "Pulse Loader",
            html: `<!DOCTYPE html>
<html><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>Loading...</title>
<style>
body{margin:0;height:100vh;display:flex;align-items:center;justify-content:center;background:#2c3e50;font-family:system-ui}
.loader{width:120px;height:120px;border-radius:50%;border:3px solid transparent;border-top-color:#3498db;animation:spin 2s linear infinite}
.loader:before{content:"";position:absolute;top:5px;left:5px;right:5px;bottom:5px;border-radius:50%;border:3px solid transparent;border-top-color:#e74c3c;animation:spin 3s linear infinite}
.loader:after{content:"";position:absolute;top:15px;left:15px;right:15px;bottom:15px;border-radius:50%;border:3px solid transparent;border-top-color:#f9c922;animation:spin 1.5s linear infinite}
@keyframes spin{0%{transform:rotate(0deg)}100%{transform:rotate(360deg)}}
p{position:absolute;color:#ecf0f1;font-size:1.2rem;margin-top:200px}
</style></head><body>
<div class="loader"></div>
<p>Loading...</p>
</body></html>`
        }
    ],
    
    offline: [
        {
            name: "Ocean Wave",
            html: `<!DOCTYPE html>
<html><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>Offline</title>
<style>
body{margin:0;height:100vh;display:flex;align-items:center;justify-content:center;background:linear-gradient(to bottom,#87CEEB 0%,#1e3c72 100%);font-family:system-ui;color:#fff;overflow:hidden}
.wave{position:absolute;bottom:0;left:0;width:100%;height:100px;background:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 1200 120' preserveAspectRatio='none'%3E%3Cpath d='M321.39,56.44c58-10.79,114.16-30.13,172-41.86,82.39-16.72,168.19-17.73,250.45-.39C823.78,31,906.67,72,985.66,92.83c70.05,18.48,146.53,26.09,214.34,3V0H0V27.35A600.21,600.21,0,0,0,321.39,56.44Z' fill='%23ffffff'/%3E%3C/svg%3E");background-size:cover;animation:wave 10s linear infinite}
@keyframes wave{0%{transform:translateX(0)}100%{transform:translateX(-1200px)}}
.content{text-align:center;z-index:1}
h1{font-size:3rem;margin-bottom:1rem}
</style></head><body>
<div class="wave"></div>
<div class="content">
<h1>🌊 Offline</h1>
<p>You're currently offline. Check your connection.</p>
</div></body></html>`
        }
    ],
    
    beta: [
        {
            name: "Beta Launch",
            html: `<!DOCTYPE html>
<html><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>Beta Version</title>
<style>
body{margin:0;height:100vh;display:flex;align-items:center;justify-content:center;background:linear-gradient(135deg,#667eea 0%,#764ba2 100%);font-family:system-ui;color:#fff}
.container{text-align:center;padding:3rem;background:rgba(255,255,255,0.1);backdrop-filter:blur(10px);border-radius:20px;box-shadow:0 8px 32px rgba(0,0,0,0.1)}
.badge{display:inline-block;background:#fff;color:#667eea;padding:0.5rem 1.5rem;border-radius:50px;font-weight:bold;margin-bottom:1rem}
h1{font-size:3rem;margin:0.5rem 0}
</style></head><body>
<div class="container">
<span class="badge">BETA</span>
<h1>Early Access</h1>
<p>You're getting a sneak peek at our latest features!</p>
</div></body></html>`
        }
    ],
    
    scheduled: [
        {
            name: "Countdown Timer",
            html: `<!DOCTYPE html>
<html><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>Scheduled Maintenance</title>
<style>
body{margin:0;height:100vh;display:flex;align-items:center;justify-content:center;background:#1a1a2e;font-family:system-ui;color:#eee}
.container{text-align:center}
h1{font-size:2.5rem;margin-bottom:2rem}
.timer{display:flex;justify-content:center;gap:2rem}
.time-block{background:#16213e;padding:2rem;border-radius:10px;min-width:100px}
.time-value{font-size:3rem;font-weight:bold;color:#0f4c75}
.time-label{font-size:0.875rem;text-transform:uppercase;opacity:0.7}
</style></head><body>
<div class="container">
<h1>Scheduled Maintenance</h1>
<div class="timer">
<div class="time-block"><div class="time-value" id="hours">02</div><div class="time-label">Hours</div></div>
<div class="time-block"><div class="time-value" id="minutes">30</div><div class="time-label">Minutes</div></div>
<div class="time-block"><div class="time-value" id="seconds">00</div><div class="time-label">Seconds</div></div>
</div>
</div>
<script>
let totalSeconds = 9000;
setInterval(() => {
  if(totalSeconds > 0) {
    totalSeconds--;
    const hours = Math.floor(totalSeconds / 3600);
    const minutes = Math.floor((totalSeconds % 3600) / 60);
    const seconds = totalSeconds % 60;
    document.getElementById('hours').textContent = String(hours).padStart(2, '0');
    document.getElementById('minutes').textContent = String(minutes).padStart(2, '0');
    document.getElementById('seconds').textContent = String(seconds).padStart(2, '0');
  }
}, 1000);
</` + `script></body></html>`
        }
    ]
};

// Function to get random template
function getRandomPlaceholderTemplate() {
    const categories = Object.keys(placeholderTemplates);
    const randomCategory = categories[Math.floor(Math.random() * categories.length)];
    const templates = placeholderTemplates[randomCategory];
    const randomTemplate = templates[Math.floor(Math.random() * templates.length)];
    
    return {
        category: randomCategory,
        name: randomTemplate.name,
        html: randomTemplate.html
    };
}

// Export to global scope for use in index.html
window.placeholderTemplates = placeholderTemplates;
window.getRandomPlaceholderTemplate = getRandomPlaceholderTemplate;
