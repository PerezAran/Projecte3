# Fase 1: Informe Tècnic — Gestor de Contrasenyes


L’incident de seguretat recent a EverPia ha posat de manifest un risc crític: l’ús de **contrasenyes febles o reutilitzades**. Aquest tipus de pràctiques són una de les principals causes de compromís de comptes dins d’empreses i organitzacions.

Els principals atacs que aprofiten aquest tipus de vulnerabilitats són:

- **Atac de diccionari**: Els ciberdelinqüents proven contrasenyes comunes que normalment utilitzem com per exemple, “123456”, "1111" fins que coinsideix.
- **Credential stuffing**: Utilitzen conjunts de credencials filtrades d’altres serveis per accedir a nous comptes (ja que molts usuaris reutilitzen la mateixa contrasenya).
- **Phishing i enginyeria social**: Quan un usuari cau en un engany i proporciona les seves credencials a un atacant.
- **Brute force**: proves automàtiques de milers de combinacions fins a trobar la correcta.

Aquests atacs tenen com a conseqüència **filtracions de dades**, **pèrdua de reputació** i **dany econòmic**.  
Per aquest motiu, és essencial que cada usuari disposi de **contrasenyes úniques, llargues i complexes** per a cada servei.

Els **gestors de contrasenyes** permeten mitigar aquests riscos, ja que:
- Generen i emmagatzemen contrasenyes segures de manera automàtica.
- Eviten la reutilització.
- Xifren les dades localment amb una **contrasenya mestra**.
- Faciliten l’ús mitjançant extensions de navegador i aplicacions mòbils.



## Comparativa Tècnica: Bitwarden vs KeePassXC

| Característica                        | **Bitwarden (Online / Núvol)**                             | **KeePassXC (Offline / Escriptori)**                        |
|--------------------------------------|-------------------------------------------------------------|-------------------------------------------------------------|
| **Model de seguretat**               | Xifratge **end-to-end (AES-256, PBKDF2)**                  | Xifratge **local (AES-256)**                               |
| **Emmagatzematge**                   | Núvol (servidors Bitwarden o autohospedat)                 | Fitxer local `.kdbx` al dispositiu                         |
| **Sincronització**                   | Sí, automàtica entre dispositius                           | No nadiua (cal sincronitzar manualment o via servei extern) |
| **Accés multiplataforma**            | Web, extensions, mòbil, escriptori                          | Només escriptori (Windows, macOS, Linux)                    |
| **Codi obert (Open Source)**         | Sí, auditat públicament                                    | Sí, comunitari                                              |
| **Model de cost**                    | Freemium (gratuït bàsic / Premium opcional)                 | Gratuït                                                     |
| **Generador de contrasenyes**        | Inclòs, configurable i accessible des del navegador         | Inclòs, configurable però manual                            |
| **Facilitat d’ús per a empreses**    | Molt alta, permet gestió d’equips i comptes compartits      | Mitjana, orientat a ús individual                           |
| **Còpies de seguretat**              | Exportació xifrada des del compte                           | Fitxer local manual                                         |
| **Dependència d’Internet**           | Necessita connexió per sincronitzar                         | No necessària                                               |


## Avantatges i Inconvenients

| Aspecte | **Bitwarden (Online)** | **KeePassXC (Offline)** |
|----------|------------------------|--------------------------|
| **Seguretat** | Xifratge fort, autenticació 2FA, però depèn del núvol. | Total control local, sense dependència externa. |
| **Usabilitat** | Molt intuïtiu i accessible des de qualsevol dispositiu. | Menys amigable per a usuaris no tècnics. |
| **Continuïtat del negoci** | Alta, ja que permet accedir-hi des de qualsevol lloc. | Pot perdre’s si el fitxer local es corromp o s’esborra. |
| **Gestió centralitzada** | Sí, ideal per equips i empreses. | No, cada usuari gestiona el seu fitxer. |
| **Cost** | Gratuït per a ús personal; Premium opcional. | Gratuït totalment. |



### Justificació:
- Ofereix **xifratge end-to-end** verificat.
- Facilita l’**ús multi-dispositiu** i la **sincronització** segura.
- Permet **gestionar equips**, compartir credencials entre departaments de manera controlada.
- Té una **interfície senzilla**, apte per personal tècnic i no tècnic.
- És **open source**, de manera que pot ser auditat i validat internament.
- Es pot instal·lar **en servidors propis** si es vol total control.

 **Conclusió:**  
Bitwarden combina seguretat, accessibilitat i escalabilitat, essent la millor opció per garantir la protecció de credencials dins d’EverPia.

