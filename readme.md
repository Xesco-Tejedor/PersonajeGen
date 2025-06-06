# 🔮 Creador de Fitxes de Personatge amb IA

Benvingut/da al Creador de Fitxes de Personatge amb IA, una eina web dissenyada per a escriptors, directors de joc, artistes i qualsevol persona que vulgui donar vida als seus personatges d'una manera completament nova. Combina la teva creativitat amb el poder de la intel·ligència artificial de Google per definir, desenvolupar i, el més important, visualitzar els teus personatges com mai abans.

[Aquí va una captura de pantalla o un GIF impressionant de l'aplicació en funcionament!]

## ✨ Característiques Principals

* **Interfície Intuïtiva en Pestanyes:** Organitza la informació del teu personatge de manera clara i senzilla (Informació Bàsica, Aparença, Personalitat).
* **Generació de Text amb IA:** Expandeix la història de fons del teu personatge amb un sol clic, afegint profunditat i detalls interessants gràcies a l'API de Gemini.
* **Generació d'Imatges amb IA:** Visualitza el teu personatge!
    * Crea **retrats únics i dinàmics** del teu personatge.
    * Genera **fulls de model detallats** amb múltiples vistes (frontal, perfil, expressions, etc.).
* **Ampla Selecció d'Estils Artístics:** Tria entre més de 20 estils artístics, des de "Retrat Fotorrealista" i "Còmic Americà" fins a "Art Gòtic" o "Vaporwave".
* **Importació i Exportació Fàcil:**
    * Guarda la teva fitxa completa en un arxiu `.json`.
    * Exporta un paquet `.zip` que inclou la fitxa, les imatges generades i un resum en Markdown.
    * Importa personatges enganxant el text JSON o simplement **arrossegant i deixant anar (Drag & Drop)** l'arxiu a l'aplicació.
* **Disseny 100% Responsable:** Fes servir l'eina còmodament des del teu ordinador, tauleta o mòbil.
* **Privacitat Primer:** Tot el procés es duu a terme al teu navegador. La teva clau API i les dades dels teus personatges no s'emmagatzemen enlloc.

## 🚀 Tecnologies Utilitzades

* **Frontend:** HTML5, Tailwind CSS, JavaScript (vanilla).
* **APIs d'IA:** Google AI Platform (API de Gemini i API d'Imagen).
* **Utilitats:** JSZip, FileSaver.js.

## 🔧 Instal·lació i Configuració

Aquesta aplicació és un únic arxiu estàtic, la qual cosa fa que la seva configuració sigui extremadament senzilla. No requereix cap _build step_ ni servidor.

1.  **Descarregar el Projecte:**
    Clona el repositori o simplement descarrega l'arxiu `index.html`.
    ```bash
    git clone [https://github.com/elteunom/elteurepositori.git](https://github.com/elteunom/elteurepositori.git)
    ```

2.  **Obrir l'Arxiu:**
    Obre l'arxiu `index.html` directament al teu navegador web preferit (Chrome, Firefox, Edge, etc.).

3.  **Obtenir una Clau API de Google AI (Molt Important):**
    Perquè la generació de text i imatges funcioni, necessites la teva pròpia clau API de Google.
    * Ves a [Google AI Studio](https://aistudio.google.com/).
    * Fes clic a "**Get API key**" i crea una nova clau en un projecte teu.
    * Assegura't que el teu projecte de Google Cloud tingui l'**API "Generative Language"** (o l'API Vertex AI) habilitada.
    * **La facturació ha d'estar activa** al teu projecte de Google Cloud perquè l'API d'imatges funcioni correctament. Google ofereix un nivell gratuït generós, però la facturació ha d'estar habilitada.

## 🎮 Com Utilitzar l'Aplicació

1.  **Enganxa la teva Clau API:** Introdueix la teva clau API de Google AI al camp corresponent.
2.  **Defineix el teu Personatge:** Omple els camps a les pestanyes "Informació Bàsica", "Aparença" i "Personalitat". Com més detallat siguis, especialment en els **"Rasgos Distintivos"**, més consistents seran les imatges.
3.  **Expandeix la Història (Opcional):** Si vols més detalls per al rerefons, escriu un resum i fes clic a "✨ Expandir Historia con IA".
4.  **Selecciona un Estil i Genera!** Tria l'estil artístic que més t'agradi i fes clic en un dels botons de generació:
    * `🔮 Generar Imagen Única` per a un retrat principal.
    * `🎨 Generar Hoja de Modelo` per a un full de referència complet.
5.  **Importa i Exporta:** Fes servir els botons d'importació (enganxant text o amb drag & drop) i exportació per guardar i compartir les teves creacions.

## 🗺️ Full de Ruta i Millores Futures

Aquest projecte està en constant evolució! La nostra visió és convertir-lo en l'eina definitiva per a la creació de personatges.

### ⚠️ En Procés de Millora (Work in Progress)

* **Generació de Fulls de Model Detallats:** Aquesta és una de les funcionalitats més potents, però també la més complexa. Actualment, aconseguir una consistència facial i física perfecta entre les diferents vistes (frontal, perfil, esquena, expressions) és un repte tècnic amb les versions actuals de les APIs. **Considerem aquesta funcionalitat com a "experimental"**. Estem treballant activament en tècniques de _prompting_ avançat i explorant noves funcionalitats de l'API per millorar dràsticament la coherència en futures actualitzacions.

### Pròximes Característiques

* **Mode Fosc:** Una interfície alternativa per a sessions de creativitat nocturnes.
* **Desar Localment:** Guardar múltiples personatges directament al navegador (`localStorage`).
* **Plantilles de Personatge:** Plantilles predefinides per a diferents gèneres (fantasia, ciència-ficció, D&D 5e, etc.).
* **Localització:** Traducció completa de la interfície a altres idiomes.

## 🙌 Com Contribuir

Les contribucions són més que benvingudes! Si tens idees per a noves funcionalitats, has trobat un error o vols millorar el codi, no dubtis a:

1.  Obrir una **Issue** per discutir el canvi.
2.  Fer un **Fork** del projecte.
3.  Crear una nova **branca** (`git checkout -b feature/NomDeLaMillora`).
4.  Fer un **Commit** amb els teus canvis (`git commit -m 'Afegida nova funcionalitat increïble'`).
5.  Fer **Push** a la teva branca (`git push origin feature/NomDeLaMillora`).
6.  Obrir una **Pull Request**.

## 📄 Llicència

Aquest projecte està sota la **Llicència MIT**. Consulta l'arxiu `LICENSE` per a més detalls.

---

**Gràcies per utilitzar i mostrar interès en el Creador de Fitxes de Personatge amb IA!**
