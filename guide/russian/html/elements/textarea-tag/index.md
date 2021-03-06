---
title: Textarea Tag
localeTitle: Textarea Tag
---
## Textarea Tag

Тег textarea HTML позволяет ввести поле, которое будет содержать текст для обратной связи или взаимодействия с пользователем. В большинстве случаев обычно считается, что текстовое поле используется как часть формы.

Программисты используют тег textarea для создания многострочного поля для ввода пользователем (полезно особенно в том случае, если пользователь должен иметь возможность вставлять в форму более длинный текст). Программисты могут указывать разные атрибуты для тегов textarea.

Образец кода:

```html

    <form> 
      <textarea name="comment" rows="8" cols="80" maxlength="500" placeholder="Enter your comment here..." required></textarea> 
    </form> 
```

Наиболее распространенные атрибуты: атрибуты `row` и `cols` определяют высоту и ширину текстового поля Атрибут `placeholder` указывает текст, который видим пользователю, он помогает пользователю понять, какие данные следует вводить в атрибут `maxlength` определяет максимальную длину текста, который можно ввести в текстовое поле, пользователь не может отправлять больше символов `required` атрибут означает, что это поле должно быть заполнено перед отправкой формы

Для получения дополнительной информации о теге textarea и его атрибутах посетите MDN или w3schools .