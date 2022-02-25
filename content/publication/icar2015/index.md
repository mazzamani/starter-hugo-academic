+++
title = "Simultaneous Human-Robot Adaptation for Effective Skill Transfer"
authors = ["Mohammad Ali Zamani", "Erhan Oztop"]

date = 2017-09-28

publication = "International Conference on Advanced Robotics (ICAR), 2015"

abstract = "In this paper, we propose and implement a human-in-the loop robot skill synthesis framework that involves simultaneous adaptation of the human and the robot. In this framework, the human demonstrator learns to control the robot in real-time to make it perform a given task. At the same time, the robot learns from the human guided control creating a non-trivial coupled dynamical system. The research question we address is how this system can be tuned to facilitate faster skill transfer or improve the performance level of the transferred skill. In the current paper we report our initial work for the latter. At the beginning of the skill transfer session, the human demonstrator controls the robot exclusively as in teleoperation. As the task performance improves the robot takes increasingly more share in control, eventually reaching full autonomy. The proposed framework is implemented and shown to work on a physical cart-pole setup. To assess whether simultaneous learning has advantage over the standard sequential learning (where the robot learns from the human observation but does not interfere with the control) experiments with two groups of subjects were performed. The results indicate that the final autonomous controller obtained via simultaneous learning has a higher performance measured as the average deviation from the upright posture of the pole."
abstract_short = "International Conference on Advanced Robotics (ICAR), 2015"
draft = false

url_pdf = "https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7251437"
url_dataset = ""
url_code = ""
url_project = "http://robotics.ozyegin.edu.tr/convergent-human-learning-for-robot-skill-generation/"
url_slides = ""
url_video = "https://www.youtube.com/watch?v=S3NW0hr72mU"
#image = "static/img/portrait.jpg"
image_preview = ""
math = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Human-robot Interaction", "Human-in-the-loop", "Imitation Learning", "Learning by Demonstration", "demos"]
categories = []

# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types= ["-1"]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[portrait.jpg]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
{{< figure src="featured2.png" title="" >}}
{{<youtube S3NW0hr72mU>}}
