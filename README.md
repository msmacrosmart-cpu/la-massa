# La Massa

**La Massa – Authentic Italian Restaurant**

Landing page de restaurante italiano: hero, destaque de ingredientes,
reservas, depoimentos de clientes, diferenciais e galeria de pratos.

## 🚀 Como rodar

O site é um único `index.html` autocontido (JS e CSS já embutidos).
Como ele usa módulos ES, **abrir com duplo clique (`file://`) não funciona** —
é preciso servir por HTTP:

```bash
python3 -m http.server 8000
# acesse http://localhost:8000
```

## 📁 Estrutura

```
.
├── index.html   # aplicação completa (HTML + CSS + JS empacotados)
└── README.md
```

## 🛠️ Tecnologias

- React (aplicação de página única)
- Build empacotado com Vite, com todos os assets inline
- CSS embutido no próprio arquivo
- Imagens hospedadas no [Pexels](https://www.pexels.com/)

## 🌐 GitHub Pages

Para publicar gratuitamente:

1. Vá em **Settings → Pages**
2. Em *Source*, selecione a branch `main` e a pasta `/ (root)`
3. Salve — o site ficará disponível em
   `https://msmacrosmart-cpu.github.io/la-massa/`

## ⚠️ Observação sobre prints e prévias

Por ser uma aplicação React, o conteúdo é renderizado por JavaScript.
Serviços de screenshot e cartões de prévia (Microlink, WhatsApp, LinkedIn)
que não executam JS podem capturar uma página em branco. Nesse caso é
preciso gerar uma versão pré-renderizada (HTML estático) do site.

## 📄 Licença

Projeto de uso pessoal/demonstrativo. As imagens pertencem aos seus
respectivos autores no Pexels.
