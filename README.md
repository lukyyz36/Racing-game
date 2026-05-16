# 🏎️ Horizon Rally: Ultimate Edition

Plně hratelná 2D závodní hra v prohlížeči, vytvořená pomocí HTML5 Canvas a čistého JavaScriptu. Hra nevyžaduje žádné externí knihovny, nabízí propracovaný kariérní mód, garáž, fyziku vozidel a je architektonicky připravena pro LAN multiplayer.

## ✨ Hlavní funkce

*   **Kariérní mód a Garáž:** Začínejte se starým vrakem (Scrap Hatch), vyhrávejte závody, vydělávejte peníze a kupujte supersporty (např. Apex Predator).
*   **Pokročilý systém vylepšení:** Investujte do vylepšení motoru (zrychlení a maximální rychlost), pneumatik (základní přilnavost) a řízení (Handling - stabilizuje auto ve dvousetkilometrových rychlostech).
*   **Dynamická fyzika:** Komplexní jízdní model, který počítá s přilnavostí povrchu (silnice vs. tráva), smyky, strmostí zatáčení podle rychlosti a využitím ruční brzdy.
*   **Chytrá AI:** Počítačem řízení protivníci brzdí do prudkých zatáček, občas použijí ruční brzdu a dynamicky reagují na pozici hráče (jemný rubberbanding).
*   **Procedurální tratě:** Generování unikátních závodních okruhů skrze dynamické checkpointy s plynulou návazností.
*   **LAN-Ready Architektura:** Zpracování uživatelských vstupů (klávesnice) je zcela odděleno od herní fyziky (Data-Driven design). Hra je tak připravena na snadné napojení WebSocketů (Node.js) pro síťový multiplayer.
*   **Automatické ukládání:** Veškerý váš postup, peníze a nakoupená auta se automaticky ukládají do `localStorage` vašeho prohlížeče.

## 🎮 Ovládání

*   `W` nebo `Šipka nahoru`: Plyn / Akcelerace
*   `S` nebo `Šipka dolů`: Brzda / Zpátečka
*   `A` / `D` nebo `Šipky do stran`: Zatáčení
*   `Mezerník`: Ruční brzda (ideální pro agresivní drifty a vybírání ostrých zatáček)

## 🚀 Jak hru spustit

Projekt má **nulové závislosti (Zero Dependencies)**. Nevyžaduje Node.js, Webpack, ani lokální server. 

1. Stáhněte si tento repozitář (nebo použijte `git clone`).
2. Otevřete soubor `index.html` v jakémkoliv moderním webovém prohlížeči (Chrome, Firefox, Safari, Edge).
3. Hrajte!

## 🛠️ Technologie

*   **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
*   **Vykreslování:** HTML5 `<canvas>` API (2D kontext)
*   **Ukládání dat:** Web Storage API (`localStorage`)

## 📝 Plánovaný rozvoj (TODO)

* [ ] Implementace lokálního serveru (Node.js/Socket.io) pro LAN multiplayer.
* [ ] Přidání překážek na trať (kameny, stromy mimo vyznačenou cestu).
* [ ] Zvukové efekty (motor, smyky, hudba v menu).

---

Vytvořeno jako komplexní ukázka možností HTML5 Canvas bez použití herních enginů.


# EN
# 🏎️ Horizon Rally: Ultimate Edition

Fully playable 2D browser racing game, built with HTML5 Canvas and vanilla JavaScript. Zero external dependencies. Features a deep career mode, garage, vehicle physics, and a LAN-ready multiplayer architecture.

![Gameplay Showcase](https://via.placeholder.com/800x450.png?text=Horizon+Rally+Gameplay)

## ✨ Key Features

*   **Career Mode & Garage:** Start with a Scrap Hatch, win races, earn money, and buy supercars (e.g., Apex Predator).
*   **Advanced Upgrade System:** Invest in engine upgrades (acceleration/top speed), tires (base grip), and steering (Handling - stabilizes the car at 200+ km/h).
*   **Dynamic Physics:** Complex handling model accounting for surface grip (road vs. grass), drifting, speed-dependent steering lock, and handbrake mechanics.
*   **Smart AI:** CPU opponents brake for sharp corners, occasionally use the handbrake, and dynamically adapt to the player's position (soft rubberbanding).
*   **Procedural Tracks:** Unique racing circuits generated via dynamic checkpoints for a smooth flow.
*   **LAN-Ready Architecture:** User input processing is entirely decoupled from game physics (Data-Driven design). Ready for easy WebSocket (Node.js) integration for network multiplayer.
*   **Auto-Save:** All progression, cash, and owned vehicles are automatically saved to your browser's `localStorage`.

## 🎮 Controls

*   `W` or `Up Arrow`: Accelerate
*   `S` or `Down Arrow`: Brake / Reverse
*   `A` / `D` or `Left/Right Arrows`: Steer
*   `Spacebar`: Handbrake (perfect for aggressive drifts and tight corners)

## 🚀 How to Run

This project has **Zero Dependencies**. It requires no Node.js, Webpack, or local server environments.

1. Download this repository (or `git clone`).
2. Open the `index.html` file in any modern web browser (Chrome, Firefox, Safari, Edge).
3. Play!

## 🛠️ Technology Stack

*   **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
*   **Rendering:** HTML5 `<canvas>` API (2D Context)
*   **Data Storage:** Web Storage API (`localStorage`)

## 📝 Planned Features (TODO)

* [ ] Implement a local server (Node.js/Socket.io) for LAN multiplayer.
* [ ] Add track obstacles (rocks, trees outside the main road).
* [ ] Audio effects (engine sounds, tire screeches, menu music).
