Short introduction about reproducible research
==============================================

There is more and more talking about reproducibility in research, and the topic of **reproducibility crisis** is getting hot. Here is a `Nature article <https://www.nature.com/news/1-500-scientists-lift-the-lid-on-reproducibility-1.19970>`_ presenting a survey on the matter.

So what is reproducible research?
A research project is done in a reproducible manner if the experiment(s) conducted in the project can be replicated in the same conditions, and the same results as in the original study can be obtained.

The main factors determining if a project will end up as reproducible or irreproducible are the following:

- Organization of data and tools
- Documentation 
- Automation

Best practices for project organization
---------------------------------------

These are some recommendations for project organization:

1. Keep each project in its own directory, which is named after the project.
2. Create a **doc** directory for text documents associated with the project.
3. Keep raw data and metadata in a **data** directory, and files generated during cleanup and analysis in a **results** directory.
4. Source code for the project’s scripts and programs should stay in **src** directory, and downloaded or compiled programs should be kept in **bin** directory.
5. Name all files to reflect their content or function - simple but very important rule of thumb.


Good sources of information and knowledge
-----------------------------------------

This workshop focuses only on a couple of RStudio functionalities, but for deeper look at various other aspects of reproducibility in scientific research, you can check websites like `NBIS Reproducible research course <http://nbis-reproducible-research.readthedocs.io/en/latest/>`_, `R for Reproducible Scientific Analysis <http://swcarpentry.github.io/r-novice-gapminder/>`_, `R Notebooks <https://rmarkdown.rstudio.com/r_notebooks.html>`_, `Writing publications with R <http://www.geo.uzh.ch/microsite/reproducible_research/post/rr-r-publication/>`_

Now let's get started with RStudio and some very useful features it provides for reproducibility.
