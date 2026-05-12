# Milestone 5 – Implementacja kluczowych mechanik

**Data zakończenia:** 08.05.2026  
**Status:** Zrealizowany 
**Cel etapu:** Zamknięcie pełnej pętli gry (**Core Loop**) poprzez dodanie systemów ekonomicznych, progresji oraz usprawnienie systemów bazowych.

---

## 📋 Zakres prac

### 1. System Ekonomii i Balansu
* **Mechanika zarobku:** Implementacja zbierania waluty w fazie dnia (eksploracja terenu parku).
* **Balansowanie danych:** Ustalenie kosztów przedmiotów w sklepie oraz wartości nagród za przetrwanie fali.
* **System leczenia:** Dodanie przedmiotów typu "apteczka" (lub regeneracja poprzez puszki) przywracających punkty zdrowia gracza.

### 2. System Sklepu i Interakcji (MVP)
* **Punkt handlowy:** Stworzenie tymczasowego stanowiska (NPC na ławce jako placeholder dla Żabki).
* **Asortyment:** Implementacja listy przedmiotów (ok. 10 pozycji), w tym m.in. puszki, kij, patelnia.
* **System Dialogowy:** Dodanie prostego dialogu powitalnego ("Dzień dobry, co chce Pani kupić?") oraz UI handlu.

### 3. Ekwipunek i Walka
* **Zarządzanie przedmiotami:** Implementacja inwentarza z obsługą slotów pod klawiszami numerycznymi `1`, `2`, `3`.
* **Mechanika zmiany broni:** Płynne przełączanie się między przedmiotami trzymanymi w dłoniach.

### 4. System Progresji (Wave System)
* **Pętla dnia i nocy:** Automatyczne przejście z nocy do kolejnego dnia po przetrwaniu fali.
* **Skalowanie trudności:** Implementacja mechanizmu zwiększającego poziom trudności (liczba/siła wrogów) wraz z każdą kolejną falą.

### 5. Poprawki Techniczne (Kamera i Interakcje)
* **Refactor Kamery TPP:** * Naprawa kolizji kamery z modelem gracza (eliminacja efektu "bicia samej siebie").
    * Naprawa widoczności – zapewnienie poprawnego focusu na otoczeniu, a nie tylko na postaci.
    * Umożliwienie interakcji/podnoszenia przedmiotów w trybie trzecioosobowym.

---

## 🎯 Rezultaty (Deliverables)
Pełna pętla gameplayowa zgodna z GDD:
**Eksploracja/Zarobek** → **Zakupy** → **Walka** → **Przetrwanie i Progresja**.

---

## ✅ Kryteria ukończenia (Definition of Done)
* [ ] Gracz może kupić przedmiot w sklepie i natychmiast go użyć.
* [ ] System ekwipunku poprawnie przypisuje przedmioty do klawiszy skrótów.
* [ ] Kamera TPP nie koliduje z postacią i pozwala na swobodną interakcję z przedmiotami.
* [ ] Poziom trudności wzrasta w sposób zauważalny z każdą kolejną nocą.
