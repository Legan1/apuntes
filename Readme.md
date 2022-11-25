#getElementByID
Permite acceder a cualquier elemento HTML a
través de su ID, este método es sensible a mayusculas
y minusculas.

#getElementByClassName
Permite acceder a cualquier elemento HTML a
través de su clase, este método es sensible a mayusculas
y minusculas(permite seleccionar mas de un elemento,
mientras tengan la misma clase)

let pais = document.getElementsByClassName("pais")
console.log(pais)
esto me permite recorrer todos los paises

for(let i=0; i<pais.length; i++){
Aqui selecciono la varible que cree anteriormente y el 
 texto se cambiara a color rojo
  pais[i].style.color="Red"
}

#getElementsByTagName


let pais = document.getElementsByTagName("p")

for(let i=0; i<pais.length; i++){
    pais[i].style.color="white"
}











#QuerySelector
Accede al primer elemento que coincida en la
busqueda, su forma de selección es similar a 
la realizada en CSS

#QuerySelectorAll
Accede a todos los elementos que coinciden en la
busqueda
