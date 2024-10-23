# wetsuite-datacollect

A collection of code, currently in the form of notebooks, 
that were used to generate readymade datasets for the wetsuite project.

This repository is mostly here to show our code for others to potentially use later.

**You may not need or want to run it at all**. That is...
* if your needs are met by a few dozen to a few hundred documents
  - then probably learn to search and fetch them specifically (these notebooks may mention how only in passing)
* if you absolutely need the current versions of everything: 
  - then probably learn to search and fetch them specifically (these notebooks may mention how only in passing)
* if you want to quickly test an idea on data, even if it's not all the latest data
  - then **keep on reading below**
* if your needs are "I want to throw a lot of text at a method", consider using our larger datasets
  - then probably look at the _results_ of these notebooks, namely the larger datasets
* if you want to create a _complete_ dataset for others to use
  - think about whether you want the responsibility for correctness and up-to-dateness
* if you want to create a smaller dataset for others for you or others to quickly start testing with
  - then **keep on reading below**


## Quick summary of each

### The things that have an API
- [api_koop_repos](api_koop_repos.ipynb)
- [api_koop_bwb](api_koop_bwb.ipynb) - fetches law text and metadata in XML form
- [api_koop_cvdr](api_koop_cvdr.ipynb)
- [api_koop_officielepublicaties](api_koop_officielepublicaties.ipynb)
- [api_rechtspraaknl_codes](api_rechtspraaknl_codes.ipynb)
- [api_rechtspraaknl_many](api_rechtspraaknl_many.ipynb)
- [api_tweede_kamer_part1_first_api_and_parties](api_tweede_kamer_part1_first_api_and_parties.ipynb)
- [api_tweede_kamer_part2_second_api_verslagen](api_tweede_kamer_part2_second_api_verslagen.ipynb)
- [api_tweede_kamer_part3_both_apis_kamerdossiers](api_tweede_kamer_part3_both_apis_kamerdossiers.ipynb)

### The things that have an API, partly
- [mixed_gemeentes](mixed_gemeentes.ipynb) - fetches municipality names and some further information into a more digestible form

### The things that we had to do some scraping for
- [web_kansspelautoriteit](web_kansspelautoriteit.ipynb)
- [web_raadvanstate_adviezen](web_raadvanstate_adviezen.ipynb)
- [web_woobesluit](web_woobesluit.ipynb)
- [web_internetconsultaties](web_internetconsultaties.ipynb)
- [web_eurlex](web_eurlex.ipynb)
	
