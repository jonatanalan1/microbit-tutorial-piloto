# Aula teste

## {Step 1}

Coloque o Botão A e depois Mostrar o Coração

```ghost
input.onButtonPressed(Button.A, function () {

})
basic.showLeds(`
    . # . # .
    # # # # #
    # # # # #
    . # # # .
    . . # . .
    `)
```

## {Step 2}



```blocks
input.onButtonPressed(Button.A, function () {
    basic.showIcon(IconNames.Heart)
})
```

```ghost
input.onGesture(Gesture.Shake, function () {

})
```
