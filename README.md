# Deriving Spatio-Temporal Geographies of Human Mobility from GPS traces
<b> Abstract </b> <br>
This study leverages on the opportunities presented by individual-level GPS data to study human mobility within cities. It develops a methodology to understand the spatio-temporal properties of collective movements using network science. Through a spatially-weighted community detection approach, functional neighbourhoods derived from human mobility patterns are generated for different time intervals and a set of metrics computed to measure the extent to which they vary across time. The results show that while the overall city structure remains stable, functional neighbourhoods tend to contract and expand over the course of the day. This work sets up a methodology to detect short-term structural changes in cities based on human mobility.
<br>
<br>
![figure_1](https://user-images.githubusercontent.com/17129483/142650678-297b1335-faf5-47c3-98f7-1c5b5d813a99.png) <br>
###### Figure 1. Maps of the communities at the general level and across day profiles. The map shows day profile community changes (yellow area) with respect to the general communities (boundaries). Map of the New York City boroughs (a), map of the general communities (b), morning communities (c), midday communities (d), afternoon communities (e) and evening communities (f).
<br>
<img width="1099" alt="table_1" src="https://user-images.githubusercontent.com/17129483/142651749-e490ec51-c85f-4ca4-8b45-c1f8a4437209.png">

###### Table 1.  Functional neighbourhoods (or Communities) identified across the entire dataset are referred to as General and are used as the baseline to assess both the stability and change of Morning, Midday, Afternoon and Evening neighbourhoods. Area is the average area in km squared of the detected communities. Stability is described by: the average H3 cells’ percentage that remain within the same community as the General (Stability), its standard deviation and average area in km squared. Change is described by: the average H3 cells’ percentage that has changed community with respect to the General, its standard deviation and average area in km squared.
<br>
<br>
