# ⚡ Faraday Lab Pro

> Uma suíte interativa de simulações de Eletromagnetismo rodando diretamente no navegador.

**Faraday Lab Pro** é uma aplicação web desenvolvida para auxiliar no ensino e compreensão de conceitos fundamentais da física elétrica e magnética. Através de visualizações dinâmicas e controles interativos, o projeto demonstra leis complexas como a Lei de Lenz, Lei de Faraday, Ressonância RLC e conversão de energia eletromagnética.

---

## 📋 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades e Módulos](#-funcionalidades-e-módulos)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Como Rodar](#-como-rodar)
- [Equipe](#-equipe)

---

## 📖 Sobre o Projeto

Este projeto foi desenvolvido como parte da disciplina de **Eletromagnetismo** (2025), ministrada pelo **Professor Everton**. O objetivo foi criar uma ferramenta visual, acessível e performática para simular fenômenos físicos em tempo real, utilizando tecnologias web modernas sem a necessidade de compilação complexa.

---

## 🚀 Funcionalidades e Módulos

O sistema conta com **8 simuladores** distintos acessíveis através de abas de navegação:

### 1. Lei de Lenz (Indução Eletromagnética)
- **O que faz:** Simula a movimentação de um ímã através de uma bobina.
- **Destaques:** Visualização da corrente induzida, sentido da corrente (LEDs) e deflexão no galvanômetro.

### 2. Barra Móvel (Lei de Faraday)
- **O que faz:** Demonstra a geração de Força Eletromotriz (Fem) ao mover uma barra condutora em um campo magnético.
- **Destaques:** Gráfico em tempo real de Fluxo e Fem, visualização da força magnética contrária.

### 3. Cabo Coaxial (Energia Magnética)
- **O que faz:** Visualiza a densidade de energia magnética armazenada entre os condutores de um cabo coaxial.
- **Destaques:** Ajuste de raios (interno/externo) e corrente; mapa de calor da densidade de energia.

### 4. Gerador AC (Geradores e Motores)
- **O que faz:** Simula uma espira girando em um campo magnético uniforme.
- **Destaques:** Osciloscópio mostrando as ondas senoidais de Fluxo e Tensão; controle de velocidade e intensidade do campo magnético.

### 5. Transformador (Indutância Mútua)
- **O que faz:** Simula a relação de transformação de tensão entre enrolamentos primários e secundários.
- **Destaques:** Comparação de ondas de entrada vs. saída; cálculo automático de Step-Up ou Step-Down.

### 6. Freio Magnético (Correntes de Foucault)
- **O que faz:** Demonstra o efeito de frenagem de um pêndulo metálico ao passar por um campo magnético intenso.
- **Destaques:** Comparação física com o campo ativado e desativado.

### 7. Circuito RLC (Ressonância)
- **O que faz:** Analisa a resposta em frequência de um circuito RLC série.
- **Destaques:** Diagrama de Fasores interativo; gráfico de curva de resposta; cálculo de impedância e corrente RMS.

### 8. Railgun (Força Magnética e Energia)
- **O que faz:** Simula o disparo de um projétil acelerado por forças de Lorentz.
- **Destaques:** Barra de carregamento de capacitores; cálculo de conversão de Energia Potencial Elétrica em Energia Cinética.

---

## 🛠 Tecnologias Utilizadas

O projeto foi construído utilizando uma abordagem "no-build" para máxima simplicidade e portabilidade:

- **[React 18](https://react.dev/):** Biblioteca principal para a interface do usuário (via CDN).
- **[Tailwind CSS](https://tailwindcss.com/):** Framework de estilização utilitária para design responsivo e moderno (via CDN).
- **[HTML5 Canvas](https://developer.mozilla.org/pt-BR/docs/Web/API/Canvas_API):** Utilizado para renderização de gráficos de osciloscópios e visualizações de campo complexas.
- **[Lucide Icons](https://lucide.dev/):** Biblioteca de ícones leve e consistente.
- **[Babel](https://babeljs.io/):** Compilador JavaScript (Standalone) para interpretar JSX no navegador.

---

## 💻 Como Rodar

Não é necessário instalar Node.js ou gerenciadores de pacotes (npm/yarn). O projeto é autocontido.

1. **Clone este repositório:**
   ```bash
   git clone [https://github.com/SEU-USUARIO/faraday-lab-pro.git](https://github.com/SEU-USUARIO/faraday-lab-pro.git)