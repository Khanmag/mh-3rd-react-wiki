### Запуск проекта

```
npm init
```

### Устанавливаем Eslint

```jsx
npm install --save-dev eslint

// инициализируем eslint и настраиваем стиль - выбираем airbnb
npx eslint --init
```

### Устанавливаем Prettier

```jsx
npm install --save-dev prettier
```

### Дружим Eslint и Prettier

Установите eslint-config-prettier:

```jsx
npm install --save-dev eslint-config-prettier
```

Затем добавьте "prettier" в массив "extends" в файле .eslintrc.\*. Убедитесь, что он находится последним, чтобы он имел возможность переопределить другие конфигурации.

```jsx
{
	"extends": [
			"some-other-config-you-use",
			"prettier"
		]
}
```

### Памятка по Git

https://training.github.com/downloads/ru/github-git-cheat-sheet/
