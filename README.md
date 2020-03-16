![baniere](https://user-images.githubusercontent.com/61732964/76750069-e512aa00-677d-11ea-8baa-ad09ec2819b3.png)

BATWOMAN
========================================================


BATWOMAN (BATtery code for WOrds/numbers Mining and ANalysis) is an text mining tool which allows to determine if certain electrodes/cells features are reported in scientific articles for both Lithium- and Sodium-ion batteries and to calculate, throughout the Shannon Entropy, the complexity to recover them. Furthermore, it enables to classify the values associated to these keywords to either exact or range of values.

Please, do not hesitate to discover the team of researchers behind the library and also the ARTISTIC project
involved : [ARTISTIC](https://www.u-picardie.fr/erc-artistic/?L=0)


Setup
========================================================
We ask you to get a virtual environment such as **conda**. Go to their webpage and [download](https://www.anaconda.com/distribution/)
it. All dependencies will be installed on your environment.

Note that you need to follow the way below to install BATWOMAN :

1. Be sure you have the Python version 3.7.
2. Following Python libraries used to be already installed : tika, nltk, pdfminer.
3. Download all necessary ressources from nltk. Open a Python shell and launch these commands :

```python
import nltk
nltk.download()
```
Then click on 'download' inside the installation window.

From this starting point, you can install the package with :
```python
pip install BATWOMAN
```

or with the setup.py :

1. Clone the repository
2. Open a terminal into the directory at the root where the **setup.py** file is located,
and launch :

```python
python setup.py install
```

Make sure all libraries required are installed with the right version.
In the case python errors occur, please upgrade the packages indicated by :


```python
pip install --upgrade [name_of_package]
```
or
```python
python -m pip install --upgrade [name_of_package]
```

Testing dependencies
========================================================

To use tika library properly, you need to get Java 7+ installed on your system. 
If you meet connexion's issues for tika server (especially with Windows), please download manually a tika-server.jar file like the following
``tika-server-1.19.jar``. then open Git bash and launch in your working folder :
```
java -jar tika-server-1.19.1.jar
```

A disconnected server is now running. You can now launch again your code for the extraction of PDF.

Example
========================================================


There is a notebook as example providing what the library is able to do. Check it 
directly on the Github page, or with [Jupyter](https://jupyter.org/install) on your own session.

Please note, due to rigth restrictions, all pdf for the notebook are not available.
 That is why we recommand you to test functions on your own.


 Authors
 ========================================================
  - **Hassna EL-BOUSIYDY** , ALISTORE PhD student
  
 Contributing 
========================================================

Pull requests are not allowed. For more informations about the library, please
 contact the authors.
 Do not hesitate to ask them if inappropriate bugs occur.
 
 
 License
========================================================

This project is licensed under the **Licence PINE**

Contributors
========================================================
@helbousiydy, @MarcDuquesnoy, @teo-lombrado-LRCS, @primo-emiliano