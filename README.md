# DespliegueFinal

# 1 Configuración del archivo docker-compose.yml

Para la creación del .yml, hemos empleado 3 servicios a destacar:
 - mysql
 - tomcat
 - nginx
 
![image](https://user-images.githubusercontent.com/91564342/173458941-2480affd-d234-44a6-96d4-6be7eb03ee5b.png)

# 2 Obtener archivos

Para poder disponer de todos los archivos del proyecto , empleamos el siguiente comando

<code> git clone https://github.com/Rafaelpereztercero/bl.git </code>
  
  ![image](https://user-images.githubusercontent.com/91564342/173459193-02ee1fa0-cf65-4426-b044-a67e7832919b.png)

  # 3 Despliegue
  
  Para realizar el despliegue, no situamos en la carptea bl y ejecutamaos el siguiente comando para "levantar" el docker-compose  en segundo plano
  <code> docker-compose up -d </code>

![image](https://user-images.githubusercontent.com/91564342/173459499-4d35452a-d06a-4220-9a1e-9cb579d13579.png)

# 4 Servicios

Los servicios empleados son los siguientes:

### Tomcat : Parte logica de bitlevel (sin interfaz grafica, engloba .java)

### Nginx : Parte "visual"  y logica de bitlevel (engloba .html .js)

### Sql : Parte de "conmsultas"  de bitlevel (engloba la base de datos)

# 5 Subir las imagenes

Primero, nos logueamos empleando <code>docker login</code>
![image](https://user-images.githubusercontent.com/91564342/173460100-2b4ff4ea-8452-4e64-9c9b-91759ec88441.png)

A continuación ,creamos un tag por imagen mediante la siguiente sintaxis 
<code>docker tag nombre_imagen nombre_usuario/nombre_repositorio</code>

Y realizamos su respectivo push
<code> docker push nombre_usuario/nombre_repositorio </code>

![image](https://user-images.githubusercontent.com/91564342/173460404-4974e927-35d3-4934-85a9-743d28abbdca.png)

![image](https://user-images.githubusercontent.com/91564342/173460358-00a942bf-b8e5-4d74-949e-6cabd499992c.png)

![image](https://user-images.githubusercontent.com/91564342/173460005-29b038f6-c6eb-4042-9ecf-8f8b1c1de951.png)
![image](https://user-images.githubusercontent.com/91564342/173460281-e420642c-bde4-48d0-88a2-3106210e11d3.png)

# 6 Resultados
El resultado es PERFECTO , todo funciona como debe de funcionar

## PRUEBA : 
ACCEDE AQUI PARA VER QUE FUNCIONA : http://164.92.120.66/Vistas/Marketplace/html/Marketplace.html


![image](https://user-images.githubusercontent.com/91564342/173460876-d589554f-5005-46a5-8b0c-e394b2f9ca52.png)

# 7 ANEXOS

Imagenes de bitlevel https://hub.docker.com/r/rafa380/bl

