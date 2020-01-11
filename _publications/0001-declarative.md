---
title: "Embedding Learning for Declarative Memories"
collection: publications
permalink: /publication/0001-declarative
excerpt: '
<p align="left">
  <img width="500" height="" src="/images/0001-declarative.png">
</p>'
date: 2017-05-28
venue: 'Published in ESWC 2017'
---
The major components of the brain’s declarative or explicit memory are semantic memory and episodic memory. Whereas semantic memory stores general factual knowledge, episodic memory stores events together with their temporal and spatial contexts. We present mathematical models for declarative memories where we consider semantic memory to be represented by triples and episodes to be represented as quadruples i.e., triples in time. E.g., (Jack, receivedDiagnosis, Diabetes, Jan1) states that Jack was diagnosed with diabetes on January 1. Both from a cognitive and a technical perspective, an interesting research question is how declarative data can efficiently be stored and semantically be decoded. We propose that a suitable data representation for episodic event data is a 4-way tensor with dimensions subject, predicate, object, and time. We demonstrate that the 4-way tensor can be decomposed, e.g., using a 4-way Tucker model, which permits semantic decoding of an event, as well as efficient storage. We also propose that semantic memory can be derived from the episodic model by a marginalization of the time dimension, which can be performed efficiently. We argue that the storage of episodic memory typically requires models with a high rank, whereas semantic memory can be modelled with a comparably lower rank. We analyse experimentally the relationship between episodic and semantic memory models and discuss potential relationships to the corresponding brain’s cognitive memories.

[Download](https://www.dbs.ifi.lmu.de/~tresp/papers/BrainMemoryV3.pdf)
