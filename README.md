# Publicações · Estúdio Problems

Programa do Estúdio (https://estudio.problemsraiz.workers.dev/publicacoes/) para publicar os vídeos exportados no YouTube
(não listado, publicar agora ou agendar) e ver a lista da equipe (Hoje, Futuros, Não listados, Publicados / no ar).

- O vídeo vai do navegador direto para o YouTube pelo módulo comum `/estudio-youtube.js` do site; Animador, Shorts e Editor
  deixam o vídeo no IndexedDB `ep-publicacoes` e abrem esta página com `?video=<id>`.
- A lista da equipe é um JSON só no turma-ia (`/publicacoes`), guardado no navegador; os filtros rodam no navegador.
- Regras: `CLAUDE.md` do repositório problemsbloxcreate-lab.github.io, seção "PUBLICAR NO YOUTUBE".
