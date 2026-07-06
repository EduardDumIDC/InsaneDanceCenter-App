# PRD - Insane Dance Center App

## 1. Introducere
Insane Dance Center App este o aplicație mobilă destinată administrării unui studio de dans. Scopul acestei aplicații este să ofere un set unificat de funcționalități pentru managerii și profesorii studio-ului, astfel încât să poată organiza activitățile zilnice mai eficient.

## 2. Obiective
Aplicatia trebuie să permită:
- organizarea calendarului comun al activităților
- gestionarea grupelor de elevi
- gestionarea elevilor și a datelor lor
- înregistrarea și monitorizarea prezențelor
- organizarea competițiilor și a rezultatelor
- gestionarea task-urilor și a priorităților
- publicarea anunțurilor către utilizatori
- generarea de rapoarte utile pentru administrare

## 3. Public țintă
- administratorii studioului
- profesorii
- managerii operaționali
- potențialii utilizatori ai unui sistem similar pentru alte școli de dans

## 4. Cerințe funcționale
### 4.1 Autentificare și acces
- utilizatorii trebuie să se poată autentifica în aplicație
- rolurile trebuie să fie diferențiate între administrator, profesor și alte tipuri de utilizatori

### 4.2 Calendar
- utilizatorii trebuie să poată vizualiza evenimentele și lecțiile programate
- administratorii trebuie să poată adăuga și edita evenimente

### 4.3 Grupuri și elevi
- aplicația trebuie să permită crearea și gestionarea grupelor
- fiecare elev trebuie să aibă date de bază și să poată fi asociat unui grup

### 4.4 Prezențe
- profesorii trebuie să poată marca prezențele la lecții
- sistemul trebuie să păstreze istoricul prezențelor

### 4.5 Competiții și rezultate
- aplicația trebuie să permită înregistrarea competițiilor
- rezultatele trebuie să poată fi introduse și urmărite

### 4.6 To-Do și anunțuri
- utilizatorii trebuie să poată crea și gestiona sarcini
- anunțurile trebuie să poată fi publicate și vizualizate rapid

### 4.7 Rapoarte
- aplicația trebuie să ofere rapoarte simple despre prezențe, grupuri și evenimente

## 5. Cerințe nefuncționale
- aplicația trebuie să fie disponibilă pe iOS și Android
- interfața trebuie să fie ușor de utilizat și intuitivă
- datele trebuie să fie stocate în siguranță
- arhitectura trebuie să permită adaptarea ulterioară pentru alte școli de dans

## 6. Tehnologii recomandate
- Frontend: Flutter
- Backend: Supabase
- Bază de date: PostgreSQL

## 7. Versiune inițială
- versiunea curentă: v0.1 Foundation
- faza inițială se va concentra pe structura de bază a aplicației și pe elementele principale ale produsului

## 8. Definiție de succes
Produsul este considerat util atunci când permite administrarea de bază a unui studio de dans printr-o interfață clară și un flux de lucru simplu pentru utilizatori.
# Product Requirements Document (PRD)

# Insane Dance Center App

Version: 1.0 Foundation

---

# 1. Scop

Insane Dance Center App este o aplicație destinată administrării complete a unui studio de dans.

Scopul principal este eliminarea caietelor și centralizarea întregii activități într-o singură aplicație.

---

# 2. Roluri

## Administrator

Permisiuni complete.

Momentan:

- Eduard
- Nico

---

## Antrenor

Momentan:

- Eduard
- Dari

Poate administra doar activitățile și grupele proprii.

---

## Asistent

Momentan nu există.

Va putea:

- vedea calendarul
- completa prezența
- vedea To-Do
- vedea anunțurile

---

# 3. Module

Dashboard

Calendar

Grupe

Elevi

Prezențe

Echipă

Competiții

To-Do

Anunțuri

Rapoarte

Setări

Arhivă

---

# 4. Obiective

- organizarea activităților
- gestionarea elevilor
- evidența prezențelor
- organizarea competițiilor
- istoricul rezultatelor
- comunicarea internă
- gestionarea echipei

---

# 5. Principii

• Telefon First

• Interfață simplă

• Maximum două apăsări pentru orice acțiune importantă

• Fără funcții inutile

• Totul se salvează automat

• Dacă o informație există deja în aplicație, utilizatorul nu trebuie să o introducă din nou.

---

# 6. Status proiect

Development

Versiune curentă

v0.1 Foundation
