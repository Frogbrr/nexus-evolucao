# NEXUS — Sistema Pessoal de Evolução

Aplicativo web progressivo (PWA) em português, pensado para uso pessoal no celular. Projeto original com estética dark fantasy azul, mecânicas de RPG e dados locais.

## Recursos incluídos
- Painel inicial com XP, nível, missões, hábitos e atividade semanal.
- Missões personalizadas com categoria, dificuldade, XP e prazo opcional.
- Hábitos diários com registro por data.
- Cronômetro de foco com sessões registradas e XP.
- Trilhas de estudos/idiomas com meta semanal e objetivo seguinte.
- Diário pessoal com check-in emocional e pequenas vitórias.
- Atributos, conquistas e histórico de atividade.
- Perfil, objetivo principal e preferências.
- Exportação/importação de backup JSON.
- Armazenamento local no navegador, sem conta.
- Manifesto PWA, ícone e cache offline básico.

## Publicar pelo iPhone usando GitHub Pages
1. Extraia o ZIP no app Arquivos do iPhone.
2. Abra seu repositório GitHub `project-system` no Safari.
3. Envie os arquivos desta pasta para a raiz do repositório: `index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg` e `README.md`.
4. Em Settings → Pages, selecione a branch principal (`main`) e a pasta raiz (`/root`) e salve.
5. Aguarde a publicação e abra o endereço do GitHub Pages no Safari.
6. Para instalar: botão Compartilhar → Adicionar à Tela de Início.

## Importante
- O site precisa estar em HTTPS para recursos PWA e service worker.
- O progresso fica no armazenamento local do navegador. Use Exportar backup regularmente e antes de trocar de aparelho ou limpar os dados do Safari.
- A instalação como PWA pode variar conforme a versão do iOS e a forma como o site é publicado.
- Este app é um projeto independente e não é cópia oficial de Life Reset ou de qualquer outro app.
- Os lembretes do sistema operacional e sincronização entre aparelhos ainda não estão incluídos. O aplicativo não pode garantir notificações quando estiver fechado.
