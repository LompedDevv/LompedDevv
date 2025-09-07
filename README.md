[README_portfolio_LOMPEDDEVV.md](https://github.com/user-attachments/files/22198489/README_portfolio_LOMPEDDEVV.md)
<!-- README PORTFÓLIO - LOMPEDDEVV -->

<div align="center">

<!-- Hero with a for-the-badge shield as a header -->
<img src="https://img.shields.io/badge/💻-LOMPEDDEVV-ff7b54?style=for-the-badge&logo=roblox" alt="LOMPEDDEVV" />

<h1 align="center">LOMPEDDEVV</h1>
<p align="center"><strong>DEVELOPER DE ROBLOX STUDIO</strong> • 🚀 <strong>1B+ DE VISITAS CONTRIBUÍDAS</strong></p>

</div>

---

<div align="center">

<!-- Gradient banner (SVG data-uri) -->
<img alt="gradient-banner" src="data:image/svg+xml;utf8,
<svg xmlns='http://www.w3.org/2000/svg' width='900' height='140'>
  <defs>
    <linearGradient id='g' x1='0' x2='1'>
      <stop offset='0' stop-color='%23ff7b54'/>
      <stop offset='0.5' stop-color='%236a11cb'/>
      <stop offset='1' stop-color='%2300b4db'/>
    </linearGradient>
    <filter id='f' height='130%'><feGaussianBlur stdDeviation='6' /></filter>
  </defs>
  <rect x='10' y='10' rx='18' ry='18' width='880' height='120' fill='url(%23g)' filter='url(%23f)' opacity='0.95'/>
  <text x='50%' y='55%' dominant-baseline='middle' text-anchor='middle' font-family='Verdana' font-size='28' fill='white'>PORTFÓLIO · LOMPEDDEVV</text>
  <text x='50%' y='78%' dominant-baseline='middle' text-anchor='middle' font-family='Verdana' font-size='14' fill='rgba(255,255,255,0.85)'>DEVELOPING IMMERSIVE ROBLOX EXPERIENCES · LUA · LIVE EVENTS · OPTIMIZATION</text>
</svg>" style="max-width:100%; border-radius:18px;"/>

</div>

---

## ✨ SOBRE MIM
Sou o **LOMPEDDEVV**, um **DEVELOPER DE ROBLOX STUDIO** focado em experiências imersivas, otimização e sistemas escaláveis. Já contribuí para **1B+ DE VISITAS**, trabalhando em projetos com foco em retenção e performance.

## 🖌️ ESTILO VISUAL (UI CORNER & GRADIENTS)
Este README simula um **site único** com:
- Banner com **gradients** e bordas arredondadas (UI corner)
- Seções limpas e “cards” (use screenshots/gifs dos jogos para substituir os placeholders)
- Badges para destacar tecnologias e métricas

---

## 🛠️ HABILIDADES
- **Luau (Lua)** — Scripting modular e patterns reutilizáveis.  
- **Game Design & Level Design** — Loops de gameplay, economia e balanceamento.  
- **Live Events & Cutscenes** — Pipelines de câmeras, triggers e animações.  
- **Otimização** — Streaming, memory budget, perf counters.  
- **Versionamento & CI** — Git, Actions, deploys automatizados.

---

## 🚀 PROJETOS EM DESTAQUE
<div align="center">

<!-- Cards side-by-side: use images/screenshots -->
<table>
  <tr>
    <td align="center" width="33%">
      <img src="https://img.shields.io/badge/Dark%20Forest-Escape-6a11cb?style=for-the-badge" alt="Dark Forest"/><br/>
      <strong>Dark Forest Escape</strong><br/>
      Terror com IA dinâmica e cutscenes.<br/>
      <a href="https://www.roblox.com/games/0000000">VER NO ROBLOX</a>
    </td>
    <td align="center" width="33%">
      <img src="https://img.shields.io/badge/Metro-Tycoon-00b4db?style=for-the-badge" alt="Metro Tycoon"/><br/>
      <strong>Metro Tycoon</strong><br/>
      Tycoon otimizado para servidores públicos.<br/>
      <a href="https://www.roblox.com/games/0000000">VER NO ROBLOX</a>
    </td>
    <td align="center" width="33%">
      <img src="https://img.shields.io/badge/Arena-Blitz-ff7b54?style=for-the-badge" alt="Arena Blitz"/><br/>
      <strong>Arena Blitz</strong><br/>
      PvP com sistema modular e matchmaking.<br/>
      <a href="https://www.roblox.com/games/0000000">VER NO ROBLOX</a>
    </td>
  </tr>
</table>

</div>

---

## 📊 MÉTRICAS & BADGES
<div align="center">
![](https://img.shields.io/badge/Luau-LUA-blue?style=flat-square) ![](https://img.shields.io/badge/Roblox%20Studio-ROBLOX%20STUDIO-brightgreen?style=flat-square) ![](https://img.shields.io/badge/Git-GIT-orange?style=flat-square) ![](https://img.shields.io/badge/1B%2B-Visitas-purple?style=flat-square)
</div>

---

## 💡 EXEMPLOS DE CÓDIGO (Luau)
```lua
-- Simple Signal module (Luau)
local Signal = {}
Signal.__index = Signal

function Signal.new()
    return setmetatable({ _handlers = {} }, Signal)
end

function Signal:Connect(fn)
    table.insert(self._handlers, fn)
    return function()
        for i, h in ipairs(self._handlers) do
            if h == fn then
                table.remove(self._handlers, i)
                break
            end
        end
    end
end

function Signal:Fire(...)
    for _, h in ipairs(self._handlers) do
        task.spawn(h, ...)
    end
end

return Signal
```

---

---

## 📫 CONTATO
- **Roblox:** https://www.roblox.com/users/8989941827/profile  
- **Discord:** lompedd

---

<sub>Feito com 💜 — quer que eu gere o `README.md` direto no seu repositório (arquivo pronto para colar)? Posso também criar as imagens de banner/gifs se quiser.</sub>
