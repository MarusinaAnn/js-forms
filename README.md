[![Build status](https://ci.appveyor.com/api/projects/status/41bq5p54wytq64fn?svg=true)](https://ci.appveyor.com/project/MarusinaAnn/js-forms)

![CI](https://github.com/MarusinaAnn/js-forms/actions/workflows/web.yml/badge.svg)

github-pages deployment - https://marusinaann.github.io/js-forms/


# Домашнее задание к занятию "Работа с HTML-формами"

Правила сдачи задания:
1. **Важно**: в рамках этого ДЗ вы можете использовать любой пакетный менеджер
2. Всё должно собираться через Webpack (включая картинки и стили) и выкладываться на Github Pages через Appveyor.
3. В README.md должен быть размещён бейджик сборки и ссылка на Github Pages
4. В качестве результата присылайте проверяющему ссылки на ваши GitHub-проекты.

---

### Popovers

#### Легенда

Есть замечательный фреймворк Bootstrap, в котором реализовано достаточно много интересных виджетов с использованием jQuery. Но, как говорят современные и модные программисты, "jQuery не нужен", поэтому вам нужно реализовать такой же виджет на чистом JS.

#### Описание

Вот так должен выглядеть виджет в целом, для упрощения будем считать, что виджет всегда должен показываться сверху.

![](./pic/Popovers.png)


У popover'а обязательно должно быть название и текст. Центрироваться он обязательно должен по горизонтали относительно элемента, который вызвал popover'а.

Не забудьте написать авто-тест на взаимодействие с DOM на базе Puppeteer или JSDOM (на ваш выбор).

**Подсказка**: страница, на которой можно "подглядеть" реализацию: https://getbootstrap.com/docs/4.3/components/popovers/. Но мы пока не проходили `translate`, `translate3d`, поэтому делайте позиционирование в px.
