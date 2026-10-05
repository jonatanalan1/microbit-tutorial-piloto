# Shake-shake4

## {Step 1}

Adicione o bloco: Ao agitar __

```blocks
basic.showNumber(1)
pins.digitalWritePin(DigitalPin.P0, 1)
pins.servoWritePin(AnalogPin.P1, 90)
```

## {Step 2}

Adicione o bloco: Mostrar string __
Altere a string para seu nome

```blocks
basic.showIcon(IconNames.Heart)
```

## {Step 3}



```blocks
basic.showLeds(`
    . # . # .
    # # # # #
    # # # # #
    . # # # .
    . . # . .
    `)
basic.pause(1000)
led.unplot(0, 0)
```
