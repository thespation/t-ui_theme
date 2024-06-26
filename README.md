# Tema para T-UI Launcher
T-UI Linux CLI Launcher é um lançador gratuito baseado em texto para android.

É distribuído sob licença GPL com algumas reservas por seu criador [Francesco Andreuzzi](https://github.com/fAndreuzzi).

# Instalação do Launcher
Acesso o GitHub do desenvovedor: [T-UI Linux CLI Launcher](https://github.com/fandreuz/TUI-ConsoleLauncher).

# Usando o tema
Com o launcher instalado, clone o repositório, descompacte e jogue a pasta na raiz do seu celular Android.<br>

**Obs:** A pasta precisa estar com o nome `t-ui`, provavelmente já terá uma, basta renomear a antiga e jogar no lugar a que clonou aqui.

# Personalização
## Ativar ou desativar exibição de clima
Por padrão está desabilitado, para ativar execute o comando:
* `$ tuiweather -enable`<br>
ou
* `$ config -set -show-weather true` e `restart` em seguida

### Tela com clima ativo:

|1|2|
|-|-|
|![Screenshot_2022-03-08-10-51-55-475_ohi andre consolelauncher](https://user-images.githubusercontent.com/84329097/157251902-562557bc-db93-4506-9ba1-fc1bf07a078e.jpg)|![Screenshot_2022-03-08-10-52-47-773_ohi andre consolelauncher](https://user-images.githubusercontent.com/84329097/157251926-69d56091-3d6a-4de7-9c0f-b4c2b6029f09.jpg)|

<hr>

Caso tenha habilitado e queira desabilitar, rode o comando:

* `$ tuiweather -disable`<br>
ou
* `$ config -set -show-weather false` e `restart` em seguida

### Tela com clima inativo:

|1|2|
|-|-|
|![Screenshot_2022-03-08-10-53-17-300_ohi andre consolelauncher](https://user-images.githubusercontent.com/84329097/157251992-1b07625c-4c06-4ad3-8331-ca21258c35ba.jpg)|![Screenshot_2022-03-08-10-54-04-642_ohi andre consolelauncher](https://user-images.githubusercontent.com/84329097/157252011-e600d63a-8ef6-487d-bd05-81b8462000c7.jpg)

## Papel de parede
Está configurado para usar o papel de parede do sistema, caso queira desativar essa opção, rode o comando:

`config -set system_wallpaper false` e `restart` em seguida<br>

Caso queira reabilitar, execute:

`config -set system_wallpaper true` e `restart` em seguida

**Obs:** papel de parede utilizado está incluso.

## Atalhos e ícones
Para modificar os ícones de atalhos que estão na parte inferior da tela, edite o arquivo `alias.txt`

## Nome de usuário
Para acrescentar o seu nome de usuário, rode os comandos:

`config -set username NomeDesejado` e `restart` em seguida<br>

ou

Edite o arquivo `ui.xml` e altere o valo *user* para o desejado (linha 80)
`<username value="user"/>`

# Documentação
* [Wiki](https://github.com/fAndreuzzi/TUI-ConsoleLauncher/wiki)
   * [Recursos](https://github.com/fAndreuzzi/TUI-ConsoleLauncher/wiki#features)
   * [Customização](https://github.com/fAndreuzzi/TUI-ConsoleLauncher/wiki#customization)
   * [Como fazer](https://github.com/fAndreuzzi/TUI-ConsoleLauncher/wiki#how-to)
  * [FAQ](https://github.com/fAndreuzzi/TUI-ConsoleLauncher/wiki#faq)
