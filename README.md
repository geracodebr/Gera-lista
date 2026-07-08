# 🛒 GeraLista — Roteiro de Apresentação (README / Portfólio)

---

## 1. Abertura / Sobre o Projeto

**GeraLista** é um Progressive Web App (PWA) de lista de compras com controle de orçamento, criado para resolver um problema real do dia a dia: organizar compras, controlar gastos e evitar surpresas no caixa do mercado.

Desenvolvido por **Geraldo Almeida Tavares (GeraCodeBR)**, formado em Análise e Desenvolvimento de Sistemas (Univille) e Desenvolvimento Web Full Stack (Senai SC), o GeraLista nasceu como projeto pessoal bem antigo, o qual utilizada planilha eletronica para fazer a lista de compras e obter os valores instantaneamente, de estudo e evoluiu para um aplicativo completo, funcional e publicado.

**🔗 Acesse:** `https://gera-lista.netlify.app/`

---

## 2. O Problema que Resolve

Listas de compras em papel ou apps genéricos raramente respondem a perguntas simples:

- Quanto já gastei até agora?
- Quanto ainda posso gastar sem estourar o orçamento?
- Esse item já foi comprado ou ainda falta?
- Como separar listas diferentes (mercado, farmácia, casa nova) sem misturar tudo?

O GeraLista foi construído linha por linha, ajuste por ajuste, para resolver exatamente essas dores.

---

## 3. Principais Funcionalidades

### 💰 Controle de Orçamento Inteligente
- Orçamento **geral** (compartilhado entre todas as listas) ou **individual** (cada lista com seu próprio limite)
- Ao criar uma nova lista, o app pergunta como definir o orçamento: valor novo, copiar de outra lista existente, ou deixar em aberto
- Painel com Disponível / Gasto / Saldo, atualizado em tempo real
- Barra de progresso visual indicando o quanto já foi consumido

### 📋 Multi-listas
- Crie quantas listas quiser (Mercado, Farmácia, Casa Nova, etc.)
- Renomeie, exclua ou alterne entre elas pelo menu suspenso
- Mova produtos de uma lista para outra sem perder dados

### 🛒 Gestão de Produtos
- Cadastro completo: nome, quantidade, unidade de medida (unidade ou quilo, com suporte a casas decimais), preço unitário
- Cálculo automático do subtotal por item (quantidade × preço)
- Marcação de "comprado" direto no cadastro ou na lista
- Edição rápida a qualquer momento, tocando no produto

### 🔎 Organização e Busca
- Barra de pesquisa fixa no topo, mesmo rolando listas longas
- Filtros: todos os produtos, só pendentes, só comprados
- Ordenação alfabética (A-Z / Z-A) ou por produtos sem preço definido

### 📲 Importação Rápida
- Cole uma lista copiada do WhatsApp (uma por linha ou separada por vírgula) e o app organiza tudo automaticamente

### 🎨 Personalização
- Modo Claro, Modo Escuro ou Automático (segue a configuração do celular)
- Interface pensada para uso rápido, no meio do mercado, com uma mão só

### 📱 Instalável como App
- Progressive Web App com manifest e service worker
- Funciona offline após primeira instalação
- Instalável na tela inicial do Android/iOS, sem precisar de loja de aplicativos

### 💬 Canal de Comunicação
- Botão de sugestões/reporte de bugs integrado, com envio direto via WhatsApp para o desenvolvedor

---

## 4. Stack Técnica

| Camada | Tecnologia |
|---|---|
| Frontend | HTML5, CSS3, JavaScript puro (vanilla) |
| Persistência | LocalStorage (dados salvos no dispositivo) |
| Distribuição | app.netlify.com |
| Formato | PWA (Progressive Web App) com manifest.json e Service Worker |
| Analytics | Google Analytics (GA4) |

**Por que vanilla JS, sem frameworks?**
Escolha proposital para dominar os fundamentos — manipulação de DOM, eventos, armazenamento local e ciclo de vida de uma aplicação — antes de abstrair complexidade com frameworks como React ou Vue.

---

## 5. Processo de Desenvolvimento

O GeraLista foi construído de forma **iterativa e colaborativa**, com ciclos curtos de feedback:

1. Protótipo inicial simples (lista + preço)
2. Adição de orçamento e cálculo de saldo
3. Introdução de multi-listas e orçamento por lista
4. Refinamento de UX (menu de ações, edição em tela cheia, importação em massa)
5. Acessibilidade e personalização visual (temas claro/escuro/automático)
6. Transformação em PWA instalável, com identidade visual e marca própria

Esse processo reflete uma metodologia próxima de **desenvolvimento ágil**: entregas pequenas, testadas a cada etapa, com ajustes guiados por uso real.

---

## 6. Destaques de UX/UI

- **Feedback imediato**: qualquer alteração (preço, quantidade, orçamento) reflete instantaneamente na tela
- **Confirmações de segurança**: exclusão de itens e listas sempre pede confirmação, evitando perdas acidentais
- **Hierarquia visual clara**: cores e contraste ajustados para leitura rápida, inclusive no modo escuro
- **Mobile-first**: cada decisão de layout pensada para uso no celular, com uma mão, em movimento

---

## 7. Aprendizados e Próximos Passos

**Principais aprendizados técnicos:**
- Gerenciamento de estado em JavaScript puro sem bibliotecas
- Trabalho com LocalStorage para persistência sem backend
- Construção de PWA (manifest, service worker, instalabilidade)
- Design responsivo focado em mobile

**Roadmap futuro (ideias em estudo):**
- Sincronização entre dispositivos (exigiria backend/autenticação)
- Compartilhamento de listas entre múltiplos usuários em tempo real
- Relatórios de histórico de compras e gastos por período
- Reconhecimento de código de barras para cadastro automático de produtos

---

## 8. Sobre o Desenvolvedor

**Geraldo Almeida Tavares** — GeraCodeBR
- Formado em Gestão de Recursos Humanos (Unisa, 2011)
- Formação em Análise e Desenvolvimento de Sistemas (Univille) e Desenvolvimento Web Full Stack (Senai SC)
- Também atua com suporte técnico e serviços residenciais através da marca **GeraTech**

📲 Contato: WhatsApp (47) 98495-9491 | GitHub: [@geracodebr](https://github.com/geracodebr) | Instagram/YouTube/TikTok: **@geratechbr**

---

## 9. Encerramento

> "O GeraLista começou como um necessidade de manter um orçamento apertado, dentro de uma economia que muda todos os dias e se tornou uma ferramenta que uso no dia a dia. Ele representa bem o que busco na programação: resolver problemas reais, de forma simples, com atenção aos detalhes que fazem diferença na experiência de quem usa. Fico à disposição para trocar ideia, ouvir sugestões ou colaborar em novos projetos."
