---
layout: project
permalink: /:title/
category: projects

meta:
  keywords: "Jekyll, Pineapple"

project:
  title: "SVG to Vector Converter"
  type: "Library to convert an SVG to a list of vectors"
  url: ""
  logo: "/assets/images/projects/yellowpineapple/logo.png"
  tech: "C#, .NET Framework"

agency:
  title: "Yellow Pineapple Co"
  url: "https://github.com/arnolds/pineapple"
  year: "2019"

images:
  - image:
    url: "/assets/images/projects/yellowpineapple/IPG-SVG.PNG"
    alt: "SVG after it's converted"
  - image:
    url: "/assets/images/projects/yellowpineapple/2020.svg"
    alt: "SVG"
---
<p style="padding: 0 0 2rem;">IPG needed to implement support for SVG files in various software products. There weren't any quick solutions online that would allow us to convert an SVG into a format that would be easy to integrate with our software, so I developed a solution.</p>
<h2>My Part</h2>
<p style="padding: 0 0 2rem;">I developed a library that parsed an SVG file and converted it into a list of vectors for use with our software products. I constructed a tree from the SVG shapes and traversed through it to assemble a vector list that IPG software could use. The tree structure was needed because SVG files have group nodes that group shapes, or other group nodes together. I implemented the library into IPG's flagship software and graphics library and released both to customers.</p>
