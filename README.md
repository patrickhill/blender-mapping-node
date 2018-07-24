# A Better Blender Mapping Node

This is an alternative mapping node for Blender that provides node inputs for the position, scale and rotation xyz values allowing you to drive any of the mapping values with formulas, textures, or whatever you want. I escpecially find this useful for randomly changing position values inside of a procedural texture node group.

## Node Breakdown

### The main mapping node
<img src="/assets/img/screenshot-main-node.png">

### The main mapping node interior
<img src="/assets/img/screenshot-mapping-interior.png">

### The rotate node
<img src="/assets/img/screenshot-rotate-node.png">


I put this together with help of <a href="https://www.youtube.com/watch?v=kAUmLcXhUj0&t=1236s">Bartek Skorupa's amazing video on manipulating texture coordinates</a> and this <a href="https://blender.stackexchange.com/questions/58426/use-another-node-to-control-vector-mapping">helpful StackExchange response by aliasguru</a>. I recommend going over both for a better understanding of how this works.