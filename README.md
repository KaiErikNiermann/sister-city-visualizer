# Sister City visualizer

[![Python Version](https://img.shields.io/badge/python-3.8.10-blue)](https://www.python.org/downloads/release/python-392/)

## Description

This project is a look into visualizing the sister-cities of the world using networkx and pyvis and trying to see if we can gain any interesting insights. I wrote this mainly because I always found the topic rather interesting but felt there were somewhat insufficient resources when it came to actually visualizing everything. I got some insipiration from [a paper](https://www.researchgate.net/publication/235356930_Not_All_Paths_Lead_to_Rome_Analysing_the_Network_of_Sister_Cities) which analized some of the properties of the sister city graph, but felt like a modern touch would be nice. Additionally writing this helped me, (and potentially others) gain a better understanding of some basic concepts in graph theory and data science.

## Installation

If you would like the run this project locally you can follow these steps

1. Clone the repository

    ```bash
    git clone https://github.com/KaiErikNiermann/sister-city-visualizer.git
    ```

2. Install the required packages

    ```bash
    make install
    ```

Then you should be able to open the jupyter notebook and run some of the codecells to see what happens.

## Notes

If you want to expand on this project then I included `make freeze` to save any new deps just for some minor added convenience.
