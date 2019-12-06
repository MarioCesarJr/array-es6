´´´javascript

const arr = [1, 5, 8, 9, 10];

// Percorrer o vetor e mostrar uma nova informação
const newArr = arr.map(function(item) {
  return item * 2;
});

console.log(newArr);

// Percorrer todo o vetor e transformar em uma única variavel/valor
const sum = arr.reduce(function(total, next) {
  return total + next;
});

console.log(sum);

// Filtrar ex: todos os números pares true/false
const filter = arr.filter(function(item) {
  return item % 2 === 0;
});

console.log(filter);

// Verifica se existe uma informação no array
const find = arr.find(function(item) {
  return item === 5;
});

console.log(find);

´´´
