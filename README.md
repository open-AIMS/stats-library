# stats-library 

A collection of resources curated by the AIMS stats team.

[**View the library here!**](https://open-aims.github.io/stats-library/)



## Adding resources

To add resources to the library, you just need to update `stat_lib.bib` with the respective bibtex entry and push it back to Github. 

While it is fine (and probably preferrable) to include many bibtex fields, we only require the following fields for this Github Pages site to function properly. Please ensure you complete the following fields for each new resource:

```
@<resource type>{<bibtex ID>,
  author = {<author names>},
  title =	{<resource title>},
  year = {<YYYY>},
  doi =	{<DOI>},
  abstract = {<article abstract>},
  url =	{<link to resource online>},
  UPLOADER = {<your first name>}, 
  AIMS_URL = {<link to file on AIMS sharepoint>},
  NOTES = {<summary/notes/description/remarks about the resource>}
}
```

Note the custom fields in ALL CAPS - these will not be present in an ordinary bibtex entry and you will have to add them yourself. If you can't be bothered writing the notes, it would be good to at least have the abstract field present.

###  **Important!!** File access restriction

When copying the link to the resource on the AIMS sharepoint please ensure you restrict access to some option other than 'anybody with link' and that by sharing the file (even internally) you are not violating copyright or confidentiality. 

Please don't let this discourage you from adding resources to the library. If you are unsure/uncomfortable sharing the file, the link to the resource online (bibtex field `url`) is sufficient.

![](.resources/sharepoint_link_access.png)



### Example bibtex entry

```
@article{Kruschke2021,
  author = {Kruschke, John K.},
  title	= {Bayesian Analysis Reporting Guidelines},
  journal = {Nature Human Behaviour},
  year = 2021,
  volume = 5,
  number = 10,
  month	= {Aug},
  pages	= {1282–1291},
  issn = {2397-3374},
  doi	= {10.1038/s41562-021-01177-7},
  url	= {http://dx.doi.org/10.1038/s41562-021-01177-7},
  publisher = {Springer Science and Business Media LLC},
  UPLOADER = {Brendan},
  AIMS_URL = {https://aimsgovau-my.sharepoint.com/notareallink},
  NOTES = {A go-to guide for the robust reporting of Bayesian analyses.}
}
```

```
@book{McElreath2020,
  doi = {10.1201/9780429029608},
  url = {https://doi.org/10.1201/9780429029608},
  year = {2020},
  month = mar,
  publisher = {Chapman and Hall/{CRC}},
  author = {Richard McElreath},
  title = {Statistical Rethinking},
  abstract = {Statistical Rethinking: A Bayesian Course with Examples in R and Stan builds your knowledge of ...},
  UPLOADER = {Brendan},
  AIMS_URL = {},
  NOTES = {Presents a (somewhat) unified framework for statistical concepts. It is also accompanied by the author's free lecture series (https://github.com/rmcelreath/stat_rethinking_2023) which are awesome.}
}
```




## To Do: 

* Decide on the structure of notes (e.g. bullets separated by * or &) and implement their display in dropdown

* Currently the title, authors (last names) and notes are searchable. Should the abstract also be searchable?