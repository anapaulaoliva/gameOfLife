# Conway's Game of Life Challenge

![image](https://user-images.githubusercontent.com/56927809/83430468-58ca6780-a3fb-11ea-9be7-c0cc071903d9.png)

## About

This is about Conway's brainchild, a fantastic solitaire pastime he calls "life". Because of its analogies with the rise, fall and alternations of a society of living organisms, it belongs to a growing class of what are called "simulation games"--games that resemble real-life processes.

The basic idea is to start with a simple configuration of counters (organisms), one to a cell, then observe how it changes as you apply Conway's "genetic laws" for births, deaths, and survivals. 

![image](https://user-images.githubusercontent.com/56927809/83429370-929a6e80-a3f9-11ea-9463-edd37780d301.png)

Conways genetic laws are delightfully simple. First note that each cell of the checkerboard (assumed to be an infinite plane) has eight neighboring cells, four adjacent orthogonally, four adjacent diagonally. The rules are:

* [1. Births](#1-births)
* [2. Survivals)](#2-survivals)
* [3. Deaths](#3-deaths)

#### 1. Births 
Each empty cell adjacent to exactly three neighbors--no more, no fewer--is a birth cell. A counter is placed on it at the next move.
![1](https://user-images.githubusercontent.com/56927809/83445074-f335a580-a411-11ea-8dac-4f2daad1ddaa.JPG)

#### 2. Survivals.
Every counter with two or three neighboring counters survives for the next generation.
![2](https://user-images.githubusercontent.com/56927809/83445080-f597ff80-a411-11ea-87e4-b2a8de6e9e1e.JPG)

#### 3. Deaths. 
Each counter with four or more neighbors dies (is removed) from overpopulation. Every counter with one neighbor or none dies from isolation.

![3](https://user-images.githubusercontent.com/56927809/83445086-f761c300-a411-11ea-99ad-4bb794184d74.JPG)

### Diagram Flow 

Made with LudidChart. You can find the link [here](https://bit.ly/36PdlmV).
![automatcellsdiagramflow](https://user-images.githubusercontent.com/56927809/83443782-ec0d9800-a40f-11ea-9e8e-970446b9db58.JPG)

##### Resources

- MATHEMATICAL GAMES:The fantastic combinations of John Conway's new solitaire game "life". (https://www.ibiblio.org/lifepatterns/october1970.html)
