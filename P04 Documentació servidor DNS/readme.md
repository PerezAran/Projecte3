# P04: Documentació del Servidor DNS

## 📝 Breu Descripció
Benvinguts a la vostra nova tasca, consultors! Com a membres de l'equip de sistemes d'**EverPia**, us heu enfrontat al repte de configurar un servidor de noms (DNS) com a prova de concepte per al nostre client **Digicore**. Actualment, el resultat d'aquesta feina es troba exclusivament dins d'una màquina virtual.

L’objectiu d'aquest producte és publicar i centralitzar aquestes configuracions a **GitHub**. D'aquesta manera, assegurem el principi de **repetibilitat**: quan es vulgui replicar la configuració en producció, n'hi haurà prou amb descarregar els arxius al nou servidor Linux i reiniciar el servei per tenir-lo completament operatiu, sense haver de començar des de zero.

---

## 🎯 Objectius Específics
* Usar GitHub per documentar i versionar configuracions reals de servidors Linux.
* Valorar els avantatges de la infraestructura com a codi i la replicació ràpida i segura de serveis IT.
* Dominar l'extracció de fitxers mitjançant protocols segurs de xarxa ($SCP$).

---

## 🛠️ Desenvolupament de la Tasca

### Fase 1: Preparació de la Connectivitat i Extracció de Fitxers
Per poder copiar els fitxers des de la màquina virtual Ubuntu Server cap a la vostra màquina física de treball (*host*), cal assegurar la connectivitat entre ambdues.

* **Pas 1.1: Configuració de la Interfície Host-Only**
  * Afegiu una segona interfície de xarxa a la configuració de la VM Ubuntu Server en mode **Host-Only (Només amfitrió)**.
  * Configureu-la correctament a nivell de xarxa i activeu-la.
  * Comproveu que teniu connectivitat fent un `ping` des de la màquina física de treball.

* **Pas 1.2: Còpia Segura de Fitxers Clau amb SCP**
  * Utilitzareu el protocol **SCP** (*Secure Copy Protocol*), inclòs amb el servei SSH, per transferir els fitxers editats de la tasca DNS.
  * **Fitxers a extreure:**
    * `/etc/bind/named.conf.options`
    * `/etc/bind/named.conf.local`
    * Tots els arxius de zones creats dins de la carpeta `/etc/bind/zones/`
  * *Tip:* Executeu la comanda `scp` des del terminal de la vostra màquina física indicant un punt (`.`) al final per descarregar els fitxers al directori actual de treball.

### Fase 2: Integració i Estructuració a GitHub
* **Pas 2.1: Creació de l'espai de treball**
  * Creeu una nova carpeta al vostre repositori anomenada `producte04` juntament amb el seu fitxer de benvinguda (ruta: `producte04/README.md`).
  * A l'arxiu `README.md`, a més del títol del producte, cal redactar una explicació clara del contingut i de la finalitat d'aquestes configuracions.

* **Pas 2.2: Pujada i Indexació de Fitxers**
  * Pugeu els fitxers de configuració general de Bind (`named.conf.options` i `named.conf.local`).
  * Per als fitxers de zona, recordeu estructurar-ho creant primer la carpeta `zones` (podeu utilitzar el truc de crear un fitxer temporal `zones/esborrar` des de la interfície web de GitHub i eliminar-lo un cop hàgiu pujat les zones reals).

---

