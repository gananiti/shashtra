# 📜 मत  
> *mat* — `mat` — (directed expression or stance linking giver, mantra, and receiver)

---

## 1. Nāma (Identity)

| Bhāṣā (भाषा) | Diacritic | ASCII | Bolī |
|---------------|------------|--------|------|
| मत | *mat* | `mat` | stance / declaration / directed opinion |

---

## 2. Uddeshya (Purpose)

A **mat** is the **directed expression of a being (gaṇa)** about a particular **concept (mantra)**, addressed toward one or more **receivers (ādātṛ)**.  
It captures **how** one consciousness regards an idea, **for whom** that stance is declared, and **why**.

Formally:
> **दातृ → मन्त्र → मन्त्र–श्रेणी → आदातृ**  
> *dātṛ → mantra → mantra-śreṇī → ādātṛ*  
> *(giver → subject-mantra → expressive-sequence → receiver)*

Every mat exists in a context (*śāstra*).  
It may express belief, advice, instruction, agreement, rejection, or silence toward a *mantra*.

Examples in human terms:
- A nation’s **law**: a mat from the state to its citizens.  
- A company’s **policy**: a mat from management to employees.  
- A person’s **habit or belief**: a mat from self to self.  
- A friend’s **advice**: a mat from one gaṇa to another.  

---

## 3. Siddhānta (Principle)

A *mat* always involves **four dimensions**:

| Sanskrit term | Transliteration | ASCII | Meaning |
|----------------|-----------------|--------|----------|
| **दातृ** | *dātṛ* | `datr` | the giver — the gaṇa expressing the mat |
| **मन्त्र** | *mantra* | `mantra` | the conceptual subject of this mat |
| **मन्त्र–श्रेणी** | *mantra-śreṇī* | `mantra_shreni` | sequence of mantras forming the expression (the “what I feel / command / believe”) |
| **आदातृ** | *ādātṛ* | `aadatr` | the receiver or intended field — who or what this mat is for |
| **निर्माणकाल** | *nirmāṇakāla* | `nirmanakala` | moment of declaration |
| **पूर्वमत / कारण** | *pūrva-mata / kāraṇa* | `purvamat / karana` | optional: reference to a previous mat and reason for change |

A *mat* can be about **oneself**:  
> “I (dātṛ) am going to wake up early (mantra), and I say this to myself (ādātṛ = same gaṇa).”

Or it can be about others:  
> “I (Amit) recommend you (ādātṛ = developers) wake up early (mantra).”

Or about a group:  
> “This company (gaṇa) expects all members (ādātṛ = team) to document their work (mantra).”

---

## 4. Rūpa (Canonical Folder Structure)

```
gananiti/shashtra/mat/
├── README.md          ← Bhāṣā definition
├── README.en.md       ← Bolī translation
├── yantra.svg         ← pictogram symbolizing flow of intent
├── chitra.json        ← relational mapping (gaṇas ↔ mantras)
└── anurag.ogg         ← aural motif of expression
```

In *Bhūmi*, mats will be stored in the **mat-table**:

```sql
CREATE TABLE mat (
    datr TEXT,               -- giver (gaṇa)
    mantra TEXT,             -- subject of stance
    mantra_sequence TEXT,    -- expression (sequence of mantras)
    aadatr TEXT,             -- receiver (gaṇa / field)
    purvamat TEXT,           -- optional: previous mat reference
    karana TEXT,             -- optional: reason (mantra-sequence)
    nirmanakala INTEGER      -- time of declaration
);
```

---

## 5. Vyākhyā (Explanation)

### 5.1. Essence

A *mat* is **not static data** but an *act of communication*.  
It is the process by which **conscious intent becomes shareable**.  
Each mat can generate reactions — other mats — in an ongoing *mat-gadana* (exchange and refinement of stances).

### 5.2. Mat about self

A person may give a mat to themselves:
```yaml
mat:
  datr: "gan:amitu"
  aadatr: "gan:amitu"
  mantra: "wake_up_early"
  mantra_sequence: ["intend", "to_try", "daily"]
```
> “I intend to try waking up early every day.”

### 5.3. Mat toward others

```yaml
mat:
  datr: "gan:amitu"
  aadatr: "gan:developers"
  mantra: "wake_up_early"
  mantra_sequence: ["recommend", "strongly"]
```
> “I highly recommend developers wake up early.”

### 5.4. Mat as law or policy

```yaml
mat:
  datr: "gan:parliament.india"
  aadatr: "gan:citizens.india"
  mantra: "pay_taxes"
  mantra_sequence: ["must", "comply"]
```
> “All citizens must pay taxes.”  
A *law* is simply a mat declared within a legal śāstra.

---

## 6. Dharma (Invariants)

1. **Contextuality:** every mat belongs to a śāstra and is valid only therein.  
2. **Directedness:** mats always flow from *dātṛ* toward *ādātṛ*.  
3. **Subject-specificity:** each mat explicitly references the mantra it concerns.  
4. **Multiplicity:** different gaṇas may issue different mats about the same mantra.  
5. **Evolution:** new mats can supersede old ones; reasons for change are recorded as *kāraṇa*.  
6. **Dialogue:** a mat received may generate a response — acceptance, rejection, modification, or silence — forming *mat-gadana*.

---

## 7. Saṃvāda (Relations)

| Related Mantra | Role |
|-----------------|------|
| [`mantra`](../mantra/README.md) | the concept or rule being discussed |
| [`gan`](../gan/README.md) | giver and receiver of mats |
| [`shashtra`](../shashtra/README.md) | contextual field |
| [`nama-chatushtaya`](../nama-chatushtaya/README.md) | naming convention |
| `gananiti/shashtra/matdan` *(future)* | act of giving a mat |
| `gananiti/shashtra/matgadana` *(future)* | process of dialogue between mats |

---

## 8. Dṛṣṭi (Mat-gadana Dynamics)

Consider the mantra **“wake up early.”**

1. **Amit** (`gan:amitu`) gives mat:  
   > “Everyone should wake up early.”  
2. **Ekta** (`gan:ekta`) responds with mat:  
   > “Ignore this mat for now.”  
3. **Siddhant** receives multiple such mats and later declares:  
   > “Reconsidering earlier; I now think waking early helps focus.”  

Each of these is a *mat*.  
Together they form a **mat-gadana** — a network of evolving stances through which meaning matures.

---

## 9. Antarmukhya (Inner Commentary)

The *mat* is how **truth circulates** — not as absolute decree but as conversation.  
A *mantra* is static awareness; a *mat* is awareness in motion.  
As *mats* accumulate, they build shared worlds of meaning — families, companies, societies, cultures.

No single mat is final; every mat invites a reply.  
The endless flow of mats among gaṇas is what makes *Gananīti* alive.

---

## 10. Closing Śloka

> **दातृमन्त्रश्रृङ्खलया आदातृं प्रति प्रवर्तते चेतनप्रवाहः स मतः।**  
> *dātṛ-mantra-śṛṅkhalayā ādātṛṃ prati pravartate cetana-pravāhaḥ sa mataḥ.*  
> “That conscious flow which moves from giver to receiver through a chain of mantras — that is a mat.”

---

### 🔖 Summary

- **Mantra ID:** `gananiti/shashtra/mat`  
- **Meaning:** a directed expression or stance connecting giver, subject, and receiver.  
- **Essence:** *dātṛ → mantra → mantra-śreṇī → ādātṛ* — opinion, policy, or rule within context.  
- **Function:** the act through which consciousness interacts, evolves, and forms collective understanding.

---
