
# Site Melhorado – Plantão Psicológico

Este pacote contém:
- `index.html` – site acessível com wizard de agendamento (série 6×), lembretes simulados e exportações.
- `config.json` – lista de **unidades presenciais** e parâmetros.

## Como publicar (GitHub Pages)
1. Envie os arquivos deste pacote para seu repositório (`main` na raiz).
2. Em **Settings → Pages** selecione **Deploy from a branch** > **main** e **/(root)** e **Save**.
3. Aguarde até 2 minutos e acesse o link exibido.

## Como usar domínio próprio (sem seu nome no link)
1. No **Settings → Pages → Custom domain**, digite seu domínio (ex.: `plantao.suaempresa.com.br`) e **Save**.
2. No provedor de DNS, crie um **CNAME** do subdomínio para `FernanddaLopes.github.io`.
3. Volte ao **Settings → Pages** e marque **Enforce HTTPS**.

Dica: Prefira **subdomínio** (ex.: `plantao.suaempresa.com.br`). Para apex (ex.: `suaempresa.com.br`), use **A records** nos IPs do GitHub Pages e mantenha o CNAME para `www`.
