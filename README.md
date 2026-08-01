# 🏋️‍♀️ Jeh Fitness — Moda & Performance

Landing page de e-commerce fitness com vitrine de produtos, seção de consultoria online e contato direto via WhatsApp. Feita em HTML puro + Tailwind CSS, sem build step — é só abrir o `index.html`.

<p align="center">
  <img src="./preview.png" alt="Preview da Jeh Fitness" width="800">
</p>

> 📸 Substitua `preview.png` por um print real do site (pode ser um screenshot da página inteira, tipo [GoFullPage](https://gofullpage.com/) ou a extensão de screenshot do próprio navegador).

---

## 🔗 Demo

[👉 Ver site online](#) <!-- troque pelo link do GitHub Pages / Vercel / Netlify -->

---

## ✨ Funcionalidades

- Vitrine de produtos com filtro por categoria (Conjuntos, Leggings, Tops)
- Contador de carrinho e feedback visual ao adicionar produto
- Menu responsivo com suporte a teclado (fecha com `Esc`, foco gerenciado)
- Formulário de newsletter com validação
- Botão flutuante e CTA de WhatsApp para a consultoria
- Layout 100% responsivo (mobile-first)

---

## 🛠️ Construído com

| Tecnologia | Uso |
|---|---|
| [HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML) | Estrutura semântica da página |
| [Tailwind CSS (CDN)](https://tailwindcss.com/) | Estilização utility-first |
| [Font Awesome 6](https://fontawesome.com/) | Ícones |
| [Google Fonts — Montserrat](https://fonts.google.com/specimen/Montserrat) | Tipografia |
| JavaScript (vanilla) | Menu mobile, filtro de produtos, carrinho, newsletter |
| [Unsplash](https://unsplash.com/) | Imagens de exemplo (trocar por fotos próprias antes de ir pra produção) |

Sem frameworks, sem bundler, sem dependências para instalar — o Tailwind e os ícones são carregados via CDN.

---

## 📁 Estrutura do projeto

```
.
├── index.html      # Página única com todo o HTML, CSS (inline) e JS
└── README.md
```

---

## 🚀 Como rodar localmente

Não tem build nem `npm install` — é HTML estático.

```bash
# clone o repositório
git clone https://github.com/seu-usuario/jeh-fitness.git
cd jeh-fitness

# abra direto no navegador
open index.html        # macOS
# ou
start index.html        # Windows
```

Se preferir um servidor local (recomendado para testar em outros dispositivos na rede):

```bash
npx serve .
# ou
python3 -m http.server 8000
```

---

## ⚙️ Antes de colocar no ar

- [ ] Trocar o número de WhatsApp placeholder (`5500000000000`) pelo número real, nos dois links do site
- [ ] Trocar as imagens do Unsplash por fotos próprias da marca
- [ ] Conectar o formulário de newsletter a um provedor real (Mailchimp, RD Station, etc.)
- [ ] Adicionar favicon
- [ ] Preencher os links do rodapé (`Trocas e Devoluções`, `Política de Privacidade`, etc.)

---

## 📄 Licença

Este projeto está sob a licença MIT — sinta-se à vontade para usar como base.

---

<p align="center">Feito com 💗 por Jeh Fitness Team</p>
