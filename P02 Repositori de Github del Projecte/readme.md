# P02: Repositori de GitHub del Projecte

## 📝 Breu Descripció
Ara que ja sabem que **GitHub** ens proporciona una plataforma molt potent per gestionar i versionar la documentació dels nostres projectes, és el moment de consolidar-ne l'ús. En aquest tercer projecte, utilitzarem el repositori base creat a la *Tasca 0* per centralitzar totes les activitats de forma organitzada.

Cada lliurament, guia tècnica, documentació o configuració haurà de tenir el seu espai propi. Per a una correcta gestió, és de vital importància que tot l'equip mantingui un **criteri d'estructura uniforme**.

---

## 🎯 Objectius Específics
* Implementar un estàndard d'organització professional en la gestió de repositoris de codi i documentació.
* Evitar la pèrdua d'informació assegurant l'accessibilitat de les guies de forma indexada.
* Dominar l'ús d'enllaços relatius en Markdown per interconnectar directoris.

---

## 🛠️ Requisits d'Estructuració del Repositori

Per garantir la traçabilitat del projecte, s'han de seguir estrictament les següents directrius d'organització:

### 1. Índex Principal (`/README.md`)
* El fitxer `README.md` situat a l'arrel de tot el repositori actuarà com a **presentació global del projecte**.
* Ha d'incloure de forma obligatòria un **índex complet amb enllaços directes** a cadascuna de les diferents carpetes de les tasques i productes.

### 2. Carpetes de Tasques (`/tascaXX`)
* Per a cada activitat de seguiment es crearà una carpeta amb el format: `tasca01`, `tasca02`, etc.
* **Dins de cada carpeta de tasca cal incloure:**
  * Un fitxer `README.md` amb l'enunciat o la descripció de l'activitat.
  * Un **enllaç intern** cap al fitxer final que contingui la solució de l'activitat (per exemple, `solucio.md`).

### 3. Carpetes de Productes (`/producteXX`)
* En el cas dels productes que requereixin un lliurament formal, es seguirà exactament el mateix criteri que amb les tasques.
* Es crearà una carpeta anomenada, per exemple, `producte04`, que contindrà la seva pròpia descripció i els fitxers de configuració o memòries tècniques corresponents.

---

## 📂 Estructura de Directoris Esperada

```text
[El Teu Repositori]/
├── README.md               <-- Presentació global del Projecte 3 + Índex amb enllaços
├── tasca01/
│   ├── README.md           <-- Enunciat de la T01 + Enllaç a la solució
│   └── solucio.md          <-- Resolució tècnica de la T01
├── tasca02/
│   ├── README.md
│   └── solucio.md
└── producte04/
    ├── README.md           <-- Descripció del lliurament del P04
    └── [fitxers_del_p04]   <-- Configuracions, scripts o documents sol·licitats