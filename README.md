# sample-ninja-game
A game I mostly copied from Youtube, to learn about pygame and also the coding flow in Python, and hopefully will make some more games on it

# How-to-play
# Things to mention:
1. There will be a zip file for the game, unzip it, and find game.exe in it, and play
2. You can also go through the files in Github, and find game.py and run it if you have Python installed, and also want to modify it

# Controls to play   
1. A/Left Arrow Key --> go left

2. D/Right Arrow Key --> go right

3. W/Up Arrow Key --> jump, and also tap the keys twice to double jump

4. Space --> Dash, also will kill enemies

# Editor
There is also an editor option for maps for those who want to edit maps and have Python installed to work on it. 
# Things to mention:
1. If you want to play on your custom map, change this line on game.py:
   ```
         def load_level(self, map_id):
        self.tilemap.load('data/maps/' + str(map_id) + '.json')
   ```
   to
   ```
       def load_level(self, map_id):
        self.tilemap.load('map.json')
   ```
3. You can only edit one map at a time :( If you save the map in the maps folder, and name it according to the pre-existing maps, you can create another one too.

# Editor Controls:
1. A/Left Arrow Kwy --> go left
2. D/Right Arrow Kwy --> go right
3. W/Up Arrow Key --> go up
4. S/Down Arrow Kwy --> go down
5. Enter --> Save
6. G --> put offgrid elements across the map
7. T --> autofill the gaps around the elements
8. Scroll to go across different elements
9. Shift + Scroll to go across the elements of the same type.
