# Angular Full Pack

Conjunto das melhores extensões para trabalhar com [Angular](https://angular.io/) e aumentar a sua produtividade neste framework fantástico!

## Sobre as extensões contidas no Angular Full Pack

- [EditorConfig for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) - Esse plugin sobreescreve as configurações do editor baseado no arquivo `.editorconfig` local.

- [VS Code ESLint extension](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - Integra o Eslint no editor para buscar erros.

- [Prettier Formatter for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - Um plugin que roda o prettier para formatar arquivos.

- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) - Automaticamente renomeia a tag par que está sendo modificada.

... Adicionar sobre mais extensões em breve

## Gostaria de instalar somente algumas extensões?

Para instalar somente algumas das extensões, basta editar o arquivo [package.json](package.json) removendo as extensões não desejadas do `extensionPack` e depois siga os procedimentos abaixo para instalar localmente.

## Como desenvolver e instalar localmente

- Clone o repositório

```bash
$ git clone https://github.com/luucasfarias/angular-full-pack
```

- Instale o vsce

```bash
$ npm install -g vsce
```

- Crie o pacote da extensão

```bash
$ vsce package
```

- Instale a extensão através do arquivo `.vsix`

1. Abra o VS Code
2. Selecione **Extensions** do menu
3. Clique em **More** > **Install from VSIX...**
4. Selecione o arquivo `angular-full-pack-x.x.x.vsix`
5. Clique em **Reload Now** para recarregar o VS Code

## Tem alguma extensão que gostaria e não tem?

Abra um PR com o nome da extensão e a mesma será analisada

**Enjoy!**
