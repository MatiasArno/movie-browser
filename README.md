# Instrucciones de uso (comandos)

- Para agregar una nueva película a la base de datos    | ts-node index.ts add --id=4411 --title="Título de la nueva peli" --tags=action --tags=classic
- Para obtener data de una película según id            | ts-node index.ts get 4411
- Para buscar una película por su título                | ts-node index.ts search --title="a"
- Para buscar una película por su tag                   | ts-node index.ts search --tag="classic"
- Para obtener todas las películas                      | ts-node index.ts

- Todos los comandos de búsqueda son combinables.