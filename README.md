
# 📊 Revisão Avaliação — Banco de Dados I

Aplicação web interativa de estudo para a disciplina **Banco de Dados I** (Prof. José Wellington — CEUB 2026), composta por dois módulos: **Flashcards** para revisão conceitual e **Simulado** para prática com questões de múltipla escolha.

🔗 **Acesse:** [Revisão para Avaliação de BD I](https://gustavolg95.github.io/revisao_BD1/)

---

## 🗂️ Estrutura do Projeto

```
revisao_BD1/
│
├── index.html               # Página inicial com links para os dois módulos
├── README.md
│
├── flashcards/
│   ├── flashcards.html      # Módulo de flashcards interativos
│   └── style.css            # Estilos do módulo de flashcards
│
└── simulado/
    ├── simulado.html        # Módulo de simulado com 30 questões
    └── style.css            # Estilos do módulo de simulado
```

---

## 📚 Módulo 1 — Flashcards

Ferramenta no estilo flashcard: o usuário vê a pergunta, clica para revelar a resposta e marca se soube ou precisa revisar.

### ✨ Funcionalidades

* Questões distribuídas em 6 categorias temáticas
* Flip animado nos cards (frente = pergunta / verso = resposta)
* Filtro por categoria para estudar um tema de cada vez
* Embaralhamento aleatório das questões
* Marcação de progresso ("✓ Eu sei!" / "✕ Revisar")
* Barra de progresso e painel de estatísticas em tempo real
* Tela de conclusão com taxa de acerto e opção de revisar apenas os erros
* Layout responsivo para mobile e desktop

### 📋 Categorias

| Categoria                  | Conteúdo                                                    |
| -------------------------- | ------------------------------------------------------------ |
| **Fundamentos**      | Dado, informação, conhecimento, modelo de dados            |
| **SGBD**             | Sistema gerenciador, DBA, funções, índices                |
| **Características** | Auto-contenção, ACID, integridade, redundância            |
| **Arquitetura**      | Níveis externo, conceitual e interno, esquema e instância  |
| **SQL**              | DDL, DML, DCL e seus comandos                                |
| **MER**              | Entidades, atributos, chaves, cardinalidade, relacionamentos |

---

## 📝 Módulo 2 — Simulado

Simulado cronometrado com 30 questões de múltipla escolha cobrindo toda a matéria da 2ª prova.

### ✨ Funcionalidades

* 30 questões de múltipla escolha
* Cronômetro de 40 minutos com alerta visual ao se aproximar do fim
* Barra de progresso por questão
* Navegação livre entre questões (anterior / próxima / finalizar)
* Tela de resultado com pontuação e estatísticas
* Revisão completa ao final com gabarito e explicações por questão

### 📋 Temas abordados

* Fundamentos: dado, informação, conhecimento, modelo de dados
* SGBD: DBA, transações, ACID, instância, esquema
* Arquitetura 3 níveis: externo, conceitual, interno
* DDL, DML, DCL — comandos SQL
* MER: entidades, atributos, chaves, cardinalidade
* 🆕 Normalização: 1FN, 2FN, 3FN, FNBC, 4FN, 5FN
* 🆕 Dependências: funcional, parcial, transitiva, multifuncional, de junção

---

## 🛠️ Tecnologias Utilizadas

* HTML5
* CSS3 (variáveis CSS, Flexbox, animação 3D com `rotateY`)
* JavaScript ES6+ (Vanilla, sem frameworks)
* Google Fonts (Syne, DM Sans)

> Nenhuma dependência ou instalação necessária — basta abrir no navegador.
>
