# Web Scraping
## Notice
It is possible that GitHub fails to display Jupyter Notebooks. Should such circumstances arise, please refer to ***Part 4. Steps*** listed below for code samples.

## Part 1. Objective
Extract historical prices of each commodity listed on the website http://www.stockq.org/ and integrate the price data of each commodity by plotting a grid of line charts.

## Part 2. Data
<br>
<div align=center><img src="https://github.com/lclh813/Parser/blob/master/Pic/2_Data.png"/></div>
<br>

## Part 3. Outline
### 3.1. Web Scraping
- Extract data from web pages.
- Tool: Python ```requests``` ```BeautifulSoup```

### 3.2. Reshape Dataframe
- Since prices differ enormously from one commodity to another, it is easier to make a comparison within a group of datasets having similar means than to make an overall assessment.   
- Tool: Python ```concat``` ```itertools``` 

### 3.3. Data Visualization
- Plot a grid of line charts and default legend items as muted to better focus on the commodity that is of interest.
- Tool: Python ```Bokeh```

## Part 4. Steps
> [***Complete Code***](https://nbviewer.jupyter.org/github/lclh813/Parser/blob/master/6_CompleteCode.ipynb)
#### [Step 1. Import Library](https://nbviewer.jupyter.org/github/lclh813/Parser/blob/master/1_ImportLibrary.ipynb)
#### [Step 2. Web Scraping](https://nbviewer.jupyter.org/github/lclh813/Parser/blob/master/2_WebScraping.ipynb)
#### [Step 3. Clean Dataset](https://nbviewer.jupyter.org/github/lclh813/Parser/blob/master/3_CleanDataset.ipynb)
#### [Step 4. Rearrange Dataframe](https://nbviewer.jupyter.org/github/lclh813/Parser/blob/master/4_ReshapeDataframe.ipynb)
#### Step 5. Data Visualization
[5.1. Interactive Line Chart: Code](https://nbviewer.jupyter.org/github/lclh813/Parser/blob/master/5_DataVisualization.ipynb)  
[5.2. Interactive Line Chart: Chart](https://lclh813.github.io/Web_Scraping/5_InteractiveLineChart.html)
