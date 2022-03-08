# t-ui_theme
T-UI Launcher tema

# Instalação do Launcher
* [Linux CLI Launcher](https://play.google.com/store/apps/details?id=ohi.andre.consolelauncher&hl=pt-BR)

# Personalização
## Ativar ou desativar exibição de clima


### Tela com clima ativo:
Por padrão está desabilitado, para ativar execute o comando:
* `$ tuiweather -enable`<br>
ou
* `$ config -set -show-weather true` e `restart` em seguida

|1|2|
|-|-|
|![Screenshot_2022-03-08-10-51-55-475_ohi andre consolelauncher](https://user-images.githubusercontent.com/84329097/157251902-562557bc-db93-4506-9ba1-fc1bf07a078e.jpg)|![Screenshot_2022-03-08-10-52-47-773_ohi andre consolelauncher](https://user-images.githubusercontent.com/84329097/157251926-69d56091-3d6a-4de7-9c0f-b4c2b6029f09.jpg)|

### Tela com clima inativo:
Caso tenha habilitado que queira desabilitar, rode o comando:
* `$ tuiweather -disable`<br>
ou
* `$ config -set -show-weather false` e `restart` em seguida

|1|2|
|-|-|
|![Screenshot_2022-03-08-10-53-17-300_ohi andre consolelauncher](https://user-images.githubusercontent.com/84329097/157251992-1b07625c-4c06-4ad3-8331-ca21258c35ba.jpg)|![Screenshot_2022-03-08-10-54-04-642_ohi andre consolelauncher](https://user-images.githubusercontent.com/84329097/157252011-e600d63a-8ef6-487d-bd05-81b8462000c7.jpg)

## Nome de usuário
Para acrecentar o seu nome de usuário, edite o arquivo `ui.xml` e altere o valo *user* para o desejado (linha 80)
`<username value="user"/>`

# Documentação
* [TUI-ConsoleLauncher](https://github.com/fAndreuzzi/TUI-ConsoleLauncher/wiki)

