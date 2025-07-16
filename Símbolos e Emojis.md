
# 💡 HTML - Símbolos e Emojis

📅 Criado em: **15 de julho de 2025**  
📚 Matéria:**Programação Web (HTML5 e CSS3)**  
✍️ Autor: **Marco**

---

## 🎯 TEMA: Como inserir símbolos especiais e emojis em documentos HTML

---

## 1. 🧩 A Necessidade de Entidades HTML

- Alguns símbolos não podem ser digitados diretamente (como < ou >) porque fazem parte da sintaxe do HTML.
- Para evitar conflitos ou problemas de exibição, usamos as chamadas **entidades de caractere (Character Entities)**.
- Toda entidade começa com `&` e termina com `;`.

---

## 2. 🔠 Tipos de Entidades HTML

### ✅ Por Nome (Entity Name)

- Sintaxe: `&nome_da_entidade;`
- Mais legível e fácil de lembrar.

| Entidade | Exibe |
|----------|--------|
| `&lt;` | < |
| `&gt;` | > |
| `&amp;` | & |
| `&copy;` | © |
| `&reg;` | ® |
| `&nbsp;` | espaço não separável |

---

### 🔢 Por Número Decimal (Entity Number)

- Sintaxe: `&#número;`
- Mais universal (baseado em Unicode)

| Entidade | Exibe |
|----------|--------|
| `&#60;` | < |
| `&#62;` | > |
| `&#38;` | & |
| `&#169;` | © |
| `&#174;` | ® |
| `&#160;` | espaço não separável |

---

### 🔡 Por Número Hexadecimal (Entity Hex)

- Sintaxe: `&#xhex;` (com x indicando hexadecimal)

| Entidade | Exibe |
|----------|--------|
| `&#x20AC;` | € (símbolo do Euro) |

---

## 3. 😀 Inserindo Emojis

- Emojis são caracteres Unicode e funcionam com `charset="UTF-8"`.
- Podem ser inseridos diretamente no HTML.

### ✅ Sintaxe Direta:

```html
<p>Eu amo programar! ❤️</p>
<p>Que dia ensolarado! ☀️</p>
```

### 🔣 Sintaxe via Código (menos comum):

```html
<p>Sorriso: &#x1F600;</p>
```

- A exibição pode variar entre sistemas e navegadores.
- Sempre use `<meta charset="UTF-8">` para garantir compatibilidade.

---

## 4. 📌 Pontos Importantes para Memorização

- Entidades HTML: Usadas para exibir símbolos especiais.
- Começam com `&` e terminam com `;`.
- Tipos: por nome (`&copy;`), número decimal (`&#169;`), ou hexadecimal (`&#x00A9;`).
- Emojis funcionam diretamente com UTF-8.
- Cuidado com caracteres especiais que fazem parte da linguagem HTML (`<`, `>` e `&`).

---

### 🚀 Dica Extra

Sempre teste a visualização do seu HTML em diferentes navegadores. Nem todos os sistemas interpretam os emojis exatamente da mesma forma!

---
nte da mesma forma!

---
