# Ejercicio 1: Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años. Consultar este artículo en Infoautónomos sobre el tema.  
### Ordenador utilizado.  
El ordenador que hemos utilizado ha sido **SERVIDOR HP PROLIANT ML150 GEN9 XEON E5-2609V4 1.7GHZ 8GB FA 550W**. 
### Descripción(sacada de la página donde se describe el ordenador).  
Basic
Altura del Rack: 5U
Compatibilidad con RAID: Sí
Fabricante de Procesador: Intel
Familia de producto: ProLiant ML150 G9
Formato: Torre
Memoria Estándar: 8 GB
Modelo de Procesador: E5-2609 v4
Niveles de RAID: 0, 1, 5, 10
Nombre de Marca: HP
Núcleo del Procesador: Octa-Core (8 Core)
Número de procesadores admitidos: 2
Respetuoso del medio ambiente: Sí
Tipo de Procesador: Xeon
Tipo de Producto: Servidor
Velocidad de Procesador: 1,70 GHz
Características Físicas
Altura del Rack: 5U
Altura: 432,6 mm
Anchura: 200 mm
Formato: Torre
Peso (Aproximado): 22,23 kg
Profundidad: 620 mm
Controladores
Compatibilidad con RAID: Sí
Niveles RAID (SDE): 0
Niveles de RAID: 0, 1, 5, 10
Tipo de controlador: Serie ATA/600
Descripción de la Alimentación
Potencia máxima de alimentación: 550 W
Voltaje de Entrada: 120 V AC
230 V AC
Información General
Código de Fabricante: 834612-425
Dirección Web de Fabricante: http://www.hpe.com
Fabricante: Hewlett Packard Enterprise
Gama de Producto: ML150 G9
Línea de Producto: ProLiant
Nombre de Marca: HP
Tipo de Producto: Servidor
Memoria
Memoria Estándar: 8 GB
Tecnología de la Memoria: DDR4 SDRAM
Pantalla y gráficos
Fabricante de Controlador Gráfico: Matrox
Modelo de Controlador de Gráficos: G200
Procesador / Chipset
Fabricante de Procesador: Intel
Modelo de Procesador: E5-2609 v4
Núcleo del Procesador: Octa-Core (8 Core)
Número de procesadores admitidos: 2
Tipo de Procesador: Xeon
Velocidad de Procesador: 1,70 GHz
Redes y Comunicaciones
Tecnología Ethernet: Gigabit Ethernet
Varios
Respetuoso del medio ambiente: Sí 
### Precio.  
Donde el precio es: **1315,00**
### Amortización a 4 años.
El cálculo de la amortización es: **1315/4=328,75**  
El coste de amortazación a 4 años es **328,75**  
### Amortización a 7 años.  
El cálculo de la amortización es: **1315/7=187,85** 
El coste de la añortización a 7 años es: **187,85**
  
    
  
# Ejercicio 2: Usando las tablas de precios de servicios de alojamiento en Internet “clásicos”, es decir, que ofrezcan Virtual Private Servers o servidores físicos, y de proveedores de servicios en la nube, comparar el coste durante un año de un ordenador con un procesador estándar (escogerlo de forma que sea el mismo tipo de procesador en los dos vendedores) y con el resto de las características similares (tamaño de disco duro equivalente a transferencia de disco duro) en el caso de que la infraestructura comprada se usa sólo el 1% o el 10% del tiempo.  
Para hacer la comparación se han escogido las empresas OVH y Hostalia  
  
* OVH ofrece:  
  1. 250 GB de disco  
  2. 1 dominio gratuito  
  3. 100 cuentas de correo de 5 GB  
  4. 4 bases de datos  
* Hostalia ofrece:  
  1. 100 GB de espacio  
  2. 1 dominio gratuito  
  3. Alojamientos de dominios ilimitados  
  4. 50 cuentas de correo  
El plan de OVH es de 6,04 con IVA y el de Hostalia es de 4,99 con IVA por lo tanto el plan anual de cada uno es:
* OVH: 72,84  
* Hostalia: 59,88  
Usando el 1% de infraestructura tenemos que:  
* OVH: 0,7284€/Año  
* Hostalia: 0,5988€/Año  
Usando el 10% de infraestructura:
* OVH: 7,284€/Año  
* Hostalia: 5,988€/Año  

# Ejercicio 3: En general, cualquier ordenador con menos de 5 o 6 años tendrá estos flags. ¿Qué modelo de procesador es? ¿Qué aparece como salida de esa orden? Si usas una máquina virtual, ¿qué resultado da? ¿Y en una Raspberry Pi o, si tienes acceso, el procesador del móvil?  
 egrep '^flags.*(vmx|svm)' /proc/cpuinfo
flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc aperfmperf eagerfpu pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch epb intel_pt tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap xsaveopt dtherm ida arat pln pts  
flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc aperfmperf eagerfpu pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch epb intel_pt tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap xsaveopt dtherm ida arat pln pts  
flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc aperfmperf eagerfpu pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch epb intel_pt tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap xsaveopt dtherm ida arat pln pts  
flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx pdpe1gb rdtscp lm constant_tsc arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc aperfmperf eagerfpu pni pclmulqdq dtes64 monitor ds_cpl vmx est tm2 ssse3 sdbg fma cx16 xtpr pdcm pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand lahf_lm abm 3dnowprefetch epb intel_pt tpr_shadow vnmi flexpriority ept vpid fsgsbase tsc_adjust bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap xsaveopt dtherm ida arat pln pts  
  
Al usar una máquina virtual y escribir el comando egrep '^flags.*(vmx|svm)' /proc/cpuinfo no me aparece nada, el procesador si sale el mismo.  
  
# Ejercicio 4: Comprobar si el núcleo instalado en tu ordenador contiene este módulo del kernel usando la orden kvm-ok. Instalar un hipervisor para gestionar máquinas virtuales, que más adelante se podrá usar en pruebas y ejercicios.  
Se ha instalado el paquete kvm-ok.  
El hipervisor instalado es virtualbox.  

# Ejercicio 5: Darse de alta en servicios de nube usando ofertas gratuitas o cupones que pueda proporcionar el profesor.  

# Ejercicio 6: Darse de alta en una web que permita hacer pruebas con alguno de los sistemas de gestión de nube anteriores.
