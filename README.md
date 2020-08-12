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


## The Steps

* Use scraping using `beautifulsoup` on the Jupyter notebook first.
* The tag information you want to get can be adjusted.

```python
 main_webpage = soup.find(____)
 box_movie = soup.find_all(___)
```

* Fill in this section to save the information that has been successfully obtained into a dataframe.

```python
df = pd.DataFrame(name of your tupple, columns = (name of the columns))
```


### Conclusion

In this project we can conclude that at
 https://www.imdb.com/search/title/?release_date=2019-01-01,2019-12-31 the most popular movies in descending order are as follows: 1.Joker, 2.Avengers:End Game, 3.Once upon a time in Hollywood, 4. Chernobyl, 5.Gisaengchung, 6. Knives Out, 7.1917
     
     
