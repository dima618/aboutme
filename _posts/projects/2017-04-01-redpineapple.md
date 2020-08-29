---
layout: project
permalink: /:title/
category: projects

meta:
  keywords: "Jekyll, Pineapple"

project:
  title: "Anti Juulinator"
  type: "The high tech solution to nicotine addiction"
  url: "https://github.com/dima618/JuulRecognizer"
  logo: "/assets/images/projects/redpineapple/logo.png"
  tech: "C#, Arduino, OpenCV"

agency:
  title: "Red Pineapple Co"
  url: "https://github.com/arnolds/pineapple"
  year: "2017"

images:
  - image:
    url: "/assets/images/projects/redpineapple/devices.jpg"
    alt: "Red Pineapple website on tablet, mobile and desktop"
  - image:
    url: "/assets/images/projects/redpineapple/desktop.jpg"
    alt: "Red Pineapple website on a desktop device"
  - image:
    url: "/assets/images/projects/redpineapple/mobile.jpg"
    alt: "Red Pineapple website on a mobile device"
---
<p>"How can we stop people vaping?" was a hot topic in 2019, so we proposed a solution: a stationary device that detects when a person brings a juul close to their face and shoots the person with water, or any liquid of choice. For the hardware, I used an arduino connected to 2 servos to control the spray head. I used the C# .NET framework to set up a windows forms application for calibrating and controlling the system. I used OpenCV to train a CascadeClassifier to recognize a Juul, and detected when the Juul would intersected with the face detection CascadeClassifier. A webcam was connected to the computer running the C# code, and we converted the positional data of the </p>
