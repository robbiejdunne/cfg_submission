# Edd Webster Junior Data Scientst Data Challenge Submission
This repository is the code submitted by [Edd Webster](https://twitter.com/eddwebster) for the Junior Data Scientst Data Challenge Submission, including a list of publicly available resources published by the football analytics community related to the project.

<p align="center">
  <a href="https://www.twitter.com/eddwebster"><img src="img/edd_webster/fifa21eddwebsterbanner.png"></a>
</p>

<p align="center">
  <a href="https://www.twitter.com/eddwebster"><img src="img/club_badges/manchester-city-fc-banner.jpg"></a>
</p>

## :wave: About This Repository and Author
Please note, all the work produced in this repository is mine and/or credited to the publicly produced code, data, and/or libraries used, and is in no way related to the work and analysis I produce for my employers.

For more information about this repository and the author, I'm available through all the following channels:
*    [eddwebster.com](https://www.eddwebster.com/);
*    edd.j.webster@gmail.com;
*    [@eddwebster](https://www.twitter.com/eddwebster);
*    [linkedin.com/in/eddwebster](https://www.linkedin.com/in/eddwebster/);
*    [github/eddwebster](https://github.com/eddwebster/); and
*    [public.tableau.com/profile/edd.webster](https://public.tableau.com/profile/edd.webster).

## Contents:
*    [Notebooks](#notebooks)
*    [Data Visualisation and Tableau](#data--tableau)
*    [Data Sources](#data--sources)
*    [Tutorials](#tutorials)
*    [Libaries](#libraries)
*    [GitHub Repositories](#githubs)
*    [Papers](#papers)
*    [Written Pieces](#written--pieces)
*    [Videos](#videos)
*    [Books](#books)
*    [Podcasts](#podcasts)

## :notebook_with_decorative_cover: Notebooks
For code, see the [notebooks](https://github.com/eddwebster/mcfc_submission/tree/master/notebooks) subfolder, in which the workflow is divided into the following:
*    [Shots](https://github.com/eddwebster/football_analytics/tree/master/notebooks/shots) - build a chance quality model that calculates the probability of a shot resulting in a goal; and
*    [Metrica Sports](https://github.com/eddwebster/football_analytics/tree/master/notebooks/metrica-sports) -  identification of shot in a y the shots in this game and write a short report describing the major chances that each team created during the game, making use of the chance quality model that you developed from the shots data.

## :floppy_disk: Data Sources

### Data sources used
Due to the 100mb file size limitation in GitHub, all engineered datasets prepared in this repository have been exported and made publicly available to view and download in Google Drive. Please see the following [[link](https://drive.google.com/drive/folders/1r2Rf3CPsKnxyxtmDRIHQ2eoW5WwCzBa0?usp=sharing)]. However, all code in this repository should enable you to scrape, parse, and engineer the datasets to the format in which I have analysed and visualised the data in this repo.
*    [Metrica Sports Sample Tracking and corresponding Event data](https://github.com/metrica-sports/sample-data). For code to work with this data, see the  [`LaurieOnTracking`](https://github.com/Friends-of-Tracking-Data-FoTD/LaurieOnTracking) GitHub repo by [Laurie Shaw](https://twitter.com/EightyFivePoint) and the corresponding Friends of Tracking tutorials;


### Documentation
[TO ADD HERE]


## :student: Tutorials
*    Friends of Tracking YouTube channel [[link](https://www.youtube.com/channel/UCUBFJYcag8j2rm_9HkrrA7w)] and Mathematical Modelling of Football course by Uppsala University [[link](https://uppsala.instructure.com/courses/28112)]. The GitHub repo with all code featured can be found at the following [[link](https://github.com/Friends-of-Tracking-Data-FoTD)]. Lectures of note include:
     +    Laurie Shaw's Metrica Sports Tracking data series for #FoT - [Introduction](https://www.youtube.com/watch?v=8TrleFklEsE), [Measuring Physical Performance](https://www.youtube.com/watch?v=VX3T-4lB2o0), [Pitch Control modelling](https://www.youtube.com/watch?v=5X1cSehLg6s), and [Valuing Actions](https://www.youtube.com/watch?v=KXSLKwADXKI). See the following for code [[link](https://github.com/Friends-of-Tracking-Data-FoTD/LaurieOnTracking)];
     +    Lotte Bransen and Jan Van Haaren's 'Valuating Actions in Football' series for #FoT - [Valuing Actions in Football: Introduction](https://www.youtube.com/watch?v=xyyZLs_N1F0), [Valuing Actions in Football 1: From Wyscout Data to Rating Players](https://www.youtube.com/watch?v=0ol_eLLEQ64), [Valuing Actions in Football 2: Generating Features](https://www.youtube.com/watch?v=Ep9wXQgAFaE&t=42s), [Valuing Actions in Football 3: Training Machine Learning Models](https://www.youtube.com/watch?v=WlORqYIb-Gg), and [Valuing Actions in Football 4: Analyzing Models and Results](https://www.youtube.com/watch?v=w9G0z3eGCj8). See the following for code [[link](https://github.com/SciSports-Labs/fot-valuing-actions)];
     +    David Sumpter's Expected Goals webinars for #FoT - [How to Build An Expected Goals Model 1: Data and Model](https://www.youtube.com/watch?v=bpjLyFyLlXs), [How to Build An Expected Goals Model 2: Statistical fitting](https://www.youtube.com/watch?v=wHOgINJ5g54), and [The Ultimate Guide to Expected Goals](https://www.youtube.com/watch?v=310_eW0hUqQ). See the following for code [3xGModel](https://github.com/Friends-of-Tracking-Data-FoTD/SoccermaticsForPython/blob/master/3xGModel.py), [4LinearRegression](https://github.com/Friends-of-Tracking-Data-FoTD/SoccermaticsForPython/blob/master/4LinearRegression.py), [5xGModelFit.py](https://github.com/Friends-of-Tracking-Data-FoTD/SoccermaticsForPython/blob/master/5xGModelFit.py), and [6MeasuresOfFit](https://github.com/Friends-of-Tracking-Data-FoTD/SoccermaticsForPython/blob/master/6MeasuresOfFit.py);
     +    Peter McKeever's ['Good practice in data visualisation'](https://www.youtube.com/watch?v=md0pdsWtq_o) webinar for #FoT. See the following for code [[link](https://github.com/petermckeeverPerform/friends-of-tracking-viz-lecture)];;
*    [Soccer Analytics Handbook](https://github.com/devinpleuler/analytics-handbook) by [Devin Pleuler](https://twitter.com/devinpleuler). See tutorial notebooks (also available in Google Colab): [1. Data Extraction & Transformation](https://github.com/devinpleuler/analytics-handbook/blob/master/notebooks/data_extraction_and_transformation.ipynb), [2. Linear Regression](https://github.com/devinpleuler/analytics-handbook/blob/master/notebooks/linear_regression.ipynb), [3. Logistic Regression](https://github.com/devinpleuler/analytics-handbook/blob/master/notebooks/logistic_regression.ipynb), [4. Clustering](https://github.com/devinpleuler/analytics-handbook/blob/master/notebooks/clustering.ipynb), [5. Database Population & Querying](https://github.com/devinpleuler/analytics-handbook/blob/master/notebooks/database_population_and_querying.ipynb), [7. Data Visualization](https://github.com/devinpleuler/analytics-handbook/blob/master/notebooks/data_visualization.ipynb), [8. Non-Negative Matrix](https://github.com/devinpleuler/analytics-handbook/blob/master/notebooks/non_neg_matrix_factorization.ipynb), [9. Pitch Dominance](https://github.com/devinpleuler/analytics-handbook/blob/master/notebooks/pitch_dominance.ipynb), [10. Convolutional Neural Networks](https://github.com/devinpleuler/analytics-handbook/blob/master/notebooks/nn_pass_difficulty.ipynb);
*    [FC Python](https://twitter.com/fc_python) tutorials [[link](https://fcpython.com/)];
*    DataViz, Python, and matplotlib tutorials by Peter McKeever [[link](http://petermckeever.com/)] - I think his website is currently in redevelopment, with many of the old tutorials not currently available (28/02/2021). Check out his revamped [How to Draw a Football Pitch](http://petermckeever.com/2020/10/how-to-draw-a-football-pitch/) tutorial;
*    [McKay Johns YouTube channel](https://www.youtube.com/channel/UCmqincDKps3syxvD4hbODSg);
*    [soccer_analytics GitHub repo](https://github.com/CleKraus/soccer_analytics) by CleKraus - a Python project that facilitates the starting point for analytics 
*    [Python for Fantasy Football series](http://www.fantasyfutopia.com/python-for-fantasy-football-introduction/) by [Fantasy Futopia](https://twitter.com/FantasyFutopia) ([Thomas Whelan](https://twitter.com/tom_whelan)). This series covers the basics of working with data in Python, working with APIs and parsing StatsBomb JSON data, scraping data using Beautifulsoup and Selenium, and Machine Learning with scikit-learn and XGBoost,  See GitHub repo for all code [[link](https://github.com/twhelan22/python-for-fantasy-football)]; and
*    [Tech how-to: build your own Expected Goals model](https://www.scisports.com/tech-how-to-build-your-own-expected-goals-model/) by Jan Van Haaren and SciSports.

## :classical_building: Libaries
*    [`mplsoccer`](https://github.com/andrewRowlinson/mplsoccer) - a Python library for drawing soccer/football pitches in Matplotlib and loading StatsBomb open-data by [Andrew Rowlinson](https://twitter.com/numberstorm);
*    [`Friends-of-Tracking-Data-FoTD`](https://github.com/Friends-of-Tracking-Data-FoTD);
*    [`SoccermaticsForPython`](https://github.com/Friends-of-Tracking-Data-FoTD/SoccermaticsForPython) - repo by David Sumpter dedicated for people getting started with Python using the concepts derived from the book Soccermatics 
*    [`LaurieOnTracking`](https://github.com/Friends-of-Tracking-Data-FoTD/LaurieOnTracking) by [Laurie Shaw](https://twitter.com/EightyFivePoint) - Python code for working with Metrica tracking data;
*    [`Expected Goals Thesis`](https://github.com/andrewRowlinson/expected-goals-thesis) by [Andrew Rowlinson](https://twitter.com/numberstorm)

## :page_with_curl: Papers
The following Shiny App from Lars Maurath is a great tool for looking up publications [[link](https://larsmaurath.shinyapps.io/soccer-analytics-library/)].
*    [Routine Inspection: A Playbook for Corner Kicks](https://www.springerprofessional.de/en/routine-inspection-a-playbook-for-corner-kicks/18671052) (2020) by [Laurie Shaw](https://twitter.com/EightyFivePoint) and Sudarshan 'Suds' Gopaladesikan.  Accompanying talk - [2020 Harvard Sports Analytics Lab](https://www.youtube.com/watch?v=yfPC1O_g-I8)];
*    [Dynamic Analysis of Team Strategy in Professional Football](https://static.capabiliaserver.com/frontend/clients/barca/wp_prod/wp-content/uploads/2020/01/56ce723e-barca-conference-paper-laurie-shaw.pdf) (2019) by [Laurie Shaw](https://twitter.com/EightyFivePoint) and [Mark Glickman](https://twitter.com/glicko). Accompanying talks - [NESSIS 2019](https://www.youtube.com/watch?v=VU4BOu6VfbU), [2020 Google Sports Analytics Meetup](https://www.youtube.com/watch?v=aQ9L6IkWI8U);


## :books: Written Pieces

### Highly Rated and Recommended Pieces
*    [Using Data to Analyse Team Formations](https://eightyfivepoints.blogspot.com/2019/11/using-data-to-analyse-team-formations.html) by [Laurie Shaw](https://twitter.com/EightyFivePoint);
*    [Structure in football: putting formations into context](https://eightyfivepoints.blogspot.com/2020/12/structure-in-football-putting.html) by [Laurie Shaw](https://twitter.com/EightyFivePoint);


### :pencil2: Blogs and Data Analytics Websites
*    [EightyFivePoints](http://eightyfivepoints.blogspot.com/) by [Laurie Shaw](https://twitter.com/EightyFivePoint);
*    [Football Data Science](http://business-analytic.co.uk/blog/home-page/) by [Dr. Garry Gelade](https://twitter.com/GarryGelade);
*    [Football Whispers](https://www.footballwhispers.com/);
*    [Soccermatics Medium blog](https://www.soccermetrics.net/blog) by [David Sumpter](https://www.soccermetrics.net/blog);
*    [soccerNurds](https://soccernurds.com/blog/);

### :newspaper: News Articles
*    [Liverpool sign up for StatsBomb 360: Ted Knutson explains why this stats revolution will change the game](https://www.skysports.com/football/news/11669/12248621/liverpool-sign-up-for-statsbomb-360-ted-knutson-explains-why-this-stats-revolution-will-change-the-game) (18/03/2021) by Adam Bate for Sky Sports News;
*    [Man City’s Big Winter Signing Is a Former Hedge Fund Brain](https://www.bloombergquint.com/markets/man-city-s-big-winter-signing-is-a-former-hedge-fund-brain) (31/01/2021) by David Dellier and Adam Blenford for Bloomberg;

## :vhs: Videos
For a YouTube playlist of over 800 Sports Analytics / Data Science videos that I have collated into one single playlist, originally for my own viewing but it may be useful to you, see [[link](https://www.youtube.com/watch?v=lLcXH_4rwr4&list=PL38nJNjpNpH9OSeTgnnVeKkzHsQUJDb70&ab_channel=FourFourTwo)]. For Football-specific Data Science lectures and seminars, see [[link](https://www.youtube.com/playlist?list=PL38nJNjpNpH-l59NupDBW7oG7CmWBgp7Y)]. For a Tableau Football specific playlist, see [[link](https://www.youtube.com/watch?v=Rx7FWugmBC4&list=PL38nJNjpNpH__B0QzZ3BA0B3AxGzt0FAl&ab_channel=TableauSoftware)].

### :man_teacher: Webinars and Lectures
*    Laurie Shaw's Metrica Sports Tracking data series for #FoT - [Introduction](https://www.youtube.com/watch?v=8TrleFklEsE), [Measuring Physical Performance](https://www.youtube.com/watch?v=VX3T-4lB2o0), [Pitch Control modelling](https://www.youtube.com/watch?v=5X1cSehLg6s), and [Valuing Actions](https://www.youtube.com/watch?v=KXSLKwADXKI). See the following for code [[link](https://github.com/Friends-of-Tracking-Data-FoTD/LaurieOnTracking)];
*    David Sumpter's Expected Goals webinars for #FoT - [How to Build An Expected Goals Model 1: Data and Model](https://www.youtube.com/watch?v=bpjLyFyLlXs), [How to Build An Expected Goals Model 2: Statistical fitting](https://www.youtube.com/watch?v=wHOgINJ5g54), and [The Ultimate Guide to Expected Goals](https://www.youtube.com/watch?v=310_eW0hUqQ). See the following for code [3xGModel](https://github.com/Friends-of-Tracking-Data-FoTD/SoccermaticsForPython/blob/master/3xGModel.py), [4LinearRegression](https://github.com/Friends-of-Tracking-Data-FoTD/SoccermaticsForPython/blob/master/4LinearRegression.py), [5xGModelFit.py](https://github.com/Friends-of-Tracking-Data-FoTD/SoccermaticsForPython/blob/master/5xGModelFit.py), and [6MeasuresOfFit](https://github.com/Friends-of-Tracking-Data-FoTD/SoccermaticsForPython/blob/master/6MeasuresOfFit.py);
*    Peter McKeever's ['Good practice in data visualisation'](https://www.youtube.com/watch?v=md0pdsWtq_o) webinar for #FoT. See the following for code [[link](https://github.com/petermckeeverPerform/friends-of-tracking-viz-lecture)];
*    [Will Spearman's masterclass in Pitch Control](https://www.youtube.com/watch?v=X9PrwPyolyU&list=PL38nJNjpNpH-l59NupDBW7oG7CmWBgp7Y)] for Friends of Tracking;
*    [How Tracking Data is Used in Football and What are the Future Challenges](https://www.youtube.com/watch?v=kHTq9cwdkGA) with Javier Fernández, Sudarshan 'Suds' Gopaladesikan, Laurie Shaw, Will Spearman and David Sumpter for Friends of Tracking;

### Others
*    [Jeff Stelling xG rant](https://facebook.com/SoccerAM/videos/1740454985978128/); and
*    [Craig Burley xG rant](https://www.youtube.com/watch?v=JBWKGij9Y5A).

## :tv: YouTube Channels
*    [Friends of Tracking](https://www.youtube.com/channel/UCUBFJYcag8j2rm_9HkrrA7w) with [David Sumpter](https://twitter.com/Soccermatics), [Javier Fernández](https://twitter.com/JaviOnData), [Laurie Shaw](https://twitter.com/EightyFivePoint), [Sudarshan 'Suds' Gopaladesikan](https://twitter.com/suds_g), [Pascal Bauer](https://twitter.com/pascal_bauer), and [Fran Peralta](https://twitter.com/PeraltaFran23);
*    [McKay Johns](https://www.youtube.com/channel/UCmqincDKps3syxvD4hbODSg);
*    [Mark Glickman](https://www.youtube.com/channel/UC-gtC2WYRAr_4eYRIUb4ovg) – for NESSIS talks, uploaded to his personal channel. Old talks are available on his [Metacafe channel](https://www.metacafe.com/channels/Mark%20Glickman/). See the official website [[link](http://www.nessis.org/)];
*    [42 Analytics](https://www.youtube.com/user/42analytics) – for SSAC conferences;
*    [StatsBomb](https://www.youtube.com/channel/UCmZ2ArreL9muPvH49Gaw0Bw);
*    [Opta](https://www.youtube.com/user/optasports) - including Opta Pro Forum talks;
*    [Tifo Football](https://www.youtube.com/channel/UCGYYNGmyhZ_kwBF_lqqXdAQ);

## :books: Books
*    [The Numbers Game](https://www.amazon.co.uk/Numbers-Game-Everything-About-Football/) by [Chris Anderson](https://twitter.com/soccerquant) and [David Sally](https://twitter.com/DavidSally6);
*    [Football Hackers](https://www.amazon.co.uk/Football-Hackers-Science-Data-Revolution/) by [Christoph Biermann](https://twitter.com/chbiermann);
*    [Soccermatics](https://www.amazon.co.uk/Soccermatics-Mathematical-Adventures-Pro-Bloomsbury/dp/1472924142/ref=tmm_pap_swatch_0?_encoding=UTF8&qid=&sr=) by [David Sumpter](https://twitter.com/Soccermatics);
*    [Soccernomics](https://www.amazon.co.uk/Soccernomics-England-Germany-France-Finally/) by Simon Kuper and [Stefan Szymanski](https://twitter.com/sszy);
*    [Money and Football: A Soccernomics Guide ](https://www.amazon.co.uk/dp/B06XCKCVQR/) by Simon Kuper and [Stefan Szymanski](https://twitter.com/sszy);
*    [Data Analytics in Football](https://www.amazon.co.uk/Data-Analytics-Football-Daniel-Memmert/) by [Daniel Memmert](https://twitter.com/DMemmert) and Dominik Raabe

## :loud_sound: Podcasts 
Spotify and YouTube links used where available.

### Football Analytics Podcasts
*    [All Stats Aren't We](https://open.spotify.com/show/22eR0UCjDdVXY2JTtjD3OI?si=kt_lY1m2QKukOvKvmWpsPA) with Jon Mackenzie and Josh Hobbs (Leeds United Podcast)
*    [American Soccer Analysis](https://www.americansocceranalysis.com/podcasts);
*    [Analytics FC Podcast](https://analyticsfc.co.uk/podcast/);
*    [Big Data Sports](https://open.spotify.com/show/3Kv1yl0tCt1JDpD0AxtxZ7) (Spanish) by [Marcelo Gantman](https://twitter.com/marcelogantman) and Agustin Mario Gimenez;
*    [The Dan & Omar Show](https://open.spotify.com/show/0mT1mtMmydvs6fmrOF4GZD?si=Dv_Pm99kSd2HD603Wc1ZOg) with Daniel Geey and [Omar Chaudhuri](https://twitter.com/OmarChaudhuri)
*    [Double Pivot Podcast](https://open.spotify.com/show/4lBU3spHZaQWJyUcCUbkY8);
*    [Differentgame - The Football Analytics Podcast](https://open.spotify.com/show/0EHSv20UxlqnOjaUNzdiGN?si=rc48L2eFRLCLXZyROU8GSw) by [Paul Riley](https://twitter.com/footballfactman) and Richard Shephard;
*    [Expected Value](https://open.spotify.com/show/5xFeWbaaLFepY5n73SfWwr);
*    [Fanalytics](https://open.spotify.com/show/3G3LWoSWZdHW4Gg6igjIHU) with [Mike Lewis](https://twitter.com/FanalyticsMike);
*    [First Time Finish Podcast](https://open.spotify.com/show/0qYuP8igBfNgTVvgmNvEgP) with Tom Underhill, Bence Bocsak, and [Ninad Barbadikar](https://twitter.com/ninadb_06);
*    [The Football Fanalytics Podacst](https://open.spotify.com/show/6JwWRPMaHfGicFBtl7nI3V?si=IwQ00tyTRPaBcW-0XLwS4w&nd=1);
*    [Football Today](https://open.spotify.com/show/1WRaXZgVlksph0IjsTNBaG?si=0zyUX59sTKqCRnq92SEylQ&nd=1);
*    [Laptop Gurus](https://open.spotify.com/show/3sPI2CtmRJeaShdqNjrGRH?si=1NRk7exnRWaNbqbDO0B72w);
*    [Looks Good on Paper podcast](https://open.spotify.com/show/7iJoF537QKPgDgQe7bblV2?si=QwiAfM2ZS0-Z4M74RESiKQ&nd=1) by [Felix Pate](https://twitter.com/lgopfelix);
*    [MRKT Insights](https://open.spotify.com/show/3q32QkmAXwth5VJwU8uzWt?si=8_vyLb6WQd2wTJt5MxdBoA);
*    [Measurables Podcast](https://open.spotify.com/show/1B2KCrfMM6sDfNICsyVDlW) by [Brendan Kent](https://twitter.com/brendankent);
*    [Open Source Sports](https://open.spotify.com/show/3vTtH2JJXbjrzOtEfjrqc4?si=HqpAZAmRTkGFwurl965thA) with Ron Yurko;
*    [The Scouted Football Podcast](https://open.spotify.com/show/4qYVKC8RlHCJrwrRCx0w6H?si=M6xgCGtdTjiy0wEl1e2CJw);
*    [smarterscout: The Why in Analytics](https://open.spotify.com/show/2QP4KXajJ5xOfW1ny78nAf?si=NQAf_4XtSFeQXAZi1bbupQ) by Dan Altman;
*    [Squawka Talker Football Podcast](https://open.spotify.com/show/7xqylrPDX54uo01n4erZQZ?si=XpMNQ43aQxKUa6QuB0dp2w);
*    [StatsBomb](https://open.spotify.com/show/2EgxEas2CUsGpuH5AGWnAO?si=yvTrhRLGSBm7XanWZnd7lA);
*    [Target Scouting](https://open.spotify.com/show/2SJENgKp4BrmeufJPKC2TH?si=hq4tXC3sSKGkej4VU8w40w) by Luke Griffin;
*    [Tifo Podcast](https://open.spotify.com/show/06QIGhqK31Qw1UvfHzRIDA?si=eJzpmtMeSPWUDP9fQ-5pqA);
*    [Training Ground Guru](https://open.spotify.com/show/1Kn9l6LifZ2AWmZri9XWHn);
*    [Three At The Back](https://open.spotify.com/show/4NbunP2podS7hIPD2BVlYF?si=OFwVjOucQP6LWZmnGmGqjg) by Opta Pro; and
*    [Zonal Marking](https://open.spotify.com/show/1o2ZogNQQmPKCntcdKnXPT).

### Noteable Episodes (including non-football-data-specific podcasts)
*    [All Stats Aren't We](https://open.spotify.com/show/22eR0UCjDdVXY2JTtjD3OI?si=kt_lY1m2QKukOvKvmWpsPA):
     +    [Bonus Episode: David Sumpter - The Ten Equations that Rule the World](https://open.spotify.com/episode/2aWNiGHVH29qnXdrw12Iet?si=gU5__QfvRsCCxjE7XjcRhQ)
     +    [The Weekly - Ep. 12 - Barnsley Debrief and Derby Preview](https://open.spotify.com/episode/1mJinsb8PJNlpghcGz0p4g?si=f5P51NayTJClOYscU3vTqA) with Ram Srinivas
*    [Analytics FC Podcast](https://analyticsfc.co.uk/podcast/):
     +    [Episode 27: David Sumpter](https://open.spotify.com/episode/6gG4VY5hRlIio0smhgTnWh?si=meS7GqPxR4WXf2PGMPATZw)
*    [Big Data Sports](https://open.spotify.com/show/3Kv1yl0tCt1JDpD0AxtxZ7) (Spanish) by [Marcelo Gantman](https://twitter.com/marcelogantman) and Agustin Mario Gimenez:
     +    [87: No es Moneyball: es Brentford](https://open.spotify.com/episode/3b8lnFZjm27ag2R0SUZRdZ?si=CI_LfzetQSCs2yLiQ5HMMg)
     +    [66: Tres Libros Sobre Sports Analytics Más Allá De Moneyball](https://open.spotify.com/episode/3nebrUaTswrXGtztoulM3S?si=2IvLTxFpQ9CfPPiGPyov3g)
     +    [65: Métrica Sports: La máquina de entender el juego](https://open.spotify.com/episode/5egzgcesbAzMlzZBxMmMIK?si=V7pTj8n7R9OWhNmMV62-wA) withg Bruno Dagnino
     +    [56: STATS PERFORM: Cómo es el nuevo gigante de los datos del fútbol](https://open.spotify.com/episode/0KoAJxa7bEE1qtIiw3e34y?si=Dkxu0pwHToiF5kmh5Vx6Iw)
     +    [47: Wyscout: 550 Mil Futbolistas "concentrados" En Un Software](https://open.spotify.com/episode/7vI1qM7KoJHkFoe11iX3Nj?si=v4BaWwBaSc61y-PM9F-75w)
     +    [35: Big Data Sports - 35: Analistas: Los nuevos "cracks" del fútbol ](https://open.spotify.com/episode/1e8KEFHNvLb5T0HUZS57gN?si=9XlTI81mSaKGYuSK4ADvfQ)
     +    [33: Google + IA = Fútbol en Real Time](https://open.spotify.com/episode/1e8KEFHNvLb5T0HUZS57gN?si=DDGSzoxIQaKnPoaULtMbjQ)
*    [Challengers Podcast](https://challengerspodcast.tumblr.com/):
     +    Expected goals (2016)
*    [The Conor J Show](https://open.spotify.com/show/2VeRpUoHzC7KN9zxB5N2iz?si=oSMPSpwbR7-IgxSzqlk6Ig):
     +    [The Role Mathematics plays in Sports and Politics (Part 1) | David Sumpter | TCJS #11 (1/2)](https://open.spotify.com/episode/7BBAToNN9Mt0Ol8c9bDtGS?si=5YNtRObXQMu7xYBEgLgmbQ)
     +    [Is Fake News Efficacious (Part 2) | David Sumpter | TCJS #11 (2/2)](https://open.spotify.com/episode/2BC0GxAIU96aYSqMlRUcuQ?si=dPSAmciQR3KIJG5ivx1uEg)
*    [The Derby County BlogCast](https://open.spotify.com/show/6JgsZlXILOQpIKvknAgQDA?si=sjgzZ2D3QbWezG9slwWHeQ)
     +    [January window preview](https://open.spotify.com/episode/6BPle4s00x3ZM85mcDV7Ip?si=eNATcAJUTX-2E8RDA7IDOg) with Ram Srinivas (MRKT Insights)
*    [Expected Value](https://open.spotify.com/show/5xFeWbaaLFepY5n73SfWwr?si=yn23mqUpQa-mvcL6CYWpgA)
     +    [Tyler Heaps](https://open.spotify.com/episode/3OQimhf73WILGLTKXnav2M?si=L3KjerEfRryp50MQv6fzXg)
     +    [Ben Mackriell](https://open.spotify.com/episode/0tVtnFljEX5Pkn7hSApPo7?si=ldLi3xi4TuehvpawJ7NQ0g)
     +    [Ravi Ramineni](https://open.spotify.com/episode/5CPu9WFvM5iqfCX2I1m3mR?si=MQKTbjZpSiq26WgQ198gNg)
     +    [Tom Worville](https://open.spotify.com/episode/0H11EE4Bv930scxKRqf9Ci?si=0JJ-Nq3TQMWYJwy7kHpKAw)
     +    [Opta Pro Forum with Karun Sign, David Perdomo Meza, Will Gurpinar-Morgan, Vignesh Jayanth](https://open.spotify.com/episode/3dkq9a0o2WcI10AIfCfhjN?si=z7pJF-yYSYOxtUa6JE_kcA)
     +    [Mike Goodman](https://open.spotify.com/episode/4dCaPFQgb1nRdYv6TB0ckf?si=_5dbscy_QeOrOuOYvD1DMw)
     +    [NESSIS, Part 1 - Ron Yurko & Dani Chu](https://open.spotify.com/episode/3pRxs7LYPX4LP9jGcFXudz?si=V7G5JpJxRZiMhqlPwblrWQ)
     +    [NESSIS, Part 2 - Laurie Shaw & Sam Gregory](https://open.spotify.com/episode/42z1UFcfgpx17acCCg5rip?si=Pyu8gFJxRiej9fE15Gs89A)
*    [Explore Explain](https://open.spotify.com/show/7khS5ikdwhW9kyE7GIcfdw?si=Wl1Nhh35RAehtJ_5w5p-Hw) with [Andy Kirk](https://twitter.com/visualisingdata):
     +    [S2E4 - Tom Worville](https://open.spotify.com/episode/7yqrJlGLbn1af9XSFbWPLK?si=SR0Ux69_SA-Uw-qW9cHNow)
*    [Fanalytics](https://open.spotify.com/show/3G3LWoSWZdHW4Gg6igjIHU?si=9v83huJIR-GUxAnKRyXLRA) with Mike Lewis:
     +    [Getting Your Foot in the Door](https://soundcloud.com/fanalytics/sports-analytics-getting-your-foot-in-the-door) with Sean Steffen
*    [Freakonomics](https://open.spotify.com/show/6z4NLXyHPga1UmSJsPK7G1?si=Nl7mbhOeRh64w3tp7alyyg) by Stephen J. Dubner:
     +    [Can Britain Get Its “Great” Back? (Ep. 393)](https://open.spotify.com/episode/7hh4DaXBCQtLZ17Lv9Lwg6?si=2F5C3k-IQLeIuaQMfkULMA) featuring Dr. Ian Graham @ 41m25s;
*    [Football CFB Podcast](https://open.spotify.com/show/2jTKOVU0uAND8DwprMPlC8?si=C-fBu4FHTaK9wuSgyniYjw):
     +    [Daniel Geey](https://open.spotify.com/episode/0zKYxeZ3WFI1l2wihjFNoQ?si=VpgfDIviRXGRcsOUD1BMhQ)
     +    [Football CFB with… Kieran Maguire](https://open.spotify.com/episode/1KvvfS84xGw4KFB2nwr9Fv?si=s2p3SQD3RbKy6pLqBYjimg)
*    [The Football Collective Podcast](https://open.spotify.com/show/3fqNuhWi6hkagJ1U0UDJfe?si=e10JT2ACS86A3JXyO1AzGQ):
     +    [S3 E1 | Sarthak Mondal speaks to Laurie Shaw about the advent of Data Science in Football The Football Collective Podcast](https://open.spotify.com/episode/1gJXuovD1L6VMimN5BtukS?si=Y-Ot43T8TluU7UEiSvReyg)
*    [The Football Pod](https://open.spotify.com/show/3QhwCTOvJN3AZqNalgjtnO?si=173ZCWfsTs-jktoS7Bz9XQ):
     +    [Episode 3 with David Sumpter](https://open.spotify.com/episode/4mnDHbUo097JuC2lQiFijo?si=7abgc4_vRM21jSKff04rWg)
*    [Football Today](https://open.spotify.com/show/1WRaXZgVlksph0IjsTNBaG?si=0zyUX59sTKqCRnq92SEylQ&nd=1)
     +    [Manchester City Enters Data Arms Race With Liverpool](https://open.spotify.com/episode/311rLza8goz2b2SBORBORn?si=aqZX6ooOSfGkY3312jJozA)
     +    [How Safe is Football's Data](https://open.spotify.com/episode/5DnpiT8dtVcQK8YDtBIgnz?si=XweL-JQCQbCMdTArB0X1LA)
     +    [Who Owns Football's Data](https://open.spotify.com/episode/5Cw5ovQ9qH3LEkOhawUXV7?si=jxLNeCXwTL6Z41o6xvDUzw)
     +    Can Data Save Manchester United? Featuring Tom Worville
     +    [Tony Bloom: The Betting Guru Running Brighton](https://open.spotify.com/episode/2N2EMqiyqEjwqdPM6zApIw?si=uhE9VWawSo6jPQfTaIeFCQ)
*    [Modern Soccer Coach Podcast](https://open.spotify.com/show/0mxCm5xfR1dH72GBQ5pl6t?si=P-BAw6ePR52yLGCukJyOGg) with Gary Curneen:
     +    [Ted Knutson: StatsBomb, Liverpool and the Data Revolution](https://open.spotify.com/episode/6L1qdBitr8s19qIXbgMuIQ?si=FoqAeTxdQiK_tmH_EubETw)
*    [Not The Top 20 Podcast](https://open.spotify.com/show/19Vn2WZiSZOeanPFDHYIb8?si=baqjrom8Sbyc0cYMtttMEQ):
     +    [Recruitment Chat with Jay Socik (Blades Analytic) & Introducing FIVEYARDS](https://open.spotify.com/episode/30ARjrCcCiUHAc5oD3eaqE?si=6OPTiLkPQCiobeVLG193hg)
*    [The Nutmegged Arena](https://open.spotify.com/show/5ZRtcboNN80YL8ohGA6Wos?si=oyRGiCxTSSmIM5KSWaXCOA) by The Nutmeg Assist:
     +    [Tuchel & Chelsea, Quality in the EFL bumping up & more](https://open.spotify.com/episode/0SvrUT6wlGYLbV1zcrk1JL?si=0NSd2eJ9SU6ffeGQxubbEw) with Ram Srinivas
     +    [#67 Manchester United's return to the top with Ninad Barbadikar](https://open.spotify.com/episode/7noFBqjF6U5iea1QMFsHsV?si=BUW2tRqaQqaeTMuoXaLmfA)
*    [Open Source Sports](https://open.spotify.com/show/3vTtH2JJXbjrzOtEfjrqc4?si=HqpAZAmRTkGFwurl965thA) with Ron Yurko;
     +    [Player Chemistry in Soccer](https://anchor.fm/open-source-sports/episodes/Player-Chemistry-in-Soccer-with-Lotte-Bransen-ejils5) with Lotte Bransen
*    [The Ornstein & Chapman Podcast](https://open.spotify.com/show/69AAB4ojTuK7gwy3ZdQdB9?si=ciYED_kESKqfa2K505QsrQ) with David Ornstein and Mark Chapman:
*    +    [Football Club Ownership: Data, Decisions & Competitive Edge](https://open.spotify.com/episode/6v739L7LR13BZs4sPmDeGD?si=3TRs_IunT6-pVhA78ZPgGw)
*    [The PinkUn Norwich City Podcast](https://open.spotify.com/show/4NU35xCqwl8kyUG9v8Sx2A?si=3AgoCZRRT5en1zaNVIEI-Q):
     +    [232: 'Analysing Norwich City's Recruitment' - The Rebound #3 - Ft. Data Analyst Ram Srinivas](https://open.spotify.com/episode/7idmp92m0Pfv2XiW8vOzZU?si=NCc6-ZDWSdWgum1WfVv-VA)
*    [Pinnacle Podcast](https://open.spotify.com/show/091oYrS0glFhP81fq32bpE?si=TmR79XGnRAm5987Zj33ImA):
*    +    [Serious About Betting: David Sumpter](https://open.spotify.com/episode/6Bt5L7wXDGvrSezYL2FU2O?si=IgQB1TArR9CBTnecZxb6qA)
*    [The Process](https://open.spotify.com/show/5H0uUcZGr6zw7AHRuLKP6D?si=7XUIxepzTYyVRS3fEwG7Lw) with James Allcott:
     +    [#16 The Future of Football with Ted Knutson (StatsBomb)](https://open.spotify.com/episode/4KKWkT6tAn2puAe2IqOtLq?si=Br5HbR_lRvCsO5oFf0sqOw)
*    [The Scouted Football Podcast](https://open.spotify.com/show/4qYVKC8RlHCJrwrRCx0w6H?si=hBYRN1GgSc2eSIDUMiwDfA&nd=1):
     +    [#26 Recruitment, Data and Sheffield United with Blades Analytic](https://open.spotify.com/episode/1EeM7PCLq5fBngMGdVROkN?si=7W6-FrhASsafAKvbmdY6DQ)
     +    [#56 Standout Stats: Premier League](https://open.spotify.com/episode/37SlOJmtoviAKgNanq7Fxq?si=JzBDUt7iRHCKhTPomuVjAA) with Mark Carey
*    Soccer Player Development Podcast:
     +    Episode 12 with Rasmus Ankersen - [YouTube](https://www.youtube.com/watch?v=S0iHetgqQpE)
*    [Squawka Talker Football Podcast](https://open.spotify.com/show/7xqylrPDX54uo01n4erZQZ?si=XpMNQ43aQxKUa6QuB0dp2w):
     +    [BIG interview with David Sumpter: Putting GPS trackers on under 10s football teams](https://open.spotify.com/episode/6c6vOWNhvUah7Mz01oiCgt?si=t7Sc0W8WRUS0ZnVWTaGt0g)
*    [Tifo Podcast](https://open.spotify.com/show/06QIGhqK31Qw1UvfHzRIDA?si=eJzpmtMeSPWUDP9fQ-5pqA):
     +    The Transfer Market & 21st Club withj [Omar Chaudhuri](https://twitter.com/OmarChaudhuri) - [Spotify](https://open.spotify.com/episode/4C21F4d5RedaQjYHCv451k?si=ca8BN8KaSdCwGUTaiaFEfw) and [YouTube](https://www.youtube.com/watch?v=A5psEy_V8YM)
     +    How Memphis Depay Used Data to Find His Next Club with [Giels Brouwer](https://twitter.com/Gielsbrouwer) - [Spotify](https://open.spotify.com/episode/0RpLcIdqdD81Z4vyVPgw5w?si=YFR38EX3QvOReG1xWEl7rw) and [YouTube](https://www.youtube.com/watch?v=wP7HH_ucwzo)
     +    How Do Football Clubs Actually Use Statistics? - [YouTube](https://www.youtube.com/watch?v=ktk-ocn2AMo)
     +    JJ Bull: Tactical Analysis & Coaching Badges - [Spotify](https://open.spotify.com/episode/4vOxLy5WINc40ApWW8PvI1?si=C4URrqf_SyCPMg4QaUUM1A) and [YouTube](https://www.youtube.com/watch?v=cYThVZO3RJ0)
     +    A Day in the Life Of: A Football Recruitment Analyst - [Spotify](https://open.spotify.com/episode/6lkHrtOP9IsJkV6i1hyAhL?si=phub1dNLSgSK2pfBDQuB4w) and [YouTube](https://www.youtube.com/watch?v=dq6C2okqZm4)
     +    Liverpool: Pressing, xG Concerns, and Klopp’s Future - [Spotify](https://open.spotify.com/episode/4AqlZZ0deXtY9a2Wh6wGWw?si=_beiVWuFQyq3GzL2Ngt0jg) and [YouTube](https://www.youtube.com/watch?v=o4ED05PJQFI)
     +    Understanding Stats in Football with [Nikos Overheul](https://twitter.com/noverheul) - [Spotify](https://open.spotify.com/episode/1vI6Go2NhNVwZ9w5CaPDTo?si=ZT_cUwhAQaiSK_ddH57tjw) and [YouTube]()
     +    Steve Morison: Tactical Insight & Football Psychology - [Spotify](https://open.spotify.com/episode/5n5mng71oIDM69LzGRG09O?si=7sgzhL8AQMKPCepNPiBz5g) and [YouTube](https://www.youtube.com/watch?v=0d0zMg3tD-Q)
     +    Football Tactics with [Michael Cox](https://twitter.com/Zonal_Marking) (Zonal Marking) - [Spotify](https://open.spotify.com/episode/5rzLuewrS9q8ueQToqhhI2?si=7GO64KzOQ6ulkFaVAH7tRA) and [YouTube](https://www.youtube.com/watch?v=46FRcn11RFQ)
     +    Football, Tactics & History with [Jonathan Wilson](https://twitter.com/jonawils) - [Spotify](https://open.spotify.com/episode/2d072VAbRxGmwPFJDYimut?si=7Bha0Gf6QGqdqD4pPZXJFA) and [YouTube]()
     +    The Future of Stats: xG, xA - [Spotify](https://open.spotify.com/episode/7fPpKZSt2o9SSNynayROwd?si=WxuV2PFCQ7yRdNSE-QOZ6g) and [YouTube](https://www.youtube.com/watch?v=sNCeA27sDvI)
*    [The Totally Football Show](https://open.spotify.com/show/30pUHuXuSQBSf7EfZQuEvS?si=3NahWL3IR-CBAKdXzQ9cGA) with James Richardson
     +    [03/07/2019: Football Hackers](https://open.spotify.com/episode/00lwcYEV82Pz639PPadlCf?si=2SZQOpIySw-zSsN6wczQwA) with Christoph Biermann
*    [Total Soccer Show](https://open.spotify.com/show/4bDhkcGQjbNqIGszh371y1?si=Bww9nrROTTmLT8AM__7NTg):
     +    Soccer stats and analytics with Ted Knutson (@mixedknuts) (in which Ted explains Expected Goals to Daryl) - [YouTube](https://www.youtube.com/watch?v=abPYPmgMPso)
     +    Mike L. Goodman (@TheM_L_G) talks USMNT tactical options, EPL trends, Expected Goals - [YouTube](https://www.youtube.com/watch?v=uxaQwMC0EYY)
     +    Everton Premier League preview: Mike L. Goodman (@TheM_L_G) talks Silva's style, Moise Kean, and replacing - [YouTube](https://www.youtube.com/watch?v=Fb94W2-THG0)
*    [Trademate Sports](https://open.spotify.com/show/2LPzUrtsWvz5iSayEGeEQK?si=prrlKqiwQ7-bKIUtbemkeQ):
     +    [Ep 19: Freelance Football Writer talks Data Analysis, Liverpool & Betting](https://open.spotify.com/episode/1wDpG7biQ5PxYfm45NNgaF?si=NwKrXzkKSVqzROhD-58Vsw) with Andrew Beasley
     +    [Ep 87: Mathematics Professor David Sumpter & Trademate CEO Marius Norheim - Using Mathematics in...](https://open.spotify.com/episode/6jYhTHxujga5D9j37uQbLt?si=3gwKy27dRcOgVij5bYpGzA)
*    [UCN/USF Sport Management - Sports Business Podcast](https://soundcloud.com/user-736114890):
     +    [Kenneth Cortsen talks to Laurie Shaw from Harvard University](https://soundcloud.com/user-736114890/sport-data-analytics-in-football-kenneth-cortsen-talks-to-laurie-shaw-harvard-university) 
*    [Where Others Won't]() by [Cody Royle](https://open.spotify.com/show/13w1hFUG3jzoA0IrmSlc4m?si=gmYlfec-RyibIf7fC6QMMQ):
     +    [Rasmus Ankersen - Discovering Talent](https://open.spotify.com/episode/7lkkikNGL4F1cfZy1I4kPK?si=CYWpdhF9SFWr-v605Jb64w)   

*    [Expected Goal literature](https://docs.google.com/document/d/1OY0dxqXIBgncj0UDgb97zOtczC-b6JUknPFWgD77ng4/edit)
