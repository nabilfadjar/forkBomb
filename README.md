# forkBomb
Fork Bomb on the Linux Machine

## What is this for?
This is to enable Fork Bomb on a linux Machine

## What was the motivation for this project?
Two of my co-workers have replaced my alias of `ls` and `ll` with a fork bomb command.

## What is the Fork Bomb?
As obtained from the definition from Wikipedia:
>In computing, a fork bomb (also called rabbit virus or wabbit[1]) is a denial-of-service attack wherein a process continually replicates itself to deplete available system resources, slowing down or crashing the system due to resource starvation.

*Link to [Fork Bomb](https://en.wikipedia.org/wiki/Fork_bomb)*

## What is the command to execute for the Fork Bomb?
Here is the command as follows:
```
:(){ :|: &};:
```
