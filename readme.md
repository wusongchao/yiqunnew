This program is quite slow, a simple way to make it faster is to parallelize the path construction phase, but i hadn't done it.

For some dataset, this program can reach a solution that not so bad, but i've only test it on several small data set, which can be found in tsplib. Of course, i will only post some "good" result, here's some screenshots.


eil51: 426(optimum) / 442.42(this program's solution) = 0.96
![Alt text](https://github.com/wusongchao/ACO-on-TSP/raw/master/screenshots/eil51.png)

eil101: 629(optimum) / 710.165(this program's solution) = 0.89
![Alt text](https://github.com/wusongchao/ACO-on-TSP/raw/master/screenshots/eil101.png)

berlin52: 7542(optimum) / 7678(this program's solution) = 0.98
![Alt text](https://github.com/wusongchao/ACO-on-TSP/raw/master/screenshots/berlin52.png)

optimum can be found in this website:
[https://www.iwr.uni-heidelberg.de/groups/comopt/software/TSPLIB95/STSP.html]

# UPDATE
In this version, i fix some small "bug" and do a tiny change to the parameter, that is, make the initial value of Tau from 0 to 1. In some case, this will improve performance.

eil51: 426(optimum) / 451.059(this program's solution) = 0.94
![Alt text](https://github.com/wusongchao/ACO-on-TSP/raw/master/screenshots/eil51new.png)

eil101: 629(optimum) / 688.416(this program's solution) = 0.91
![Alt text](https://github.com/wusongchao/ACO-on-TSP/raw/master/screenshots/eil101new.png)

berlin52: 7542(optimum) / 7677.12(this program's solution) = 0.98
![Alt text](https://github.com/wusongchao/ACO-on-TSP/raw/master/screenshots/berlin52new.png)