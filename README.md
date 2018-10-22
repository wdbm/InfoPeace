# InfoPeace

![](https://raw.githubusercontent.com/wdbm/InfoPeace/master/media/McDonalds_Nutrition_Systems.png)

The beginnings of a collection of ideas for societal-level defences against active disinformation campaigns and strategies or: How I learned to stop worrying and start a collaborative repository to try to address mind-hacking and consider development of Kōans for neo-fascists

# Some broad ideas

## Observable radicalization networks

[*Alternative Influence: Broadcasting the Reactionary Right on YouTube*](https://www.wdbm.pro/fb6041c5-a4ae-4b5e-bc3f-71d4bcd68d11) attempts to describe an "Alternative Influence Network" (AIN) consisting of a network featuring vertices that use YouTube to communicate information, and attempts to describe characteristics of the vertices. It attempts to qualify, to some degree, the radicalization capabilities of this network.

## Generalized Network Dismantling

[*Generalized Network Dismantling*](https://www.wdbm.pro/6332ea7e-18aa-4f5d-9f6c-5203654296a2) suggests ideas that disrupt information networks. While the current generations of [adversarial examples](https://www.wdbm.pro/52dd98ab-161b-4879-91b4-5f8981832540) in the context of machine learning might not be applicable to individual humans, might they be applicable to networks of humans? How would generalized network dismantling techniques in social media be implemented, observed or even combated?

There are many tools available in this context ranging from ethical to unethical. One class of tool is counter-disinformation. Another class of tool is deplatforming/node attenuation.

### Scale-free networks

The degree of a vertex in a graph or network is the number of connections it has to other nodes, and the degree distribution is the probability distribution of these degrees over the whole network. A scale-free network is a network that has a degree distribution that follows a power law, at least asymptotically. Examples of scale-free networks might be the scientific paper citation network, or the [webgraph](https://en.wikipedia.org/wiki/Webgraph) of the World Wide Web, or social networks.

Scale-free networks are more robust to random attacks than random network structures but are *more vulnerable* to targeted attacks. Finding the set of influential vertices (the minimal set of nodes the removal of which results in the network fragmented into subnetworks of subcritical size is called the network dismantling problem. It is an NP-hard problem. The paper [*Generalized Network Dismantling*](https://www.wdbm.pro/6332ea7e-18aa-4f5d-9f6c-5203654296a2) attempts to address the question of how to select the set of vertices which, when removed/deactivated/attenuated can stop the spread of (dis)information. The paper posits the idea of the cost of removing a node, a non-negative real number, which might be defined by a function of vertex centrality characteristics, such as degree, page-rank, betweenness or other characteristics not suitable for description in a simple graph object.

# IPUUID4

This is a simple general reference format that can be generated in the following way, perhaps as a `.bashrc` function:

```Python
ipuuid4(){python -c "import uuid; print(uuid.uuid4())"}
```

Such identifier codes could be used with a link-shortening service like [ovipositor](https://www.wdbm.pro/ovipositor).

![](https://raw.githubusercontent.com/wdbm/InfoPeace/master/media/image20181018_175523456.jpg)
![](https://raw.githubusercontent.com/wdbm/InfoPeace/master/media/image20181018_175644246.jpg)

# Aesthetic Colors

|**color**  |**hexcode**|
|-----------|-----------|
|![][f1e1bd]|\#f1e1bd   |
|![][eeba85]|\#eeba85   |
|![][e18d76]|\#e18d76   |
|![][9c837e]|\#9c837e   |
|![][5b7887]|\#5b7887   |

# Background

The following is a proposed order of consumption. Inclusion does not imply endorsement.

|**relative aesthetic**|**title**                                                                                                              |**author(/s)**/**sources**                                       |**datetime**   |**comments**                                  |**IPUUID4**                                                     |
|----------------------|-----------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------|---------------|----------------------------------------------|----------------------------------------------------------------|
|![][5b7887]           |*THE ROBOT AND THE BABY*                                                                                               |John McCarthy                                                    |2004-10-16T1656|                                              |[ref](https://www.wdbm.pro/09663760-cbdf-4bb4-bd06-ff1fbffb1224)|
|![][5b7887]           |*Machete Season*                                                                                                       |Jean Hatzfeld                                                    |2003           |                                              |[ref](https://www.wdbm.pro/38f6de7a-0d4f-41a0-ab38-4420dce30da2)|
|![][5b7887]           |*Manna*                                                                                                                |Marshall Brain                                                   |2003           |                                              |[ref](https://www.wdbm.pro/1522b5e6-56df-4208-acbd-18c48325d211)|
|![][9c837e]           |*A Declaration of the Independence of Cyberspace*                                                                      |John Perry Barlow                                                |1996-02-08     |                                              |[ref](https://www.wdbm.pro/226e9b26-0dd5-4623-8c79-7cc59af9520c)|
|![][f1e1bd]           |*The Tao of Programming*                                                                                               |Geoffrey James                                                   |1987           |                                              |[ref](https://www.wdbm.pro/73925d3a-5d04-4f04-9c68-b0408c55553d)|
|![][5b7887]           |*What is free software? Version 1.153*                                                                                 |Richard M. Stallman                                              |2018           |                                              |[ref](https://www.wdbm.pro/80e7b3a2-8577-4836-875b-5faace8c6699)|
|![][e18d76]           |*Cryptonomicon*                                                                                                        |Neal Stephenson                                                  |1999           |                                              |[ref](https://www.wdbm.pro/ced3e3de-0267-4684-8fa3-5814d0a4e23d)|
|![][5b7887]           |*Bitcoin: A Peer-to-Peer Electronic Cash System*                                                                       |Satoshi Nakamoto                                                 |2008-11        |                                              |[ref](https://www.wdbm.pro/e726c7ad-03c4-4ee1-b551-4941ba5788eb)|
|![][5b7887]           |*The Electome: Where AI Meets Political Journalism*                                                                    |MIT Media Lab                                                    |2016-08-29     |                                              |[ref](https://www.wdbm.pro/52e4ebd8-34ff-4d1b-aae1-17b974fcb62c)|
|![][f1e1bd]           |*Lying*                                                                                                                |Sam Harris                                                       |2011           |                                              |[ref](https://www.wdbm.pro/ea8161fb-f288-4723-af4f-3052608ccecb)|
|![][f1e1bd]           |*Solaris*                                                                                                              |Stanisław Lem                                                    |1961           |                                              |[ref](https://www.wdbm.pro/a7f408a8-07c8-40ed-9308-ff55d22576b5)|
|![][9c837e]           |*Solaris*                                                                                                              |Andrei Tarkovsky                                                 |1972-05-13     |                                              |[ref](https://www.wdbm.pro/a4ee0cae-29f6-47b2-92cd-b7e926437659)|
|![][f1e1bd]           |*The Three Stigmata of Palmer Eldritch*                                                                                |Philip K. Dick                                                   |1965           |                                              |[ref](https://www.wdbm.pro/d00658f0-e428-4b2f-8f98-dddb8703d7c6)|
|![][e18d76]           |*Alternative Influence: Broadcasting the Reactionary Right on YouTube*                                                 |Rebecca Lewis                                                    |2018-09        |                                              |[ref](https://www.wdbm.pro/fb6041c5-a4ae-4b5e-bc3f-71d4bcd68d11)|
|![][e18d76]           |*Stalker*                                                                                                              |Andrei Tarkovsky                                                 |1979           |                                              |[ref](https://www.wdbm.pro/b2142bf8-ee16-4a51-bbab-9c035bc1db68)|
|![][5b7887]           |*The Hidden Author of Putinism*                                                                                        |Peter Pomerantsev                                                |2014-11-07     |                                              |[ref](https://www.wdbm.pro/fa79ffd4-087f-4ef3-a107-33537bb6aed7)|
|![][f1e1bd]           |*Orbis Sensualium Pictus [Visible World in Pictures]*                                                                  |John Amos Comenius                                               |1658           |                                              |[ref](https://www.wdbm.pro/b318a281-e8b8-4750-959b-c8703d4b48ee)|
|![][5b7887]           |*HyperNormalisation*                                                                                                   |Adam Curtis                                                      |2016-10-16     |                                              |[ref](https://www.wdbm.pro/23959c86-4a06-4d6e-ab02-d99f02348740)|
|![][f1e1bd]           |*The Terminator* subliminals in the punks scene                                                                        |Rob Ager, James Cameron                                          |2017-06-30     |                                              |[ref](https://www.wdbm.pro/86edceb2-21a5-4c78-92b5-d94eb4258d7b)|
|![][f1e1bd]           |*The Terminator* subliminals in the Tech Noir club scene                                                               |Rob Ager, James Cameron                                          |2016-09-01     |                                              |[ref](https://www.wdbm.pro/454eeafd-8a18-461d-bba6-805d379f001d)|
|![][5b7887]           |*The Aesthetic*                                                                                                        |Natalie Wynn/ContraPoints                                        |2018-09-19     |                                              |[ref](https://www.wdbm.pro/52840730-e790-44b7-a9b3-5592e7651972)|
|![][9c837e]           |*The Panama Papers*                                                                                                    |Bastian Obermayer, Frederik Obermaier                            |2016           |                                              |[ref](https://www.wdbm.pro/48fda897-d266-45a1-93ea-c3156154df58)|
|![][f1e1bd]           |*The CERN ritual*                                                                                                      |unknown                                                          |2016-08        |                                              |[ref](https://www.wdbm.pro/c646da7a-a731-4b68-87b7-e251c3c4d5b1)|
|![][f1e1bd]           |*Fear: Trump in the White House*                                                                                       |Bob Woodward                                                     |2018-09-11     |                                              |[ref](https://www.wdbm.pro/88591f31-875a-472b-a828-3e332859d1e4)|
|![][e18d76]           |*Foundations of Geopolitics*                                                                                           |Aleksandr Dugin                                                  |1997           |2018-10-17 Google Translate Russian to English|[ref](https://www.wdbm.pro/642229f1-319e-43b7-9492-dc678b08698b)|
|![][f1e1bd]           |*The non-paradox of tolerance*                                                                                         |Zinnia Jones                                                     |2011-06-09     |                                              |[ref](https://www.wdbm.pro/6c689bba-bd51-4468-8f3a-545968cb29a2)|
|![][5b7887]           |*Decrypting the Alt-Right: How to Recognize a F@scist*                                                                 |Natalie Wynn/ContraPoints                                        |2017-09-01     |                                              |[ref](https://www.wdbm.pro/b35ea4b1-1ed0-4ad5-ae9c-4b2ebbb60c79)|
|![][5b7887]           |*High Commissioner Dialogue with Ben Ferencz*                                                                          |UN                                                               |2018-08-07     |                                              |[ref](https://www.wdbm.pro/0f2dd31f-3d38-4e48-b313-3f031f28d3a2)|
|![][f1e1bd]           |*From Dictatorship to Democracy*                                                                                       |Gene Sharp                                                       |1993           |                                              |[ref](https://www.wdbm.pro/0900817a-4a62-49b1-8fce-77d128d817b1)|
|![][e18d76]           |*Prevent Strategy*                                                                                                     |UK Home Office                                                   |2011           |                                              |[ref](https://www.wdbm.pro/ee66cf1c-59f9-40fb-9172-fe0e6042d978)|
|![][eeba85]           |*Enabling further research of information operations on Twitter*                                                       |Vijaya Gadde, Yoel Roth                                          |2018-10-17     |                                              |[ref](https://www.wdbm.pro/d2393913-1417-4644-90e4-d09fdd3eb265)|
|![][5b7887]           |*Generalized Network Dismantling*                                                                                      |Xiao-Long Ren, Niels Gleinig, Dirk Helbing, Nino Antulov-Fantulin|2018-01-04     |                                              |[ref](https://www.wdbm.pro/6332ea7e-18aa-4f5d-9f6c-5203654296a2)|
|![][5b7887]           |*Adversarial examples in the physical world*                                                                           |Alexey Kurakin, Ian Goodfellow, Samy Bengio                      |2016-07-08     |                                              |[ref](https://www.wdbm.pro/52dd98ab-161b-4879-91b4-5f8981832540)|
|![][5b7887]           |*Believing Bullshit: How Not to Get Sucked into an Intellectual Black Hole*                                            |Stephen Law                                                      |2011           |                                              |[ref](https://www.wdbm.pro/48d4c55d-86b5-4cfe-8b68-33ffbe98c21e)|
|![][9c837e]           |*Unskilled and Unaware of It: How Difficulties in Recognizing One's Own Incompetence Lead to Inflated Self-Assessments*|Justin Kruger, David Dunning                                     |1999           |                                              |[ref](https://www.wdbm.pro/ca20479b-5d43-4177-b035-85e7a2b4c0a4)|
|![][9c837e]           |*Utopia for Realists*                                                                                                  |Rutger Bregman                                                   |2017           |                                              |[ref](https://www.wdbm.pro/5e66187b-aedd-4974-92bb-19c7bcde1ee1)|
|![][5b7887]           |*TFLOSSH: Towards Free/Libre and Open Source Software and Hardware*                                                    |Will Breaden Madden                                              |2018           |                                              |[ref](https://www.wdbm.pro/82ef0d86-6564-48a5-813d-a55e319fe45b)|
|![][9c837e]           |*denarius unconditional universal basic income guarantee (that section)*                                               |Will Breaden Madden                                              |2018           |                                              |[ref](https://www.wdbm.pro/becca019-ae8f-47e3-a643-f27bece03534)|
|![][eeba85]           |*distributed_wellbeing*                                                                                                |Will Breaden Madden                                              |2016           |                                              |[ref](https://www.wdbm.pro/701e1a41-6fc2-4386-84cb-4540818c784f)|
|![][5b7887]           |*Apocalypse Now*                                                                                                       |Francis Coppola                                                  |1979-05-10     |                                              |[ref](https://www.wdbm.pro/518900c6-1962-4b33-8799-276a2a4f93de)|

# Resources

|**relative aesthetic**|**title**                                                                                                              |**author(/s)**/**sources**                                       |**datetime**   |**comments**                                  |**IPUUID4**                                                     |
|----------------------|-----------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------|---------------|----------------------------------------------|----------------------------------------------------------------|
|![][f1e1bd]           |*Bellingcat’s Digital Toolkit*                                                                                         |Bellingcat                                                       |2018-06        |                                              |[ref](https://www.wdbm.pro/9a10dc63-1b46-47e3-b097-3e8900e77c0f)|

# Data

|**relative aesthetic**|**title**                                                                                                              |**author(/s)**/**sources**                                       |**datetime**   |**comments**                                  |**IPUUID4**                                                     |
|----------------------|-----------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------|---------------|----------------------------------------------|----------------------------------------------------------------|
|![][5b7887]           |*Twitter Elections Integrity Database*                                                                                 |Twitter                                                          |2018-10-17     |                                              |[ref](https://www.wdbm.pro/1f775bd3-f8c3-4b74-86cb-50db965fe682)|

![](https://raw.githubusercontent.com/wdbm/InfoPeace/master/media/2018-10-19T1432Z.png.png)

[//]: # (handy reference-style links)

[f1e1bd]: https://raw.githubusercontent.com/wdbm/InfoPeace/master/media/f1e1bd.png
[eeba85]: https://raw.githubusercontent.com/wdbm/InfoPeace/master/media/eeba85.png
[e18d76]: https://raw.githubusercontent.com/wdbm/InfoPeace/master/media/e18d76.png
[9c837e]: https://raw.githubusercontent.com/wdbm/InfoPeace/master/media/9c837e.png
[5b7887]: https://raw.githubusercontent.com/wdbm/InfoPeace/master/media/5b7887.png
