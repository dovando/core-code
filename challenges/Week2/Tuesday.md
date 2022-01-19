1
function multiply(a, b){
  return a * b;
}

// las funcione SIEMPRE retornan un valor
// los metodos no, solo hacen algo pero no devuelven nada ejemplo de un metodo

2
function uniTotal (string) {
// total up dem unicodes!
var arr = Array.from(string);//SE CONVIERTE LA CADENA A UN ARREGLO => [a,a,a]
var sum = 0;
for (var i = 0; i < arr.length; i++) {// se hace un for para iterar el arreglo
	sum += arr[i].charCodeAt(0); //con charCodeAt(0) se convierrte al numero ascii y se va sumando
}
console.log(sum);//se imprime la suma
return sum; // como es una funcion debe de devolver un valor 
}

3
function getChar(c){
  // ...
  return String.fromCharCode(c)
}

4
function addBinary(a,b) {
  const sum = a+b;
  return sum.toString(2);

}

5
function finalGrade (exam, projects) {
  if (exam > 90 && projects >= 10) {
    return 100;
  } else if (exam > 75 && projects >= 5) {
    return 90;
  } else if (exam > 50 && projects >= 2) {
    return 75;
  } else {
    return 0;
  }
}