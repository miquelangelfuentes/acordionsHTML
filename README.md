# Extractor de Contingut d'Acordió Bootstrap

Una aplicació web senzilla i intuïtiva per processar fitxers HTML que contenen acordions de Bootstrap, desplegant automàticament tot el contingut plegat per poder-lo visualitzar i exportar fàcilment.

🚀 **Accés directe a l'aplicació web:** [https://miquelangelfuentes.github.io/acordionsHTML/](https://miquelangelfuentes.github.io/acordionsHTML/)

---

## 📋 Funcionalitats

- **Arrossegar i deixar anar (Drag & Drop):** Carrega fitxers `.html` directament des del teu explorador de fitxers.
- **Desplegament automàtic:** Elimina les classes de col·lapse (`collapse`) i afegeix la classe `show` als elements d'acordió Bootstrap perquè tot el contingut quedi visible.
- **Previsualització instantània:** Mostra una vista prèvia del contingut extret abans de descarregar-lo.
- **Descàrrega directa:** Genera i descarrega el fitxer HTML modificat amb un sol clic (`contingut_acordio_extret.html`).
- **Sense servidor ni backend:** Funciona 100% al navegador de manera privada i segura (res no s'envia a cap servidor extern).

---

## 🛠️ Tecnologies utilitzades

- **HTML5 & Vanilla JavaScript** (DOMParser, FileReader, Blob API)
- **Tailwind CSS** (via CDN)
- **Inter Font** (Google Fonts)

---

## 💻 Ús local

Pots obrir directament el fitxer `index.html` amb qualsevol navegador modern, o bé clonar el repositori:

```bash
git clone https://github.com/miquelangelfuentes/acordionsHTML.git
cd acordionsHTML
# Obre index.html al teu navegador
```
