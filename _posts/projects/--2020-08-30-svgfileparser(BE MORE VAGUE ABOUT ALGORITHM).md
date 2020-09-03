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
<p style="padding: 0 0 2rem;">IPG needed to implement support for SVG files in our various software products, and there weren't any quick solutions online that would allow us to convert an SVG into the format we needed. </p>
<h2>My Part</h2>
<p style="padding: 0 0 2rem;">I developed a library that parsed an SVG file and converted it into a list of vectors for use with our software products. My library read through the XML and constructed a tree of shape nodes with the shape properties. I then used depth first traversal in order to create each shape from the specified properties, and combine everything into one list of vectors. The tree structure was needed because SVG files have group nodes that group shapes, or other group nodes together.</p>