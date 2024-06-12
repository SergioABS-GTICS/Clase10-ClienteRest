# Clase10-ClienteRest

## Utilización de Daos

Los Daos nos servirán para modelar la información que vamos a extraer de la DB de algún objeto 

Primero consummos a partir del service que nos dan según la documentación y hacemos los entities:

![image](https://github.com/SergioABS-GTICS/Clase10-ClienteRest/assets/154263057/ffda36a2-3ee3-4ac2-87c3-91f86c1b0eaf)

Luego, hacemos los Daos (Se le asigna component):

![image](https://github.com/SergioABS-GTICS/Clase10-ClienteRest/assets/154263057/28dfa297-648e-452b-be80-e5f7ae04705e)

Luego crear la vista teniendo en cuenta los nombres del entity

## Crear (Save)

![image](https://github.com/SergioABS-GTICS/Clase10-ClienteRest/assets/154263057/e04397de-6172-4848-8197-bb2cabd90b04)


## Editar (Primero mandar a vista con los datos seteados y luego actualizar)

![image](https://github.com/SergioABS-GTICS/Clase10-ClienteRest/assets/154263057/71b482a6-a92a-4784-b120-40910402b9ed)


![image](https://github.com/SergioABS-GTICS/Clase10-ClienteRest/assets/154263057/d6b01eaa-f4a5-495e-84c9-8fbba8d41668)

1) Creamos una clase DTO en base al consumo (No coincide con el Entity):

   ![image](https://github.com/SergioABS-GTICS/Clase10-ClienteRest/assets/154263057/1284aab2-58bb-4300-86bc-c755a6fb7aa2)


    ![image](https://github.com/SergioABS-GTICS/Clase10-ClienteRest/assets/154263057/b696cc59-fd75-4c6c-b432-0cac4c5509ba)
   
2) Hacer la vista, mandar por model si necesitamos listas y mandar el producto
   En la propia vista tenemos el boton que redirige al "save" y guardamos.
3) En el controller con url "save" guardamos el producto
   En el ProductoDao implementamos si guardamos como creando o como actualizando

Para RequestParam:

![image](https://github.com/SergioABS-GTICS/Clase10-ClienteRest/assets/154263057/6e250ef9-e8b8-4e31-9c98-1e8f3f8f4929)

Para PathVariable:

![image](https://github.com/SergioABS-GTICS/Clase10-ClienteRest/assets/154263057/63609321-4bd9-4163-8359-9e6bab11a25b)


