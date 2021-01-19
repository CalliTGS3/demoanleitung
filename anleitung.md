# Beipiel Anleitung für it@school

## Einleitung @unplugged

**So schliesst Du Deinen @boardname@ am Laptop an.**

```template
let x = 0
basic.showString("Hello!")
basic.clearScreen()
```


## Schritt 1 @fullscreen

Nimm den Anzeigeblock und zeichne ein großes Herz.

```blocks
basic.forever(function() {
    basic.showLeds(`
        . # . # .
        # # # # #
        # # # # #
        . # # # .
        . . # . .`);
})
```


## Schritt 2 @fullscreen

Lösche anschließend den Bildschirm.

```blocks
basic.forever(function() {
    basic.showLeds(`
        . # . # .
        # # # # #
        # # # # #
        . # # # .
        . . # . .`);
basic.clearScreen()
}
)

```

