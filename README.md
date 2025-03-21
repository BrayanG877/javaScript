// x=prompt("Digite el primer numero");
// y=prompt("Digite el segundo numero");
// if(x>y){
//     alert ("El primer numero es mayor ");
// }



// const Mensaje = function (nombre){
//     console.log(`hola ${nombre}!`)
// }
// Mensaje=("pepe");

// const nombre =[
//     ["pepe","aguilar"]
//     ["juan","mendez"]
//     ["camila","cabello"]
//     ["pepe","coral"]
// ]

//["pepe aguilar","juan mendez",  ]
// const result = nombre.map(concatenar);

// console.log=(result);

// function concatenar(nombre){
//     return nombre [0]+``+ nombre[1]+``+ ind;
// }
// const obj = {
//     nombre:"pepe",
//     edad: 12,
//     devolverEdad: ()=>{
//         console.log(this.edad)
//     }
// }
// obj.devolverEdad()
// function suma(){
//     num1=2;
//     function suma2(){
//         return num1+5;
//     }
// }+
// console.log (suma)
// const n1 = Number(15);

// console.log(n1, typeof n1)

// const n1 = new Number(15);

// console.log(n1, typeof n1)

// const n1 = parseInt("15.6");

// console.log(n1, typeof n1)

const n1=5/"a";

console.log(n1, typeof n1)

const arr=new Array(1,2,3,4,5,6)
const eliminado = arr.splice(2);
console.log(arr, eliminado)

const arr=new Array(1,2,3,4,5,6)
const eliminado = arr.splice(2,0,7);
console.log(arr, eliminado)

const arr = [3].fill(5)        //new array(3).fill("*");
console.log(arr)

const arr = new array(3).fill("*");
Object.preventExtensions(arr);
arr.push(89)
console.log(arr)

const arr=new Array(
    {Nombre: "juan", edad: "20"},
    {Nombre: "andres", edad: "10"},
    {Nombre: "alex", edad: "30"},
    {Nombre: "albeiro", edad: "40"},
    {Nombre: "hernando", edad: "50"},
);

const result = arr.find(value => {
    return value.Nombre == "maria";
})
const result = arr.find((value, indx, arreglo )=> {
    console.log(arreglo[indx]);      //itera sobre cada elemento y dependiendo del resultado lo coloca como true o false
    return indx == 5;
})
console.log(result)


const result = arr.find((value, indx, arreglo, targ )=> {
    thisArg = Arg;    //itera sobre cada elemento y dependiendo del resultado lo coloca como true o false
    return indx == 5;
})
console.log(result)

const arr=new Array(8,5,1,3,20,75,0);
arr.sort((a,b)=>a-b);             //ordena todo en orden alfabetico
console.log(arr)

const arr=new Array(8,5,1,3,20,75,0);
arr.reverse            //invierte posicion no hace nada mas
console.log(arr)

const conj=new set();
const a=()=> console.log("Hola");
const b=()=> console.log("Hola");
conj.add (5);
conj.add ("pera");
conj.add (true);
conj.add (()=>console.log("hola"));
conj.add (()=>console.log("hola"));         //invierte posicion no hace nada mas
conj.add (a);
conj.add (b);
conj.delete("pera"); //elimina el elemento mencionado
console.log(conj.size)
console.log(conj.conj.has(4))

//map=clave, valor
const mapeo=new map();
mapeo.set("nombre","mendez");
mapeo.set("equipo","real madrid");

console.log(mapeo)


const formulario= new FormData();
formulario.append("nombre","mendez");
formulario.append("dice","El real es el mejor!");
console.log(formulario);

const formulario= new FormData();
formulario.append("nombre","mendez");
formulario.append("nombre","juan");
formulario.append("dice","El real es el mejor!");
console.log(formulario.has("equipo"));    

const formulario= new FormData();
formulario.append("nombre","mendez");
formulario.append("nombre","juan");
formulario.append("dice","El real es el mejor!");
console.log(formulario.get("dice"));

const formulario= new FormData();
formulario.append("nombre","mendez");
formulario.append("nombre","juan");
formulario.append("dice","El real es el mejor!");
for(let[clave, valor] of formulario)
    console.log(clave, valor)

