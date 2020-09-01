---
layout: project
permalink: /:title/
category: projects

meta:
  keywords: "Jekyll, Pineapple"

project:
  title: "Automated Repository Tester"
  type: "Jekyll"
  url: "https://github.com/arnolds/pineapple"
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
<p style="padding: 0 0 2rem;">Customers of IPG requested support for SVG files, and there weren't any quick solutions online that would allow us to convert an SVG into the format we needed. </p>
<h2>My Part</h2>
<p style="padding: 0 0 2rem;">I developed a library that parsed an SVG file and converted it into a list of vectors for use with our software products. My library read through the XML and constructed a tree of shape nodes with the shape properties. I then used depth first traversal in order to create each shape from the specified properties, and combine everything into one list of vectors. The tree structure was needed because SVG files have group nodes that group shapes, or other group nodes together.</p>
