# apuntes-clase-react

# useContext()

3 pasos para el uso de useContext()

1. Crear el contexto
2. Proveer el contexto = Crear el Provider, para proveer el contexto
3. Consumir el contexto

Un Provider tambien no deja de ser un componente de React, lo que va renderizar es lo que envuelve osea el children

El Provider lo que tiene como valor es la informacion al que queremos acceder y no necesarimente tiene que ser un estado, podria ser tambien un objeto, string, numero, etc.

El contexto es una forma de inyeccion de dependencias, es decir que pueder saltar el uso de props a traves de componentes e inyectar la informacion al componente que necesita. Puedes tener sin problemas informaciones estaticas, ejemplo una lista de colores de themas, tokens, configuraciones, traducciones y entre otros.

En conclusion no solo sirve para estados globales.

useContext() = es singleTon solo se crea una vez

---
