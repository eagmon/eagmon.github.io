---
layout: page
title: Selected Publications
permalink: /publications/
---

{% assign publications = "
  [
    {
      'authors': 'Skalnik, C. J., Cheah, S. Y., Yang, M. Y., Wolff, M. B., Spangler, R. K., ... Agmon, E., & Covert, M. W.',
      'year': '2023',
      'title': 'Whole-cell modeling of E. coli colonies enables quantification of single-cell heterogeneity in antibiotic responses.',
      'journal': 'PLOS Computational Biology',
      'link': 'https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1011232'
    },
    {
      'authors': 'Johnson, G. T., Agmon, E., Akamatsu, M., Lundberg, E., Lyons, B., Ouyang, W., ... & Horwitz, R.',
      'year': '2023',
      'title': 'Building the next generation of virtual cells to understand cellular biology.',
      'journal': 'Biophysical Journal',
      'link': 'https://www.cell.com/biophysj/pdf/S0006-3495(23)00236-9.pdf'
    },
    {
      'authors': 'Agmon, E., Spangler, R.K., Skalnik, C.J., Poole, W., Morrison, J.H., Peirce, S.M., and Covert, M.W.',
      'year': '2022',
      'title': 'Vivarium: an interface and engine for integrative multi-scale modeling in computational biology.',
      'journal': 'Bioinformatics',
      'link': 'https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btac049/6522109?login=true'
    },
    {
      'authors': 'Covert, M. W., Gillies, T. E., Kudo, T., & Agmon, E.',
      'year': '2021',
      'title': 'A forecast for large-scale, predictive biology: Lessons from meteorology.',
      'journal': 'Cell systems',
      'link': 'https://www.cell.com/cell-systems/pdf/S2405-4712(21)00200-3.pdf'
    },
    {
      'authors': 'Agmon, E., and Spangler, R.K.',
      'year': '2020',
      'title': 'A multi-scale approach to modeling _E. coli_ chemotaxis.',
      'journal': 'Entropy',
      'link': 'https://www.mdpi.com/1099-4300/22/10/1101'
    },
    {
      'authors': 'Macklin, D.N., Ruggero, N.A., Carrera, J., Choi, H., Horst, T.A., Mason, J.C., Sun, G., Agmon, E., DeFelice, M.M., Maayan, I., Lane, K., Spangler, R.K., Gillies, T.E., Paull, M.L., Akhter, S., Bray, S.R., Weaver, D.S., Keseler, I.M., Karp, P.D., Morrison, J.H., and Covert, M.W.',
      'year': '2020',
      'title': 'Simultaneous cross-evaluation of heterogeneous _E. coli_ datasets via mechanistic simulation.',
      'journal': 'Science',
      'link': 'https://science.sciencemag.org/content/369/6502/eaav3751.abstract'
    },
    {
      'authors': 'Agmon, E., Solon, J., Bassereau, P., and Stockwell, B.R.',
      'year': '2018',
      'title': 'Modeling the effects of lipid peroxidation during ferroptosis on membrane properties.',
      'journal': 'Scientific Reports',
      'link': 'https://www.nature.com/articles/s41598-018-23408-0'
    },
    {
      'authors': 'Agmon, E. and Stockwell, B.R.',
      'year': '2017',
      'title': 'Lipid homeostasis and regulated cell death.',
      'journal': 'Current Opinion in Chemical Biology',
      'link': 'https://www.sciencedirect.com/science/article/abs/pii/S1367593117300650'
    },
    {
      'authors': 'Agmon, E., Gates, A.J., and Beer, R.D.',
      'year': '2016',
      'title': 'The structure of ontogenies in a model protocell.',
      'journal': 'Artificial Life',
      'link': 'https://drive.google.com/open?id=0B6V70xlycys7YXlCT2ZpbUo1QVU'
    },
    {
      'authors': 'Agmon, E., Gates, A.J., Churavy, V. and Beer, R.D.',
      'year': '2016',
      'title': 'Exploring the space of viable configurations in a model of metabolism-boundary co-construction.',
      'journal': 'Artificial Life',
      'link': 'https://drive.google.com/open?id=0B6V70xlycys7a2dCWGdOMXplcm8'
    }
  ]
%}

{% for publication in publications %}
1. **{{ publication.authors }}** ({{ publication.year }}). {{ publication.title }} _{{ publication.journal }}_. [Available here]({{ publication.link }})
{% endfor %}
