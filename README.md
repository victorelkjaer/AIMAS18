# Artificial Intelligence & Multi Agent Systems 2018

This repo contains the work of [Victor Elkjær Birk](https://github.com/victorelkjaer), [William Frisch Møller](https://en.wikipedia.org/wiki/Moustache#Styles) and [Daniel Thoren](https://github.com/DannyDannyDanny) for the course [Artificial Intelligence and multi-agent systems](http://kurser.dtu.dk/course/02285) at DTU.

## Set up git and pull the repo
1. I'll give you [collaborator access](https://help.github.com/articles/permission-levels-for-a-user-account-repository/#collaborator-access-on-a-repository-owned-by-a-user-account), which, most importantly, gives you pull/push access to the repo.

2. Setup git on your machine - either with [Github Desktop (recommended)](https://desktop.github.com) or [manually](https://help.github.com/articles/set-up-git/#setting-up-git).

3. At the top of the page press **setup in desktop** (or use terminal and git) to setup the repository on your machine. Take a note of the directory in which you place the repo.

4. Enter your favorite Emoji below, then **commit** and **push** the git - verify that the emoji shows up on the [repo webpage](https://github.com/DannyDannyDanny/AIMAS18).

## About the authors
* **Danny** mustache lvl 0
* **Victor**
* **William**

## Warmup Assignment

### Compile and run files (java)
* Open a new terminal session
* Navigate to the repo's folder `01 Warmup Assignment` directory with:
`cd ~/Path/To/Repo/01\ Warmup\ Assignment/`
* Compile SearchClient java files with:
`javac searchclient/*.java`
* Run code:
`java -jar server.jar -l levels/SAD1.lvl -c "java -Xmx2g searchclient.SearchClient -dfs" -g 50 -t 300`

* Set parameters
  * *In the example above we are using the DFS algorithm and 2GB RAM.*
  * *Replace `-dfs`- with `-astar`, `-wastar` or `-greedy` to change search algorithm*
  * *Replace `-Xmx2g` with another RAM setting limit or `-jar`*
