# 02 · Biology of *Vibrio cholerae*

[← Introduction](01_introduction.md) | [Home](../README.md) | [Next: Epidemiology →](03_epidemiology.md)

---

## 2.1 Taxonomy and Classification

*Vibrio cholerae* is a Gram-negative, facultatively anaerobic, comma-shaped (vibrioid) bacterium belonging to the family *Vibrionaceae* within the class *Gammaproteobacteria*. The genus *Vibrio* encompasses over 100 species, the majority of which are free-living aquatic organisms.

*V. cholerae* is classified into more than **200 serogroups** based on the O-antigen structure of the lipopolysaccharide (LPS). Of these, only **O1** and **O139** are associated with epidemic and pandemic cholera.

### O1 Serogroup Classification

```
V. cholerae O1
├── Biotype: Classical (historical; no longer circulating)
└── Biotype: El Tor (current pandemic)
    ├── Serotype: Ogawa
    ├── Serotype: Inaba
    └── Serotype: Hikojima (rare)
```

> ⚠️ Non-O1/non-O139 strains (NAG vibrios) can cause sporadic gastrointestinal illness but have **not** been responsible for large-scale pandemics. Serogroup confirmation is therefore a critical first step in any diagnostic or genomic workflow.

---

## 2.2 Morphology and Growth Characteristics

| Feature | Description |
|---------|-------------|
| Shape | Comma-shaped (vibrioid), 1.4–2.6 μm × 0.5–0.8 μm |
| Motility | Rapid; single polar flagellum |
| Gram stain | Negative |
| Optimal temperature | 37°C |
| pH range | 6.0–9.0 (alkaline preferred) |
| NaCl tolerance | 0.5–3% |
| Oxidase test | Positive |
| Selective media | TCBS agar — yellow colonies (sucrose fermentation) |

On **TCBS agar**, *V. cholerae* produces **yellow colonies** due to sucrose fermentation, distinguishing it from *V. parahaemolyticus* (green colonies) and *V. vulnificus* (green colonies).

---

## 2.3 Virulence Mechanisms

The pathogenicity of epidemic *V. cholerae* O1/O139 rests on two principal virulence determinants:

### 2.3.1 Cholera Toxin (CT)

Encoded by the **`ctxAB`** genes, carried on the **CTXφ bacteriophage** integrated into the chromosome.

```
CTXφ Prophage
├── ctxA  →  Toxic A subunit (ADP-ribosylates Gs protein)
├── ctxB  →  Binding B subunit (GM1 ganglioside receptor)
├── ace   →  Accessory cholera enterotoxin
└── zot   →  Zonula occludens toxin
```

**Mechanism of disease:**
1. CtxB binds GM1 ganglioside on intestinal epithelial cells
2. CtxA enters the cell and ADP-ribosylates the stimulatory G protein (Gs)
3. Constitutive activation of adenylate cyclase → ↑↑↑ cAMP
4. Massive chloride efflux via CFTR channels; water follows osmotically
5. Result: profuse rice-water diarrhoea (up to 20 L/day in severe cases)

### 2.3.2 Toxin-Coregulated Pilus (TCP)

Encoded by **VPI-1** (Vibrio Pathogenicity Island 1), a ~39.5 kb horizontally acquired genomic island.

- Essential for intestinal colonisation
- Also serves as the receptor for CTXφ phage acquisition
- Strains lacking `tcpA` are avirulent in human volunteer studies

### 2.3.3 Additional Virulence Factors

| Factor | Gene(s) | Function |
|--------|---------|----------|
| Haemagglutinin/Protease | `hap` | Mucosal detachment; environmental shedding |
| Vibrio Polysaccharide | `vps-I`, `vps-II` | Biofilm formation; environmental persistence |
| Type VI Secretion System | `T6SS` | Interbacterial competition; gut colonisation |
| Neuraminidase | `nanH` (VPI-2) | GM1 receptor modification |
| Neuraminidase | `vpsT`, `vpsR` | Regulation of VPS biosynthesis |

---

## 2.4 Environmental Reservoirs and Ecology

> ✅ **Key concept:** *V. cholerae* is not just a human pathogen — it is a **natural aquatic organism** with complex environmental biology.

*V. cholerae* forms close associations with **copepods and other zooplankton**, to which it attaches via chitin-binding proteins. It can enter a **viable but non-culturable (VBNC)** state under unfavourable conditions, making detection by culture alone insufficient.

### Environmental Risk Factors for Bloom Events

- Rising water temperatures (linked to El Niño/ENSO cycles and climate change)
- Eutrophication and algal blooms
- Flooding events that mobilise contaminated sediments
- Poor sanitation infrastructure amplifying faecal-oral transmission

---

## 2.5 Antimicrobial Resistance Biology

*V. cholerae* acquires resistance through:

| Mechanism | Details | Antibiotics Affected |
|-----------|---------|---------------------|
| SXT/R391 ICEs | Integrative and conjugative elements; horizontally acquired | Tetracycline, TMP-SMX, chloramphenicol, streptomycin |
| Plasmid-mediated | Less common; ESBLs documented in South Asia | Beta-lactams |
| Efflux pumps | VexAB, VexCD overexpression | Fluoroquinolones |
| Point mutations | *gyrA* (S83I/F, D87G/N/Y), *parC* (S85L) | Fluoroquinolones |
| Macrolide resistance genes | *ermB*, *mphA* | Azithromycin |

> ⚠️ Fluoroquinolone resistance via *gyrA* mutations is a critical concern, as **ciprofloxacin** is a first-line cholera treatment. See [Page 14: AMR Detection](14-amr.md) for full analysis workflow.

---

## 2.6 The CTXφ – TCP – V. cholerae Infection Cycle

Understanding the molecular interaction between CTXφ phage, TCP, and the bacterium is fundamental to interpreting genomic surveillance data:

```
Environmental V. cholerae (non-toxigenic)
         │
         ▼ (chitin-induced competence; VPI-1 acquisition via HGT)
V. cholerae + TCP (tcpA+)
         │
         ▼ (CTXφ phage uses TCP as receptor → integrates as prophage)
Toxigenic V. cholerae (ctxAB+ tcpA+)
         │
         ▼ (human ingestion → small intestine colonisation via TCP)
CT production → massive fluid secretion → rice-water diarrhoea
         │
         ▼ (shed in stool → environmental amplification)
Environmental contamination → onward transmission
```

This cycle explains why both `ctxAB` AND `tcpA` must be present for epidemic potential, and why both are screened in every genomic analysis (see [Page 15: Virulence Gene Prediction](15-virulence.md)).

---

## Key Takeaways

- *V. cholerae* O1 El Tor is the sole cause of the current seventh pandemic
- Cholera toxin (CT) and Toxin-Coregulated Pilus (TCP) are the two essential virulence determinants
- The organism has a complex environmental reservoir — surveillance must account for both environmental and clinical isolates
- Antimicrobial resistance is largely mediated by SXT ICEs and fluoroquinolone-resistance mutations

---

[← Introduction](01_introduction.md) | [Home](../README.md) | [Next: Epidemiology →](03_epidemiology.md)

*Licensed [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) · PHA4GE Cholera Genomics Working Group*