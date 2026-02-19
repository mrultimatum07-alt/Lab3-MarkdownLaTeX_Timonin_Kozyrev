# Лабораторная работа №3. Работа с Markdown-разметкой и базовое использование LaTeX в документации проекта.
Данная лабораторная работа посвящена изучению лёгкого языка разметки Markdown и системы вёрстки математических формул LaTeX. Цель работы — приобрести практические навыки оформления документации, README-файлов и отчётов с использованием современных инструментов, поддерживаемых платформами GitHub, VS Code и другими. В ходе работы создаётся структурированный проект, инициализируется Git-репозиторий, а также отрабатываются ключевые элементы синтаксиса Markdown и LaTeX.
## Содержание (Table of Contents)
- [Структура проекта](#структура-проекта)
- [Заголовки (H1–H3)](#заголовки-h1h3)
- [Горизонтальная линия](#горизонтальная-линия)
- [Форматирование текста](#форматирование-текста)
- [Списки](#списки)
- [Цитата](#цитата)
- [Блок кода](#блок-кода)
- [Таблица](#таблица)
- [Изображение из папки img/](#изображение-из-папки-img)
- [Ссылка](#ссылка)
- [Чекбокс](#чекбокс)
- [Сноска](#сноска)
- [ALert-блоки Github](#alert-блоки-github)
- [Inline LaTeX](#inline-latex)
- [Block LaTex](#block-latex)
---

## Структура проекта
- Lab3_MarkdownLaTeX_Timonin_Kozyrev
  - docs(Markdown-файлы с примерами)
     -  advancedMarkdownLab3_Timonin_Kozyrev
     -  codeQuotesLab3_Timonin_Kozyrev
     -  formattingLab3_Timonin_Kozyrev
     -  headersLab3_Timonin_Kozyrev
     -  LatexLab3_Timomini_Kozyrev
     -  linksImagesLab3_Timonin_Kozyrev
     -  listsLab3_Timonin_Kozyrev
     -  ReadmePushLab3_Timonin_Kozyrev
     -  separatorsLab3_Timonin_Kozyrev
     -  tablesLab3_Timonin_Kozyrev
	- img(Скриншоты выполнения заданий)
	   - advancedMarkdownCommitLab3_Timonin_Kozyrev
	   - codeCommitLab3_Timonin_Kozyrev
	   - commitStructureLab3_Timonin_Kozyrev
	   - formattingCommitLab3_Timonin_Kozyrev
	   - gitPushLab3_Timonin_Kozyrev
	   - headersCommitLab3_Timonin_Kozyrev
	   - latexCommitLab3_Timonin_Kozyrev
	   - linksCommitLab3_Timonin_Kozyrev
	   - listsCommitLab3_Timonin_Kozyrev.png 
	   - separatorsCommitLab3_Timonin_Kozyrev
	   - tablesCommitLab3_Timonin_Kozyrev
	- README (Главный файл документации)

---

## Заголовки (H1–H3)
# Заголовок H1
## Заголовок H1
### Заголовок H1

## Горизонтальная линия

---

## Форматирование текста
**Полужирный**
*Курсив*
~~зачёркнутый~~
`Моноширный`

## Списки
- Маркированный
  - Вложенный
1. Нумерованный

## Цитата
> Ыыыыыыыыыыыы

## Блок кода
```python
print("ыыыы")
```

## Таблица
| ЫыЫ | ЫЫЫ | ЫЫы |
|:----------|:-----------|:-----------|
|1|4|7|
|2|5|8|
|3|6|9| 

## Изображение из папки img/

![Push screenshot](./img/gitPushLab3_Timonin.png)

## Ссылка
Внешняя: [Github](https://github.com)
Внутреняя: ![Скриншот задания](/img/listsCommitLab3_Timonin.png)
## Чекбокс
- [ ] Писать что-то нормальное
- [x] ЫЫЫЫЫЫЫЫЫЫЫЫЫЫЫ
## Сноска
Сноска[^1]
[^1]:Примечание
## ALert-блоки Github
>[!Note]
> ы

>[!TIP]
> ы?

> [!WARNING]
> Ы!

## Inline LaTeX
Площадь круга: $S = \pi r^2$

## Block LaTex
$$
\sum_{i=1}^n i = \frac{n(n+1)}{2}
$$

