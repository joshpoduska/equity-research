##How to manage folders for collaboration

Managing projects can be difficult across teams.  It can even be difficult 
on your own machine – how many “Untitled.ipynb” files do you have on your machine 
right now??  Introducing a common folder structure and naming convention can go 
a long way towards making sure everyone on the team knows where to find things.  
It’s also a simple way to highlight the professionalism of your team’s work when 
you share it more broadly across an organization. 

One system you can use – and there are many – is something like [the structure 
used by SVDS].  It’s a great starting point but it might not fit every company.  
More important than which structure you choose, is that you choose one and 
stick to it. 

####Folder Naming Convention:
- **develop** (these are lab style notebooks, maintained by individuals)
- **deliver** (final analysis, code, presentations delivered to client and maintained by the team)
- **figures** (figures generated, or embedded in presentations, or deliverables)
- **src** (any modules & scripts created)
- **data** (any data projects, csv files, or DB connectors you create)


####File Naming Convention:
[ISO 8601 date]-[Data Scientist's initials]-[2-4 word description]

This works great because you can sort by date, search by data scientist, and 
quickly understand what the file is about.  





####Example Directory Structure:

- develop 
    - 2017-08-11-jm-credit-missing-data-analysis.ipynd
- deliver
    - probability-delinquency-rates.ipynb
    - training-validation-metrics.ipynb
- figures
    - delinquencies-vs-age.jpg
    - log-debt-income-ratio-vs-open-loans.png
- src
    - init.py
    - data-transformations.py
    - final-model-ensemble.py
- data
    - raw_data
        - cs-training.csv
        - cs-testing.csv
    - clean_data
        - test-data-clean.csv
        - train-data-clean.csv


[the structure 
used by SVDS]: https://svds.com/jupyter-notebook-best-practices-for-data-science/
