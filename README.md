# Проект: Путешествие по России


### Описание
В данном проекте реализована адаптивная верстка под различные типы экранов. Были использованы медиазапросы. Например в блоке ```photo-grid``` :
```css
@media screen and (max-width: 1270px) and (min-width: 1010px) {
	.photo-grid {
		width: 100%;
		gap: 14px;
	}
}

@media all and (max-width: 1010px) {
	.photo-grid {
		width: 95%;
		gap: 16px;
	}
}
@media all and (max-width: 700px) {
	.photo-grid {
		gap: 12px;
	}
}
```

Использовалить относительные величины ширины и высоты ```vw``` и ```vh``` соответсвтвенно, а такжке использовались проценты ```%``` при задании размеров блоков.
Реализован способ построение сеток **Grid layout** в блоке ```photo-grid``` и ```place```.
[Ссылка на GitHab Pages](https://mr-pooh.github.io/russian-travel/)