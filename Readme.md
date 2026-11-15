# API de la Cafetería del CRUI

Mini API con Node.js + Express para administrar los productos del menú.

## Requisitos
- Node.js 18 o superior

## Instalación
npm install

## Ejecución
npm start        # o: npm run dev (se reinicia solo al guardar)

El servidor queda en http://localhost:3000


## Rutas
GET:
/ | Mensaje de bienvenida
/api/productos | la lista de todo
/api/productos/:"id" | te lista un producto por id
/api/resumen | Cantidad y precio promedio


POST:
/api/productos | Crea un producto


PUT:
/api/productos/:id | Modifica un producto


##DELETE:

/api/productos/:id | Elimina un producto

como los datos viven en memoria: se pierden al apagar el servidor.
