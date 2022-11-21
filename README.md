# godot_dijkstra_test
Test for MatejSloboda / Dijkstra_map_for_Godot project

Tested on:
Godot 3.5.1
Window 11
Chrome(latest) and Microsoft Edge(latest)

How to reproduce:
1. Create new project and create a parent node
2. Attach visualisation.tscn as child node
3. Download HTML5 template & run
4. select either "cost map" or "direction map" in dialog box
5. Open developer tools

Error in picture below appears in developer tools: 

"ERROR: Interface does not have a library for the current platform."
"SCRIPT ERROR: Attempt to call function 'new' in base 'NativeScript' on a null instance." <- i'm assumming this is on dijkstramap = DijkstraMap.new()

![](/issue.PNG "Issue")
