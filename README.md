# Tatame

App single-file para acompanhar a frequência na academia de jiu-jitsu: 3 aulas por semana ao longo de 13 semanas (39 aulas em 90 dias).

Inclui uma **Biblioteca** de movimentações (guardas, raspagens, passagens, finalizações, controles e escapes), com busca, filtro por categoria e um tutorial resumido por técnica: foto da posição, ponto-chave, ideia central, passo a passo, detalhes, erros comuns, conceito de referência e técnicas relacionadas.

O visual segue uma linha minimalista de inspiração oriental: fundo de papel, tinta e vermelhão, títulos em serifa mincho (Shippori Mincho) e texto em Zen Kaku Gothic New. 

## Fotos das técnicas

Cada técnica mostra uma foto na lista e no tutorial, nesta ordem de prioridade:

1. **Foto da academia** em `img/<id>.jpg` (veja `img/README.md` para a lista de ids). É o caminho recomendado: fotos dos próprios professores demonstrando a posição.
2. **Wikimedia Commons**, fotos com licença livre cadastradas no código, exibidas com o crédito "Foto: Wikimedia Commons" linkando para a página do arquivo (hoje cerca de 15 técnicas).
3. **Sem foto**: espaço reservado "Foto em preparação".

## Escopo desta versão (lado do aluno)

Este app é a visão do aluno. O aluno envia a confirmação de que vai treinar; ela fica **pendente** (com um X para cancelar) até o professor registrar a presença. Dependem de um módulo admin, ainda a fazer:

- registrar presença e aprovar ou recusar confirmações enviadas;
- grade de aulas, professores e regra de graduação da academia (hoje dados fixos, somente leitura no perfil);
- colegas, contagem de confirmados e chat (hoje exemplos locais).

## Como usar

Abra `index.html` direto no navegador — não precisa de build, servidor nem dependências. O progresso fica salvo no `localStorage` do próprio navegador.

Se o repositório estiver com GitHub Pages ativado, o app também roda em `https://<usuario>.github.io/tatame/`.
