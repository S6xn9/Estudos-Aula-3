
# ✍️ HTML - Parágrafos e Quebras (Capítulo 05 - Aula 01)

📅 Criado em: **15 de julho de 2025**  
📚 Matéria: **Desenvolvimento Web / HTML**  
✍️ Autor: **Marco**

---

## 🧩 TEMA: Como estruturar texto em parágrafos e usar quebras de linha em HTML

---

## 1. 🧾 A Tag `<p>`: Parágrafos

- A tag `<p>` é usada para definir um **parágrafo de texto**.
- Um dos elementos mais importantes para **organizar blocos de texto**.
- **Comportamento padrão**: o navegador adiciona **espaço antes e depois** de cada parágrafo.
- **Sintaxe**:
  ```html
  <p>Este é o primeiro parágrafo do meu texto.</p>
  <p>Este é o segundo parágrafo, separado do anterior por um espaço.</p>
  ```
- **Importância**: Melhora a **legibilidade** e é crucial para a **semântica do conteúdo**.

---

## 2. 🔁 A Tag `<br>`: Quebra de Linha

- A tag `<br>` cria uma **quebra de linha** dentro do mesmo parágrafo.
- **Não cria espaçamento** como a tag `<p>`.
- É uma **tag autofechante** (não tem fechamento).
- **Sintaxe**:
  ```html
  <p>Este é um texto com uma quebra de linha.<br>
  O restante do texto continua na linha de baixo, mas ainda faz parte do mesmo parágrafo.</p>
  ```
- **Quando usar**:
  - Endereços
  - Poemas
  - Linhas que precisam continuar no mesmo contexto, só embaixo
- **Evite usar** `<br><br>` para simular parágrafos — use `<p>` corretamente.

---

## 3. ⚔️ Diferença Fundamental: `<p>` vs. `<br>`

| Tag | Efeito Visual | Semântica | Espaço Vertical |
|-----|---------------|-----------|------------------|
| `<p>` | Cria um novo bloco de texto | Representa um parágrafo | Sim (antes e depois) |
| `<br>` | Quebra a linha no mesmo bloco | Só muda a visualização | Não adiciona espaço |

**Exemplo Comparativo**:
```html
<p>Este é o primeiro parágrafo.</p>
<p>Este é o segundo parágrafo. Eles terão um espaço maior entre si.</p>

<p>Este é um texto com uma quebra de linha.<br>
A segunda parte aparece abaixo, mas no mesmo parágrafo.</p>
```

---

## 4. 🧠 Pontos Importantes para Memorização

- `<p>`: Blocos independentes. Cria margem.
- `<br>`: Quebra de linha interna. Sem margem.
- **Use cada tag com seu significado semântico correto**.
- `<b>` e `<i>` são **estilos visuais** aplicados **dentro dos parágrafos**, não servem para estruturar o texto.

---

### 🚀 Dica de Estudo
Se possível, adicione essas anotações no seu Notion ou repositório pessoal. Criar seu próprio material ajuda a memorizar melhor!

---
