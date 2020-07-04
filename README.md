# Обучение Яндекс Практикум

## Проектная работа 10 

[Ссылка на форму](https://qwelp.github.io/sprint-10-homework.github.io/)

### Валидация полей

#### Name
```html
[А-ЯЁ]{1}[а-яё]+(-[А-ЯЁ]{1}[а-яё]+)?
```

#### Email
```html
[a-z0-9-.]+@[a-z0-9-]+\.[a-z]+(.[a-z]+)?
```

#### Телефон
```html
(\+7|8)( |\()?[0-9]{3}(\))?( |-)?[0-9]{3}(-)?[0-9]{2}(-)?[0-9]{2}
```

#### Сайт
```html
((http|https)://)?(www.)?([0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}|[a-z0-9-]+\.[a-z]+[a-z]+?)(:[0-9]{2,5})?([a-z/]+)?#?

```

Версия v0.0.5