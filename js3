//1. Сумма квадратов массива

let arr = [1,5,6,10,2,6,9,0];
let newArr = [];
for(let i = 0; i < arr.length; i++) {
  let sqr = arr[i] * arr[i];
  newArr.push(sqr);
}
console.log(newArr);
 
let sum;
let j;
for( j = 0, sum = 0; j < newArr.length; j++) {
  sum += newArr[j];
}
 
console.log(sum);

//2. Вывести индексы нулевых элементов массива, а потом удалить нули
const e34 = [13,0,56,57,0,4,72,152];

let b = e34.findIndex(item => {
    if (item === 0){
        return true;
    }
});
 console.log(b);

  const c = e34.filter(function(e){return e != 0});
   console.log(c);

   /* В этом задании создавал большой массив с объктами пробовал разные методы
   const tankers = [
    {name: 'John', age: 25, battles:15,destroyed:4},
    {name: 'Stepan', age: 19, battles:5,destroyed:0},
    {name: 'Jack', age: 23, battles:11,destroyed:2},
    {name: 'Tony', age: 18, battles:1,destroyed:0},
    {name: 'дядя Ваня', age: 34, battles:50,destroyed:37},
    {name: 'Толян', age: 27, battles:46,destroyed:74} 
]
const newbieIndex = tankers.findIndex(person => person.destroyed <= '0');
console.log(newbieIndex)

const nonull = tankers.filter(function(destroy){return destroy !=0});
console.log (nonull);

Почему то индекс определяет только первого найденного элемента и поиск останавливается.
Не могу разобратся.(
    */
   
   
   
    //3. Самое длинное слово в предложении и его индекс

    let CosmicRangers = ["Blazer", "Teron", "Keller", "Dezintegrator", "Multifazer"];
    let sorted = CosmicRangers.sort((a, b) => b.length - a.length );
    
    console.log(sorted[0]);

    /* С помощью метода sort находим самое длинное слово и переносим его на первое место 
    в массиве. Не совсем соотеветсвует но с findIndex увы так и не разобрался.*/
    
    
     4. Среднюю длину слова в предложении
                                                                    ¯\_(ツ)_/¯
