# P03: Rèplica Web Professional

## 📝 Breu Descripció
Després de superar la primera fase de supervivència tècnica a **EverPia**, l’equip de la consultora ha rebut un nou encàrrec d’un client exigent: replicar en local una web corporativa real feta amb WordPress. L'objectiu és analitzar-ne l’estructura, entendre’n l’arquitectura de continguts i aprendre bones pràctiques de desenvolupament i manteniment web professional.

Aquest repte s’emmarca dins l’escenari de *"Sobreviure en una empresa IT"*, on no només cal fer funcionar els sistemes, sinó fer-ho amb criteri, rigor tècnic i capacitat d’adaptació. En aquest cas, el client vol una còpia fidel de la web [davidperalvarez.com](https://davidperalvarez.com/), un lloc que combina claredat, estructura SEO, disseny net i continguts professionals.

Treballarem des d'un entorn local de proves amb **WP Local** per reproduir fidelment el lloc, tant a nivell de pàgines i enllaços com d’aparença i organització interna.

---

## 🎯 Objectius Específics
* Analitzar de forma crítica una web professional en producció feta amb WordPress.
* Reproduir estructures de contingut complexes de forma manual utilitzant editors de blocs.
* Entendre la importància de la coherència visual, la jerarquia de la informació i l’experiència d’usuari (UX).
* Descobrir i utilitzar eines d'auditoria externa per detectar temes, tipografies i codis de color en entorns web.

---

## 🛠️ Requisits i Desenvolupament de la Tasca

> ⚠️ **Nota de realització:** Aquesta tasca és de caràcter **individual**. Cada consultor ha de construir el seu propi lloc.

### 1. Entorn de Treball
* Utilitzar **WP Local** instal·lat al PC de classe.
* Crear un nou lloc de WordPress amb el següent format de nom obligatori: 
  `replica_[el_teu_nom]` (Exemple: `replica_Aran`).

### 2. Fase d'Investigació Prèvia i Auditories
Abans de començar a maquetar, cal analitzar la web original utilitzant les següents eines de suport:
* **Estructura i Pàgines:** Consultar el [Sitemap XML oficial](https://davidperalvarez.com/page-sitemap.xml) per conèixer totes les URL reals existents.
* **Tema i Plugins:** Detectar la tecnologia utilitzada mitjançant [WP Theme Detector](https://www.wpthemedetector.com/).
* **Paleta de Colors:** Escanejar i trobar el codi hexadecimal dels colors de la web amb [Image Color Picker](https://imagecolorpicker.com/ca).
* **Tipografia:** Identificar les fonts de text de l'original amb [MyFonts](https://www.myfonts.com/es).

### 3. Creació i Jerarquia de Pàgines
S'han de crear manualment totes les pàgines principals que conformen l'arquitectura del lloc web, incloent-hi:
* Inici
* Sobre mí
* Academia básica
* Mantenimiento para academias online
* Consultoría para academias online
* Proyectos que he realizado
* Descarga
* Contactar
* Pàgines legals (Política de privacidad, cookies, condiciones de uso, etc.).

*Nota de contingut: Podeu copiar el text original de la web o fer servir text de farcit (**Lorem Ipsum**), però respectant sempre els títols, subapartats i distribucions de l'original.*

### 4. Maquetació i Configuració del Lloc
* **Editor recomanat:** Es recomana instal·lar el plugin **Kadence Blocks – Gutenberg Blocks** per disposar de més elements de maquetació de blocs.
* **Ajustos de WordPress:**
  * Configurar una pàgina d'**Inici estàtica**.
  * Dissenyar el menú principal de navegació respectant els submenús de la web original.
  * Configurar correctament els **Enllaços permanents (Permalinks)**, l'idioma i la zona horària del lloc.
  * Escollir i ajustar un tema (*Theme*) que s'adapti millor a l'estil visual de la referència.

---

## 📦 Lliurables
* [ ] **Evidència de la rèplica funcional** en local per a la revisió directa del consultor/professor.
* [ ] **Documentació o captures del procés** de clonació (segons s'indiqui a les tasques de seguiment del projecte).