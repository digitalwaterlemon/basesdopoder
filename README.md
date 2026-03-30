# 🎯 Raio-X da Liderança: Poder e Influência

Bem-vindo ao repositório do **Raio-X da Liderança**, uma aplicação web interativa desenvolvida para mapear as tendências comportamentais de líderes e empreendedores. 

Esta ferramenta foi idealizada e desenvolvida por **Raphael Furlan**, inspirada nos aprendizados e metodologias vivenciados no **EMPRETEC 2026**.

## 📖 Sobre o Projeto

O aplicativo é a digitalização e modernização do clássico teste de **Bases do Poder Social** (desenvolvido originalmente pelos psicólogos John R. P. French e Bertram Raven). Ele permite que o usuário distribua pontos entre situações práticas do dia a dia corporativo e, em seguida, gera um diagnóstico profundo sobre seu estilo de liderança.

### 🚀 Principais Funcionalidades
* **Interface Dinâmica (Single-Slider):** UX moderna que obriga o usuário a tomar decisões claras, eliminando respostas neutras.
* **Gráfico de Radar Interativo:** Geração de gráfico em tempo real (via Chart.js) mostrando a distribuição dos 63 pontos nas 7 bases de poder.
* **Diagnóstico Inteligente:** O sistema lê as faixas de pontuação e entrega feedbacks personalizados para cada base (Coerção, Ligação, Competência, Informação, Posição, Identificação e Recompensa).
* **Mapeamento de Arquétipos:** Um algoritmo cruza os dados do usuário com 7 perfis clássicos de liderança corporativa, entregando um "Mapa da Mina" com plano de ação, dicas de livros, vídeos e pontos de atenção.
* **Geração de Relatório (PDF):** CSS otimizado para impressão limpa e corporativa, ocultando elementos de interface e preservando os dados vitais.
* **Privacidade Total (Zero-DB):** Aplicação 100% *Client-Side*. Nenhum dado é enviado para servidores ou bancos de dados.

## 💻 Tecnologias Utilizadas
* **HTML5:** Estruturação semântica.
* **CSS3:** Estilização baseada em *Frosted Glass / Glassmorphism* (inspirado no Apple iOS/visionOS), tipografia moderna e `@media print` para exportação.
* **JavaScript (Vanilla):** Lógica matemática dos sliders, algoritmo de ranqueamento de perfis e injeção dinâmica de conteúdo. Código ofuscado em produção para proteção de IP.
* **Chart.js:** Biblioteca open-source para renderização do gráfico de teia.

## 🛠️ Como Usar (Para Desenvolvedores)
Por ser uma Single Page Application (SPA) baseada apenas em Front-end, não há necessidade de build ou instalação de dependências.
1. Faça o clone do repositório.
2. Abra o arquivo `index.html` em qualquer navegador moderno.
3. Para hospedar, basta ativar o **GitHub Pages** apontando para o branch `main`.

## ⚖️ Isenção de Responsabilidade
Esta ferramenta tem fins exclusivamente educacionais e de auto-reflexão empreendedora. **NÃO constitui um diagnóstico psicológico, psiquiátrico ou laudo comportamental clínico.** Os resultados não possuem validade científica para justificar contratações, demissões ou diagnósticos médicos. O uso e a interpretação das informações são de inteira responsabilidade do usuário.

## 📄 Licença e Créditos
* **Desenvolvido por:** Raphael Furlan
* **Contato:** rapfur@gmail.com
* **Base Teórica:** Bases do Poder Social (French & Raven) / Metodologia adaptada de seminários de empreendedorismo.

Este projeto está sob a licença **Creative Commons Atribuição-NãoComercial 4.0 Internacional (CC BY-NC 4.0)**. 
Você é livre para compartilhar e adaptar o material, desde que dê o crédito apropriado e **não o utilize para fins comerciais**.