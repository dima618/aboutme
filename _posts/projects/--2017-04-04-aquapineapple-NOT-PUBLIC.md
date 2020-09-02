---
layout: project
permalink: /:title/
category: projects

meta:
  keywords: ""

project:
  title: "Automated Repository Tester"
  type: "Jekyll"
  url: ""
  logo: "/assets/images/projects/aquapineapple/logo.png"
  tech: "C#, .NET Framework"

agency:
  title: "Aqua Pineapple Co"
  url: "https://github.com/arnolds/pineapple"
  year: "2018"

images:
  - image:
    url: "/assets/images/projects/aquapineapple/devices.jpg"
    alt: "Aqua Pineapple website on tablet, mobile and desktop"
  - image:
    url: "/assets/images/projects/aquapineapple/desktop.jpg"
    alt: "Aqua Pineapple website on a desktop device"
  - image:
    url: "/assets/images/projects/aquapineapple/mobile.jpg"
    alt: "Aqua Pineapple website on a mobile device"
---
<p style="padding: 0 0 2rem;">My supervisor at IPG has an ongoing project that I am lucky to be a part of. We are developing a program for automatically pulling and testing commits made to the company repository. Apart from building each solution, the system installs and runs each new commit of a software, then if necessary it tests the software using our laser controllers. The program acts as a safety net for all of the developers, and saves us tons of time on testing before a release.</p>
<h2>My Part</h2>
<p style="padding: 0 0 2rem;">I have been working on adding tests for the library that I have been responsible for maintaining and updating over the course of my internship, and creating tests for the TCP command feature of our flagship software. Testing each program requires a different approach, so automated tests have to be coded specifically for each software. The library tests test every shape generation function and output the each shape with various properties with the laser, and verifies the output. The TCP tests send TCP commands to the software and verify that the return messages match the expected returns. This is important because our customers use the TCP feature to automate their own processes and we need to ensure that our TCP commands and their returns never change.</p>
