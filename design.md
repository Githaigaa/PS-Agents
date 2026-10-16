# GROUP MEMBERS
- 168974 – Koi JoyJudy Wangui
- 189545 – Omondi Angela Achieng
- 189225 – Githaiga Emmanuel Mundia

## QUESTION 1
PEAS Framework Design
Performance Measure: Fuel Efficiency, time taken to reach the destination (Kisumu), cost of the path(total kilometers travelled), safety(avoiding collision) (Stuart Russell, 2022).
Environment: Road signs & traffic lights, weather conditions, pedestrians, traffic & other vehicles, towns along the road, highway networks for example A8, B1, B3, B5.
Actuators: Steering wheel, accelerator, brake, indicators, gear shift (Vikiru, 2026).
Sensors: GPS, speedometer, radar, Cameras

Classifying the Environment
a.	Observability
Partially observability – The agent is not fully aware of its environment since it cannot see beyond hills and buildings or even around meandering corners along the roads.

b.	Determinism
Stochastic – The next state cannot be determined only by the actions and current state of the agent (Vikiru, 2026). Other drivers, pedestrians, and weather conditions make the environment unpredictable.

c.	Episodic vs Sequential
Sequential – Current actions depend on the previous actions (Vikiru, 2026). For example, deciding to turn right at Oyugis depends on having driven from Bomet through Narok.

d.	Static vs Dynamic
Dynamic – The environment changes while the agent is deliberating to choose an action (Stuart Russell, 2022). For example, Traffic moves, traffic lights change, and speed limit also changes. This requires the agent to consult the environment frequently and act in real-time.

e.	Single vs multi-Agent
Multi-Agent – The trailer operates with other agents such that the agent’s decision affect and are affected by these other agents for example, human drivers, pedestrians and cyclists.

References
Stuart Russell, P. N. (2022). Artificial Intelligence A Modern Approach (4 ed.). Pearson. Retrieved from Artificial Intelligence A Modern Approach.pdf
Vikiru, A. (2026). Intelligent Agents. 1-34. Retrieved from Intelligent Agents.pdf



## QUESTION 2: DIRECTED GRAPH AND SEARCH TREE
![A directed graph showing possible paths that the PS-Agent can take.](https://github.com/JoyJudy/PS-Agents/blob/main/images/DIRECTED-GRAPH.drawio.png)

![A search tree showing possible routes from Nairobi, the initial state, to Kisumu, the goal state.](https://github.com/JoyJudy/PS-Agents/blob/main/images/SEARCH_TREE.jpg)


## QUESTION 3
| PATH | DISTANCE(KM) |
|:-------------|--------------:|
| Ahero - Kisumu | 23.5 |
| Bomet - Kisii | 84 |
| Bomet - Litein | 46 |
| Eldoret - Kapsabet | 47 |
| Eldoret - Webuye | 72 |
| Kakamega - Kisumu | 51 |
| Kapsabet - Kisumu | 80.3 |
| Kapsoit - Ahero | 49.9 |
| Kapsoit - Kisumu | 72.9 |
| Kericho - Ahero | 60.9 |
| Kericho - Kapsoit | 11.3 |
| Kisii - Oyugis | 28 |
| Litein - Kericho | 33 |
| Maai Mahiu - Narok | 89 |
| Molo - Kericho | 64.2 |
| Nairobi - Maai Mahiu | 53.8 |
| Nairobi - Nakuru | 161 |
| Nakuru - Eldoret | 158 |
| Nakuru - Kericho | 108 |
| Nakuru - Molo | 48.5 |
| Nakuru - Nyahururu | 63.5 |
| Narok - Bomet | 81 |
| Nyahururu - Molo | 111 |
| Oyugis - Ringa | 14 |
| Ringa - Sondu | 22 |
| Sondu - Ahero | 29.5 |
| Webuye - Kakamega | 48.5 |

  
### PATH COSTS
1. Nairobi - Nakuru - Kericho - Kapsoit - Ahero - Kisumu: **353.7km**
2. Nairobi - Nakuru - Molo - Kericho - Kapsoit - Kisumu: **357.9km**
3. Nairobi - Nakuru - Eldoret - Kapsabet - Kisumu: **446.3km**
4. Nairobi - Nakuru - Eldoret - Webuye - Kakamega - Kisumu: **490.5km**
5. Nairobi - Nakuru - Nyahururu - Molo - Kericho - Kapsoit - Ahero - Kisumu: **484.4km**
6. Nairobi - Maai Mahiu - Narok - Bomet - Kisii - Oyugis - Ringa - Sondu - Ahero - Kisumu: **424.8km**
7. Nairobi - Maai Mahiu - Narok - Bomet - Litein - Kericho - Ahero - Kisumu: **387.2km**


**_OPTIMAL PATH_**: Nairobi - Nakuru - Kericho - Kapsoit - Ahero - Kisumu<br/>
**_OPTIMAL PATH COST_**: **353.7km**


## GROUP PHOTO
![Team Members](https://github.com/JoyJudy/PS-Agents/blob/main/images/Group%20Work%20Photo.jpeg)
