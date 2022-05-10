1.	Al inspeccionar el código desde el navegador, se observa que ahí un error, en la variable 
guessSubmit.addeventListener('click', checkGuess), se coloco de forma correcta: guessSubmit.addEventListener('click', checkGuess)
2.	Se cambio la variable randomNumber por: Math.floor(Math.random() * 100)+1 ya que la que tenía, no funcionaba para el juego.
3.	El mensaje para cuando se ganaba o se perdia el juego estaba al revez, se coloco de forma correcta.
4.	se observa que en el código es mal la constante lowOrHi: document.querySelector('lowOrHi'), se coloca de forma correcta: const lowOrHi = document.querySelector('.lowOrHi'); 
5.	se observa que esta mal la variable del botón para restear el juego: resetButton.addeventListener('click', resetGame); se coloca de forma correcta: resetButton.addEventListener('click', resetGame);
6.	dentro de la función de resetgame se cambió la función randonNumber por Math.random() * 10
7.	se coloco que solo acepte valores numéricos
8.	se cambio el contador para que tenga 10 intentos
