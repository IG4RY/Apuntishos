   |‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾|   
   |   ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈         INTRODUCCIÓN          ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈   |   
   |____________________________________________________________________________________________________________________________________________|   

Ayooo wsupp, que onda. Aquí Edu.


Ø Velo en pantasha completa con la fuente de letra "Consolas" tamaño 12 regular

Ø Este es un archivito de advertencias y tutorial feo para todos los TIA Portal 13 — 19 descargados de PLC4me.com.

Ø Los intenté dejar comprimidos para que pese menos y cuando se necesite de extraigan los archivos.
Recomiendo que antes de extraerlo le des doble click y veas qué contiene para que no se te haga un batidero de archivos.

! Cualquier reclamo a mi papá (ja, no lo vas a encontrar), yo toi chiquito y no sé ajsjs. Pero merezco sus mejores insultos yes yes.

 La contraseña de los archivos es: plc4me.com


   |‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾|   
   |   ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈          INSTALACIÓN          ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈ ≈   |   
   |____________________________________________________________________________________________________________________________________________|   



No estoy seguro del orden de instalación de cada versión, pero cuando instalé el V16 era maomeno así:
[x] = variable		|	[APU] = Pueden ser versiones Advanced, Professional, Unified, bla bla.

1. TIA Portal STEP7 Prof V[x]
2. StartDriver
3. SiVarc V[x]
4. SIMATIC WinCC Panel Images V[x]
5. SIMATIC Automation Tool V[x]
6. PLSCIM V[x]
7. PLCSIM [APU] V[x]
8. Energy Suite for TIA V[x]
9. Sim EKB.
	1. Seleccionar todas las llaves
	2. Botón superior con una llave amarilla  y un círculo negro con una cruz que dice "Install long"
	3. Se abre una ventana emergente. Seleciconar "Todos". Se seleccionarán muchos en azul.
	
		3.1 Si esta ventana no aparece, volvemos a selecionar todas las llaves con la primer casilla (si no lo estaban)
		> click en el botón de las 2 llaves amarillas (el de arriba de esta casilla) > Todas/All.
	4. Ya deberán estar instaladas. Verificamos con click en el cuadro azul de la esquina inferior derecha
	 > Disco local C: > Verificar que estén varias licencias instaladas

El proceso es darle siguiente una y otra vez (como todo buen tutorial, yes yes simon).



							|‾‾     ‾‾    ‾‾     ‾‾    ‾‾   ‾‾|
							   ~     ADVERTENCIAS     ~  
					    		|_     _     _     _     _   _|


 La wea de las licencias EKB según eso jala ya para todas las versiones, así que en teoría no hace falta que instales otro.

 Cuando salga algo de reiniciar es recomendable hacerlo si nos lo pide y e ignorar cualquier advertencia (se necesitan librerías o pop ups de apps hasta completar todo el proceso.

 WinCC Advances/Professional no jala: lamentablemente en mi caso, cuando intenté instalar el TIA V16 el WinCC me pedía un archivo de configuración y aunque buscamos y tratamos mi compañero y sho no encontramos solución porque las rutas de carpetas que había en internet y los archivos involucrados eran totalmente diferentes a las mías jsjs. No sé cómo lo solucionaron o encontraron forma de no necesitarlo pero dijeron que ya no había que preocuparse.

ꙨjꙨ: Verifica la instalación para cada versión. Puede haber cosas diferentes y no queremos sorpresas ijiji