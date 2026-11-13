# Brain Cell Atlas Readers

Two single-file web pages that make published brain cell atlas tables readable.

- `human.html`: Human Brain Cell Cluster Reader. 31 superclusters, 461 clusters, 3,313 subclusters.
- `mouse.html`: Mouse Brain Cell Type Explorer. 34 classes, 338 subclasses, 1,201 supertypes, 5,322 clusters.
- `index.html`: landing page linking the two.

Each page is self-contained: the data are embedded in the file and no server is needed. Every value is copied from the authors' annotation tables. The pages assign no function to any cell group.

## Data and credit

Human reader

- Siletti K. et al., Transcriptomic diversity of cell types across the adult human brain. Science 382, eadd7046 (2023). https://doi.org/10.1126/science.add7046
- Tables: `cluster_annotation.xlsx`, `subcluster_annotation.xlsx`, `dissections.xlsx` from https://github.com/linnarsson-lab/adult-human-brain
- Label definitions: https://github.com/linnarsson-lab/auto-annotation-ah

Mouse explorer

- Yao Z. et al., A high-resolution transcriptomic and spatial atlas of cell types in the whole mouse brain. Nature 624, 317-332 (2023). https://doi.org/10.1038/s41586-023-06812-z
- Tables: WMB-taxonomy release 20231215 of the Allen Brain Cell Atlas, including `cl.df_CCN202307220.xlsx`; region names from Allen-CCF-2020.

## Licence

The Allen Brain Cell Atlas data are shared under CC BY NC 4.0 (attribution, non-commercial). Keep the credits above with any copy of these pages and do not use them commercially without checking with the data owners.

## Status

Draft for checking by the data authors. Corrections welcome through Issues.

Epistemic Systems Lab
