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
  year: "2019"

images:
  - image:
    url: "/assets/images/projects/redpineapple/FacialRecognitionCapture.PNG"
    alt: "Red Pineapple website on tablet, mobile and desktop"
  - image:
    url: "/assets/images/projects/redpineapple/JuulandFace.PNG"
    alt: "Red Pineapple website on a desktop device"
  - image:
    url: "/assets/images/projects/redpineapple/desktop.jpg"
    alt: "Red Pineapple website on a mobile device"
---
<p style="padding: 0 0 2rem;">"How can we stop people from vaping?" was a hot topic in 2019, so we proposed a solution: a stationary device that detects when a person brings a juul close to their face and shoots the person with water, or any liquid of choice. This was acomplished by a camera, and a rotating spray head that would aim at the person within the camera's view and shoot them with water if necessary.</p>
<h2>My Part</h2>
<h1>Software:</h1>
<p style="padding: 0 0 2rem;">I created a Windows Forms Application using the C# .NET framework for calibrating and running the OpenCV image recognition for both: Juuls and faces. For recognizing the Juul I had to train a CascadeClassifier myself, but luckily OpenCV already provided a CascadeClassifier trained for faces. Since the webcam on the computer was separate from the spray head and could be placed anywhere, I had to implement a calibration tool that would record the servo positions when the spray head was pointed in each corner of the camera view. Using these servo positions, I was able to translate coordinates from the webcam's view to the correct servo positions; ensuring that the spray head was pointed at the person.</p>
<h1>Hardware:</h1>
<p style="padding: 0 0 2rem;">I wired up an arduino with 2 servos to rotate our motorized spray head around 2 axes, and wired up a transistor to the electric motor on the spray head so that we could fire the spray head using a signal from the arduino.</p>
<p style="padding: 2rem 0 0;">My partner's responsibilities included writing the code for the arduino, and mounting the sprayhead onto the 2 servo's.</p>

