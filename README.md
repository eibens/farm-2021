# FARM 2021

This repository contains links and public data related to our paper submission to [FARM 2021](https://functional-art.org/). 

- Waltz Generator: [Demo](https://isolin.github.io/farm-2021/waltz), [Output](files/waltz)
- Fragment Generator: [Demo](https://isolin.github.io/farm-2021/fragment), [Output](files/fragment), [Spec](spec/fragment/spec.pdf)
- Fragment Generator (extended): [Demo](https://isolin.github.io/farm-2021/fragment-x), [Output](files/fragment-x)
- [Files referenced in the paper](files/paper)

## Paper

- *Title*: Temporal-Scope Grammars for Polyphonic Music Generation
- *Authors*: *(anonymous for review process)*

**Abstract**: We present temporal-scope grammars for automatic composition of polyphonic music. In the context of this work, polyphony can refer to any arrangement of musical entities (notes, chords, measures, etc.) that is not purely sequential in the time dimension. Given that the natural output of a grammar is a sequence, the generation of sequential structures, such as melodies, harmonic progressions, and rhythmic patterns, follows intuitively and has already been explored in prior works. By contrast, we associate each musical entity with an independent temporal scope, allowing the representation of arbitrary note arrangements on every level of the grammar. With overlapping entities we can model chords, drum patterns, and parallel voices -- polyphony on small and large scales. We further propose the propagation of sub-grammar results through the derivation tree for synchronizing independently generated voices. For example, we can synchronize the notes of a melody and bass line by reading from a shared harmonic progression. 

