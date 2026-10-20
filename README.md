# atividade-function
function fizzBuzz(numero) {
    if (typeof numero !== 'number') return numero;
    if (numero % 3 === 0 && numero % 5 === 0) return 'FizzBuzz';
    if (numero % 3 === 0) return 'Fizz';
    if (numero % 5 === 0) return 'Buzz';
    return numero;
}

for (let i = 0; i <= 100; i++) {
console.log(i,  fizzBuzz(i))
}


/* Tbm funciiona.

const fizzBuzz = (numero) => {
    if (typeof numero !== 'number') {
        return numero;
    }
    if (numero % 3 === 0 && numero % 5 === 0) {
        return 'fizzbuzz';
    } else if (numero % 3 === 0){
        return 'fizz';
    } else if (numero % 5 === 0){
        return 'buzz';
    } else { return numero; 

    }
};
   for (let i = 0; i <= 100; i++) {
        console.log(fizzBuzz(i));
    }
*/
