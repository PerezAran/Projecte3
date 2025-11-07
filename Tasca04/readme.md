# Breu descripció

**Innovatech**, una start-up tecnològica emergent, està experimentant un ràpid creixement i pateix un caos en la gestió dels seus usuaris i accessos.  
Actualment, cada servei intern (servidor de fitxers, wiki de documentació, etc.) utilitza la seva pròpia base de dades d'usuaris i contrasenyes i, a més, als ordinadors clients s’usa autentificació local.  
Això genera diversos problemes crítics:

- **Ineficiència Operativa:** Cada cop que s'incorpora o marxa un empleat, l'equip tècnic ha de crear o eliminar el compte en múltiples sistemes.  
- **Risc de Seguretat:** Els usuaris sovint acaben reutilitzant contrasenyes entre serveis per evitar l'oblit.  
- **Manca d'Escalabilitat:** A mesura que Innovatech afegeix nous serveis, el problema es fa insostenible.

El CEO d’Innovatech ha contactat amb **EverPia** per tal d’implementar una solució d’autenticació centralitzada.  
La solució proposada és utilitzar **OpenLDAP (Lightweight Directory Access Protocol)** per ser una solució robusta i de codi obert, que s’alinea amb l’esperit d’Innovatech, ja que tots els ordinadors de l’empresa usen **GNU/Linux**.

La vostra missió serà implementar el servei **OpenLDAP** en un servidor Linux.  
Això implica:
- Instal·lar el servei.  
- Configurar el domini base.  
- Crear la jerarquia d'unitats organitzatives.  
- Integrar usuaris i grups per donar accés a altres serveis de xarxa.  
- Configurar un equip client per autenticar els usuaris mitjançant el directori.

S’ha redactat un document on s’especifica clarament la feina que s’ha de desenvolupar.  
El teniu disponible en el **plec de condicions tècniques** (també al Moodle de l’assignatura).

---

### Material de classe (disponible al Moodle)
- UD04.AA1 Serveis de Directori  
- UD04.AA2 Instal·lació OpenLDAP  
- UD04.AA3 Configuració del directori  
- UD04.AA5 Agregar client al directori  

---

## Objectius específics de la tasca / Finalitat de la tasca

- Instal·lació i configuració de serveis de directori en sistemes lliures.  
- Gestió d’objectes del directori: OU, grups i usuaris usant comandes i eines de gestió gràfica.  
- Configurar els clients per disposar d’autenticació centralitzada.  

---

## Competències treballades

- **a)** Determinar la logística associada a les operacions d’instal·lació, configuració i manteniment de sistemes microinformàtics.  
- **f)** Instal·lar, configurar i mantenir serveis multiusuari, aplicacions i dispositius compartits en un entorn de xarxa local.  
- **l)** Assessorar i assistir al client, canalitzant a un nivell superior els supòsits que ho requereixin.  
- **q)** Complir amb els objectius de la producció, col·laborant amb l’equip de treball i actuant conforme als principis de responsabilitat i tolerància.  

---

## RA(s) de la tasca

- **0224.RA2** Gestiona usuaris i grups de sistemes operatius en xarxa, interpretant especificacions i aplicant eines del sistema.  
- **0224.RA3** Realitza tasques de gestió sobre dominis identificant necessitats i aplicant eines d'administració de dominis.  

---

## CA(s) de la tasca

- **2.1** Configura i gestiona comptes d'usuari.  
- **2.4** Distingeix el propòsit dels grups, els seus tipus i àmbits.  
- **2.5** Configura i gestiona grups.  
- **2.6** Gestiona la pertinença d'usuaris a grups.  
- **3.1** Identifica la funció del servei de directori, els seus elements i nomenclatura.  
- **3.2** Reconeix el concepte de domini i les seves funcions.  
- **3.4** Realitza la instal·lació del servei de directori.  
- **3.5** Realitza la configuració bàsica del servei de directori.  
- **3.6** Utilitza agrupacions d'elements per a la creació de models administratius.  
- **3.7** Analitza l'estructura del servei de directori.  
- **3.8** Utilitza eines d'administració de dominis.  

---

## C(s) de la tasca

- **2.** Gestió d’usuaris i grups  
- **3.** Gestió de dominis  

---

## Capacitats clau treballades

- Autonomia  
- Innovació  
- Relació interpersonal  
- Organització del treball  
- Responsabilitat  
- Treball en equip  
- Resolució de problemes  
