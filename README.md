


put the plugin directory in $rtp/pack/\*/start to add at start
put the plugin directory in $rtp/pack/\*/opt to add when running packadd


myplugin                    <== Plugin root
  ├───lua                   <== All Lua code
  │       func.lua          <== any file you need
  │       myplugin.lua      <== Plugin Entry Point
  │
  └───plugin                <== All Files here are run at packadd
          myplugin.lua      <== require 'myplugin' here to run on packadd
