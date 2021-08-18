## FOOD MICRO

On this side you will find information on scripts, data and pipelines for working with microbiology data - in particular amplicon sequencing data such as 16s for bacterial characterization. 

There is both plug-n-play content for scientists new to data analysis of microbiome type data, but also more advanced tools. 

### Data analysis 

#### Bioinformatics FASTQ to dataset object

For details on how to process the fastq files please visit the websites [QIIME](http://qiime.org/) and [DADA2](https://benjjneb.github.io/dada2/tutorial.html/).

#### Getting data into R

Hawing the bioinformatic processed files in place, importing and establishing an phyloseq object in R is described here: [Import data](https://joey711.github.io/phyloseq/import-data.html)

#### Working with Microbiome data using R 

There are a bunch of tools available for handling microbiome data. The package phyloseq encaptulates functionallity covering most of what is needed, however, sometimes a you may want to do a tricky analysis or plot the results in a taylored way, and here you may need to enrich your pipeline with tools from associated packages. 
However, using phyloseq as core is very powerfull. The datails are can be found on the [phyloseq tutorial](https://joey711.github.io/phyloseq/index.html). 

#### Plug-n-play workflows using R

There are a few online tools by which the computation is done _elsewhere_ and hence do not require software installation.

- [Step by step guide for using a _webbased_ platform](https://github.com/jcame/MicrobiomeAnalyst_UCPH-FOOD)

However, if you do not want to be limited by functionallity, then use the more flexible tools as used in R. 

If you are new to R and Rstudio, then use a bit of time on getting familar with this progam. See for instance this [introduction](https://microucph.github.io/amplicon_data_analysis/html/Rstudio.html) and some [basic functionallity](https://microucph.github.io/amplicon_data_analysis/html/R.html). Furhter it is very good idea to get familiar with using [Rmarkdown](https://rmarkdown.rstudio.com/) files as this intergrates code, output, figures and your own narrative. 

- [Microbiome Data analysis](https://mortenarendt.github.io/MicrobiomeDataAnalysis/)
- [Microbiome Analysis](https://yanhui09.github.io/microbiome_analysis)
- [Amplicon Data analysis](https://microucph.github.io/amplicon_data_analysis/)
- [Comprehensive list of microbiome tools in R](https://microsud.github.io/Tools-Microbiome-Analysis/)

#### How to use the resources

After setting up R and Rstudio, copy-paste or download a work-flow and try it out on the data supplied with it. In this way, you will be able to reproduce the same results as presented in the tutorial. In the case there are troubles you will also be able to trouble shoot those. Most often it is a missing package or a copy-paste fault such as missing an ending parentesize. 

When the pipeline works, go through each step to make sure that you understand what is happening, and what the output tells you. 

After this, you are ready to exchange the input data to your own, by simply loading another dataset at the start of your script, and rename the relevant objects to match the tutorial. From here, you line by line execute the code on your own data, and make appropriate modifications if needed. For instance, the design might be names differently etc. 

### Data

Within the tutorial pages referenced above, there are access to public datasets, in addition we have these datasets from various projects

- dataset one
- dataset two 
- ...


## Student projects

We allways has a bunch of intersting research projects ongoing within food and health systems focusing on microbiology. If you are a master or bachelor student you can do your project as a part of one of our larger project, work on new questions on existing data, or go to the wetlab to produce your own data. Please see [the projects](https://food.ku.dk/english/research_at_food/research-by-section/microbiology-and-fermentation-research/) or contact one of the seniors in the section to get started.  

## People and organization

Microbiology in food and health is a research group under the [Department of Food Science](https://food.ku.dk/english/research_at_food/sections/microbiology/) at University of Copenhagen. 


