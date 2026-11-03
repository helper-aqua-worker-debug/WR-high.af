# Wild Rift Assistant: pașii următori

Stare la 3 noiembrie 2026: Utilizatorul a raportat M0 + M1 implementate local pe `feat/wr-mvp-m0-m1`, 46/46 teste, compilare și typecheck reușite. Modificările sunt necomise și datele sunt DEMO/SYNTHETIC. Aceste rezultate nu au fost verificate independent în checkoutul Groot.

## 1. Păstrează și verifică munca existentă

În același checkout Groot, verifică branchul, HEAD, modificările și fișierele necomise. Citește `docs/M0_M1.md` și handofful. Nu folosi reset, clean sau stash și nu schimba branchul. Rulează verificările existente și fă review independent pentru validare, merge, confirmări, rezultate întârziate și separarea datelor demonstrative. Nu presupune că remote-ul conține această muncă.

## 2. M2: primele date reale, verificate

Începe cu Garen pe BARON, după confirmarea de către utilizator a modului și regiunii. Verifică patchul curent și sursele oficiale relevante. Construiește un set suficient de iteme, componente, costuri, boots/enchant și incompatibilități pentru o recomandare legală. Notează sursa, versiunea și data fiecărui set de date; nu promova DEMO la date reale. Runele neverificate rămân indisponibile și nu blochează itemele verificate.

## 3. M3: primul asistent manual utilizabil

Creează o interfață utilizabilă pe telefon: campion, rol, fază și informațiile cunoscute despre echipe. Prezintă ordinea itemelor, motivele, alternativele și versiunea datelor. Schimbarea sau ștergerea intrărilor recalculează rezultatul; informațiile necunoscute rămân necunoscute. În joc, fără inventar și buget, arată o ordine de referință, nu un ordin «cumpără acum». Runele pentru meciul curent sunt tratate diferit înainte și după începerea jocului.

## 4. Acceptare locală

Rulează teste de logică și interfață, verifică recomandările față de exemple factuale și cere review independent. Documentează pornirea, limitele și revenirea la versiunea anterioară. Primul rezultat este funcțional numai pentru campionii, modul și datele verificate.

## 5. Extindere, apoi opționale

Extinde treptat la Malphite și Darius pe BARON, cu exemple contextuale și date revizuite. Ulterior, dacă utilizatorul dorește, adaugă screenshot cu confirmare umană și opțiunea PWA. Stabilește separat procesarea imaginilor, confidențialitatea, costurile și publicarea. Nu lăsa screenshotul să blocheze fluxul manual.

## Prompt pentru agentul din Groot

Continuă proiectul separat Wild Rift în checkoutul existent al repository-ului https://github.com/helper-aqua-worker-debug/WR-high.af, pe branchul feat/wr-mvp-m0-m1. Începe cu verificarea și reviewul M0/M1, apoi construiește M2 și M3 pentru un prim asistent manual local Garen/BARON. Verifică branchul, HEAD, diff și fișierele necomise; păstrează toată munca existentă. Nu folosi reset, clean sau stash și nu schimba branchul. Citește handofful și docs/M0_M1.md. Cere-mi doar regiunea și modul dacă nu le poți determina; verifică patchul și sursele factuale actuale. Păstrează datele DEMO separate. Fă teste, review independent, instrucțiuni de pornire și rollback. Runele neverificate rămân indisponibile. Fără push, merge, deploy, servicii plătite, chei sau acces nou. Nu adăuga OCR sau PWA în această etapă. Dacă o dependență sau o aprobare este necesară, explică exact ce și de ce.
