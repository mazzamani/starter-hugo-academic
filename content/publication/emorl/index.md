+++

title = "EmoRL: Real-time Acoustic Emotion Classification using Deep Reinforcement Learning"
authors = ["Egor Lakomkin*", "Mohammad Ali Zamani*", "Cornelius Weber", "Sven Magg", "Stefan Wermter"]

date = 2018-05-22

publication = "International Conference on Robotics and Automation (ICRA), 2018"

abstract = "Acoustically expressed emotions can make communication with a robot more efficient. Detecting emotions like anger could provide a clue for the robot indicating unsafe/undesired situations. Recently, several deep neural network-based models have been proposed which establish new state-of-the-art results in affective state evaluation. These models typically start processing at the end of each utterance, which not only requires a mechanism to detect the end of an utterance but also makes it difficult to use them in a real-time communication scenario, e.g. human-robot interaction. We propose the EmoRL model that triggers an emotion classification as soon as it gains enough confidence while listening to a person speaking. As a result, we minimize the need for segmenting the audio signal for classification and achieve lower latency as the audio signal is processed incrementally. The method is competitive with the accuracy of a strong baseline model, while allowing much earlier prediction."
abstract_short = "International Conference on Robotics and Automation (ICRA), 2018"
draft = false

url_pdf = "https://arxiv.org/abs/1804.04053"
url_dataset = ""
url_code = ""
url_project = "http://secure-robots.eu/"
url_slides = ""
url_video = "https://www.youtube.com/watch?v=bheIo0RUwT0"
#image = "static/img/portrait.jpg"
image_preview = "portrait.jpg"
math = false


# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Reinforcement Learning", "Human-Robot Interaction", "Emotion Recognition", "demos"]
categories = []
featured= true
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[portrait.jpg]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Left"
+++
{{<youtube bheIo0RUwT0>}}
