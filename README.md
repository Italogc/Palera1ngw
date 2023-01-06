# Palera1ngw
Novo Palera1n Gui-Windows Linux Passos

1º) Download Palera1n Gui Windows Linux:

https://www.mediafire.com/file/kk0j9r92m0gngho/Palera1n-GUI-LINUX.zip/file


2º) Extrair a pasta no arquivo compactado e dar "cd" nesta pasta no terminal do linux;


3º) Para instalar todas dependências automaticamente:

sudo chmod +x *

sudo sh install.sh
---------------------------------------------------------------------------------------------------------------------

# Processo:

4º) Abrir uma nova janela de terminal dando "cd" na pasta extraída acima (minimizar a janela anterior de instalação, mas não feche), conecte seu aparelho via cabo usb e bote o comando abaixo:

sudo sh pairdevice.sh

5º) abrir um novo terminal dando cd na pasta extraída do palera1n gui acima e dê o seguinte comando:

sudo python3 palera1n-gui.py

6º) Modo "Device File Update" (DFU):
Quando abrir a janela do palera1n no seu linux, bote manualmente seu aparelho em modo dfu antes de fazer qualquer outro passo.


- Para iPads:

1 -  Segure o botão "ligar/desligar" por 3 segundos;
2 -  Sem soltar o botão "ligar/desligar" segure junto também o botão "home/início" por mais 4 segundos, quando o aparelho desligar em tela preta segure por mais 2 segundos;
3 -  Solte o botão "ligar/desligar" e continue segurando o botão "home/início" por mais 6 segundos e solte o botão.
Não mexa mais no aparelho, ele deve estar em tela preta se der certo o procedimento de dfu, mas se aparecer no logo da maçã da apple e reiniciar é porque você errou no tempo de segurar os botões e deverá refazer os passos anteriores até o aparelho ficar em dfu com sucesso;


- Para iPod Touch e iPhones 6 e 7:

1 - Pressione rápido o botão "aumentar volume" e depois o botão "abaixar volume";
2 - Pressione e segure juntos por exatamente 5 segundos os botões "ligar/desligar" e "diminuir volume";
3 - Solte o botão "ligar/desligar" e continue segurando o botão "diminuir volume" por mais 5 segundos, depois solte o botão e não mexa mais no aparelho.
Ele deve estar em tela preta se der certo o procedimento de dfu, mas se aparecer no logo da maçã da apple e reiniciar é porque você errou no tempo de segurar os botões e deverá refazer os passos anteriores até o aparelho ficar em dfu com sucesso;


- Para iPhone 8 e mais recentes:

1 - Pressione rápido o botão "aumentar volume" e depois o botão "abaixar volume";
2 - Pressione e segure por 10 segundos o botão "ligar/desligar";
3 - Continue sugurando o "ligar/desligar" e segure junto também o botão "diminuir volume" por mais 5 segundos;
4 - Solte o botão "ligar/desligar" e continue segurando o botão "diminuir volume" por mais 6 segundos e depois solte o botão e não mexa mais no aparelho.
Ele deve estar em tela preta se der certo o procedimento de dfu, mas se aparecer no logo da maçã da apple e reiniciar é porque você errou no tempo de segurar os botões e deverá refazer os passos anteriores até o aparelho ficar em dfu com sucesso;


7º) Na janela do Palera1n Jailbreak no seu linux escolha a opção de seu melhor agrado, "tethered" ou "semi-tethered".
Vale a pena você saber que:
* o modo "semi-tethered" o seu aparelho toda vez que ele desligar vai ficar travado na tela de "modo restauração" e você vai precisar de reexecutar todo processo de jailbreak desse palera1n novamente para que seu aparelho ligue novamente; 

* o modo "tethered" o seu aparelho desligado poderá ligar normalmente mas com o jailbreak desativado até que você reexecute esse processo de jailbreak do palera1n no seu linux, mas esse processo de tethered vai pesar exatamente 12GB de memória de sistema no armazenamento do seu aparelho.


8º) Após a escolha do passo anterior, na nova janela do programa que abrir você vai ter que digitar a versão exata do ios que está instalada no seu aparelho conectado, por exemplo 16.1.1, e em seguida apertar no botão OK;


9º) Volte na janela de terminal aonde você digitou o comando do (passo 5º) acima, e tecle dentro dela e depois dê enter no teclado para que o processo do jailbreak do palera1n continue normalmente;


10°) Para aparelhos com iOS16, quando no terminal aparecer alguma mensagem escrita "Phase 1 Done! Rebooting your device... Waiting to normal mode device", sem retirar o aparelho do cabo usb e sem fechar nenhuma janela de terminal no linux, bote seu aparelho em modo DFU novamente (passo 6º acima) para o processo do jailbreak continuar normalmente.
Caso seu aparelho já esteja em dfu ou tela preta, reboote o seu aparelho manualmente para depois botar em modo dfu manualmente; para rebootar o seu aparelho:

Para iPads:  Segurar juntos os botões "desligar" e "home" até o logotipo da apple aparecer na tela do aparelho, e solte os botões;

Para iPhones: Segurar juntos os botões "desligar" e "diminuir volume" até o logotipo da apple aparecer na tela do aparelho, e solte os botões;


11º) Após o passo anterior o seu jailbreak no terminal vai reconhecer o seu aparelho em modo DFU e vai continuar com o procedimento de jailbreak,
se necessário clique na janela de terminal do processo de jailbreak e tecle enter no teclado para o processo continuar...


12º) No final quando você tiver alguma mensagem "Device is Jailbroken" parabéns o seu jailbreak foi concluído com sucesso, mas é recomendado manter o aparelho conectado com o terminal aberto na primeira vez, porque você vai ter que abrir seu aplicativo "Tips / Dicas" instalado no seu aparelho e depois clicar na opção "install" para que todos dados do jailbreak sejam instalados no seu aparelho juntamente do sileo e os arquivos do bootstrap. Depois disso já pode soltar o seu aparelho do cabo usb e use o jailbreak com moderação.
