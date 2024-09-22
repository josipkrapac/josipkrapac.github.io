---
layout: post
author: Josip Krapac
---

# WIP

## Data acquisition
## Data formats
- [SMILES](https://en.wikipedia.org/wiki/Simplified_Molecular_Input_Line_Entry_System) used for representig molecules
- [FASTA](https://en.wikipedia.org/wiki/FASTA_format) used for representing amino-acid or nucleotide sequences
- The rest start from [here](https://www.perplexity.ai/search/what-file-formats-are-used-for-3c.x9TLBS_abC0Wm6hN7aQ)

## Tasks
### Structure and properties prediction
The assumption in this case is that we have a pool of candidates whose structure and properties we want to predict. 

Best results are obtained using quantum mechanical simulations, which capture the problem at the level of atoms, but these are computationally complex and therefore slow. 

The goal of this group of methods is to achieve result as close possible to more precise ones, by employing ML methods that are orders of magnitude faster. This enables exploration of an exponentially bigger pool of candidates in the same amount of time, or directed search by sequentially exploring the space of candidates, adding batches of candidates to the pool.
### Sequence / composition design
We distinguish between the methods that start from an existing object and modify it so the modified object has structure and function closer to the target one, and de novo methods that don't start from an existing object.
#### Template-based design
#### Rational design
This group of methods assumes the knowledge about relationships between the specific initial sequence that describes the object and its structure and function to guide sequence changes that yield the target sequence whose structure or function are close to target one. 
#### Directed evolution
This group of methods mimics evolution, exploring the space of sequences without guidance. It's more time consuming, but assumes less.
#### De novo design
Instead of starting from an existing candidate, de novo design starts from scratch, starting from target structure and properties and a model that is constrained by fundamental physical and chemical principles that is used to produce a set of candidates with target properties.

### Courses and materials 
- [Biochemistry 1 @ MIT](https://ocw.mit.edu/courses/5-07sc-biological-chemistry-i-fall-2013/)
- [Biochemistry 2 # MIT](https://ocw.mit.edu/courses/5-08j-biological-chemistry-ii-spring-2016/)
- [Open Catalyst Project](https://opencatalystproject.org/)
- ["Fake it until you make it? Generative De Novo Design and Virtual Screening of Synthesizable Molecules"](https://chemrxiv.org/engage/chemrxiv/article-details/64ad5354ba3e99daefe70a18)