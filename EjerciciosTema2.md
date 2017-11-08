# 1. Descargar y ejecutar las pruebas de alguno de los proyectos anteriores, y si sale todo bien, hacer un pull request a este proyecto con tests adicionales, si es que faltan (en el momento que se lea este tema).  
Al ejecutar las pruebas de test.py se han obtenido los siguientes resultados.  
python test.py  
...  
----------------------------------------------------------------------  
Ran 3 tests in 0.000s  
  
OK  

Esto quiere decir que los test han ido bien. No faltan test que realizar a este proyecto.

# 2. Para la aplicación que se está haciendo, escribir una serie de aserciones y probar que efectivamente no fallan. Añadir tests para una nueva funcionalidad, probar que falla y escribir el código para que no lo haga (vamos, lo que viene siendo TDD).  
Para la aplicación de mostrar la clasificación de la liga santander y los partidos de la jornada se han hecho los tes de probar que el número de equipos que se tiene es correcto. Como no hay base de datos todavia se ha creado una estructura de datos estatica en el código que contiene 5 equipos y el test comprueba que hay 5 equipos introducidos en la estructura de datos.  
Para probar que un test falla se comprueba el numero de partidos de una jornada que deberan ser 10, pero como no se han introducidos estos datos todavía en la aplicación el test da error al estar la estructura de datos que contiene los partidos de la jornada vacíos.  
El código para la prueba de equipos es: 
  ~~~
require "test/unit"  
  
class TestEquipos < Test::Unit::TestCase  
  
  def test_simple  
    equipos=["Barcelona", "Valencia", "Real Madrid", "Sevilla", "Atletico"]  
  	cont=0  
    i=0  
    while i<equipos.length()  
      cont+=1  
      i+=1  
    end  
    assert_equal(5, cont )  
  
  end  
  
end  
~~~  
El código para el test que falla es parecido siendo el código el siguiente:
~~~  
  require "test/unit"  
  
class TestEquipos < Test::Unit::TestCase  
  
  def test_simple  
    jornada=[]  
  	cont=0  
    i=0  
    while i<jornada.length()  
      cont+=1  
      i+=1  
    end  
    assert_equal(10, cont )  
  
  end  
  
end  
~~~  
