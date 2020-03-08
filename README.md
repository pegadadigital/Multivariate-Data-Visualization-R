# Multivariate Data Visualization with R
This content is based on the course of [Udemy](https://www.udemy.com/course/multivariate-data-visualization-with-r/?utm_source=adwords&utm_medium=udemyads&utm_campaign=R_v.PROF_la.EN_cc.ROW_ti.7432&utm_content=deal4584&utm_term=_._ag_85479003034_._ad_395185643400_._kw__._de_c_._dm__._pl__._ti_dsa-774930037369_._li_1031424_._pd__._&matchtype=b&gclid=CjwKCAiAzJLzBRAZEiwAmZb0ann4PbsIk-XaAmra_VSWqObNtfuL62xemPGA7qrm1gPyrwSU-hVVWxoCeOMQAvD_BwE)

Graphically depict visual 2D, 3D, 4D (and so on) relationships that exist in multivariate data sets.

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
* Introduction to Lattice and to Trellis Graphics.ipynb
 1. Histogram
 2. Kernel Density Plot
 3. Superposition
 4. Trellis Object
 5. Functions in lattice
 6. Summary figures functions
 
