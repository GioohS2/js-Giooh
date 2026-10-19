# 🏓 Ping Pong

> Um simulador interativo de tênis de mesa bidimensional que roda diretamente no navegador. O projeto resolve o desafio de aplicar conceitos de física vetorial e detecção de colisões precisas em um ambiente web dinâmico.

## 📌 Índice
* [Visão Geral](#visão-geral)
* [Funcionalidades](#funcionalidades)
* [Tecnologias Utilizadas](#tecnologias-utilizadas)
* [Como Rodar o Projeto](#como-rodar-o-projeto)
* [Licença](#licença)

---

## 🔍 Visão Geral
>Este projeto foi desenvolvido para servir como um jogo de ping-pong casual e altamente fluido. Ele utiliza renderização gráfica baseada em canvas e cálculos matriciais em tempo real para simular as rebatidas da bolinha. O grande diferencial técnico é o uso de hitboxes customizadas, garantindo precisão matemática milimétrica quando a esfera atinge o retângulo da raquete.
---

## ✨ Funcionalidades
• Movimentação fluida das raquetes baseada em eventos do teclado/mouse.
• Motor de física para rebatidas angulares e cálculo de velocidade.
• Sistema matemático de detecção de colisão 2D entre raquetes e bolinhas.
• Gerenciamento e reprodução de efeitos sonoros estéreo durante as partidas.

---

## 💻 Tecnologias Utilizadas
• JavaScript (ES6+) - Linguagem base do projeto.
• p5.js (v1.9.2) - Framework para renderização gráfica e ciclo de renderização do Canvas.
• p5.sound (v1.0.1) - Biblioteca nativa para manipulação do AudioContext, mixers e efeitos sonoros.
• p5.collide2D (v0.7.3) - Biblioteca matemática para checagem vetorial e interceptação geométrica de hitboxes.



---

## 🚀 Como Rodar o Projeto

Pré-requisitos:Pré-requisitos: Você precisará ter o Git instalado na sua máquina para clonar o repositório. Por se tratar de uma aplicação front-end estática, um navegador Web moderno (Chrome, Firefox, Edge) é o suficiente.

1. Clone este repositório:
   ```bash
   git clone https://github.com
   ```
2. Entre na pasta do projeto:
   ```bash
   nome-do-projeto
   ```
3. Como o ecossistema utiliza scripts locais e processamento de som via requisições de áudio, recomenda-se rodar o projeto através de um servidor local (como a extensão Live Server do VS Code ou via comandos Python/Node).
 Caso prefira rodar por comando via Python, execute na raiz do projeto:
```bash
python -m http.server 8000
```

4. Abra o navegador e acesse http://localhost:8000
---

## 📝 Licença
Distribuído sob a licença MIT e parte dos algoritmos de colisão sob a CC BY-NC-SA 4.0 (derivada das mecânicas originais de Jeffrey Thompson). Veja o arquivo LICENSE para mais detalhes.
