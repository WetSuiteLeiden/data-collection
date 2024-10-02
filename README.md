# wetsuite-datacollect

A collection of code, currently in the form of notebooks, 
that were used to generate readymade datasets for the wetsuite project.

Depends on the core wetsuite development.


## Consider whether you want to do your own collection at all

This repository is partly here just be showing our work,
and might prove useful to you to create more custom datasets yourself.

At the same time, if you would wish to make a datasets that cover _everything_ of a type,
you may need to need to fetch tens of gigabytes in hundreds of thousands of items, 
and that will easily take weeks.
And then you have made yourself responsible to keep it up to date.
Which is absolutely doable, but it's an extra responsibility.

Point is that if one of our existing datasets suit your needs,
you can start using them today, even if they _don't_ have the most recent records. 

(And if it's only somewhat out of date, you may have some luck asking us to update.)

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
	
