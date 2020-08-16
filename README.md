# urbandata

![alt text](https://github.com/Guilhermegcz/urbandata/blob/master/images/capa.jpg)  

The project born from the desire to use data for urban analysis. The main guide is comparing commercial places and everything around an apartment with its price, to rent or to buy.

## tools
data: Python, Jupyter Notebook, Pandas, BeautifulSoup, Selenium, Scikit-learn, Lightgbm, API places   
images: Autocad, Photoshop, Indesign  

## data source
- buying apartments: Loft - https://loft.com.br/  
- rent apartments: Quinto Andar - https://www.quintoandar.com.br/  
- places: Google places API   

## web scraping
It starts with selecting neighborhood and scraping on Quinto Andar and Loft the apartaments who is available to rent or buy. Then with google places api, scraping urban info about the area arround the apartment.

![alt text](https://github.com/Guilhermegcz/urbandata/blob/master/images/mapa-pontos-image.gif)  


## data cleaning
From the raw data, it starts the data cleaning  removing duplicate lines, columns that will not be used in the analysis and outliers.

## analysis
First step is check the  proximity of the places in relation to the apartment, then separate places by categories and quantify those. After that check the outliers and apply regression models to compare places variables with apartment prices

## city scale
![alt text](https://github.com/Guilhermegcz/urbandata/blob/master/images/mapa-google.gif)  

## model
![alt text](https://github.com/Guilhermegcz/urbandata/blob/master/images/regressor-model2.jpg)


## insights and results
relationship between apartments in different neighborhoods
![alt text](https://github.com/Guilhermegcz/urbandata/blob/master/images/analysis-correlation.jpg)


![alt text](https://github.com/Guilhermegcz/urbandata/blob/master/images/analysis-correlation-df2.jpg)


simulation including new variables
![alt text](https://github.com/Guilhermegcz/urbandata/blob/master/images/minhocao.gif)

## issues
model can be improved to get a better projection of values  

## future resolutions
Search for more places variables. Check the influence of urban conditions such as topography, flooding.   
Check if the value of places can influence the price of the apartment.   
Analyze the transformation of neighborhoods with the opening of new establishments.



