# UFO Sightings Analysis
Comparing United States UFO sightings before and after the start of the Covid-19 pandemic.

the full report can be accessed on UFO_Anlysis_Full_Report.pdf in the repository and the jupyter notebook containing the code that powered the analysis is named UFO_Analysis.ipynb also contained in the main directory. 

The python notebook includes the script in the beggining used to webscrape the data from the National UFO reporting center data base at https://nuforc.org/webreports/ndxevent.html. The script takes a very long time so it is recomonded to skip this step, comment out the code and use the data file csv contained in the directory of this repository.


### Prerequisites

In order to do this analysis the following libraries were used:

* numpy
* pandas
*textblob
*NLTK
* matplotlib
* statsmodels.api
* scipy.stats
* sklearn.preprocessing
*BeautifulSoup

Enter the following into the terminal:
```


pip install numpy
pip install pandas
pip install matplotlib
pip install statsmodels
pip install scipy
pip install sklearn
pip install NLTK
pip install bs4


```

### The Data  


* Data is from the Nation UFO Reporting center database https://nuforc.org/.

## Author

* **John Cook** - *Initial work* - [johngncook](https://github.com/johngncook)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
