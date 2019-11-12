+++
title = "SecureSizer: An gate-sizing framework for mitigating fault attacks in hardware"
date = 2019-06-03T06:12:56-07:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Fault attacks", "Hardware Security", "EDA for security"] 
categories = ["Hardware Security" ]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""


+++


Fault attacks are one of the growing physical attacks exploits that target edge devices. The attacker introduces faults at specific locations in the device during encryption thereby corrupting the result of the operation. These faults are introduced by either manipulating the system clock, the power supply or by using a laser. Traditional countermeasures rely on redundant logic, parity checking which introduce area and power overheads. In this work, we explore the idea of gate-sizing as a countermeasure for fault attacks. We observe that by modifying the parameters of the vulnerable gates, the side-channel resistance of the design improves. We leverage this observation and propose SecureSizer, a gate-sizing technique to improve the side-channel resistance of the design. We show that the overheads of the proposed technique are less when compared to traditional countermeasures.
