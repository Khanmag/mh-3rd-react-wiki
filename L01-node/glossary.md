### Node.js

Node.js - программная платформа, основанная на движке V8 (компилирующем JavaScript в машинный код), превращающая JavaScript из узкоспециализированного языка в язык общего назначения.

### NPM (Node Package Manager)

NPM - это пакетный менеджер для языка программирования JavaScript. Он позволяет разработчикам легко устанавливать, обновлять и управлять сторонними библиотеками и инструментами, необходимыми для разработки приложений на платформе Node.js.

### package.json

`package.json` - это файл конфигурации для проектов на платформе Node.js. Он содержит метаданные о проекте, а также информацию о его зависимостях, скриптах, версии и других настройках, необходимых для правильной установки, сборки и работы приложения.

### REPL

REPL (Read-Eval-Print Loop) - это интерактивная среда, которая позволяет вводить команды или выражения, а затем немедленно выполнять их и выводить результаты. REPL предоставляет пользователю возможность взаимодействовать с программой или языком программирования на уровне командной строки. Node.js поставляется с встроенным REPL.

### node_modules

`node_modules` - это папка в проектах на платформе Node.js, которая содержит установленные пакеты (модули) JavaScript, которые используются в проекте. Когда вы устанавливаете сторонние библиотеки или инструменты с помощью пакетного менеджера NPM (Node Package Manager), они автоматически загружаются и сохраняются в папку node_modules.

### Модуль

Модуль - это фрагмент кода, который может быть использован повторно и изолированно в приложениях. Модули помогают организовать код, разделять его на отдельные компоненты и повторно использовать функции, переменные и другие ресурсы без необходимости дублирования кода.

### NPX

`npx` - это инструмент, входящий в состав пакетного менеджера NPM начиная с версии 5.2.0. Он используется для запуска пакетов Node.js и выполняет их без необходимости явно устанавливать эти пакеты глобально на вашей системе. Ранее, для выполнения пакетов или команд, установленных через NPM, вы должны были установить их глобально, что могло вызывать проблемы с версиями или нежелательными конфликтами между различными проектами.

npx решает эту проблему, предоставляя удобный способ временно устанавливать и запускать пакеты. Когда вы вызываете команду с использованием npx, он проверяет, установлен ли указанный пакет в локальной директории (в папке проекта), и если он там отсутствует, временно устанавливает его, выполняет команду, а затем удаляет временную установку.

### Eslint

ESLint (сокращение от "ECMAScript Lint") - это инструмент статического анализа кода для JavaScript. Он используется для обнаружения потенциальных проблем в коде, стандартизации стиля кодирования и обеспечения согласованности кодовой базы в проектах на JavaScript.

ESLint позволяет определить и предотвратить ошибки, антипаттерны и другие проблемы в коде на ранних этапах разработки. Он проверяет код на соответствие заданным правилам и нормам стиля, что помогает улучшить качество кода, облегчить его читаемость и снизить возможность возникновения ошибок.

### Prettier

Prettier - это инструмент автоматического форматирования кода, который используется для улучшения внешнего вида и стиля вашего кода. В отличие от ESLint, который сконцентрирован на статическом анализе и обнаружении потенциальных проблем в коде, Prettier фокусируется исключительно на форматировании и приведении кода к единому стандарту стиля.

### .eslintrc

`.eslintrc` - это конфигурационный файл для ESLint, инструмента статического анализа кода JavaScript. ESLint позволяет определять правила и настройки, которые будут применяться к вашему проекту при анализе и проверке кода на соответствие определенным стандартам стиля, ошибкам и потенциальным проблемам.

### eslint-config-prettier

`eslint-config-prettier` - это пакет конфигурации для ESLint, который позволяет избежать конфликтов между правилами форматирования ESLint и Prettier. Когда используются и ESLint, и Prettier одновременно, они могут применять различные правила форматирования, что приводит к нежелательным изменениям кода или взаимным перезаписям правил.

Для предотвращения таких конфликтов и создания единой и согласованной системы форматирования, разработчики обычно устанавливают eslint-config-prettier. Этот пакет предоставляет конфигурацию ESLint, которая отключает все правила, конфликтующие с Prettier, оставляя только правила, касающиеся статического анализа кода.
