### **Product Comparison**

Este archivo se enfoca en comparar los avances que se tenian en el Stage 2 con los del stage 3, el cual es la entrega del producto final. Se revisaran todos los cambios hechos con el fin de demostrar cuanto avanzó el producto y cuales son las áreas que tuvieron una mejora.

### **Main changes**
| Category | Stage 2 | Stage 3|
|----------|---------|--------|
|**Abstraction Process**| The class diagram was started and the relationships were established using the proper notation. The classes added were **Ticket**, **Ventas**, **Renta** and one for the lockers | In this stage, the class diagram was completed after many updates. New classes were added, such as **TipoServicio**, **Etiqueta**, **Reporte**, **Servicio** and **Ubicacion**|.
|**Requirement Correspondence (FR/NFR)**| The functional and non-functional requirements were refined, resulting in 9 functional requirements and 5 non-functional ones.| We then divided the requirements into **“blocks”** based on their purpose, and within each block we included the corresponding FRs and NFRs. The blocks are: **Finanzas**, **Reportes**, **Tickets**, and **Configuracion**|.
|**MVC (Model)**| Some class models were created, but the actual coding had not yet started. | All the models were eventually added: **Ticket**, **Renta**, **Venta**, **Servicio**, **TipoServicio**, **Reporte**, **Etiqueta**, and **Ubicacion**. Some models that existed previously were removed, such as **Descuento**, **Locker**, and **RentaObjeto**. All the code for each model has now been fully implemented.|
|**MVC (Controller)**| The controllers were created, but they were only test versions, meaning they weren’t the final ones. The controllers included in the second delivery were: **DescuentoController**, **LockerEasyController**, **RentaController**, **TicketController**, **TransaccionController** and **VentaController**. | The controllers were refined according to the established models, and some older ones—such as **LockerEasyController**, **TransaccionController**, **DescuentoController** were removed. The final controllers are: **RentaController**, **TicketController**, **ReporteController**, **VentaController**, **EtiquetaController** and **InventarioController**.|
|**MVC (View)**| The View had not been defined yet | The View section and its complete code were already implemented, and the following was added: **PruebasGUI**, **TicketGUI**, and **Styles.css**.|
|**Backend**|In the backend, the Model and Controller layers are included, and in Stage 2 only the prototypes and a few small pieces of code had been started. | In this stage, both were completed and the code was finalized. |
|**Frontend**| The frontend hadn’t been started yet, but there was already an idea of how it would look. | In this stage, the frontend was completed: the **GUI** was added, the **styles** were implemented, and everything was connected to the backend. |
|**DataBase**| Nothing had been planned regarding the database. | The entire database was designed using **PostgreSQL** in **PgAdmin**, the models were updated to function as entities, the **DAOs** were created, and everything was connected to the database through **Hibernate**.|


El diagrama de clases fue iniciado y se estableceieron sus relaciones con su simbología. Las clases agregadas fueron ticket, ventas, renta y una para los lockers.

En este Stage se finalizó el diagrama de clases después de muchas actualizaciones, se agregaron nuevas clases, como TipoServicio, Etiqueta, Reporte, Servicio y Ubicacion.


FR y NFR
Los requerimientos funcionales y no funcionales fueron refinados y se establecieron 9 funcionales y 5 no funcionales

Ahora los requerimientos los dividimos en "bloques" de acuerdo a para que sirve cada uno, y dentro de cada bloque se encuentra los FR y NFR correspondientes. Los bloques son: Finanzas, Reportes, Tickets, y Configuración.

Se establecieron algunos modelos de las clases, pero no se comenzó con el código directamente.

Se agregaron todos los modelos: Ticket, Renta, Venta, Servicio, TipoServicio, Reporte, Etiqueta y Ubicación. Algunos modelos que se tenian anteriormente fueron eliminados, como Descuento, Locker y ObjetoRenta. Se estableció ya todo el código de cada modelo.

Los Controladores fueron creados, pero fueron de pruebas, es decir que no eran los finales. Los controladores en la segunda entrega fueron: 

Se pulieron los controladores de acuerdo a los modelos ya establecidos, y se eliminaron algunos viejos como:____ y los controladores finales son:  

Se aplicaron ya los apartados de Vista y su código completo, se añadió: 



En backend pertenecen Model y Controller y en el Stage 2 apenas se habían comenzado a establecer los prototipos y unas pequeñas piezas de código.
En este Stage se completaron ambos y el código quedó terminado.

El frontend no se había comenzado aun, pero ya se tenía alguna idea de como iba a ser.
En este Stage se terminó el Frontend, se añadió el GUI, los estilos y se conectó con el backend.

No se había planeado nada acerca de la Base de datos
Se estableció toda la base de datos, se usó PostgreSQL en PgAdmin, se modificaron los modelos para que sean Entidades, también se crearon los DAOs y se conectó todo a la base de datos mediante hibernate.

