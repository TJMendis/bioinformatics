# Algorithms for DNA Sequencing (JHU)

Notebooks following Course 3 of the *Genomic Data Science* specialization on Coursera, taught by Dr. Ben Langmead at Johns Hopkins University.

The course covers algorithms for processing DNA sequencing data — exact and approximate string matching, indexing, and alignment — built up from first principles. My notebooks here are my own implementations following the lecture material, with reference implementations from Dr. Langmead's openly published lecture code included for comparison where relevant.

**Source materials:**
- [Course on Coursera](https://www.coursera.org/learn/dna-sequencing)
- [Dr. Langmead's teaching site](https://www.langmead-lab.org/teaching.html)
- [Lecture notebooks GitHub](https://github.com/BenLangmead/ads1-notebooks)

## Notebooks

| Notebook | Topic |
|----------|-------|
| `BoyerMoore.ipynb` | My implementation of Boyer-Moore exact string matching from scratch — bad character rule, good suffix rule (cases A/B/C), and match-skip combined into a full algorithm |
| `boyer_moore_Lecturer_code.ipynb` | Dr. Langmead's reference `BoyerMoore` class, kept separately for comparison with my implementation |
| `k-mer_indexing.ipynb` | Dictionary-based k-mer index — building the index, query with lookup-then-verify |
| `k-mer_indexing_sorted_list.ipynb` | Sorted-list k-mer index using `bisect` for binary search lookup |

## Note on academic integrity

These notebooks contain only material from lecture videos and publicly available course content. Graded programming assignments and quiz solutions are deliberately not committed to this repository while I am enrolled in the course. See the [main README](../README.md) for full details.
