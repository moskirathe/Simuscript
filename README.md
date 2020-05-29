# SimuScript
SimuScript is a Domain Specific Language that allows users to build a gampe map, by specifying the size of the map, setting different terrains, characters and then playing a game simulation to see the game in action.

Characters can be customized to have different qualities. For example, characters may like some characters and be scared of others. Characters can be given the ability to drop items as well as collect items that others have dropped.

SimuScript is built for prospective game developers, providing an intuitive way to test out game ideas through the construction of draft maps and worlds, and the ability to run quick simulations to see how the game would play out.

<img src="https://simuscript.000webhostapp.com/images/demo.png" width="300" height="300">

### EBNF
*EBNF goes here*

### Example Program
```
set grid size to be(15,15)
set rectangle (0,0)(14,14) as grass
draw from (0,0)(14,14) using rock with waviness 2 thickness 1
Define chicko as chicken that moves that drops feather that collects friedegg
define bigkitty as wolf that moves that drops meat that collects diamond
place bigkitty anywhere 5 times
place chicko anywhere 8 times
play for 10 seconds
```

### DEMO
Want to see SimuScript in action? Here is a [demo](https://simuscript.000webhostapp.com/main.html "SimuScript Demo")

