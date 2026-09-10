# Tatame

App single-file para acompanhar a frequência na academia de jiu-jitsu: 3 aulas por semana ao longo de 13 semanas (39 aulas em 90 dias).

O perfil mostra faixa, graus, grupo e toda a frequência (aulas desde o último grau, ritmo, próximo grau, últimas semanas e últimos treinos) em modo leitura: nome, faixa, graus e grupo são atualizados pelo professor no módulo admin. Na grade e na home, um ícone de kimono marca as aulas do seu grupo. O chat mostra a bolinha no footer só quando há mensagens novas, com contador por conversa e separador de não lidas dentro da conversa.

Inclui uma **Biblioteca** de movimentações (guardas, raspagens, passagens, finalizações, controles e escapes), com busca, filtro por categoria e um tutorial resumido por técnica: espaço para a foto da posição, ponto-chave, ideia central, passo a passo, detalhes, erros comuns, conceito de referência e técnicas relacionadas.

O visual segue uma linha minimalista de inspiração oriental: fundo de papel, tinta e vermelhão, tipografia sem serifa (Zen Kaku Gothic New). 

## Fotos das técnicas

Ainda não definidas: cada técnica mostra um espaço reservado neutro na lista e no tutorial, à espera das fotos da academia.

## Escopo desta versão (lado do aluno)

Este app é a visão do aluno. O aluno envia a confirmação de que vai treinar; ela fica **pendente** (com um X para cancelar) até o professor registrar a presença. Dependem de um módulo admin, ainda a fazer:

- registrar presença e aprovar ou recusar confirmações enviadas;
- cadastro do aluno (nome, faixa, graus, grupo), grade de aulas, professores e regra de graduação (hoje dados fixos, somente leitura);
- colegas, contagem de confirmados e chat (hoje exemplos locais).

## Login e cronômetro

- **Login**: tela inicial limpa com usuário e senha. O acesso é validado no próprio app (usuário `andrean`, senha `12345678`) até o módulo admin passar a controlar as contas. A sessão fica salva no aparelho; "Sair da conta" no perfil volta para o login sem apagar os dados.
- **Cronômetro** (aba no footer): tempo ajustável por minutos e segundos ou presets (3, 5, 6, 7 e 10 min). Ao iniciar, aparece a contagem 3, 2, 1, "Valendo!" em tela cheia e o relógio começa. Dá para pausar, continuar e resetar. Bipes nos últimos segundos e ao terminar.

## Como usar

Abra `index.html` direto no navegador — não precisa de build, servidor nem dependências. O progresso fica salvo no `localStorage` do próprio navegador.

Se o repositório estiver com GitHub Pages ativado, o app também roda em `https://<usuario>.github.io/tatame/`.
