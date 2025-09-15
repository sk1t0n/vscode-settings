# vscode-settings

Мои настройки и установленные расширения для редактора кода VS Code.

[![license](https://img.shields.io/github/license/sk1t0n/vscode-settings.svg?style=flat-square)](LICENSE) [![vscode-settings](https://img.shields.io/badge/vscode-settings-brightgreen.svg?style=flat-square)](settings.json)

<details>
<summary>Содержание</summary>

- [Замена настроек VS Code](#замена-настроек-vs-code)
- [94 Расширения для VS Code](#94-расширения-для-vs-code)
  - [AI](#ai)
  - [Git](#git)
  - [Docker, Kubernetes](#docker-kubernetes)
  - [Переменные среды](#переменные-среды)
  - [Проверка орфографии](#проверка-орфографии)
  - [Единый формат настроек для популярных редакторов кода и IDE](#единый-формат-настроек-для-популярных-редакторов-кода-и-ide)
  - [Apache, Nginx](#apache-nginx)
  - [Базы данных](#базы-данных)
  - [PHP](#php)
    - [Laravel](#laravel)
  - [JavaScript, TypeScript](#javascript-typescript)
  - [Python](#python)
  - [Go](#go)
  - [Rust](#rust)
  - [Protobuf](#protobuf)
  - [HTML, XML](#html-xml)
  - [CSS](#css)
  - [Markdown](#markdown)
  - [YAML, Neon, TOML](#yaml-neon-toml)
  - [Темы, иконки](#темы-иконки)
  - [Разное](#разное)
- [Лицензия](#лицензия)

</details>

## Замена настроек VS Code

1. Открыть палитру команд в VS Code: **CTRL + SHIFT + P**.
2. Ввести json, выбрать пункт **Preferences: Open User Settings (JSON)** и нажать **ENTER**.
3. Частично или полностью заменить содержимое открытого файла содержимым файла **settings.json** из репозитория.

## 94 Расширения для VS Code

### AI

1. [Windsurf Plugin (formerly Codeium): AI Coding Autocomplete and Chat for Python, JavaScript, TypeScript, and more](https://marketplace.visualstudio.com/items?itemName=Codeium.codeium)
2. [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
3. [GitHub Copilot Chat](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-chat)

### Git

1. [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)
2. [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
3. [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
4. [Conventional Commits](https://marketplace.visualstudio.com/items?itemName=vivaxy.vscode-conventional-commits)
5. [GitHub Actions](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-github-actions)

### Docker, Kubernetes

1. [Container Tools](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-containers)
2. [Kubernetes](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-kubernetes-tools)

### Переменные среды

1. [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)

### Проверка орфографии

1. [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
2. [Russian - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-russian)

### Единый формат настроек для популярных редакторов кода и IDE

1. [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

### Apache, Nginx

1. [Apache Conf](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-apache)
2. [Apache Conf Snippets](https://marketplace.visualstudio.com/items?itemName=eiminsasete.apacheconf-snippets)
3. [NGINX Configuration Language Support](https://marketplace.visualstudio.com/items?itemName=ahmadalli.vscode-nginx-conf)

### Базы данных

1. [SQLTools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools)
2. [SQLTools PostgreSQL/Cockroach Driver](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools-driver-pg)
3. [SQLTools MySQL/MariaDB](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools-driver-mysql)
4. [SQLTools SQLite](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools-driver-sqlite)
5. [SQL Formatter](https://marketplace.visualstudio.com/items?itemName=adpyke.vscode-sql-formatter)

### PHP

1. [PHP Awesome Snippets](https://marketplace.visualstudio.com/items?itemName=hakcorp.php-awesome-snippets)
2. [PHPUnit Snippets](https://marketplace.visualstudio.com/items?itemName=onecentlin.phpunit-snippets)
3. [php cs fixer](https://marketplace.visualstudio.com/items?itemName=junstyle.php-cs-fixer)
4. [Composer](https://marketplace.visualstudio.com/items?itemName=DEVSENSE.composer-php-vscode)
5. [PHP](https://marketplace.visualstudio.com/items?itemName=DEVSENSE.phptools-vscode)
6. [PHP Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client)
7. [PHP IntelliSense](https://marketplace.visualstudio.com/items?itemName=zobo.php-intellisense)
8. [PhpStorm Parameter Hints in VScode](https://marketplace.visualstudio.com/items?itemName=MrChetan.phpstorm-parameter-hints-in-vscode)
9. [PHP Namespace Resolver](https://marketplace.visualstudio.com/items?itemName=MehediDracula.php-namespace-resolver)
10. [PHP Getters & Setters](https://marketplace.visualstudio.com/items?itemName=phproberto.vscode-php-getters-setters)
11. [PHP Constructor](https://marketplace.visualstudio.com/items?itemName=MehediDracula.php-constructor)
12. [PHP Add Property](https://marketplace.visualstudio.com/items?itemName=kotfire.php-add-property)
13. [PHP DocBlocker](https://marketplace.visualstudio.com/items?itemName=neilbrayfield.php-docblocker)
14. [PHP Debug](https://marketplace.visualstudio.com/items?itemName=xdebug.php-debug)
15. [PHP Profiler](https://marketplace.visualstudio.com/items?itemName=DEVSENSE.profiler-php-vscode)
16. [PHPUnit Test Explorer](https://marketplace.visualstudio.com/items?itemName=recca0120.vscode-phpunit)
17. [PHP Server](https://marketplace.visualstudio.com/items?itemName=brapifra.phpserver)

#### Laravel

1. [Laravel Snippets](https://marketplace.visualstudio.com/items?itemName=onecentlin.laravel5-snippets)
2. [Laravel Model Snippets](https://marketplace.visualstudio.com/items?itemName=ahinkle.laravel-model-snippets)
3. [Laravel Blade Snippets](https://marketplace.visualstudio.com/items?itemName=onecentlin.laravel-blade)
4. [Laravel Extra Intellisense](https://marketplace.visualstudio.com/items?itemName=amiralizadeh9480.laravel-extra-intellisense)
5. [Laravel Ide Helper](https://marketplace.visualstudio.com/items?itemName=georgykurian.laravel-ide-helper)
6. [Laravel Artisan](https://marketplace.visualstudio.com/items?itemName=ryannaddy.laravel-artisan)
7. [Laravel goto view](https://marketplace.visualstudio.com/items?itemName=codingyu.laravel-goto-view)
8. [laravel-goto-components](https://marketplace.visualstudio.com/items?itemName=naoray.laravel-goto-components)
9. [Laravel Blade Spacer](https://marketplace.visualstudio.com/items?itemName=austenc.laravel-blade-spacer)
10. [Laravel Blade formatter](https://marketplace.visualstudio.com/items?itemName=shufo.vscode-blade-formatter)

### JavaScript, TypeScript

1. [Biome](https://marketplace.visualstudio.com/items?itemName=biomejs.biome)
2. [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
3. [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
4. [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
5. [Document This](https://marketplace.visualstudio.com/items?itemName=oouo-diogo-perdigao.docthis)

### Python

1. [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
2. [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)
3. [Python Debugger](https://marketplace.visualstudio.com/items?itemName=ms-python.debugpy)
4. [Python Environments](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-python-envs)

### Go

1. [Go](https://marketplace.visualstudio.com/items?itemName=golang.Go)
2. [go-lines](https://marketplace.visualstudio.com/items?itemName=gofenix.go-lines)

### Rust

1. [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)

### Protobuf

1. [vscode-proto3](https://marketplace.visualstudio.com/items?itemName=zxh404.vscode-proto3)

### HTML, XML

1. [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
2. [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
3. [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
4. [Highlight Matching Tag](https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag)
5. [XML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml)

### CSS

1. [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
2. [CSS Modules](https://marketplace.visualstudio.com/items?itemName=clinyong.vscode-css-modules)
3. [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
4. [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)

### Markdown

1. [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
2. [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
3. [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)
4. [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf)

### YAML, Neon, TOML

1. [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)
2. [Nette Latte + Neon](https://marketplace.visualstudio.com/items?itemName=Kasik96.latte)
3. [Even Better TOML](https://marketplace.visualstudio.com/items?itemName=tamasfe.even-better-toml)

### Темы, иконки

1. [GitHub Theme](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme)
2. [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)

### Разное

1. [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)
2. [Explorer Exclude](https://marketplace.visualstudio.com/items?itemName=PeterSchmalfeldt.explorer-exclude)
3. [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
4. [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)
5. [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)
6. [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
7. [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
8. [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
9. [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
10. [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)
11. [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
12. [Draw Folder Structure](https://marketplace.visualstudio.com/items?itemName=jmkrivocapich.drawfolderstructure)
13. [Image preview](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-preview)
14. [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)

## Лицензия

[MIT](LICENSE)
