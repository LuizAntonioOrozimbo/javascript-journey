# 🟦 4. Template — cabecalho-aula.md

<!-- Cabeçalho padrão para todas as aulas -->

## Aula ${numeracao} — ${titulo}

- **Disciplina:** ${disciplina}
- **Fonte:** ${fonte}
- **Data:** ${data}

```js
console.log(`Disciplina: ${disciplina}`);
console.log(`Fonte da aula: ${fonte}`);
console.log(`Aula: ${numeracao} — ${titulo}`);
```

---

## ✅ **BLOCO 5 — Template `texto-aula.md`**

```md
# Aula ${numeracao} — ${titulo}

## 📌 Assunto da aula
Descreva aqui o que você estudou.

---

## 🧠 O que aprendi
- ponto 1  
- ponto 2  
- ponto 3  

---

## 🧪 Código da aula

```js
// Seu código aqui
```

🔗 Referências

- link opcional

---

### 🟦 **6. Snippet para VSCode — Cabeçalho automático**

Crie ou edite:

`File > Preferences > User Snippets > New Global Snippet File`

Nome sugerido: **aulas-javascript.code-snippets**

Conteúdo:

```json
{
  "Cabecalho Aula JavaScript": {
    "scope": "javascript,typescript",
    "prefix": "jsheader",
    "body": [
      "// ===============================",
      "// Aula ${1:00} — ${2:Título da Aula}",
      "// Disciplina: JavaScript",
      "// Fonte: ${3:Curso/Canal}",
      "// Data: ${4:2025-01-01}",
      "// ===============================",
      "",
      "console.log(`Disciplina: JavaScript`);",
      "console.log(`Fonte da aula: ${3:Curso/Canal}`);",
      "console.log(`Aula: ${1:00} — ${2:Título da Aula}`);",
      "",
      ""
    ],
    "description": "Cabeçalho padrão para aulas de JavaScript"
  }
}
```
