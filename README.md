[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Eumaeus/covid-data/master?filepath=index.ipynb)

# Personal COVID-19 Data and Model

This a project of my personal curiosity about COVID-19 and what context and perspective we can get from responsible, public data.

Data is drawn from:

- [The *New York Times*](https://github.com/nytimes/covid-19-data)
- [“Deaths and Mortality”, CDC](https://www.cdc.gov/nchs/fastats/deaths.htm)
- [“Stats of the State of South Carolina”, CDC](https://www.cdc.gov/nchs/pressroom/states/southcarolina/southcarolina.htm)
- [South Carolina Department of Health and Environmental Control (DHEC)](https://www.scdhec.gov/vital-records/parentage/sc-vital-records-data-and-statistics)
- [The Office of National Statistics, UK](https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/deaths/datasets/weeklyprovisionalfiguresondeathsregisteredinenglandandwales)
- [2019 Novel Coronavirus COVID-19 (2019-nCoV) Data Repository by Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19)

These notebooks use the [Almond kernel](https://almond.sh/).  You can run a notebook server with the Almond kernel using a docker container like this:

    docker run -it --rm -p 8888:8888 almondsh/almond:0.9.0

You can also work interactively with these notebooks on [mybinder.org](http://localhost:8888/?token=5a251f9b9c551ace50591064574607ab7550c59779a8984b).

If you have Jupyter Notebooks installed locally, with the Almond kernal, you can run this with:

    jupyter notebook

This work is based on that of [Neel Smith](https://github.com/neelsmith/nomisma-jupyter).

