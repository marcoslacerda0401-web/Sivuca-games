# FOLE — A Jornada de Mestre Sivuca

Jogo musical e biográfico em HTML, CSS e JavaScript, pensado para navegador e dispositivos móveis.

## Como jogar
- Abra o site ou o arquivo `index.html` em um navegador moderno.
- Arraste o fole na ilustração para controlar a pressão do ar.
- Toque nas teclas claras para a melodia e nos botões vermelhos para os baixos.
- Nos desafios de improvisação, alterne entre melodia e baixos até completar a barra.
- Use as setas esquerda/direita do teclado para movimentar o fole.
- O progresso é salvo localmente no navegador.

## Publicar com GitHub Pages
O repositório já contém um workflow de publicação automática. Para ativar o site uma única vez:

1. Abra **Settings → Pages** no repositório.
2. Em **Build and deployment → Source**, selecione **GitHub Actions**.
3. Salve. A próxima atualização na branch `main` executará a validação e tentará publicar o site.
4. Acompanhe o resultado em **Actions**. O endereço publicado aparece em **Settings → Pages**.

## Testes automáticos
A cada envio para `main`, o GitHub Actions:
- extrai o JavaScript embutido e verifica a sintaxe com Node.js;
- verifica se os identificadores HTML não estão duplicados;
- confere proteções básicas do desafio de improvisação de Nova York.

## Observações
- O áudio é sintetizado no navegador com Web Audio API; não contém gravações comerciais.
- Cenas e diálogos dramatizados são ficcionais, não citações reais.
- Os fatos biográficos são apresentados como história; escolhas do jogador não alteram esses fatos.
- O salvamento usa o armazenamento local do navegador. Limpar os dados do navegador pode apagar a jornada.
