1. **Nombres y apellidos:** Justo Antonio Garrido Herrador
2. **Fecha:** entrega 19-11-2020
3. **Laboratorio / Demos**: UtilizacionAzureCLIparaCrearBorrarMV.md
4. **Resumen del Ejercicio:** Crear una máquina virtual linux en Azure ejecutando Apache y sirviendo una página web de prueba.
1. **Objetivos**: 
   
      1.  ¡¡¡. 
      
         **Pasos**: 
      
         1.   ¡¡¡.
6. **Dificultad o problemas presentados y como se resolvieron:** ¡¡¡.
7. **Detalles de la entrega**:
   
      1. **Evidencias capturas de pantalla en carpeta**: **Capturas**. ( ruta: ...\\CFTIC610-AZ-900T1-MS-Azure-Fundamentals\20201118 Tarea 1 Módulos AZ-900CFTIC\Capturas). Índice de las capturas en este propio documento, a continuación.



------

## EXPLICACIÓN DE LAS CAPTURAS DE PANTALLA:



Creación del grupo de recursos:

![03-az-create-group-1](Capturas/03-az-create-group-1.png)



![04-az-create-group-2](Capturas/04-az-create-group-2.png)

Creación de la VM Linux:

![05-az-vm-create-1](Capturas/05-az-vm-create-1.png)



![06-az-vm-create-2](Capturas/06-az-vm-create-2.png)



![07-az-vm-create-3](Capturas/07-az-vm-create-3.png)

No pude entrar con el password puesto en la orden de creación y lo resetee, poniéndole el mismo valor:

![08-reset-pasword](Capturas/08-reset-pasword.png)

Conectarse por ssh:

![09-conectarse](Capturas/09-conectarse.png)

Después de actualizar, upgradear,instalar y verifcar apache:

![10-verificar-apache](Capturas/10-verificar-apache.png)

Vamos a abrir el puerto 80 en el Network Security Group de Azure:

![11-abrir-puerto-en-NSG](Capturas/11-abrir-puerto-en-NSG.png)

Realizamos alguna modificación en la página web inicial: 

![12-modificar-pagina-inicial](Capturas/12-modificar-pagina-inicial.png)


![13-az-vm-stop-1](Capturas/13-az-vm-stop-1.png)
![14-az-vm-stop-2](Capturas/14-az-vm-stop-2.png)
![15-az-vm-deallocate-1](Capturas/15-az-vm-deallocate-1.png)
![16-az-vm-deallocate-2](Capturas/16-az-vm-deallocate-2.png)
![17-az-vm-start-1](Capturas/17-az-vm-start-1.png)
![18-az-vm-start-2](Capturas/18-az-vm-start-2.png)
![19-az-vm-delete-1](Capturas/19-az-vm-delete-1.png)
![20-az-vm-delete-2](Capturas/20-az-vm-delete-2.png)
![21-az-vm-show](Capturas/21-az-vm-show.png)
![22-az-group-delete-1](Capturas/22-az-group-delete-1.png)
![23-az-group-delete-2](Capturas/23-az-group-delete-2.png)
![24-az-group-delete-3](Capturas/24-az-group-delete-3.png)
