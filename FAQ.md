# Frequently asked questions about my text visualization programming experiments

## How and why did you get started creating animations using only text?
After running my own YouTube channel for over a year during high school, I became interested in animations using the Adobe After Effects tool.
This tool allows users to create custom animations using code. 
So I started experimenting with applying my coding skills to create unique animations with only text that I had never seen done before.
By limiting myself to text characters it forced me to apply mathematics and a variety of programming techniques to create the animations.

## What specific technologies did you use for these visualizations?
I primarily used JavaScript and Adobe After Effects.
During the course of my journey, for various experiments, I ventured outside of After Effects and ended up coding a basic math parser, a basic markdown parser and a 3d cube visualization as separate side projects.
I also ended up taking an online course on writing parsers which strengthened my experience with recursive approaches to problem solving.

## How often do you apply mathematical concepts to create your animations?
It depends on the animation. I use trigonometric functions like sin() and cos() a lot since they allow me to loop my animations infinitely due to their unique wave shapes. 
For one animatio where I had a bunch of text characters oscillate in the shape of a [lemniscate](https://en.wikipedia.org/wiki/Lemniscate)/infinity symbol, I had to [derive the parametric equations](https://twitter.com/textperimentor/status/1645170198800891910/photo/1) for a lemniscate so they could be represented in JavasScipt. 
The cartesian equation of a lemniscate cannot be represented in JavaScript due to its nature.
All other infinity symbol animations that I found online used keyframes to “hardcode” the lemniscate shape with approximation rather than doing it dynamically.
