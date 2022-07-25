# web-scraping
1:-Read excel file with pandas and put that into pandas dataframe
  df=pd.read_csv(f"url")
  
2:-Scrape data from the url's, which are extracted through the given google spreadsheet and append that to a new dataframe.

3:-View the top 100 rows and drop null values if needed.

4:-Convert that dataframe into json file.
df2 = Product.to_json(orient = 'columns')
