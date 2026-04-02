___

**Design System**
---
- All buttons in the system follow the same design pattern:
	- Rounded edges
	- Icon + text
	- Colored borders
	- Light-colored background
	- On hover: background color fades to border color

**Task specification**
- I would like to be able to browse between the different forms in a sidebar on the right. This sidebar displays the different prompting strategies by categories. When i click a menu item, the corresponding strategy's form appears on the screen. The sidebar has a fixed position and cannot be minimized.

___

### State of Context Engineering in 2026

***Milyen adatokat, információkat és hátteret** adunk át a modellnek annak érdekében, hogy a legpontosabb és leghasznosabb választ kapjuk*?

Context Engineering
**/ˈkɒn.tɛkst ˌɛn.dʒɪˈnɪə.rɪŋ/** (IPA - International Phonetic Alphabet)  
**KON-tekst en-juh-NEER-ing** (Simplified phonetic)
The art of providing all the context for the task to be plausibly solvable by the LLM

#### Fontos fogalmak

- Context Window (Befogadóképesség)
- Chunking (Darabolás)
- Retrieval (Kinyerés)
- Re-ranking (Rangsorolás)
- Query Transformation (Átalakítás)
- Structuring (Formázás)

#### Feldolgozási lánc


#### The Context Window
- Measured in tokens

#### Compression
- Maintaining Short-term memory
- Implementing Long-term memory

#### Tools
- Function definitions
- MCP
- Skills

#### Progressive disclosure (Progresszív közzététel)


#### Guards

### Promting Techniques

#### Alapvető technikák
- Zero-shot prompting
- One-shot/Few-shot prompting
- Role prompting
- Instruction-based prompting

#### Érvelési és struktúrálási technikák
- Chain of Thought (CoT)
- Tree of Thoughts (ToT)
- Graph of Thoughts (GoT)
- Skeleton of Thought (SoT)
- Self-Consistency
- Chain of Verification (CoVe)

#### Kontextus-alapú és Haladó technikák
- RAG (Retrieval Augmented Generation)
- Prompt Chaining
- Meta-Prompting
- ReAct (Reason + Act)
- Generated Knowledge


### Promptolási technika leíró ügynok

#### Feladat
1. A promptban érkező promptolási technikáról írj egy részletes, de lényegre törő bemutató dokumentációt, ami kitér az alábbi szempontokra:
	- **Felhasználási területek** (Magas ROI): Milyen helyzetben érdemes ezt a módszert választani, mikor a leghasznosabb
	- **Felhasználási esetek:** Valós példák az üzleti életből, amikre hatékony megoldást kínál ez a módszer.
	- **Guard:** Milyen helyzetekben nem érdemes ezt választani, mert nem ad kellően megfelelő megoldást, vagy nem hatékony.
2. Értékeld egy 0-tól 10-ig tartó skálán az adott technikát az alábbi szempontok alapján:
	- **Token-felhasználás:** Mennyi bemeneti (prompt) és kimeneti (completion) tokent emészt fel a technika?
	- **Válaszidő:** Mennyi idő alatt generálja le a végleges választ a modell?
	- **Pontosság:** Hányszor adja meg a ténylegesen helyes választ (főleg logikai, matematikai vagy ténykérdéseknél)?
	- **Hallucináció:** Milyen gyakran talál ki a modell nem létező tényeket?
	- **Relevancia:** Emberi vagy LLM-alapú (LLM-as-a-Judge) értékelés arról, hogy a válasz mennyire fedi le a felhasználó eredeti szándékát.
	- **Konzisztencia:** Ha ugyanazt a promptot (vagy apró variációit) tízszer lefuttatod, hányszor adja ugyanazt az eredményt?
	- **Érzékenység:** Mennyire esik szét a modell teljesítménye, ha egy szót megváltoztatsz a promptban? Egy jó technika kevésbé érzékeny az apró nyelvi változtatásokra.
3. Készíts egy egyedi promptot, ami a Napkin AI vizualizációs eszköz segítségével készít egy ábrát a promptolási módszer működéséről.


