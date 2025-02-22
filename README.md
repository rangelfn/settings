# 🚀 Configuração do VS Code para Node.js, Vue.js e PHP

Este repositório documenta a configuração ideal do **VS Code** para trabalhar com **Node.js**, **Vue.js**, **PHP** e tecnologias relacionadas. Aqui você encontrará as configurações otimizadas, os plugins recomendados e as melhores práticas.

![VS Code Config](https://github.com/rangelfn/settings/assets/23268600/978c01a0-efd4-45d9-a2c0-c76e130c132b)

---

## 📖 Sumário
- [Requisitos](#requisitos)
- [Extensões Recomendadas](#extensões-recomendadas)
- [Configuração do VS Code](#configuração-do-vs-code)
  - [Configurar Git Bash como terminal padrão](#configurar-git-bash-como-terminal-padrão)
  - [Habilitar formatação automática com Prettier e ESLint](#habilitar-formatação-automática-com-prettier-e-eslint)
  - [Configuração para Vue.js](#configuração-para-vuejs)
  - [Configuração para PHP](#configuração-para-php)
  - [Configuração do Live Server](#configuração-do-live-server)
- [Como Usar](#como-usar)
- [Dúvidas ou Sugestões](#dúvidas-ou-sugestões)
- [Licença](#licença)
- [📜 Arquivo Completo de Preferências](#arquivo-completo-de-preferências)

---

## Requisitos
Antes de começar, certifique-se de que você tenha instalado:
- [VS Code](https://code.visualstudio.com/)
- [Node.js](https://nodejs.org/)
- [Git](https://git-scm.com/)
- [PHP](https://www.php.net/)

## Extensões Recomendadas
Instale as seguintes extensões para melhorar a produtividade no VS Code:
```
drcika.apc-extension
formulahendry.auto-close-tag
naumovs.color-highlight
usernamehw.errorlens
miguelsolorio.fluent-icons
ecmel.vscode-html-css
Zignd.html-css-class-completion
Nur.just-black
onecentlin.laravel-blade
onecentlin.laravel5-snippets
ritwickdey.LiveServer
PKief.material-icon-theme
miguelsolorio.min-theme
jaguadoromero.vscode-php-create-class
mansoorkhan96.php-cs-fixer
bmewburn.vscode-intelephense-client
MehediDracula.php-namespace-resolver
esbenp.prettier-vscode
Alexey-Strakh.stackoverflow-search
miguelsolorio.symbols
```

Para instalar todas de uma vez, execute no terminal:
```sh
code --install-extension drcika.apc-extension \
    formulaHendry.auto-close-tag \
    naumovs.color-highlight \
    usernamehw.errorlens \
    miguelsolorio.fluent-icons \
    ecmel.vscode-html-css \
    Zignd.html-css-class-completion \
    Nur.just-black \
    onecentlin.laravel-blade \
    onecentlin.laravel5-snippets \
    ritwickdey.LiveServer \
    PKief.material-icon-theme \
    miguelsolorio.min-theme \
    jaguadoromero.vscode-php-create-class \
    mansoorkhan96.php-cs-fixer \
    bmewburn.vscode-intelephense-client \
    MehediDracula.php-namespace-resolver \
    esbenp.prettier-vscode \
    Alexey-Strakh.stackoverflow-search \
    miguelsolorio.symbols
```

## Configuração do VS Code

### Configurar Git Bash como terminal padrão
No arquivo **settings.json**, adicione:
```json
"terminal.integrated.defaultProfile.windows": "Git Bash",
"terminal.integrated.profiles.windows": {
    "Git Bash": {
        "path": "C:\\Program Files\\Git\\bin\\bash.exe"
    }
}
```

### Habilitar formatação automática com Prettier e ESLint
```json
"editor.formatOnSave": true,
"editor.defaultFormatter": "esbenp.prettier-vscode",
"editor.codeActionsOnSave": {
    "source.fixAll": true,
    "source.fixAll.eslint": true
}
```

### Configuração para Vue.js
```json
"vetur.format.defaultFormatter.html": "prettier",
"vetur.format.defaultFormatter.js": "prettier",
"vetur.format.defaultFormatter.css": "prettier",
"volar.autoInsert.parentheses": true
```

### Configuração para PHP
```json
"php.executablePath": "/usr/bin/php",
"php-cs-fixer.rules": "@PSR12",
"intelephense.format.enable": true
```

### Configuração do Live Server
```json
"liveServer.settings.port": 5500
```

## Como Usar
1. Clone este repositório
```sh
git clone https://github.com/rangelfn/settings.git
```
2. Abra o VS Code e aplique as configurações
3. Instale as extensões recomendadas
4. Reinicie o VS Code

Agora seu VS Code está pronto para desenvolver com **Node.js, Vue.js e PHP**! 🎯🔥

---

## Dúvidas ou Sugestões
📢 Caso tenha dúvidas ou sugestões, abra uma [issue](https://github.com/rangelfn/settings/issues) no repositório!

---

## Licença
📝 Este projeto está sob a licença MIT. Sinta-se à vontade para usar, modificar e compartilhar! 🚀

---

## 📜 Arquivo Completo de Preferências
Para acessar o arquivo completo das preferências do VS Code, clique [aqui](https://github.com/rangelfn/settings/blob/main/preferences_vs_code).
