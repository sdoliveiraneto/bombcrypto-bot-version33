# bombcrypto-bot-version33

# Bot feito pelo https://github.com/MatheusHAS fiz somente adição da nova tela de login.

# Funções extras adicionadas
Usar navegador com zoom diferente (escala)
Suporte a multiplas contas no mesmo monitor (usar URL do IFRAME para acessar)
Debug por funções do jogo
Suporte a monitores retina
Instalação:
1- Baixe e instale Python na versão maior que 3 no site oficial ou através da windows store .

2 - Após instalado python:

Para windows executar como administrador o arquivo run.batna pasta principal.
Para linuxo arquivo run.shna pasta principal.
Configurações:
Você pode configurar algumas opções alterando o arquivo config.yamlna pasta principal do bot.

scale_image
Você agora tem suporte para colocar quantos % de zoom está usando em seu navegador.

Se atente ao ZOOM também da janela de notificação do Metamask , ela deve ser a mesma usada no navegador.

enable
Quando True, ativa a funcionalidade de usar uma escala diferente. Caso contrário, deixe o valor comoFalse

O valor deve ser: TrueouFalse

percent
A porcentagem de zoom do seu navegador e da janela de notificação do metamask.

O Valor deve ser de: 50a 100. Quanto menor o valor, mais impreciso serão as detecções do bot.

is_retina_screen
Caso seu computador seja um dispositivo mac com tela retina, será necessário ativar essa opção para que o bot realize cliques com precisão. Se seu bot move o mouse para lugares aleatórios, talvez essa opção te ajude.
O valor deve ser: Truepara ativar, ou Falsepara desativar

mouse_move_speed
Você pode configurar a velocidade com que o mouse se move na tela antes da realização do clique.
O valor deve ser de: 0.1a1

multiples_accounts_same_monitor
Essa opção habilita o uso de multiplas contas no mesmo monitor, sendo as ações feitas de forma sincronizada, ou seja, uma janela por vez. Para usar essa funcionalidade sugerimos usar uma URL do IFRAME do jogo.

enable
O Valor deve ser: Truepara habilitar ou Falsepara desabilitar

window_contains_title
Essa opção oferece a possibilidade de alterar o texto que será utilizado para detectar como janelas. Esse texto deve estar no título da janela do nunca.
