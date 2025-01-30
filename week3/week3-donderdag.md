**Datum:** `[30/01/2025]`  
**Studentnaam:** `[Sarah El Fraihi]`  
**Groepsnaam:** `[MEELS]`

---

## 1) Wat heb ik vandaag gedaan voor mijn project?

> **Activiteiten:**
>
> - De highlightSpecificIcon() functie aangepast zodat iconen onmiddellijk de juiste kleur behouden bij de eerste klik.
> - De event listener op kaarticonen aangepast zodat het icoon wordt geüpdatet vóór de pop-up opent.
> - Testen en debuggen om ervoor te zorgen dat iconen correct werken zonder dubbel te moeten klikken.
> - Probleem:

- De ondertitel en de knoppen kregen pas de correcte kleur na een tweede klik.
  Oplossing:
- CSS-hertekening geforceerd via void element.offsetWidth;
- De nieuwe kleurklassen correct toegepast vóór het tonen van de pop-up.
- requestAnimationFrame() gebruikt om de ondertitel onmiddellijk te updaten.
  > - displayTourChatbotMessage() aangepast zodat het correct op elke pagina een standaard AI-bericht toont.
  > - checkPageAndHighlight() aangepast zodat het bij elke paginawissel de chatbot opnieuw instelt.
  > - Getest met verschillende pagina’s in de tours om te verzekeren dat de chatbot overal correct werkt.
  > - Voorheen werkte de chatbot niet goed als je op “Enter” drukte. Dit is opgelost zodat berichten zowel met de Enter-toets als de verzendknop worden verstuurd.
  > - Chatberichten beperken tot max. 3, zodat het scherm niet te vol raakt.
  > - Even listener aangepast zodat iconen correct worden geüpdatet vóór de pop-up opent.
  > - Onderliggende structuren getest en verbeterd om te verzekeren dat alles soepel werkt.
  > - Nieuwe lettergrootte ingesteld in @media (max-width: 768px) zodat de titels niet te groot zijn.

---

## 2) Wat heb ik nieuw geleerd of voor het eerst zelf gedaan?

> **Nieuwe skills:**
>
> -

---

## 3) Wat is mijn gevoel over vandaag?

> **Algmeeen gevoel:**
>
> - **"boos"**
> - Ik ben boos omdat twee van mijn teamleden niets doen. Ze hebben drie dagen lang samen gewerkt aan één video, maar die duurt slechts een paar seconden. Daarnaast klaagden ze over de code, terwijl ze er zelf niets aan hebben bijgedragen.

---
