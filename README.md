# Projeto 02 – Página de receita (somente HTML)

Crie `index.html`: uma página com sua receita favorita, tabela nutricional e um formulário de avaliação.

**Requisitos**

1. **R1** – Base do documento: `<!DOCTYPE html>`, `lang="pt-BR"`, `<meta charset="UTF-8">` e `<title>`.
2. **R2** – `<header>` com um `<h1>` e um `<nav>` com 3+ links internos (`href="#algum-id"`), todos apontando para ids que existem na página.
3. **R3** – O `<main>` tem 3+ `<section>`, cada uma com `id` e um `<h2>`.
4. **R4** – Lista de ingredientes: uma `<ul>` com 5+ `<li>`.
5. **R5** – Modo de preparo: uma `<ol>` com 4+ `<li>`.
6. **R6** – Uma `<table>` com `<caption>`, `<thead>` com 3+ `<th>` e `<tbody>` com 3+ linhas (todas com o mesmo número de células do cabeçalho).
7. **R7** – Uma `<figure>` com `<img>` (com `alt`) e `<figcaption>`.
8. **R8** – Um `<form>` com `<button type="submit">`.
9. **R9** – Todo campo do formulário (5+ campos) tem um `<label>` associado (`for` + `id`).
10. **R10** – Todos os campos têm `name`; um `<input type="text" required>` (nome) e um `<input type="email" required>`.
11. **R11** – O formulário tem um `<select>` com 3+ `<option>`, um `<textarea maxlength="...">`, 2+ `<input type="radio">` com o mesmo `name` e 1+ `<input type="checkbox">`.
12. **R12** – Existe um `<footer>` e não há CSS (sem `style` e sem `<style>`).

---

## Como entregar

1. Clone o repositório: `git clone https://github.com/NicolasDimitri/web-02-receita.git` e entre na pasta.
2. Crie uma branch: `git switch -c meu-projeto`
3. Crie os arquivos pedidos aqui na raiz, ao lado deste README.
4. `git add .` → `git commit -m "mensagem"` → `git push -u origin meu-projeto`
5. No GitHub, clique em **Compare & pull request** → **Create pull request**.
6. Um comentário automático aparece no PR com uma **tabela de requisitos**, cada um com ✅ (passou) ou ❌ (não passou) e a dica do que falta.
   Corrija, faça novo commit + `git push` e o comentário é atualizado.
7. Com tudo ✅, clique em **Merge pull request**.

## Testar no seu computador (opcional)

```bash
npm install
npx playwright install --with-deps chromium   # só na primeira vez
npm test
```

> Não altere as pastas `tests/`, `scripts/` e `.github/`.
