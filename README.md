# Lagrange calc

Make adaptability smooth

## Installing

1. Clone this repo 

```
https://github.com/DmitriyOrlov53/lagrange_calc.git
```

2. Add "lagrange_calc.sass" in your project

```sass
@import ./[some path]/lagrange_calc.sass

//Here are pixels used, but you can use another measure. 
//Maximum: two pairs of values.
$points: 320: 16*1.1, 1024: 16*1.064
//Can use another measure.
$full-value: 100vw

.foo
    width: calc(#{LagrangeCalc($full-value, $points)})
```

## Decription

The basics of the script are taken by the Lashrange polynomial

## Error or wish?

Write to me in the mail orlov.dmitriy2303@outlook.com

## Author

Dmitry Orlov, student and novice web developer

## License

This project is licensed under the MIT License