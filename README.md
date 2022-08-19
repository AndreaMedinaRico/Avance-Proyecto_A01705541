# Avance-Proyecto_A01705541
Este repositorio es creado para almacenar los avances del algoritmo para el programa.

# CONTEXTO 

  El Programa para la Evaluación Internacional de Alumnos de la OCDE (Organización para la Cooperación y el Desarrollo Económico) realiza encuestas cada 3 años a diversos países para evaluar el desempeño de los alumnos de 15 años en cuanto a lectura, matemáticas y ciencias. En la prueba de 2018, los alumnos mexicanos se encontraron por debajo del promedio de todos los países a los que se les aplica la encuesta, y fue el tercer lugar de América Latina. 

  Con el fin de que los alumnos sean capaces de desarrollar más sus habilidades y obtengan un mejor puntaje, se desarrollará un programa que permita al usuario escoger el área de matemáticas (álgebra, trigonometría) y ciencias (tipos de enlaces) en las que desea trabajar. Dependiendo de la que escoja, irán apareciendo ejercicios ya establecidos para su práctica, junto con una explicación breve de cómo hacerlo si es que lo necesitan, como si fueran pistas.
  
  La intención es que sea una actividad dinámica, debido a que va destinada a jóvenes de 15 años con bastante energía y distracciones en la mayoría de los casos. Por esto, el usuario será capaz de avanzar de nivel conforme vaya teniendo respuestas correctas hasta completar el juego o la actividad. 
  
  Este es el modelo del algoritmo en pseudocódigo de los pasos que seguirá.
  
  INICIO 
  
  nombre - cadena 
  nivel - numero entero
  opcion - numero entero 
  area - numeor entero
  
  // quimica sera 1 y matematicas 2 
  
  nivel = 1
  
  INGRESAR nombre 
  INGRESAR opcion 
  MOSTRAR nivel
  
  SI opcion = 1
  
    INGRESAR area
    //algebra sera 1 y trigonometria 
    
      SI area = 1
        MIENTRAS nivel<= 10
        MOSTRAR ejercicio 
    
        SI respuesta correcta 
      
          SUBIRNIVEL()
        
         SI NO
      
          BAJARNIVEL()
            Mostrar explicacion
    
        SI area = 2
    
     SI NO 
        MOSTRAR("Opción no válida")
  
  SI opcion = 2
  
       MIENTRAS nivel<= 10
      MOSTRAR ejercicio 
    
      SI respuesta correcta 
      
        SUBIRNIVEL()
        
      SI NO
      
        BAJARNIVEL()
        Mostrar explicacion
  
  SI NO
    MOSTRAR("Esta opción no está disponible")
    
  def SUBIRNIVEL() :
    nivel = nivel + 1
    
  def BAJARNIVEL() : 
    nivel = nivel -1
  
  
  
