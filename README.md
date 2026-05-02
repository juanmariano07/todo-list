# ✅ TaskFlow — Lista de Tarefas

Aplicação de gerenciamento de tarefas com CRUD completo, filtros e persistência de dados no navegador.

![Preview](https://img.shields.io/badge/status-concluído-4ade80?style=flat-square)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

---

## 📋 Sobre o projeto

TaskFlow é uma aplicação de lista de tarefas construída com JavaScript puro, sem frameworks. O projeto implementa as quatro operações fundamentais de qualquer sistema: **criar, ler, atualizar e deletar** dados (CRUD).

O estado da aplicação persiste via `localStorage`, garantindo que as tarefas continuem salvas mesmo após fechar o navegador.

---

## ✨ Funcionalidades

- ➕ Adicionar tarefas (via botão ou tecla Enter)
- ✔️ Marcar/desmarcar tarefas como concluídas
- 🗑️ Deletar tarefas individualmente
- 🧹 Limpar todas as tarefas concluídas de uma vez
- 🔽 Filtros: Todas / Pendentes / Concluídas
- 📊 Barra de progresso e contadores em tempo real
- 💾 Dados persistidos no `localStorage`
- 🎞️ Animações de entrada e remoção
- 📱 Layout responsivo

---

## 🚀 Como executar

```bash
# Clone o repositório
git clone https://github.com/SEU-USUARIO/todo-list.git

# Acesse a pasta
cd todo-list

# Abra o index.html no navegador
# Ou use Live Server no VS Code
```

---

## 🧠 Conceitos aplicados

| Conceito | Onde foi usado |
|---|---|
| CRUD | Criar, ler, atualizar e deletar tarefas |
| Gerenciamento de estado | Array central como única fonte da verdade |
| `localStorage` | Persistência dos dados entre sessões |
| `Array.filter()` | Sistema de filtros (pendentes/concluídas) |
| `Array.map()` | Renderização da lista de tarefas |
| Manipulação de DOM | Atualização da interface a cada mudança de estado |
| Prevenção de XSS | Sanitização do input do usuário com `escapeHtml` |
| Animações CSS | Transições de entrada e saída dos cards |

---

## 💡 Padrão de arquitetura

Este projeto usa o padrão **Estado → Render**, onde toda mudança nos dados chama a função `render()` que reconstrói a interface. Esse é exatamente o conceito por trás de frameworks como React.

```
Ação do usuário
      ↓
Atualiza o array `tasks`
      ↓
Salva no localStorage
      ↓
Chama render()
      ↓
Interface atualizada
```

---

## 📁 Estrutura do projeto

```
todo-list/
└── index.html   # HTML + CSS + JS em arquivo único
```

---

## 👤 Autor

**Juan da Costa Mariano**
[![GitHub](https://img.shields.io/badge/GitHub-SEU--USUARIO-181717?style=flat-square&logo=github)](https://github.com/SEU-USUARIO)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Juan%20Mariano-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/SEU-USUARIO)
