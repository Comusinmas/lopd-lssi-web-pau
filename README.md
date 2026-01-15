# M06 UF3. Recuperació LOPD-GDD LSSI: Adaptació pàgina web

Aquest repositori conté la versió adaptada a la normativa legal vigent de la pàgina web "I+ Web".

## 📋 Activitats realitzades

S'han realitzat les següents modificacions per complir amb la LOPD-GDD i la LSSI-CE:

1. **Anàlisi de Cookies**: 
   - S'ha utilitzat l'eina `cookie-checker` sobre la versió publicada.
   - S'han identificat **2 cookies analítiques** de tercers: `_ga` i `_ga_G-6WY7M0XGC0` (Google Analytics).

2. **Adaptació del Codi**:
   - S'ha inclòs un **avís de cookies (banner)** a la part inferior de la pàgina `index.html`.
   - S'ha modificat el **formulari de contacte** afegint un checkbox de consentiment obligatori per a la Política de Privacitat (obligatori per LOPD-GDD).
   - S'ha actualitzat el **menú de navegació** i el **peu de pàgina** per incloure enllaços directes a les noves seccions legals.

3. **Noves Seccions Legals**:
   - S'han creat els fitxers `avis-legal.html`, `privacitat.html` i `cookies.html` dins de la carpeta `/docs/`.

## 📁 Estructura del projecte

La carpeta `/docs/` conté la web funcional:
- `index.html`: Pàgina principal amb el banner de cookies i formulari adaptat.
- `avis-legal.html`: Informació del titular de la web (LSSI).
- `privacitat.html`: Informació sobre el tractament de dades personals (LOPD).
- `cookies.html`: Detall de les cookies utilitzades i la seva finalitat.
- `img/`: Carpeta amb els recursos gràfics originals.

## 🌐 Comprovació de Cookies
La pàgina està configurada perquè el script de Google Analytics es carregui de forma persistent (tal com es trobava a l'enunciat original), permetent així que les eines d'anàlisi detectin les cookies i l'usuari pugui visualitzar el banner informatiu de consentiment.
