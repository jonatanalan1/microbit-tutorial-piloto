# Botão e Ícone

## {Step 1}

Toque no bloco ``||basic:mostrar ícone||`` e escolhe um ícone pra aparecer na tela do micro:bit.

```blocks
basic.showIcon(IconNames.Heart)
```

## {Step 2}

Agora usa o bloco ``||input:ao pressionar botão||`` pra fazer o ícone só aparecer quando apertar o botão A.

```blocks
input.onButtonPressed(Button.A, function () {
    basic.showIcon(IconNames.Heart)
})
```
