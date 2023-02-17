# Kuepa-Prueba

#BAJADA

// La app de estudiante funciona Como un MERNSTACK debemos bajarnos el Servidor y aparte el Cliente que se encuentra en que se encuentra en https://github.com/Maiky33/Kuepa-cliente una vez hayamos bajado nuetros archivos client/server debemos meterlos en una carpeta, abrir la carpeta en el editor de codigo y empezar a instalar las dependencias Para ambas Carpetas

#INSTALACION

//Debemos Estar ubicados  server e Instalar las dependencias con el comando npm i 
//una vez hecho esto tendremos que configurar la url de la base de datos


#CONFIGURACION

//Tenemos que poner la carpeta cliente junto con la carpeta server

//El servidor debe usarse en el puerto 4000

//para poder connectar a la base de datos ademas de la dependencia mongoose debemos usar el servicio atlas que ofrece Mongodb este servicio es gratuito, se debe 
instalar la dependecia cors para asi poder conectar al servidor / base de datos sin errores 

//en el archivo index.js de la carpeta server a la variable LET url:'mongodb+srv://maicol:maicol997608@kuepa.qq1uoxh.mongodb.net/?retryWrites=true&w=majority'

//Debemos  cambiarlo por la url nos proporcione el servicio de atlasMongo // de esta manera conectamos a la base de datos

#ARRANCAR APP

//una vez estemos seguros de las dependencia de la conneccion a la base de datos haya sido totalmente exitosa debemos dirigirnos a la carpeta server e inicializar el servidor con el comando //npm run dev de esta manera nos devera salir en consola dos mensajes de coneccion al servidor y a la base de datos
