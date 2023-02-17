# Kuepa-Prueba



#Instalacion

//Debemos Estar ubicados  server e Instalar las dependencias con el comando npm i 
//una vez hecho esto tendremos que configurar la url de la base de datos


#Configuracion

//Tenemos que poner la carpeta cliente junto con la carpeta server
//El servidor debe usarse en el puerto 4000
//para poder connectar a la base de datos ademas de la dependencia mongoose debemos usar el servicio atlas que ofrece Mongodb este servicio es gratuito, se debe 
//instalar la dependecia cors para asi poder conectar al servidor / base de datos sin errores 
//en el archivo index.js de la carpeta server a la variable let url:'mongodb+srv://maicol:maicol997608@kuepa.qq1uoxh.mongodb.net/?retryWrites=true&w=majority'
debemos  cambiarlo por la url nos proporcione el servicio de atlasMongo // de esta manera conectamos a la base de datos

#Arrancar App 

//una vez estemos seguros de las dependencia de la conneccion a la base de datos haya sido totalmente exitosa debemos dirigirnos a la carpeta server e inicializar el servidor con el comando //npm run dev de esta manera nos devera salir en consola dos mensajes de coneccion al servidor y a la base de datos
