## Trabalhando com css

### Propriedades

- text-align: define o alinhamento do texto
- font-size: define o tamanho da fonte
- background: define o background do elemento
- color: define a cor do elemento
- width: define a largura do elemento
- height: define a altura do elemento
- border: define a borda do elemento
- padding: define o espaçamento interno do elemento
- margin: define o espaçamento externo do elemento

### Declaração

#### In line

```html
<p style="font-size: 20px">
  <en
    >Nossa missão é:
    <strong
      >"Proporcionar auto-estima e qualidade de vida aos clientes".</strong
    ></en
  >
</p>
```

#### Head

```html
<head>
  <style>
    p {
      text-align: center;
    }
  </style>
</head>
```

#### Arquivo externo style.css

- Referencia no HTML

```html
<head>
    <link rel="stylesheet" href="style.css">
</head>
```

- Arquivo style.css

```css
p {
  text-align: center;
}
```

##### Por estrutura

```css
/*define que a cor do elemento contido na tag strong e em respectivamente terá color: red*/
em strong {
    color: red;
}
```

##### Por identificador

```css
#missao {
    font-size: 20px;
}
```

### Boas práticas

- O CSS deve corresponder a mesma estrutura do HTML