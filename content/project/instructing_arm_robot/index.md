+++
date = "2018-01-23"
title = "Robot that performs language instructions"
summary = "Presented at European Researchers' Night in the Parlamentarium, Brussels, Belgium."

draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["human-robot interaction", "Robotics", "Deep Learning"]
categories = []

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[featured.jpg]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"

external_link = "https://zamani.github.io/outreach/outreach/"
+++
*Click* [*here*]({{< ref "outreach" >}}) *for more photos*

Spoken language is potentially the most intuitive way to communicate with robot. In this project, we assembled an arm robot to demonstrate to public, especially younger kids, how they can instruct robot to perform actions. This project includes automatic speech recognition (ASR), text to speech, spoken language understanding, vision, and motion planning. 

To work with our robot, a user can wake up the robot by its name "Jarvis". Then, the robot confirms that is ready to receive a new command by saying "Yes!". After hearing the confirmation, the user give a command such as "Pick cube number 5 and put it near cube numebr 1". Although, we had our own domain-specific ASR model, due to operating condition which was in an extremely noisy condition we used the Google ASR. We ask the Google ASR the top most probable hypotheses. These hypotheses are used to identify the intended cubes as well as a target position for the picked cube. If there was no target position is commanded then robot performed a handover when users says "Release!".

 Using a top camera robot locates the cubes using the April tags on top each cubes and using moveIt! package it plans and performs the trajectory to reach to the cube. Jarvis can grasp the cube using a electomagnet which is installed at the end-effector of the robot. There is also a metal piece is attached to the top of the cubes. 

