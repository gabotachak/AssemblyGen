# AssemblyGen
ASSEMBLY GENERATOR v2.5 Alpha 
 
Autores: Andrés Silva
Julio Rodriguez
Sebastian León
Fabián Perdomo

 Fecha: 18 de junio de 2019
 Lenguaje: Java 
 
 
  MANUAL DE USUARIO 
 
 
 1. Ingresar datos (Pestaña Assembly Code):
 Para ingresar ipo assembly en Assembly Generator existen dos métodos
 diferentes:

 Ingresarlo manualmente >  Para ingresar datos de esta forma se usarán los
 botones y espacios de texto en la parte inferior del programa. Primero, se 
 escogerá a qué tipo pertenecen los datos que se insertarán (.data ó .code)
 Luego se procederá a escribir los datos a insertar dentro de los espacios de 
 texto LABEL, MNEMO y OPERANDS, estos se deben escribir con la correcta 
 anotación isa (Instruction Set Architecture), de lo contrario, los datos no 
 aparecerán dentro de las tablas.
 Una vez ingresadas las instrucciones se hará click en el botón añadir e 
 inmediatamente aparecerán los datos dentro de las tablas correspondientes. 
  
 Ingresarlo por medio de un archivo > Se tiene que hacer click en el 
 simbolo de carpeta (parte superior de la interfaz), ahí se abrirá el 
 explorador de documentos y se podrá seleccionar un archivo .txt o .agf el 
 cual debe tener la estructura de un Assembly Code, luego de cargar el 
 archivo sus datos aparecerán correspondientemente en las tablas 
 .data y .code 
  



 2. Pestaña Machine Code:
 Una vez se oprima el boton ejecutar empezará a aparecer los datos en sus 
 respectivas tablas en el machine code.
 El código aparecerá para Xilinx y para C++ cada uno tendrá dos botones que 
 permitirá copiar al portapapeles el código de las tablas.  


 
 3. Botones > Eliminar:elimina una linea seleccionada
		Editar: Edita una linea seleccionada
  Guardar: Genera un archivo .agf que guardará los datos 
  ingresados
		Nuevo proyecto: Borra los datos de las tablas para empezar 
  de cero 

 
