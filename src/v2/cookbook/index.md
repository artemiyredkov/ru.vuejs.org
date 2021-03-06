---
title: Введение
type: cookbook
order: 0
---

## Книга рецептов vs Руководство

Чем книга рецептов отличается от раздела "Руководство"? В чем её необходимость?

* **Бо́льший фокус**: В руководстве мы, по сути, рассказываем историю. Каждый раздел основывается на знаниях из предыдущего. В книге рецептов, каждый рецепт может и должен быть независимым. Это означает, что рецепты могут сосредоточиться на одном конкретном аспекте Vue, а не на том, чтобы дать общий обзор.

* **Больше подробностей**: Чтобы не делать руководство слишком большим, мы постарались включить только самые простые примеры, которые помогут вам разобраться с каждой возможностью. Затем мы пошли дальше. В книге рецептов мы можем описывать более сложные примеры, сочетая вместе разные особенности. Каждый рецепт может быть таким же длинным и подробным, каким он должен быть, чтобы вы могли глубоко изучить каждый аспект.

* **Изучение JavaScript**: В руководстве мы предполагаем, что вы знакомы с ES5 JavaScript. Например, мы не будем объяснять, как `Array.prototype.filter` работает в вычисляемом свойстве, которое фильтрует список. Однако, в книге рецептов основные возможности JavaScript (включая ES6/2015+) можно изучить и объяснить в контексте того, как они помогают нам создавать лучшие приложения Vue.

* **Изучение экосистемы**: Для продвинутых возможностей, мы предполагаем, что вы имеете некоторые знания об экосистеме. Например, если вы хотите использовать однофайловые компоненты в Webpack, мы не объясняем, как настроить Webpack. В книге рецептов у нас есть пространство для изучения экосистемы этих библиотек подробнее — по крайней мере, в том виде, в котором это будет полезно для разработчиков Vue.

## Участие в книге рецептов

### Что мы ищем

Книга рецептов показывает разработчикам примеры работы или интересные сценарии использования, а также постепенно объясняет более сложные детали. Наша цель — выйти за рамки простого вводного примера и продемонстрировать концепции, которые более широко применимы, а также некоторые недостатки того или иного подхода.

Если вам интересно сделать свой вклад, создавайте issue с тегом **cookbook idea** с вашей идеей, чтобы мы могли обсудить с вами детали для успешного добавления вашего нового рецепта. После того, как ваша идея будет одобрена, пожалуйста, следуйте нижеприведенному шаблону. Некоторые разделы необходимы, а некоторые нет. Настоятельно рекомендуется, выполнять действия по порядку, но это необязательно.

Рецепт в целом должен:

> * Решать конкретную распространённую проблему
> * Начинаться с наипростейшего примера
> * Постепенно увеличивать сложность
> * Ссылаться на другие документы, вместо повторного объяснения
> * Чётко описывать проблему, а не рассчитывать на осведомленность
> * Объяснять процесс, а не конечный результат
> * Описывать плюсы и минусы вашего подхода, в том числе ситуации, когда он не уместен
> * Упомянуть альтернативные решения, если они есть, но описывать подробности в отдельном рецепте

Мы просим вас следовать приведенному ниже шаблону. Однако мы понимаем, что бывают моменты, когда может потребоваться отклонение для большей ясности. В любом случае, все рецепты должны в какой-то момент обсудить нюансы выбора, сделанного с использованием этого шаблона, предпочтительно в форме альтернативного шаблона в соответствующем разделе.

### Простой пример

_обязательно_

1.  Опишите проблему парой предложений.
2.  Объясните простое доступное решение.
3.  Покажите небольшой пример кода.
4.  Объясните, что выполняет данный код.

### Подробная информация

_обязательно_

1. Обращайтесь к общим вопросам, которые могут возникнуть при просмотре примера. (Цитаты отлично подходят)
2. Покажите примеры распространенных ошибок и как их можно избежать.
3. Покажите примеры кода с использованием хороших и плохих практик.
4. Обсудите, почему это может быть подходящим шаблоном. Ссылки для справки не требуются, но поощряются.

### Реальный пример

_обязательно_

Продемонстрируйте код, который будет использовать распространенный или интересный подход решения, либо путем:

1. Описания кратких примеров настройки 
2. Предоставления примера на codepen/jsfiddle

Если вы решите сделать последнее, вы все равно должны описать, что это и как это работает.

### Дополнительно

_опционально_

Очень полезным будет небольшое описание этого шаблона, где еще он может использоваться, за счёт чего он хорошо работает. Также вы можете оставить здесь дополнительные материалы для изучения.

### Когда избегать этого шаблона

_опционально_

Хоть этот раздел необязательный, но настоятельно рекомендуется. Нет смысла писать его для чего-то очень простого, например, для переключения классов, основанных на изменении состояния, но для более продвинутых шаблонов, таких как примеси, это жизненно необходимо. Ответ на большинство вопросов разработки — [«Как посмотреть!»] (https://codepen.io/rachsmith/pen/YweZbG), этот раздел предназначен для этого. Здесь мы будем честно смотреть, когда шаблон полезен и когда его следует избегать, или когда что-то еще имеет смысл.

### Альтернативные варианты

_обязательно_

Этот раздел необходим, если вы указали раздел со случаями, когда следует избегать. Важно изучить другие подходы, чтобы люди, которые скажут: «что-то является антипаттерном в определенных ситуациях», не оставались в недоумении. При этом не забывайте, что многие люди имеют разную структуру кода и решают разные цели. Приложение маленькое или большое? Интегрируется ли Vue в существующий проект или создается с нуля? Их пользователи пытаются достичь одной цели или многих? Много ли асинхронных данных? Все эти проблемы будут влиять на альтернативные решения. Хороший рецепт дает разработчикам ответы на все вопросы.

## Спасибо

Требуется время, чтобы внести свой вклад в документацию, и если вы тратите время на отправку PR в этот раздел нашей документации, мы вам очень благодарны.
