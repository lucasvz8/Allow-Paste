# 👑 Allow-Paste
🔧 Stable:
```javascript
javascript:(function(){fetch('https://raw.githubusercontent.com/lucasvz8/Allow-Paste/main/main.js').then(r=>r.text()).then(t=>{let s=document.createElement('script');s.textContent=t;document.documentElement.appendChild(s)}).catch(e=>alert('Erro ao carregar o script: '+e));})();
