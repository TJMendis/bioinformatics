# Algorithms for DNA Sequencing (JHU)

Notebooks following Course 3 of the *Genomic Data Science* specialization on Coursera, taught by Dr. Ben Langmead at Johns Hopkins University.

The course covers algorithms for processing DNA sequencing data — exact and approximate string matching, indexing, and alignment — built up from first principles. My notebooks here are my own implementations following the lecture material, with reference implementations from Dr. Langmead's openly published lecture code included for comparison where relevant.

**Source materials:**
- [Course on Coursera](https://www.coursera.org/learn/dna-sequencing)
- [Dr. Langmead's teaching site](https://www.langmead-lab.org/teaching.html)
- [Lecture notebooks GitHub](https://github.com/BenLangmead/ads1-notebooks)

## Notebooks

| File | Topic |
|------|-------|
| `k-mer_indexing.ipynb` | k-mer indexing (dictionary and sorted-list with `bisect`) |
| `bm_preproc.py` | Dr. Langmead's reference `BoyerMoore` class (preprocessed bad-character and good-suffix tables) |
| `approximate_matching.ipynb` | Naive approximate matching |
| `edit_distance.ipynb` | Edit distance — recursive formulation |
| `edit_distance_dp.ipynb` | Edit distance — dynamic programming |
| `global_alignment.ipynb` | Global alignment with weighted edit distance |
| `overlap_method.ipynb` | Pairwise overlap detection between reads |
| `overlap_graph.ipynb` | Overlap graph construction |
| `shortest_super_string.ipynb` | Shortest superstring — brute-force exploration |
| `shortest_common_super_string.ipynb` | Shortest common superstring |
| `scs_greedy_algorithm.ipynb` | Greedy algorithm for shortest common superstring |
| `de_bruijn_graph.ipynb` | De Bruijn graph construction from k-mers |

## Note on academic integrity

These notebooks contain only material from lecture videos and publicly available course content. Graded programming assignments and quiz solutions are deliberately not committed to this repository while I am enrolled in the course. See the [main README](../README.md) for full details.

---

## Course certificate

Completed May 27, 2026. [Verify on Coursera](https://coursera.org/verify/CQ6VXVD300AW).

<img src="certificate.png" alt="Algorithms for DNA Sequencing certificate" width="700">
