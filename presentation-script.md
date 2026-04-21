# 5-MINUTE PRESENTATION SCRIPT: EL ARCHIVO

## SLIDE 1: Title — 0:00-0:30

Good [morning/afternoon]. Today I'm presenting **EL ARCHIVO: An Interactive Bad Bunny Lyric Analyzer**.

This project was created for CULP 3101, Professor Melinda González's course "Bad Bunny, Poetry & Puerto Rico" here at Georgetown.

The title references Bad Bunny's song "Debí Tirar Más Fotos" — *I Should Have Taken More Photos*. That song argues that Puerto Rico's erasure is happening because we failed to document it. **This website IS the act of taking more photos** — creating a digital archive of Puerto Rican resistance through Bad Bunny's lyrics.

---

## SLIDE 2: Research Process & Methodology — 0:30-1:15

**My research process had three phases:**

First, I returned to our course texts — Rodriguez-Madera's *The Bad Bunny Enigma*, Barreiro León's work on decolonial poetry, and Guimond's Hawaii-Puerto Rico comparison — and identified **five thematic frameworks**:

1. **Decolonial Poetry** — reggaetón as resistance and fugitive practice
2. **Diaspora & Migration** — the circuit between island and mainland
3. **Gentrification & Place** — Act 60, displacement, the Hawaii parallel
4. **State Violence & Resistance** — Hurricane Maria, Telegramgate, protests
5. **Memory & Futures** — archives, erasure, and cultural survival

Second, I selected **14 songs from 2016-2026** that best exemplified these frameworks. I listened chronologically, reading lyrics alongside political events, mapping which songs responded to which crises.

Third, I realized the *connections* between songs mattered as much as individual lyrics. So instead of a traditional paper, **I built four interactive data visualizations** to show those relationships — a constellation network, a diaspora globe, a political timeline, and an annotated lyric theater.

---

## SLIDE 3: Main Findings — 1:15-3:00

**[SHOW WEBSITE DEMO OR SCREENSHOTS OF VISUALIZATIONS]**

Let me walk you through my main findings using the four visualizations.

**Finding #1: Bad Bunny's work forms a political archive.**

In the **Lyric Theater**, you can explore 14 songs with full annotations. Take "El Apagón" — released after LUMA Energy's privatization caused massive blackouts. The lyrics say *"Los pobres no tienen ná'"* (The poor have nothing) while showing footage of displaced Puerto Ricans. This isn't just a song — it's documentation of state failure.

**Finding #2: The political case emerges from relationships, not individual songs.**

The **Constellation View** shows this network structure. "El Apagón" connects to "Lo Que Le Pasó a Hawaii" because both songs address colonial dispossession and gentrification. "Afilando los Cuchillos" connects to "Estamos Bien" because both demand government accountability after Hurricane Maria. The *density of these connections* reveals how Bad Bunny builds a cumulative political argument across albums.

**Finding #3: Diaspora geography is central to Puerto Rican identity.**

The **Diaspora Map** plots 12 locations from San Juan to the Bronx to Hawaii. Songs like "NUEVAYoL" and "Voy a LLeVARte Pa PR" trace the circuit between island and mainland — what our course texts call "Nuyorican consciousness." The arc lines show how identity moves across borders.

**Finding #4: Music responds to political crisis in real time.**

The **Political Timeline** proves temporal proximity. July 11, 2019: Telegramgate leaks. July 15: "Afilando los Cuchillos" drops — **4 days later**. July 22: Governor resigns. Or Hurricane Maria in 2017 (2,975 deaths) followed immediately by "Estamos Bien." **The music is always responding to something real.**

---

## SLIDE 4: Technical Execution — 3:00-3:45

From a technical standpoint, this is a **self-contained single-page application** — no frameworks, just HTML, CSS, and JavaScript.

I used:
- **D3.js** for the constellation network and globe projection
- **TopoJSON** for geographic data
- **Canvas API** for the animated particle background
- **CSS3 glass-morphism** for that archival, frosted aesthetic
- **Scroll-triggered animations** for progressive disclosure

The design system pulls from the Puerto Rican flag — navy backgrounds, red accents, cream text. The entire site uses three typefaces: Cormorant Garamond for display, Inter for body text, JetBrains Mono for metadata.

Every element is interactive: expandable cards, draggable globes, hoverable constellation nodes, smooth scroll navigation.

---

## SLIDE 5: Connection to Course Themes — 3:45-4:30

So how does this connect to the broader themes we've explored in CULP 3101?

**One: Reggaetón as Decolonial Practice**

We discussed how reggaetón isn't just entertainment — it's *cimarronaje*, fugitive practice, resistance encoded in genre. This project demonstrates that by showing how Bad Bunny uses music to document what the state tries to erase. He's creating a counter-archive to official narratives about Puerto Rico.

**Two: The Puerto Rican "Crisis" as Colonial Continuity**

Our course traced Hurricane Maria, PROMESA, Telegramgate, gentrification — not as isolated crises but as colonial continuity. The **Political Timeline** visualization makes that continuity visible. From 2016's Junta to 2026's Super Bowl, there's an unbroken line of resistance *through* Bad Bunny's discography.

**Three: Diaspora Consciousness**

We read about Nuyorican identity and the island-mainland circuit. The **Diaspora Map** shows this isn't abstract — it's geographic, traceable through specific songs tied to specific places. "NUEVAYoL" literally moves between New York and Puerto Rico, embodying that split consciousness.

**Four: Memory Work as Political Work**

"Debí Tirar Más Fotos" argues that forgetting is political violence. This project *enacts* memory work — it's taking the photos Bad Bunny says we should have taken. It's preserving what gentrification, displacement, and colonial amnesia want erased.

---

## SLIDE 6: Conclusion — 4:30-5:00

Bad Bunny sang "Debí Tirar Más Fotos" at the Super Bowl in February 2026 to **over 100 million viewers**. That performance turned "I should have taken more photos" into a global demand to witness Puerto Rico's reality.

This project answers that demand. **EL ARCHIVO is taking more photos.**

It documents a decade of resistance — from 2016's PROMESA Act to 2026's Super Bowl protest — through lyrics, maps, timelines, and networks. It's a living political archive built to survive the gentrification, displacement, and colonial forgetting that the music itself fights against.

Thank you. I'm happy to take questions or give a live demo.

---

**TOTAL TIME: ~5:00**

---

## VISUAL AIDS & PRESENTATION STRUCTURE

### Required Elements Coverage:

✅ **Research/Creative Process** — Covered in Slide 2 (three-phase methodology: frameworks → song selection → visualization design)

✅ **Main Findings/Themes** — Covered in Slide 3 (four key findings about archive, relationships, diaspora, temporal proximity)

✅ **Course Connection** — Covered in Slide 5 (explicit links to decolonial practice, colonial continuity, diaspora consciousness, memory work)

✅ **Visual Aids** — Screenshots or live demo of all four visualizations throughout presentation

### Recommended Visual Aids for Each Slide:

**Slide 1:** Title slide with project logo/website hero image

**Slide 2:** Diagram showing your three-phase research process + list of five frameworks with color codes

**Slide 3:**
- Screenshot of Lyric Theater (expandable card)
- Screenshot of Constellation View (network graph)
- Screenshot of Diaspora Map (globe with pins)
- Screenshot of Political Timeline (dual-track chronology)

**Slide 4:** Code snippets or architecture diagram (D3.js network, Canvas animation, glass-morphism CSS)

**Slide 5:** Split-screen showing course text excerpts alongside corresponding visualizations

**Slide 6:** Full-screen of website homepage or impactful quote slide

### SPEAKER NOTES

**Key Points to Emphasize:**
- The project title performs its own thesis (taking photos = documentation)
- Research process was iterative: texts → songs → relationships → visualizations
- Four findings build on each other (archive → network → geography → temporality)
- Each visualization answers a different research question
- Direct engagement with course texts (Rodriguez-Madera, Barreiro León, Guimond)
- Form serves content (decolonial digital humanities)

**Potential Q&A Topics:**
- Why these 14 songs? (Chronological span, framework representation, political significance)
- Technical implementation details (D3.js, Canvas API, why no frameworks)
- Framework selection methodology (derived from course texts)
- How you handled Spanish/English translation decisions
- Challenges in visualizing temporal proximity
- Future additions (more albums, community engagement, API access)
- Accessibility considerations (screen readers, keyboard navigation)

**Demo Tips if Time Permits:**
1. **Lyric Theater:** Expand "El Apagón" card to show annotations
2. **Constellation:** Hover over edge between "El Apagón" ↔ "Lo Que Le Pasó a Hawaii"
3. **Globe:** Rotate to show San Juan, then click the Bronx pin for "NUEVAYoL"
4. **Timeline:** Scroll to July 2019 to show Telegramgate → song → resignation sequence

**Timing Flexibility:**
- If running short: Expand on Slide 3 findings with more lyric examples
- If running long: Consolidate Slides 2-3 or shorten technical details in Slide 4
- Always prioritize: Process → Findings → Course Connection
