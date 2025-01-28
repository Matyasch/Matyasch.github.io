---
title: 'SNAP: Sequential Non-Ancestor Pruning for Targeted Causal Effect Estimation With an Unknown Graph'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tom Claassen
  - Sara Magliacane

date: '2025-01-27'
doi: ''

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: The 28th International Conference on Artificial Intelligence and Statistics
publication_short: AISTATS 2025

abstract: "Causal discovery can be computationally demanding for large numbers of variables. If we only wish to estimate the causal effects on a small subset of target variables, we might not need to learn the causal graph for all variables, but only a small subgraph that includes the targets and their adjustment sets. In this paper, we focus on identifying causal effects between target variables in a computationally and statistically efficient way. This task combines causal discovery and effect estimation, aligning the discovery objective with the effects to be estimated. We show that definite non-ancestors of the targets are unnecessary to learn causal relations between the targets and to identify efficient adjustments sets. We sequentially identify and prune these definite non-ancestors with our Sequential Non-Ancestor Pruning (SNAP) framework, which can be used either as a preprocessing step to standard causal discovery methods, or as a standalone sound and complete causal discovery algorithm. Our results on synthetic and real data show that both approaches substantially reduce the number of independence tests and the computation time without compromising the quality of causal effect estimations."

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: 'https://openreview.net/pdf?id=uyTL5Bvosj'
url_code: 'https://github.com/matyasch/snap'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:

---
