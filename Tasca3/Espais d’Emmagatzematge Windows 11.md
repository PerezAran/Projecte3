**Espais d’Emmagatzematge Windows 11**

## **Configuració inicial:**

![][image1]

![][image2]

## **Efecte mirall doble:** 

## **Partició del disc:**

Primer de tot entrerem a **“administrar espacios de almacenamiento”:**

## ![][image3]

Un cop dins crearem un espai de disc d'emmagatzematge, (entrem a la opció marcada).

![][image4]

I s´obrirà aquest panell, que al que haurem de fer serà posar les característiques que volem que tingui al nostre disc.  
![][image5]

Un cop haguem posat totes les característiques, acabarem de crear al disc del tot, fen clic a la part marcada.

Ara ja podem veure el disc principal i veurel partit en dos particions en efecte mirall.

![][image6]

## **Posar informacío dins del disc i eliminar 1 disc:**

![][image7]

![][image8]

Ara tancarem la màquina virtual i eliminem un disc de la mateixa manera que abans haviem creat un.

![][image9]![][image10]

Ara podem veure que hi ha una partició que no funciona correctament, ja que hem eliminat un disc de la màquina virtual. Ara mirarem si s'ha guardat la informació en l´altre partició, per comprovar si l´efecte mirall s'ha creat correctament.  
![][image11]  
En aquesta imatge es pot veure que se'ns ha guardat la informació correctament ✅:

![][image12]

I ara podem afegir un altre cop al disc perquè no ens dongui cap error i estigui tot correcte.

![][image13]

## **Efecte mirall triple:** 

Ara al primer que farem serà borrar el disc de paritat doble que hem fet per la part anterior. Un cop l´hem eliminitat hem d'afegir els discos necesaris fins a tenir 5:

![][image14]

I haurem de agregar les unitats fins a tenir 5, per poder fer la partició de mirall triple.  
![][image15]

Ara haurem de crear un espai d´emmagatzematge amb els 5 discos com també em fet amb la part anterior, però amb **reflejo triple.**

![][image16]  
                    

Amb amb aquesta imatge es pot comprovar que s´ha creat correctament.

![][image17]

Ara posarem arxius dins, del disc i eliminem una de les unitats que hem afegit desde al VM, per veure que pasa.

![][image18]

![][image19]

En aquesta imatge es pot veure que ja em trencat una de les unitats partides.

I en aquí ja es veu que seguim tenint l'arxiu, la unica diferencia es que ha distribuït la informació de recuperació entre els 5 discos partits per eficiència.

![][image20]
