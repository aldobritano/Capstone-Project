# Capstone-Project

# Web-Scrapping using Beautifulsoup

This project was developed as a form of final project for a bootcamp in Indonesia called algoritma. Here we will also use a simple dashboard flask to display our scrap and visualization results

## Dependencies

Make sure to install the following libraries:

- beautifulSoup4
- pandas
- flask
- matplotlib

Or simply install requirements.txt in the following way

```python
pip install -r requirements.txt
```


## What You Need to Do

* Please try scraping using `beautifulsoup` on the notebook first.
* The tag information you want to get can be adjusted.

```python
 main_webpage = soup.find(____)
 box_movie = soup.find_all(___)
```

* Fill in this section to save the information that has been successfully obtained into a dataframe.

```python
df = pd.DataFrame(name of your tupple, columns = (name of the columns))
```


### Data Resource

1. Data for films released in 2019 from `imdb.com/search/title/? Release_date = 2019-01-01,2019-12-31`

     
     
