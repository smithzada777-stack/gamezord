# 🎮 GameZord

> **Última atualização:** 31/05/2026 — 11:30 (horário local)

## 📋 Descrição
Clone completo do Agar.io com bots, dividir células (split), ejetar massa, física suave e zoom dinâmico. Modos Fácil, Médio e Difícil.

## 🎯 Objetivo
Começar pequeno, comer comida e células menores para crescer, dividir para capturar presas, e evitar ser comido.

## 🎮 Como Jogar
- **Mouse:** movimentar
- **Espaço:** dividir célula (split) — atira metade na direção do mouse
- **W:** ejetar massa (pequena bolinha que outros podem comer)
- Comece pequeno (raio 15) e cresça comendo comida e bots menores
- O zoom aumenta conforme você cresce
- Células separadas se juntam após ~15 segundos
- **Fácil:** 6 bots lentos | **Médio:** 10 bots | **Difícil:** 16 bots agressivos (alguns se dividem)

## 🌐 Deploy
- **Produção:** https://gamezord.vercel.app
- **GitHub:** https://github.com/smithzada777-stack/gamezord

## 📁 Estrutura do Projeto
```
game teste/
├── CONTEXTO.md
├── index.html     (jogo completo HTML + CSS + JS)
└── .gitignore
```

## 🧱 Pilha Tecnológica
- HTML5 Canvas
- JavaScript puro (zero dependências)
- Vercel (deploy estático)

## ✅ Funcionalidades
- [x] Mecânica Agar.io completa (comer, crescer, fugir)
- [x] Split (dividir célula com Espaço)
- [x] Ejetar massa (com W)
- [x] Zoom dinâmico baseado no tamanho
- [x] Física suave com velocidade inercial
- [x] Bots com IA (Easy/Medium/Hard)
- [x] Leaderboard ao vivo
- [x] Partículas visuais ao comer células
- [x] Modos Fácil, Médio e Difícil

---

*Este arquivo serve como registro de contexto e decisões do projeto.*
