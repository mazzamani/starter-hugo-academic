+++
title = "Seminar Talk"
date = 2017-06-17T14:15:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
#time_start = 2030-06-01T13:00:00
#time_end = 2030-06-01T15:00:00
all_day = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

# Abstract and optional shortened version.
abstract = ""
abstract_short = "Reinforcement Learning using Symbolic Representation for Performing Spoken Language Instructions"

# Name of event and optional event URL.
event = "Seminar/Oberseminar: Knowledge Technology Group, University of Hamburg"
event_url = ""

# Location of event.
location = "Hamburg, Germany"

# Is this a featured talk? (true/false)
featured = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["internal-project"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = "example-slides"

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Does the content use math formatting?
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)


  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Right"
+++
Abstract: 
Spoken language is one of the most efficient ways to instruct robots about performing domestic tasks. However, the state of the environment has to be considered to successfully plan and execute the actions. We propose a system which can learn to recognize the user's intention and map it to a goal for a reinforcement learning (RL) system. This system is then used to generate a sequence of actions toward this goal considering the state of the environment. Symbolic representations are used for both input and output of a Deep RL module. To show the effectiveness of our approach, the TellMeDave corpus is used to train the intention detection model and in a second step train the RL module towards the detected objective represented by a set of state predicates. We show that the system can successfully recognize instructions from this corpus and map them to the corresponding objective as well as train an RL system with symbolic input.
