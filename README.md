# Multivariate Data Visualization with R
This content is based on the course of [Udemy](https://www.udemy.com/course/multivariate-data-visualization-with-r/?utm_source=adwords&utm_medium=udemyads&utm_campaign=R_v.PROF_la.EN_cc.ROW_ti.7432&utm_content=deal4584&utm_term=_._ag_85479003034_._ad_395185643400_._kw__._de_c_._dm__._pl__._ti_dsa-774930037369_._li_1031424_._pd__._&matchtype=b&gclid=CjwKCAiAzJLzBRAZEiwAmZb0ann4PbsIk-XaAmra_VSWqObNtfuL62xemPGA7qrm1gPyrwSU-hVVWxoCeOMQAvD_BwE)

Graphically depict visual 2D, 3D, 4D (and so on) relationships that exist in multivariate data sets.

![alt text](https://github.com/pegadadigital/Multivariate-Data-Visualization-R/blob/master/Images/1.png "Img1") ![alt text](https://github.com/pegadadigital/Multivariate-Data-Visualization-R/blob/master/Images/2.png "Img2")

### Starting Docker container

The project has a **Docker** folder with composer yaml file based on [stefanproell](https://github.com/stefanproell/jupyter-notebook-docker-compose) scripts. Follow the instructions bellow to start the container:
* Generate the password token and put it in **.env** file:\
`generate_token.py -p S-E-C-R-E-T` 
* Generet cert file or use the one in SSLCERT folder:\
`openssl req -x509 -nodes -newkey rsa:2048 -keyout jupyter.pem -out jupyter.pem`
* Adapt **.env** variables, alter variables directories:
    * LOCAL_WORKING_DIR
    * ACCESS_TOKEN
    * PORT
    * LOCAL_DATASETS
    * LOCAL_MODULES
    * LOCAL_SSL_CERTS
* Start the container:\
`docker-commpose up --build`

### Visualization

The **Notebook** folder has the source files in Jupyter:
* Introduction to Lattice and to Trellis Graphics Chapter 1.ipynb
 1. Histogram
 2. Kernel Density Plot
 3. Superposition
 4. Trellis Object
 5. Functions in lattice
 6. Summary figures functions
 
* Introduction to Lattice and to Trellis Graphics Chapter 2.ipynb
 1. Dimension and phisical layout
 2. Aspect Ratio
 3. Layout
 4. Grouped Displays
 5. Annotation: Captions, Labels and Legends
 6. Scales and axis
 7. The Panel Function
 8. Summary figures functions
 
* Introduction to Lattice and to Trellis Graphics Chapter 3.ipynb
 1. densityplot
 2. histogram
 3. qqmath
 4. ecdfplot
 5. qq
 6. bwplot
 7. stripplot

* Multiway Tables and Scatter Plots Chapter 4.ipynb
 1. dotplot
 2. barchart
 3. xyplot
 
* Multiway Tables and Scatter Plots Chapter 5.ipynb - Scatter Plot
* Trivariate Displlays Chapter 6.ipynb