## Supplemental Material

An academic publication's supplemental material is that ill-defined thing you throw all of the extra
content that you couldn't fit into your original submission. E.g., extra analyses, dope videos, all
of your raw data files, source code, *et cetera*.
As a computer scientist, including the source code used to conduct my experiments is a critical step
toward ensuring that my work is reproducible.

During my tenure as a graduate student, I've learned that through the combined powers of public GitHub
repositories and Zenodo, I can include as much supplemental material as I'd like with any publication,
regardless of the publication's venue.
In fact, I see no excuse for _any_ academic publication that leans on software not having supplemental
material (e.g., source code and data at a minimum).

### Why write supplemental material?

- Integrity and reproducibility
  - process of cleaning/writing a guide => another time to notice and fix mistakes
    - e.g., For a previous paper, I noticed bug in control
- Additional content
  - Extra analyses
  - Exploratory experiments

### How to have supplemental material for anything

I use two services to include & reference supplemental material: GitHub and Zenodo.
You'll need an account on both, and you'll need to have

Make GitHub repository.

Turn Zenodo on for your GitHub repository.

Put stuff in the repository.

Make a release on GitHub, which tells Zenodo to generate a DOI. Pro tip: you can export the citation
from zenodo to your favorite reference format (todo image).

Cite your repository

### Writing good supplemental material

![spidermeme](./2020-03-27-media/spiderman.jpg)

- Hold your reader's (and future you's) hand.
- Make things web-accessible
  - github pages
  - R markdown (ipython => html)
