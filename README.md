# Tatame

App single-file para acompanhar a frequência na academia de jiu-jitsu: 3 aulas por semana ao longo de 13 semanas (39 aulas em 90 dias).

Inclui uma **Biblioteca** de movimentações (guardas, raspagens, passagens, finalizações, controles e escapes), com busca, filtro por categoria e um tutorial resumido por técnica: ilustração da posição (você em tinta, oponente em cinza, ponto-chave em vermelho), ideia central, passo a passo, detalhes, erros comuns, conceito de referência e técnicas relacionadas.

O visual segue uma linha minimalista de inspiração oriental: fundo de papel, tinta e vermelhão, títulos em serifa mincho (Shippori Mincho) e texto em Zen Kaku Gothic New. As ilustrações são SVG desenhados no próprio arquivo, sem imagens externas.

## Escopo desta versão (lado do aluno)

Este app é a visão do aluno. O aluno envia a confirmação de que vai treinar; ela fica **pendente** (com um X para cancelar) até o professor registrar a presença. Dependem de um módulo admin, ainda a fazer:

- registrar presença e aprovar ou recusar confirmações enviadas;
- grade de aulas, professores e regra de graduação da academia (hoje dados fixos, somente leitura no perfil);
- colegas, contagem de confirmados e chat (hoje exemplos locais).

## Como usar

Abra `index.html` direto no navegador — não precisa de build, servidor nem dependências. O progresso fica salvo no `localStorage` do próprio navegador.

Se o repositório estiver com GitHub Pages ativado, o app também roda em `https://<usuario>.github.io/tatame/`.
