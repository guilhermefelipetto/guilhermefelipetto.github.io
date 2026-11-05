# guilhermefelipetto.github.io

Site pessoal de Guilherme Felipetto, publicado pelo GitHub Pages em
<https://guilhermefelipetto.github.io/>.

- `index.html`: página inicial.
- `portifolio/`: CV completo (sobre, experiência, projetos, publicações, prêmios, formação).
- `projetos/`: repositórios em destaque, cada um com uma página própria em `projetos/<nome>/`.

O site é HTML e CSS estático, sem build. Os textos existem em português e
inglês na mesma página: cada trecho tem um `<span class="pt">` e um
`<span class="en">`, e o botão EN/PT-BR alterna qual dos dois aparece. Toda
alteração de texto precisa ser feita nas duas versões.

Para ver localmente:

```bash
python -m http.server 8000
```

e abrir <http://localhost:8000/>.
