# Human Language is a Distributed KV Store
An important theory invented by me on 3/30/2023. 
![](imgs/input-output)

The author(which is me) suggests that humans are state machines and language acquisition/maintenance is a thing only because all state machines form a large distributed KV store.

## Rule 1: Local Communication, Global Convergence
![](imgs/global-convergence)
$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$ *line weight represents communication frequency*

Newcomers(babies)<sup>[0]</sup> join the system and then perform log catch-up<sup>[1]</sup> with their most ajacent nodes(parents). Even though this kind of communication only happens locally, all the state machines in non-partitioned networks(countries) will eventually converge<sup>[2]</sup>.

<b>Note</b>:\
[0] In this rule we are talking about native speakers. \
[1] Log catch-up refers to language acquisition. \
[2] Convergence means when receiving a message "How are you", 99.99 percent of the state machines will reply with "I'm good".
