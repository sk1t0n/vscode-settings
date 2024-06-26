# vscode-settings

Репозиторий советует полезные расширения для редактора кода VS Code и содержит мои настройки.

[![license](https://img.shields.io/github/license/sk1t0n/vscode-settings.svg?style=flat-square)](LICENSE) [![vscode-settings](https://img.shields.io/badge/vscode-settings-brightgreen.svg?style=flat-square)](https://github.com/sk1t0n/vscode-settings)

<details>
<summary>Содержание</summary>

- [Замена настроек VS Code](#замена-настроек-vs-code)
- [Полезные расширения VS Code](#полезные-расширения-vs-code)
  - [AI](#ai)
  - [Git](#git)
  - [Docker](#docker)
  - [Переменные среды](#переменные-среды)
  - [Проверка орфографии](#проверка-орфографии)
  - [Единый формат настроек для популярных редакторов кода и IDE](#единый-формат-настроек-для-популярных-редакторов-кода-и-ide)
  - [Форматирование кода](#форматирование-кода)
  - [Apache](#apache)
  - [Nginx](#nginx)
  - [Базы данных](#базы-данных)
  - [C#](#csharp)
  - [PHP](#php)
    - [Laravel](#laravel)
  - [JavaScript, TypeScript](#javascript-typescript)
    - [Vue](#vue)
  - [Python](#python)
  - [Go](#go)
  - [Rust](#rust)
  - [HTML, XML](#html-xml)
  - [CSS, SASS](#css-sass)
  - [Markdown](#markdown)
  - [reStructuredText](#restructuredtext)
  - [YAML](#yaml)
  - [Neon](#neon)
  - [TOML](#toml)
  - [Темы, иконки](#темы-иконки)
  - [Разное](#разное)
- [Лицензия](#лицензия)

</details>

## Замена настроек VS Code

1. Открыть палитру команд в VS Code: **CTRL + SHIFT + P**
2. Ввести json, выбрать пункт **Preferences: Open User Settings (JSON)** и нажать **ENTER**
3. Частично или полностью заменить содержимое открытого файла содержимым файла **settings.json** из репозитория

## Полезные расширения VS Code

Некоторые настройки предназначены для конкретного расширения. Ниже представлены основные расширения рекомендуемые к установке.

### AI

1. [Codeium: AI Coding Autocomplete and Chat for Python, Javascript, Typescript, Java, Go, and more](https://marketplace.visualstudio.com/items?itemName=Codeium.codeium)

### Git

1. [GitLens - Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
2. [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)

### Docker

1. [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
2. [Docker Compose](https://marketplace.visualstudio.com/items?itemName=p1c2u.docker-compose)

### Переменные среды

1. [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)

### Проверка орфографии

1. [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
2. [Russian - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-russian)

### Единый формат настроек для популярных редакторов кода и IDE

1. [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

### Форматирование кода

1. [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

### Apache

1. [Apache Conf Snippets](https://marketplace.visualstudio.com/items?itemName=eiminsasete.apacheconf-snippets)
2. [Apache Conf](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-apache)

### Nginx

1. [NGINX Configuration Language Support](https://marketplace.visualstudio.com/items?itemName=ahmadalli.vscode-nginx-conf)

### Базы данных

1. [SQLTools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools)
2. [SQLTools Microsoft SQL Server/Azure](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools-driver-mssql)
3. [SQLTools PostgreSQL/Cockroach Driver](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools-driver-pg)
4. [SQLTools MySQL/MariaDB](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools-driver-mysql)
5. [SQLTools SQLite](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools-driver-sqlite)

### CSharp

1. [C#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
2. [C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit)
3. [C# Extensions](https://marketplace.visualstudio.com/items?itemName=jchannon.csharpextensions)
4. [C# Snippets](https://marketplace.visualstudio.com/items?itemName=jorgeserrano.vscode-csharp-snippets)
5. [C# XML Documentation Comments](https://marketplace.visualstudio.com/items?itemName=k--kato.docomment)
6. [.NET Core Tools](https://marketplace.visualstudio.com/items?itemName=formulahendry.dotnet)
7. [ASP.NET Core Switcher](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.asp-net-core-switcher)
8. [ASP.NET Helper](https://marketplace.visualstudio.com/items?itemName=schneiderpat.aspnet-helper)

### PHP

1. [PHP Awesome Snippets](https://marketplace.visualstudio.com/items?itemName=hakcorp.php-awesome-snippets)
2. [php cs fixer](https://marketplace.visualstudio.com/items?itemName=junstyle.php-cs-fixer)
3. [PHP](https://marketplace.visualstudio.com/items?itemName=DEVSENSE.phptools-vscode)
4. [Composer](https://marketplace.visualstudio.com/items?itemName=DEVSENSE.composer-php-vscode)
5. [PHP Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client)
6. [PHP IntelliSense](https://marketplace.visualstudio.com/items?itemName=zobo.php-intellisense)
7. [PHP Namespace Resolver](https://marketplace.visualstudio.com/items?itemName=MehediDracula.php-namespace-resolver)
8. [PHP Getters & Setters](https://marketplace.visualstudio.com/items?itemName=phproberto.vscode-php-getters-setters)
9. [PHP Constructor](https://marketplace.visualstudio.com/items?itemName=MehediDracula.php-constructor)
10. [PHP DocBlocker](https://marketplace.visualstudio.com/items?itemName=neilbrayfield.php-docblocker)
11. [PHP Debug](https://marketplace.visualstudio.com/items?itemName=xdebug.php-debug)
12. [PHP Profiler](https://marketplace.visualstudio.com/items?itemName=DEVSENSE.profiler-php-vscode)
13. [PHP Server](https://marketplace.visualstudio.com/items?itemName=brapifra.phpserver)
14. [Twig Language 2](https://marketplace.visualstudio.com/items?itemName=mblode.twig-language-2)

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

1. [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
2. [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
3. [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
4. [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
5. [Document This](https://marketplace.visualstudio.com/items?itemName=oouo-diogo-perdigao.docthis)

#### Vue

1. [Vue - Official](https://marketplace.visualstudio.com/items?itemName=Vue.volar)
2. [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
3. [Vue 3 Support - All In One](https://marketplace.visualstudio.com/items?itemName=Wscats.vue)

### Python

1. [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
2. [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)
3. [MagicPython](https://marketplace.visualstudio.com/items?itemName=magicstack.MagicPython)
4. [Python Debugger](https://marketplace.visualstudio.com/items?itemName=ms-python.debugpy)
5. [Python Environment Manager](https://marketplace.visualstudio.com/items?itemName=donjayamanne.python-environment-manager)
6. [autoDocstring - Python Docstring Generator](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring)

### Go

1. [Go](https://marketplace.visualstudio.com/items?itemName=golang.Go)
2. [Go Nightly](https://marketplace.visualstudio.com/items?itemName=golang.go-nightly)

### Rust

1. [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)

### HTML, XML

1. [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
2. [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
3. [XML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml)

### CSS, SASS

1. [Sass (.sass only)](https://marketplace.visualstudio.com/items?itemName=Syler.sass-indented)
2. [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
3. [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
4. [CSS Modules](https://marketplace.visualstudio.com/items?itemName=clinyong.vscode-css-modules)
5. [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
6. [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
7. [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)

### Markdown

1. [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
2. [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)
3. [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf)
4. [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)

### reStructuredText

1. [reStructuredText](https://marketplace.visualstudio.com/items?itemName=lextudio.restructuredtext)

### YAML

1. [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

### Neon

1. [Nette Latte + Neon](https://marketplace.visualstudio.com/items?itemName=Kasik96.latte)

### TOML

1. [Even Better TOML](https://marketplace.visualstudio.com/items?itemName=tamasfe.even-better-toml)

### Темы, иконки

1. [GitHub Theme](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme)
2. [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
3. [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

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
12. [advanced-new-file](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file)

## Лицензия

[MIT](LICENSE)
