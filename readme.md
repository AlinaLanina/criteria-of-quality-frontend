# Критерии хорошей верстки

Обязательные и необязательные критерии оценки вёрстки.

[Проверить вёрстку](https://nicothin.github.io/criteria-of-quality-frontend/index.html)

## Автоматизация некоторых проверок

Нужно поставить зависимости: `npm i`

Проверяемые файлы и папки положить в `test/`, вызвать `npm run lint`. Найденные ошибки будут показаны в консоли с упоминанием файла, строки и описания ошибки.

Проверка | Инструмент | Описание
--- | --- | ---
Соответствие БЭМ | [bemlint](https://github.com/DesTincT/bemlint) | Соответствие разметки правилам БЭМ-а (разделители `__` и `--`)
Соответствие `.editorconfig` | [eclint](https://github.com/jedmao/eclint) | Соответствие всех файлов правилам, описанным в `.editorconfig`
Соответствие `.htmllintrc` | [htmllint](https://github.com/htmllint/htmllint) | Соответствие разметки правилам, описанным в `.htmllintrc`
 |  |
