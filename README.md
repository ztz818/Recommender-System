# Recommender-System
分别基于协同过滤算法和基于TensorFlow建立推荐系统

一、基于协同过滤的推荐系统

协同过滤(collaborative filtering)：利用某兴趣相投、拥有共同经验之群体的喜好来推荐用户感兴趣的信息。比如说，你和另外一个人都喜欢看电影，而你们所喜欢的电影类型都差不多，那个人对于某一部电影的评价很高，而这部电影你没有看过。那么，我是不是就能将这部电影推荐给你呢？基于协同过滤的推荐，有基于用户和基于物品。

本项目可实现的功能：

1、基于用户的协同过滤

2、基于项目的协同过滤

3、基于内容的过滤算法

4、混合推荐系统

示例：
The 10 nearest neighbors of That Thing You Do! (1996):

Sleepless in Seattle (1993)

Braveheart (1995)

Toy Story (1995)

Batman (1989)

Groundhog Day (1993)

Pretty Woman (1990)

Star Trek: First Contact (1996)

While You Were Sleeping (1995)

Sabrina (1995)

Grosse Pointe Blank (1997)

具体实现见项目内代码

二、基于tensorflow的个性推荐系统


使用文本卷积神经网络，并利用多层循环深度网络完成电影推荐的任务。 

实现的推荐功能如下：

1、指定用户和电影进行评分

2、推荐同类型的电影

3、推荐您喜欢的电影

4、看过这个电影的人还看了（喜欢）哪些电影

系统结构如下

![](https://github.com/chengstone/movie_recommender/blob/master/assets/model.001.jpeg)

训练的loss：

![](https://github.com/chengstone/movie_recommender/blob/master/assets/loss.png)

示例：

推荐您喜欢的电影

以下是给您的推荐（用户234）：


1642

[1688 'Anastasia (1997)' "Animation|Children's|Musical"]

994

[1007 'Apple Dumpling Gang, The (1975)' "Children's|Comedy|Western"]

667

[673 'Space Jam (1996)' "Adventure|Animation|Children's|Comedy|Fantasy"]

1812

[1881 'Quest for Camelot (1998)' "Adventure|Animation|Children's|Fantasy"]

1898

[1967 'Labyrinth (1986)' "Adventure|Children's|Fantasy"]

具体实现见项目内代码

