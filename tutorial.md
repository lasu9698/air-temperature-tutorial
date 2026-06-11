# Show Air Temperature on the Micro:bit

Let's write a program to show air temperature

## Step 1
Go to basic ``||basic : show number||``  and put it inside basic ``||basic: forever||`` block

```blocks
basic.forever(function () {
    basic.showNumber(0)
})

```

## Step 2
Inside the basic  ``||basic : show number||`` block, put  input ``||input: temperature||`` block. This will show air temperature in Celcius.

```blocks
basic.forever(function () {
    basic.showNumber(input.temperature())
})

```

## Congratulations, you did it!
Download the program to your Micro:bit and test it out!

