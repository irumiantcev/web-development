# CSS

## Примеры, облегчающие жизнь


### Вписать img в блок
```scss
img{
	width: 100%;
	height: 100%;
	display: block;
	object-fit: cover; //no IE
}
```

или

```scss
img{
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
}
```