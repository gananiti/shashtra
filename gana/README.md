# 📜 गण  
> *gaṇa* — `gan` — (contextual collective or conscious being)

---

## 1. Nāma (Identity)

| Bhāṣā (भाषा) | Diacritic | ASCII | Bolī |
|---------------|------------|--------|------|
| गण | *gaṇa* | `gan` | collective or being |

---

## 2. Uddeshya (Purpose)

A **gaṇa** is a **conscious entity or collective** capable of giving (*dātṛ*) or receiving (*ādātṛ*) *mantras* and *mats*.  
It can represent a **person**, **group**, **institution**, **machine**, or any **node of awareness** that participates in meaning.

Every *śāstra* arises from one or more *gaṇas*, and every *mat* expresses a relationship between *gaṇas* through *mantras*.

---

## 3. Siddhānta (Principle)

A *gaṇa* is **contextually unique**, never globally so.  
Its identity exists only **within a field of reference** — a *śāstra*, a *mat*, a *trust-circle*, or a *conversation*.  
To pretend otherwise would require omniscience and violate privacy, freedom, and locality.

Hence:
1. **Context defines identity.** A name is valid only inside the scope where it is spoken.  
2. **Multiplicity is natural.** The same being may appear as different *gaṇas* in different contexts.  
3. **Resolution is relational.** When needed, equivalence between two *gaṇas* is declared by another *mat*, not by fiat.  
4. **Privacy is dharma.** No being is obliged to reveal all its names across contexts.

---

## 4. Rūpa (Canonical Folder Structure)

```
gananiti/shashtra/gan/
├── README.md          ← Bhāṣā definition
├── README.en.md       ← Bolī translation
├── yantra.svg         ← emblem representing gaṇa
├── chitra.json        ← relational map (local scope)
└── anurag.ogg         ← sound motif (voice of this gaṇa)
```

Future *Bhūmi* tables will store *gaṇas* along with the *context identifier* that bounds their uniqueness.

---

## 5. Vyākhyā (Explanation)

### 5.1. Essence
*Gaṇa* means “group, assembly, collection.”  
In *Gananīti*, it stands for **a node of awareness inside a bounded context** — something capable of intention and expression.

A *gaṇa* might be:
- `gan:amitu` — Amit speaking as an individual inside a certain śāstra  
- `gan:fifthtry` — the collective of Amit, Deepti, Siddhant within organizational context  
- `gan:bharata` — the conceptual nation-gaṇa used in legal śāstras  
- `gan:machine.anumana` — an autonomous reasoning entity inside Bhūmi  

Each is valid **only within its declared frame**.

### 5.2. Declaration example

```yaml
gaṇa:
  nama_chatushtaya:
    bhasha: "गण"
    diacritic: "gaṇa"
    ascii: "gan"
    boli: "collective being"
  type: "individual | collective | machine | lineage"
  context: "gananiti/shashtra"        # scope of validity
  aliases: ["gan:amitu.personal", "gan:amitu.public"]
  created_at: 1732100000
```

---

## 6. Dharma (Invariants)

1. **Contextual identity:** a *gaṇa* exists only within a specific semantic or social context.  
2. **Freedom of naming:** any *gaṇa* may choose its own name within a context.  
3. **Declarative equivalence:** sameness across contexts is expressed via *mats*, not enforced globally.  
4. **Non-coercion:** no system may compel a *gaṇa* to reveal or unify its identities.  
5. **Relational persistence:** a *gaṇa’s* history lives through its *mats* and *śāstras*, not through central indexes.

---

## 7. Saṃvāda (Relations)

| Related Mantra | Role |
|-----------------|------|
| [`mantra`](../mantra/README.md) | gaṇas perceive and express mantras |
| [`shashtra`](../shashtra/README.md) | curated and evolved by gaṇas |
| `gananiti/shashtra/mat` *(future)* | records relations among gaṇas and mantras |
| `gananiti/shashtra/nama-chatushtaya` | defines naming within contexts |
| `amitu/data/context` *(future)* | defines contextual boundary schemas |

---

## 8. Dṛṣṭi (Example)

Within the śāstra `gananiti/shashtra`:
```yaml
gan:amitu
  type: individual
  description: "Amit Upadhyay (within Gananīti context)"
  roles: ["creator", "scribe"]

gan:gananiti_team
  type: collective
  members: ["gan:amitu", "gan:siddhant", "gan:deepti"]
```

The same person may have another manifestation elsewhere:
```yaml
gan:amitu.personal
  context: "amitu/shashtra"
  description: "private reflective self"
```

No registry is needed to prove they’re the same;  
that relationship can be expressed later through a *mat* stating equivalence.

---

## 9. Antarmukhya (Inner Commentary)

The *gaṇa* principle ensures **plural truths** without **total control**.  
Identity in *Gananīti* is *local, voluntary, and revocable*.  
This preserves both privacy and autonomy while allowing meaning to emerge through shared mantras.  

To speak as a *gaṇa* is to **enter a context of meaning**, not to register a global name.

---

## 10. Closing Śloka

> **यत्र यत्र चित्तं तत्र तत्र गणः।**  
> *yatra yatra cittaṃ tatra tatra gaṇaḥ* —  
> “Wherever there is awareness, there is a gaṇa.”

---

### 🔖 Summary

- **Mantra ID:** `gananiti/shashtra/gan`  
- **Meaning:** contextual being or collective capable of meaning-making.  
- **Essence:** identity exists only within context; there is no global namespace.  
- **Function:** binds *mantras*, *mats*, and *śāstras* to conscious agents while preserving privacy and multiplicity.

---
