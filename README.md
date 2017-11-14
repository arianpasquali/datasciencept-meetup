# Data Science Portugal Meetup (DSPT) 

## An exploratory data analysis

This is a pet project that aims to explore what is possible to do using public available data from the DSPT* community.
At this point I have explored the Meetup API* (https://www.meetup.com/).

Feel free to play with it, collaborate and expand it.

* Data Science Portugal (DSPT) is an informal community of data science enthusiasts created with the purpose of sharing knowledge and experience in the fields of data science, machine learning and artificial intelligence. For more info visit http://www.meetup.com/datascienceportugal.

* Meetup is a social network to organize meetups https://www.meetup.com/ 

### Map visualization

If you are running this notebook in your local jupyter environment you can install a special widget to plot maps inline.
In order to enable it inyour env follow these steps:

Using pip:

> $ pip install ipyleaflet
> $ jupyter nbextension enable --py --sys-prefix ipyleaflet

Using conda:

> $ conda install -c conda-forge ipyleaflet

If you have JupyterLab, you will also need to install the JupyterLab extension:

> $ jupyter labextension install jupyter-leaflet
