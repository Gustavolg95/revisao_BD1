# 🃏 Flashcards — Banco de Dados I

Aplicação web de flashcards interativos para estudo da disciplina **Banco de Dados I**, com 50 questões organizadas por categoria, flip animado e acompanhamento de progresso.

---

## 📸 Visão Geral

Ferramenta de estudo no estilo flashcard: o usuário vê a pergunta, clica para revelar a resposta, e marca se soube ou precisa revisar. Ao final, é exibida uma tela com a taxa de acerto e a opção de revisar apenas os erros.

---

## ✨ Funcionalidades

- **54 questões** distribuídas em 6 categorias temáticas
- **Flip animado** nos cards (frente = pergunta / verso = resposta)
- **Filtro por categoria** para estudar um tema de cada vez
- **Embaralhamento** aleatório das questões
- **Marcação de progresso** ("Eu Sei!" / "Preciso Revisar")
- **Barra de progresso** e painel de estatísticas em tempo real
- **Tela de conclusão** com taxa de acerto e opção de revisar apenas os erros
- Layout responsivo para mobile e desktop

---

## 📚 Categorias

| Categoria | Conteúdo |
|---|---|
| **Fundamentos** | Dado, informação, conhecimento, modelo de dados |
| **SGBD** | Sistema gerenciador, DBA, funções, índices |
| **Características** | Auto-contenção, ACID, integridade, redundância |
| **Arquitetura** | Níveis externo, conceitual e interno, esquema e instância |
| **SQL** | DDL, DML, DCL e seus comandos |
| **MER** | Entidades, atributos, chaves, cardinalidade, relacionamentos |

---

## 🗂️ Estrutura do Projeto

```
FlashcardsBD/
│
├── index.html      # Aplicação completa (HTML + lógica JavaScript)
└── style.css       # Estilos, temas e responsividade
```

> Toda a lógica de navegação, filtragem, embaralhamento e progresso está embutida no `index.html` via JavaScript puro, sem dependências externas.

---

## 🎨 Design System

As cores são gerenciadas via variáveis CSS:

| Variável | Valor | Uso |
|---|---|---|
| `--bg-dark` | `#0a0e27` | Background da página |
| `--bg-card` | `#1a1f3a` | Fundo dos cards |
| `--accent-primary` | `#00d4ff` | Ciano — destaques principais |
| `--accent-secondary` | `#ff6b9d` | Rosa — verso do card / erros |
| `--accent-tertiary` | `#ffd93d` | Amarelo — estatísticas |
| `--success` | `#00ff88` | Verde — acertos |

---

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3 (variáveis CSS, Flexbox, animação 3D com `rotateY`)
- JavaScript ES6+ (Vanilla, sem frameworks)
- Google Fonts (Bebas Neue, IBM Plex Sans)

---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/flashcards-bd1.git
   ```

2. Abra o arquivo `index.html` diretamente no navegador.

> Nenhuma dependência ou instalação necessária.
