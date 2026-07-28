# AIB — Atualizações

Repositório **público** com os arquivos de atualização automática do app **Aib** (AIBGLAMOUR).
Aqui ficam **apenas os binários** (`app.asar`) e a versão publicada (`versao.json`).
O **código-fonte** fica no repositório privado.

O app confere `versao.json` ao abrir; se houver versão mais nova, baixa o `app.asar`,
confere a integridade (sha256) e troca sozinho — com reversão automática se algo der errado.
