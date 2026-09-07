# Frenkisk

A reconstruction of **Merovingian Frankish** — the language spoken at the court
of Clovis and Childebert around 550, of which neither a running text nor a
grammar survives. It is built to serve as a **translation target**.

⚠ **To see what it looks like, open
[`frenkisk-specimen.md`](frenkisk-specimen.md) first** — four short texts with
their originals alongside. Each was translated by **two readers working
separately**, who had nothing but the three delivered files; what appears there
is what both arrived at, word for word.

⚠ **For the full description — script, sound laws, noun and verb inflection,
syntax, method, limits — see [`frenkisk-paper.pdf`](frenkisk-paper.pdf)**
(14 pages, 5 figures).

---

## To translate a text — this is all you need to know

**Hand over these three files, and nothing else:**

| file | what it is | how it is read |
|---|---|---|
| **[`frenkisk-kit-translator.md`](frenkisk-kit-translator.md)** | the grammar | **is read** — it carries a reading map at its head, with line numbers |
| **[`frenkisk-dictionary.md`](frenkisk-dictionary.md)** | the dictionary | **is queried**, not read |
| **[`frenkisk-index.md`](frenkisk-index.md)** | the index into Frenkisk | a **lead**, never an answer: always go back to the entry |

### The brief — copy it as it stands

```
Hello — I have reconstructed a language, Frenkisk (Merovingian Frankish,
around 550). Everything is in this folder:

<path to the folder>

The three files to use:

- frenkisk-kit-translator.md — the grammar
- frenkisk-dictionary.md — the dictionary
- frenkisk-index.md — the index into Frenkisk

Could you translate this text for me?

> <your text here>

Use only those three files, open nothing else in the folder, and do not
invent forms from what you know of Old Saxon or Old High German.

⚠ Above all, never reach for Old English. It is close enough to look
helpful and it is the one witness this language forbids.

Give me the translation, and if anything blocked you or you had to
guess, tell me in a few lines at the end.
```

⚠ **The brief is short on purpose.** A long one was tried and improved nothing:
the discipline lives in the files, not in the instruction.

---

## The state of the language

| | |
|---|---|
| lemmas | **1746** |
| index entries | 3848 |
| nouns with a settled class / nouns | 347 / 982 |
| verbs with four principal parts / verbs | 210 / 229 |
| reference scene covered | **194 words out of 196** |
| cases declared open | 32 |
| automatic controls passing | **35 / 35** |

⚠ **This repository is being migrated to English.** The grammar, the glosses and
the etymological notes were written in French; the change is under way and
measured at each step by a dedicated control. Until it completes, parts of the
delivered files are still in French. The figure above for the reference scene is
a coverage of **French** vocabulary and will be re-measured on an English scene.

---

## What this repository does not contain

**It publishes the kit, not the workshop.**

The paper and [`STATE.md`](STATE.md) describe source registers, automatic controls
and 75 rounds of blind translation. **Those pieces are not here**: the delivered
files are generated from them, but the tooling, the working journals and the
copyrighted third-party sources stay outside the repository.

Two consequences, stated plainly:

- the paper's figures are **not verifiable** from this repository alone — they
  are reported here, not reproducible here;
- the delivered files are not to be corrected by hand. They are **generated**; a
  correction made here would be overwritten at the next pass.

---

## What this is, and what it is not

Frenkisk fills its gaps **under discipline** — a declared, domain-dependent
hierarchy of witnesses, dated rulings, open cases left open rather than quietly
filled. **But it does fill them.**

> This is a **historically anchored conlang**, not a scholarly reconstruction.

The places where it had to choose are written out, one by one, in
[`STATE.md`](STATE.md).

⚠⚠ **Old English is never admitted as support.** Typologically it sits too
close: leaning on it would make an Ingvaeonic language out of one that is not.
This warning matters more, not less, for readers working in English — the
nearest wrong answer is always the easiest one to reach.

---

## Licences

| | |
|---|---|
| [`LICENSE`](LICENSE) | **MIT** — the tooling (not published in this repository) |
| [`LICENSE-CONTENT`](LICENSE-CONTENT) | **CC BY-SA 4.0** — the language, the texts and the kit |

Copyrighted third-party sources (grammars under copyright, archival
photographs, CC BY-NC-ND transcriptions, laboratory databases) have never been
committed to this repository, at any point in its history.

> *A serious project does not distribute its sources: it distributes the path
> that leads to them.*
