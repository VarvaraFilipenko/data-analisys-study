# Computer game analysis
*Libraries: pandas, matplotlib.pyplot (hist, plot, boxplot, scatter, bar), seaborn, stats, numpy*

*There is a historical data on sale of games, user and expert ratings, genres and platforms (e.g. Xbox or PlayStation) from open sources. It needs to identify patterns that determine the success of the game. This will allow to bet on a potentially popular product and plan advertising campaigns.
There is the data before 2016. Imagine it is December 2016 and you are planning a campaign for 2017. We need to work out the principle of working with data. It doesn’t matter if you forecast sales for 2017 according to 2016 or 2027 according to 2026.
The abbreviation ESRB (Entertainment Software Rating Board) comes across in the data set - this is an association that determines the age rating of computer games. ESRB evaluates gaming content and assigns it a suitable age category, for example, For Adults, For Young Children, or For Adolescents.*


This is an education project which includes:
1) Data preparations 
    - fills NaN values (by median, by info extracted from text)
    - changes type of data
    - creating calculated fields
2) Exploratory Data Analysis: 
    - counting:
        - number of games per year (plot: kind='bar')
        - the sales in term of platform (groupby)
        - analysis of sales for top-8 platform (pivot_table, sns.catplot, sns.relplot)
        - mean sales analysis (sns.boxplot)
        - researching the correlation between reviews and sales (correlation coefficient)
3) Describing a user portrait for each region
4) Hypothesis tests (st.ttest)