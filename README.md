# homework 6 - string operations and APIs

## Instructions

1. Your final document should be an `.md` file (GitHub-flavored markdown) knitted from an R Markdown file. Create a folder called `/homework` where you will add the `.md` file, and a folder called `/src` where you will  place the `.Rmd` file and any other scripts you used to create the reports.

  In answering each of the questions for the assignment please include
  - the question as a header in your R Markdown report,
  - the raw code that you used to generate any tables, and
  - the top ten rows of the resulting `tibble`. (Do not include more than ten rows for any table in your report).

2. when you are done with your final `push` to this repo, submit the link to this repo on Canvas. (Make sure to `commit` your progress throughout the day, and `push` your progress at the end of each day.)



### Assignment items `[100 pts]`

**Part 1:** Use string operations to extract tweets from the following Twitter data from `@realdonaldtrump`: `load(url("http://varianceexplained.org/files/trump_tweets_df.rda"))`

After you load the `.rda` file, the `data.frame` object will be named `trump_tweets_df` and available in your R session.

Use string operations on relevant columns in the data to:

1. [`10 pts`] return a count of all tweets contain hash tags

2. [`10 pts`] return numeric values of all tweets (only numbers)

3. [`10 pts`] replace a word of your choice contained in all tweets with a new word of your choice

**Part 2:** Use the `APIs.R` script and refer to the [`blsAPI`](https://www.rdocumentation.org/packages/blsAPI/versions/0.2.1/topics/blsAPI) package to answer the following questions:

1. [`10 pts`] Can you change the industry code in the API URL so that you return data for Manufacturing layoffs only? Did the value of manufacturing layoffs increase or decrease each year?

2. [`10 pts`] Can you change the location code in the API URL you created to return manufacturing jobs so that you return data for New York state only? Did the value of manufacturing layoffs increase or decrease in New York each year?  

3. [`20 pts`] Refer to the section entitled, "What if there is no R package? Option #1: Manipulate URL directly". Can you change the term used in the New York Times article search API URL so that you return article data for hillary clinton?  How many TOTAL articles were returned by this API search?  

4. [`30 pts`] Find an API of interest to you.  Sign up for an API key if necessary. Describe the API concisely and make a single call on the API and return an example of the returned data here.
