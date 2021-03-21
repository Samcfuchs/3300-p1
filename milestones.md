# Project 1: Phase I

Team members: Sam Fuchs (scf73), Max Coleman (mac488), Leo Decter (ljd83)

## Project Ideas

- pokemon:
    - visualize the total number of pokemon and the total for each type across all generations
    - can do visualization for 1 type versus 2 type pokemon
    - charts for each generation
    - Stats
    - stats of least common combinations of types
    - game difficulty (measured by catch rate) vs generation
    - https://www.kaggle.com/abcsds/pokemon 
    - https://www.kaggle.com/mariotormo/complete-pokemon-dataset-updated-090420 
- Effects of COVID lockdowns on alcohol consumption in a local region
-https://pubs.niaaa.nih.gov/publications/surveillance-covid-19/COVSALES.htm#fig1 
- FIFA players: offense vs defensive player stats
    - https://www.kaggle.com/stefanoleone992/fifa-20-complete-player-dataset 
- Gamestop stock price: show changes in price as a result of user activity
    - Combine with post data from r/WallStreetBets to show how reddit posts affected the stock price
- Disc golf: show players' performance on different holes
    - long vs. short distance performance
https://udisclive.com/live/waco2021?d=MPO
https://www.pdga.com/players/rankings/world
- Chess: what squares most often have check? or checkmate? what pieces attack there?
    - https://www.kaggle.com/datasnaek/chess 

## Work for week 1

All members:

- Find datasets for the above ideas
- Identify potential directions of analysis
- Choose a favorite project idea

# Project 1: Phase II

Project Idea: Visualize the stats of pokemon of different types and generations!
Identify and present some interesting patterns or trends in pokemon stats.

What We did:

- Max: I looked over the data sets for Pokemon and the alcohol consumption
during COVID to see if they had the proper information we wanted and how easy it
would be to implement. I also discussed and presented ways in which to parse the
data from the chess dataset in order to make it into chunks that could be used
for the domains and how we would create the grid system. 
- Leo: I found data sets for our disc golf project idea. This included results
from recent tournaments and current international player rankings. I also talked
with my group members about possible ways to explore our newfound datasets.
- Sam: Gathered data sets for chess and FIFA, looked through the proposals my
partners introduced, chose a project from the options presented, made a github
repo for collaboration

Work for next week:

- Max: develop initial data cleaning code
- All members: do some basic exploratory data analysis
- All members will have a work session over the weekend to further develop our visualization. Further tasks will be assigned after that session.
- To be assigned:
    - Design viz
    - Implement viz design
    - Write report

Questions for TA:

* We didn’t receive feedback for phase 1, so any feedback on the basic project
idea is welcome. 
* Because we won’t be able to implement interactivity, should we stay away from
designs that incorporate “too many” data points (e.g. a scatterplot of all 800
pokemon) if the user won’t be able to identify individual points? 
* To what extent does our code need to be written in JavaScript? Could we write
pre-processing code in python and output a clean, static data file that we
import to JS?
