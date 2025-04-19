---
created: <% tp.date.now("YYYY-MM-DD") %>
tags: #zettel
---

# <% tp.file.title %>

## Основная идея

Кратко и ясно, в одном-двух предложениях. Сформулируй так, будто объясняешь мысль другу.

## Обоснование / Контекст

Почему эта мысль важна? Откуда она? Может быть, цитата, пример или контекст.

## Связанные заметки

- [[...]]
- [[...]]


> [!Link]-  **Ссылки на текущую заметку**
> ``` dataview
> table without id file.inlinks as "Какие заметки ссылаются" where file.name = this.file.name 
> ```

[https://mindinbox.ru/](https://mindinbox.ru/)
