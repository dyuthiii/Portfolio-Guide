# 🌻Dyuthi's Portfolio 
A quick guide to my portfolio, walking you through some of the projects I've worked on and the skills I have picked up along the way. 

## 📚Table of Contents
- [SQL](#sql)
- [Coding: Python & R](#coding-python-and-r)
- [Visualizations](#visualizations)
- [Reports](#reports)



# SQL

| Project | Project Description | 
|:---|---|
|![United States](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/us.png "United States") [Web-Scraping Political Contributions from the FEC](https://github.com/dyuthiii/PoliticalFinanContributions.git) | Here, I used an API key from the FEC's website to scrape all the financial contributions to various politicians. I had to run this over multiple days and multiple scripts as the DB ended up being too large, or some contributions were missed. I stored the scraped data in a large relational database using SQLite. The database can be found in the linked Repo. Querying Politicians should give the contributions. However, this data is limited to between January 2022 and 11 November 2024. Check out the README for more info.|
***

# Coding: Python and R

| Project | Area | Project Description | Language| Libraries |    
|:---|---|---|---|---|
|🐍[Snopes Web-Scraping and Data Analysis](https://github.com/dyuthiii/Snopes.git)| Web-Scraping, Data Analyses, Machine Learning| I web-scraped the Snopes website (a fact-checking news source) from January to July 2025. I used this data to build [Tableau Visualizations](#visualizations) about  news catergory they the rating of misinformation given by snopes. Additionally, I performed some basic data analyses and built a predictive model to see if the model could effectively categorize news articles as real or fake.| Python| pandas, Beautiful Soup, scikit learn, re|
|💃[Latent Dirichlet Allocation (LDA) of Taylor Swift's Albums using Lyrics](https://github.com/dyuthiii/Taylor-Swift-Albums-LDA.git) | Natural Language Processing (NLP)| I explored emerging themes in Taylor Swift's albums using NLP LDA techniques to find latent dimensions. This process involved cleaning up the lyrics using RegEx, lemmatization, Word Vectorization, visualizing word frequencies across albums, and training and testing the LDA model using GridSearchCV. Some fun and interesting insights here, check it out! | Python| pandas, re, nltk, spaCy, gensim, matplotlib|
|📈[NLP on public Earning Calls of Medical Corporations](https://github.com/dyuthiii/CorpEarningCallNLP.git)| Natural Language Processing (NLP)| This one was our group project for our Natural Language Processing class! My part involved cleaning up web-scraped earning call transcripts and conduct Sentiment Analysis and Topic Extraction from them. We aimed to train an ML model to predict stock prices of these companies based on the sentiments extracted from the transcripts, and test if the model could accurately predict stock price changes based on the transcript sentiments and topics.| Python| re, nltk|
|![Spain](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/es.png "Spain") [Language adaptations of mental health interventions: Wysa in English and Spanish](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=1fVoVJcAAAAJ&citation_for_view=1fVoVJcAAAAJ:u5HHmVD_uO8C)| Research: Digital Mental Health| This paper is about the effectiveness of cultural adaptation (like language adaptations) of Digital Mental Health Interventions (DMHI) for diverse populations. This paper compared the uptake of Wysa in Spanish and Wysa in English across Spanish-speaking countries. We found that there were noticeable preferences for interventions in one's own language. For analysis, I conducted descriptive analysis, content analysis on user text, and inferential tests (Wilcoxon test: a non-parametric form of the independent t-test).| R| dplyr, psych, tidyr, ggplot2, stringr, lubridate|
|![Singapore](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/sg.png "Singapore") [Examining a Brief Web and Longitudinal App-Based Intervention \[Wysa\] ](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=1fVoVJcAAAAJ&citation_for_view=1fVoVJcAAAAJ:u-x6o8ySG0sC)| Research: Digital Mental Health| This paper dissects the impact of Wysa as a Mental Health support tool during the COVID-19 pandemic. It involves a mixed-method approach that utilizes regression analyses and qualitative coding. I conducted descriptive analysis, content analysis on user text, inferential tests, and logistic regression, which aimed to predict what type of negative thought patterns were effectively reframed using the psychological model. This paper was extremely fun as it involved my quantitative skills, combined with classical psychological models of mental illness and negative thoughts.| R| dplyr, psych, tidyr, ggplot2, glm|
***

# Visualizations

| Project Link | Project Description | Dashboard Link |
|:---|---|---|
|🐍[Snopes articles Dashboard](https://public.tableau.com/views/SnopesTableauViz/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)| This is the Tableau Public Dashboard of the Snopes Articles (Jan-July 2025) web-scraping I did. I aimed to make visualizations about the most popular Snopes articles and what categories they were in. Additionally, I added a treemap to view the Ratings by Snopes to see which categories received what kind of ratings. There's also information about the authors and more in-depth visualizations.| [Tableau Public](https://public.tableau.com/views/SnopesTableauViz/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)|
|💼[Columbia Business School (CBS) 2025 Peer Comparison]<!--(https://public.tableau.com/app/profile/dyuthi.dinesh/viz/2025Top30PeerSchoolsBoardBookCharts/M7top30admitrateandyield?publish=yes)-->| Dashboard comparing CBS's applications, admits, and enrollments over the years (2019-2024), and compared to peer schools. All the data was collected from the USNEWS website for 2025 Top Business Schools using the Wayback machine.|[Tableau Public Dashboard]<!--(https://public.tableau.com/app/profile/dyuthi.dinesh/viz/2025Top30PeerSchoolsBoardBookCharts/M7top30admitrateandyield?publish=yes)-->|
|🌸 [Visualizations Page](https://github.com/dyuthiii/Portfolio-Guide/blob/ff5822e7ddda432b71b9195e5b95ac1b0f4cbb96/Visualizations.md) | This page has the screenshots of some of my visualizations, which I can't directly link due to confidentiality.| [Page](https://github.com/dyuthiii/Portfolio-Guide/blob/ff5822e7ddda432b71b9195e5b95ac1b0f4cbb96/Visualizations.md)|
***



# Reports
|Report Name | Organization | My Role |
|:---|---|---|
|🧠[Employee Mental Health Report](https://drive.google.com/file/d/1oKPcUWQzcePjlC4yxyrklCvDoVrZLuH8/view?usp=sharing)| Wysa Inc.|For this report, I conducted all of the data analysis on R and created visualizations for the report. I can't link the code or the data due to confidentiality reasons, but the report is public, and I loved working on it and analyzing mental health data!|
|🆘[The Role of AI in Mental Health Crises](https://www.wysa.com/role-of-ai-in-sos)| Wysa Inc.|For this report, I conducted all the data analysis on R. I found the findings super insightful and important in the digital mental health field. Again, can't make the code public, but do peruse the report for some interesting findings.|
|🤖[Conversational AI for Mental Health: Potential & Risks](https://www.wysa.com/conversational-ai)| Wysa Inc.| I helped with the literature review for this report. I learned a lot about the state of AI in mental health during 2022, and have kept up with it since then. I think a lot has changed, but the take-home message about safety and guardrails still applies, imo.|

