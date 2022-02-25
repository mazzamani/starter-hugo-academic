+++
title = "Deep Reinforcement Learning using Symbolic Representation for Performing Spoken Language Instructions"
authors = ["Mohammad Ali Zamani", "Sven Magg", "Cornelius Weber", "Stefan Wermter"]

date = 2017-09-28

publication = "In 2nd Workshop on Behavior Adaptation, Interaction and Learning for Assistive Robotics (BAILAR) in 26th IEEE International Symposium on Robot and Human Interactive Communication (RO-MAN), 2017"

abstract = "Spoken language is one of the most efficient ways to instruct robots about performing domestic tasks. However, the state of the environment has to be considered to plan and execute the actions successfully. We propose a system which can learn to recognise the user’s intention and map it to a goal for a reinforcement learning (RL) system. This system is then used to generate a sequence of actions toward this goal considering the state of the environment. The novelty is the use of symbolic representations for both input and output of a neural Deep Q-network which enables it to be used in a hybrid system. To show the effectiveness of our approach, the Tell Me Dave corpus is used to train the intention detection model and in a second step to train the RL module towards the detected objective, represented by a set of state predicates. We show that the system can successfully recognise command sequences from this corpus as well as train the deep-RL network with symbolic input. We further show that the performance can be significantly increased by exploiting the symbolic representation to generate intermediate rewards."
abstract_short = "In 2nd Workshop on Behavior Adaptation, Interaction and Learning for Assistive Robotics (BAILAR) in 26th IEEE International Symposium on Robot and Human Interactive Communication (RO-MAN), 2017"
draft = false

url_pdf = "http://www.cogrobotics.unina.it/roman/papers/BAILAR2017_paper_7.pdf"
url_dataset = ""
url_code = ""
url_project = "http://secure-robots.eu/"
url_slides = ""
url_video = ""
#image = "static/img/portrait.jpg"
image_preview = ""
math = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Reinforcement Learning", "Spoken Language Instruction"]
categories = []

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[portrait.jpg]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
{{< figure src="featured1.png" title="" >}}
