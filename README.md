# elections-flip-margin

This repo contains data and analysis used to write the article [How many votes does it take to change the outcome of a U.S. presidential election?](https://www.kylegiddon.com/elections-flip-margin/), available on my personal website.

The core analysis and production of graphics is in the Jupyter notebook `elections.ipynb`.

### Data sources
Data are taken from two sources and compiled into the `/data` folder:

1. The Massachusetts Institute of Technology Election Data and Science Lab provides state-level returns by year. Data is downloadable as a .tab file.
1. The U.S. National Archive tracks the number of electoral votes for each state in each election. Each year is on its own web page in a table. I manually copied and pasted each yearly table into a CSV.