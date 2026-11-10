# Publicações · Estúdio Problems

Programa do Estúdio (https://estudio.problemsraiz.workers.dev/publicacoes/) para ORGANIZAR os vídeos da equipe no YouTube,
em visual Metro (Windows 8). Abas Shorts (vídeo em pé) e Vídeos longos, com faixas Neste navegador · Não publicados · Na fila ·
Agendados · Não listados · Publicados (arrastar ou "Mover…" muda formato, canal, situação e data) e a Agenda do mês.
Canal padrão: Animador → Turma do Problems, Editor → Problems, Shorts → a pessoa escolhe. Publicar (não listado, agora ou agendar)
continua possível, mas não é o foco.

- O vídeo vai do navegador direto para o YouTube pelo módulo comum `/estudio-youtube.js` do site; Animador, Shorts e Editor
  deixam o vídeo no IndexedDB `ep-publicacoes` e abrem esta página com `?video=<id>`.
- A lista da equipe é um JSON só no turma-ia (`/publicacoes`), guardado no navegador; os filtros rodam no navegador.
- Regras: `CLAUDE.md` do repositório problemsbloxcreate-lab.github.io, seção "PUBLICAR NO YOUTUBE".
