<div align="center">

<h1>
  Pixel <img src="https://img.shields.io/badge/%20-%20?style=flat&color=f97316" width="14" height="14"> QR
</h1>

**Uma biblioteca JS de código aberto para gerar QR codes estilizados**

[![npm](https://img.shields.io/badge/qr--code--styling-v1.8.3-orange?style=flat-square)](https://www.npmjs.com/package/qr-code-styling)
[![Vite](https://img.shields.io/badge/Vite-6.x-646cff?style=flat-square)](https://vitejs.dev/)
[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](#licença)

</div>

---

## ✨ Sobre

**PixelQR** é uma aplicação web para gerar QR codes altamente customizáveis, construída com JavaScript vanilla + Vite. Permite personalizar cores, estilos de pontos, cantos, logos embutidos e muito mais — tudo em tempo real, com preview instantâneo.

> Design inspirado em [Denys Kozak](https://github.com/kozakdenys/qr-code-styling) · Powered by [qr-code-styling](https://www.npmjs.com/package/qr-code-styling)

---

## 🖼️ Preview

![PixelQR Screenshot](https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6)

---

## 🚀 Funcionalidades

- 🎨 **Customização completa** — cor dos pontos, cantos quadrados, cantos redondos e fundo
- 🖼️ **Logo embutido** — adicione imagens ou use logos prontos (WhatsApp, Instagram, Wi-Fi)
- 💾 **Download em PNG, SVG ou WebP**
- 🌓 **Dark mode / Light mode** com detecção automática do sistema
- 🌐 **Suporte a PT-BR e EN** — alternância de idioma em tempo real
- 📋 **Histórico de QR codes** — salva os últimos 5 gerados localmente
- ⚡ **Estilos prontos** — Neon, Classic, Minimal, Corporate
- 🎯 **Hero dinâmico** — gradiente do banner sincroniza com a cor escolhida

---

## 🛠️ Tecnologias

| Tech | Uso |
|------|-----|
| [Vite 6](https://vitejs.dev/) | Build tool e dev server |
| [qr-code-styling](https://www.npmjs.com/package/qr-code-styling) | Engine de geração dos QR codes |
| [Tailwind CSS 4](https://tailwindcss.com/) | Estilização |
| [Lucide React](https://lucide.dev/) | Ícones |
| [Motion](https://motion.dev/) | Animações |
| JavaScript Vanilla | Componentes e estado da aplicação |

---

## ⚙️ Como rodar localmente

**Pré-requisito:** Node.js instalado

```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/pixelqr.git
cd pixelqr

# 2. Instale as dependências
npm install

# 3. Configure as variáveis de ambiente
cp .env.example .env.local
# Edite .env.local e adicione sua GEMINI_API_KEY

# 4. Inicie o servidor de desenvolvimento
npm run dev
```

Acesse em: `http://localhost:3000`

---

## 📦 Scripts disponíveis

```bash
npm run dev      # Inicia o servidor de desenvolvimento
npm run build    # Gera o build de produção
npm run preview  # Visualiza o build localmente
npm run lint     # Verifica erros de TypeScript
npm run clean    # Remove a pasta dist
```

---

## 📁 Estrutura do projeto

```
pixelqr/
├── src/
│   ├── components/
│   │   ├── Header.js        # Cabeçalho com toggle de tema e idioma
│   │   ├── Hero.js          # Banner com gradiente dinâmico
│   │   ├── Controls.js      # Painel de customização
│   │   ├── Preview.js       # Preview e download do QR code
│   │   ├── Accordion.js     # Componente de acordeão
│   │   └── StyleButtons.js  # Botões de estilos prontos
│   ├── translations.js      # Strings em PT-BR e EN
│   ├── style.css            # Estilos globais e variáveis CSS
│   └── main.js              # Inicialização e estado da aplicação
├── index.html
├── vite.config.ts
└── package.json
```

---

## 🌓 Dark Mode

O dark mode é gerenciado via atributo `data-theme` no `<html>` e variáveis CSS. A preferência do sistema é detectada automaticamente com `prefers-color-scheme` e salva no `localStorage`.

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma _issue_ ou enviar um _pull request_.

1. Faça um fork do projeto
2. Crie sua branch: `git checkout -b feature/minha-feature`
3. Commit suas mudanças: `git commit -m 'feat: minha nova feature'`
4. Push para a branch: `git push origin feature/minha-feature`
5. Abra um Pull Request

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<div align="center">
  Feito com ❤️ e muito café ☕
</div>
