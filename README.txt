
Plantão Psicológico Levemente – v3 (Site estático de demonstração)

O que há de novo:
- Texto de acolhimento no cabeçalho.
- Identidade visual (Pantone 281 C e 118 C) e fonte "Bookerly" com fallback.
- Unidades presenciais com local detalhado via config.json.
- Portal do Psicólogo com campo para inserir link de sessão online (Google Meet/Teams/Zoom).
- ICS inclui LOCAL e, se houver, o link da sessão na DESCRIÇÃO.

Como publicar (GitHub Pages):
1) Envie index.html e config.json para a raiz do repositório.
2) Settings → Pages → Deploy from a branch (main / root) → Save.
3) Abra o link exibido após o deploy.

Observação:
- Se tiver o arquivo da fonte Bookerly (WOFF/WOFF2) com licença, posso incluir @font-face. Caso contrário, o site usa Georgia/Times como fallback.
