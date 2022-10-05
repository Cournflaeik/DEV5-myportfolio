# DEV5-myportfolio
My portfolio for Dev5, including all my lab projects

## Week 1 - GIT
* Lab1 github: https://github.com/LarissaDeBorgher/DEV5-LAB1

## Week 2 - ES6
* Lab2 github: https://github.com/Cournflaeik/Labo2_ES6
* Lab2 sandbox: https://codesandbox.io/s/elien-de-geetere-labo2-es6-yjnntx

## Week 2 - Discovered feature:
Heb je ooit een nummer langer willen maken dan het is?
Ik vond op (https://www.javascripttutorial.net/es-next/) de padStart() en de padEnd() functies die characters toevoegen aan een string, zijnde het langs voor of langs achter.

Gecombineerd met de slice functie kan je zo gemakkelijk strings gedeeltelijk verbergen

```

let bankrekening = 4651654865485656;
let laatste4Nummers = bankrekening.toString().slice(-4);

//voeg *** toe voor het nummer zodat de totale string 16 characters heeft
let verborgenBankrekening = laatste4Nummers.padStart(16, "*");

console.log(verborgenBankrekening);



```