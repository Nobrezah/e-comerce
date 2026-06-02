# 🛍️ E-commerce Interface

Loja virtual completa com React, Next.js 14, TypeScript e gerenciamento de estado com Zustand.

## ✨ Funcionalidades

- Listagem de produtos com cards interativos
- Filtro por categoria e busca em tempo real
- Ordenação (preço, avaliação, relevância)
- Carrinho lateral (drawer) com animação
- Controle de quantidade e remoção de itens
- Persistência do carrinho com localStorage (Zustand persist)
- Badge de desconto e controle de estoque
- Layout responsivo

## 🛠 Stack

| Tecnologia   | Uso                                    |
|--------------|----------------------------------------|
| Next.js 14   | App Router, SSR                        |
| TypeScript   | Interfaces e tipagem completa          |
| Tailwind CSS | Design system utility-first            |
| Zustand      | Estado global do carrinho              |

## 🚀 Como rodar

```bash
npm install
npm run dev
```

Acesse [http://localhost:3000](http://localhost:3000)

## 📁 Estrutura

```
src/
├── app/
│   ├── layout.tsx
│   └── page.tsx           # Página principal com filtros
├── components/
│   ├── layout/
│   │   └── Header.tsx     # Header com botão do carrinho
│   ├── product/
│   │   └── ProductCard.tsx
│   └── cart/
│       └── CartDrawer.tsx # Sidebar do carrinho
├── store/
│   └── cart.ts            # Zustand store
├── lib/
│   └── products.ts        # Dados mock de produtos
└── types/
    └── index.ts
```
