# Raport săptămânal PANDA TUR AGENȚIE

Cockpit de vânzări (platformă + CRM), protejat cu parolă. Conținutul paginii este criptat (AES-256-GCM); se deschide doar cu parola internă.

**Vânzări — perioadă la alegere:** în pagină se alege perioada (presetări sau două date), iar cifrele se compară cu aceleași date din ultimii 2 ani. Datele vin automat din online.pandatur.md: serverul (`python -m cockpit`, timerul `cockpit.timer`, 06:00 și 21:30 ora Chișinăului) descarcă exporturile, reconstruiește pagina și o publică aici. Link pentru o perioadă anume: `#vanzari?de=2026-11-16&pana=2026-11-22`.

Fila **Liduri (CRM)** e încă fixă pe 09–15.11.2026.
