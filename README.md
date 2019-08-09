## Data merging and cleaning for the social pressure project

Files modifying the database

1. **[C_01_merge_sources.ipynb](C_01_merge_sources.ipynb)** : merges the 3 scraping rounds.

2. **[C_02_remove_scraped_strings_errors.ipynb](C_02_remove_scraped_strings_errors.ipynb)** : removes events scraped by error.

3. **[C_03_create_search_str_dates.ipynb](C_03_create_search_str_dates.ipynb)** : Creates a **string \_\_date** variable identifying the database events.

4. **[C_04_clean_text.ipynb](C_04_clean_text.ipynb)** : Creates a variable **text_clean** with the cleaned versions of the tweet texts.

5. **[C_05_tag_dup100.ipynb](C_05_tag_dup100.ipynb)** : Creates a variable **dup_100** with tweets repeated 100 and more times (_using the cleaned version of the tweets texts_)

6. **[C_06_clean_users_names_and_empty_tweets.ipynb](C_06_clean_users_names_and_empty_tweets.ipynb)** : Cleans users names and empty tweets

7. **[C_07_search_strings_not_in_tweets.ipynb](C_07_search_strings_not_in_tweets.ipynb)** : Creates 3 variables to check if the search string appears in the texts (**str_in_text**) of the tweets, in the usernames (**str_in_user**) or in the related conversations (**str_in_conv**)

8. **[C_08_merge_with_events_ids.ipynb](C_08_merge_with_events_ids.ipynb)** : Merges the tweets database with the related events ids / calculates the number of tweets by event

Files to explore the database

1. **[E_01_explore_by_events.ipynb](E_01_explore_by_events.ipynb)** : Explore data by events.

2. **[E_02_explore_busers.ipynb](E_02_explore_busers.ipynb)** : Explore data by users.

3. **[E_02_explore_busers.ipynb](E_02_explore_busers.ipynb)** : Explore no matches (tweets with no search strings in the text, user name or coversation).
