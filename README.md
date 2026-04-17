# Super Trunfo Jogo de Comparação
# 🌍 Jogo dos Países (C - Console)

Este é um jogo simples feito em linguagem C onde o jogador enfrenta o computador em um sistema de comparação entre países, baseado em regras de “pedra, papel e tesoura” adaptadas para atributos econômicos.

---

## 🎮 Como funciona o jogo

O jogador escolhe um país e o computador escolhe outro aleatoriamente.  
Cada país representa um atributo:

- 🇨🇳 China → População  
- 🇨🇦 Canadá → PIB  
- 🇷🇺 Rússia → Área  

---

## 📌 Menu inicial

O programa começa com um menu:

- `1` → Iniciar jogo  
- `2` → Ver regras  
- `3` → Sair  

---

## 📜 Regras do jogo

O sistema funciona em ciclo de vantagem:

- 👥 População vence PIB  
- 💰 PIB vence Área  
- 📏 Área vence População  

---

## 🧠 Lógica do jogo

- O jogador escolhe um país
- O computador escolhe aleatoriamente (`rand() % 3 + 1`)
- Os dois são comparados
- O resultado é definido por regras de vitória

---

## ⚙️ Tecnologias usadas

- Linguagem C
- Biblioteca `stdlib.h` (aleatoriedade)
- Biblioteca `time.h` (seed do random)
- Estruturas de controle (`switch`, `if/else`)

---

🧾 Exemplo de execução
Menu Inicial!
1. Iniciar Jogo
2. Ver Regras
3. Sair
Escolha uma opção: 1

Jogo dos Países.
1. China
2. Canadá
3. Rússia
Boa Sorte!
🏆 Resultado possível
🤝 Empate → ambos escolhem o mesmo país
🎉 Vitória → regra favorece o jogador
❌ Derrota → computador vence pela regra
