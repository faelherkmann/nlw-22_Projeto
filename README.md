# 🎬 ClipMaker AI

> Transforme vídeos longos em cortes virais com inteligência artificial, precisão cirúrgica e um toque de magia digital.

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-blue)
![HTML](https://img.shields.io/badge/HTML-5-orange)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![Gemini API](https://img.shields.io/badge/IA-Gemini_API-purple)
![Cloudinary](https://img.shields.io/badge/Cloudinary-media_management-red)

---

## 🚀 Sobre o Projeto

O ClipMaker AI é uma aplicação web criada durante o NLW 22 da Rocketseat com foco em automatizar a criação de cortes virais para redes sociais.

A ideia é simples: o usuário envia um vídeo, define algumas preferências e a IA entra em cena para identificar os melhores momentos, gerar sugestões de cortes e transformar conteúdo longo em vídeos curtos, rápidos e prontos para performar no TikTok, Reels e Shorts.

Agora o projeto também conta com:

- 🌙 Modo Dark e Light
- ⏱️ Definição de duração do corte em até 60 segundos
- 🎯 Escolha manual do ponto inicial do corte
- 🤖 Caso o usuário não escolha o início, a IA decide automaticamente o melhor trecho

O objetivo é transformar horas de edição manual em poucos cliques.

---

## 🧠 Tecnologias Utilizadas

### 🌐 HTML5
Estrutura toda a aplicação, organizando componentes, formulários, botões, áreas de upload e visualização.

### 🎨 CSS3
Responsável pela estilização do projeto, incluindo:

- Layout responsivo
- Efeitos visuais
- Organização dos elementos
- Modo Dark e Light
- Experiência visual mais moderna e agradável

### ⚡ JavaScript
O cérebro da aplicação.

Com JavaScript foi possível:

- Capturar eventos do usuário
- Controlar upload de vídeos
- Manipular inputs
- Gerenciar troca de tema
- Validar duração dos cortes
- Definir ponto inicial do vídeo
- Consumir APIs externas
- Integrar inteligência artificial ao fluxo do projeto

### 🤖 Gemini API
A Gemini API entra como motor de inteligência artificial do projeto.

Ela é utilizada para:

- Interpretar o contexto do vídeo
- Identificar momentos mais interessantes
- Gerar sugestões de cortes
- Escolher automaticamente trechos quando o usuário não define manualmente
- Tornar o processo mais rápido e inteligente

### ☁️ Cloudinary
O Cloudinary é utilizado para armazenamento e manipulação de mídia.

Com ele é possível:

- Fazer upload de vídeos
- Gerenciar arquivos na nuvem
- Facilitar a exibição e recuperação dos vídeos processados
- Melhorar a performance no carregamento

---

## 🛠️ Funcionalidades

- Upload de vídeos
- Geração de cortes virais com IA
- Escolha manual do início do corte
- Definição de duração máxima do corte
- Sugestão automática de cortes
- Interface responsiva
- Alternância entre Dark Mode e Light Mode
- Integração com APIs externas
- Processamento inteligente de conteúdo

---

## 🎯 Fluxo da Aplicação

```text
Usuário envia vídeo
        ↓
Escolhe duração e início do corte
        ↓
Caso não escolha, IA decide automaticamente
        ↓
Gemini analisa o conteúdo
        ↓
Cloudinary armazena o vídeo
        ↓
Aplicação gera o corte final
