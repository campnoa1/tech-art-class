# tech-art-class
Repository for homework.

**DOCUMENTATION**

This tool is used to generate a flower pot house based on concept art from this artist: https://www.artstation.com/artwork/ayoozR

General usages are adjusting height and width of pot, adjusting plant sizes and numbers, adjusting windows in many ways.

**More detailed list:**

  "Pot Base" Collection > "Pot top half:"   
  
    -Height of top: Pulls top face of pot body up and down along with the topper.
    
    -Scale of top: Scales top face along with everything on the topper.
    
    -Window Collection: Allows for changing what windows are available to be chosen for instancing on body of pot from within a collection.
    
    -Window Distance: The minimum distance between each instanced window.
    
    -Window Density: Sheer number of windows instanced. (May not display the number desired, derived from Window Distance and Window Density Factor)
    
    -Window Density Factor: Density of windows instanced.
    
    -Window Seed: Changes seed of instances.
    
    -Window Density Top Scaler: Instances below Topper by a specified factor distance.
    
    -Window Density Bottom Scaler: Instances above bottom of pot (the cut out portion) by a specified factor distance.
    
    -Window Global Scale: Global scale of windows across all axis.
    
    -Window Tilt: Z axis tilt scaler of all windows.

    
  "Pot Topper" Collection > "Logs:"    
    -Log Count: Number of logs instanced in a ring.
    
  "Pot Topper" Collection > "Pipe Rings:"    
    -Ring Count: Number of rings instanced in a ring along the tube.
    
  "Pot Topper" Collection > "Pot Topper Top:"    
    -Overall Sphere Count: Adjusts radius of underlying sphere allowing for more plant sphere to display.
    -Overall Sphere Translation: Adjusts underlying sphere's location.
    -Overall Sphere Rotation: Adjusts underlying sphere's rotation.
    -Plant Min Distance: Minimum distance between each displayed plant sphere.
    -Plant Density Max: Sheer number of plant spheres instanced.
    -Plant Density Factor: Density of plant spheres instanced.
    -Plant Random Scale Min: Minimum scale values of plant spheres.
    -Plant Random Scale Max: Maximum scale values of plant spheres.
    -Plant Global Scale: Global scale of all plant spheres.
    -Plant Seed: Changes seed of instances:
    -Leaf Distance Min: Minimum distance between each leaf.
    -Leaf Density Max: Sheer number of leaves instanced.
    -Leaf Density Factor: Density of leaves instanced.
    -Leaf Seed: Changes seed of instances.
    -Leaf Object: Allows for object instanced to be changed.
    -Min Leaf Scale: Minimum scale of leaves instanced.
    -Max Leaf Scale: Maximum scale of leaves instanced.
    -Leaf Global Rotation: Global rotation of all leaves around a pivot.
    -Leaf Global Scale: Global Scale of all leaves.
    
  "Pot Topper" Collection > "Shingles Bottom" AND "Shingles Top:"    
    -Seed: Changes seed of instances.
    -Tile Count: Number of instanced tiles.
    -Randomize Rotation: Randomize the rotation of each instance by small margins.

**Reflection**

What went well? -     
I managed to get pretty much everything I wanted to be working, working. That would mostly be all the trouble shooting I had to do with the windows.

What did I struggle with? -     
I struggled with most of it. I eventually started getting it all down to some degree (the geonodes), but a lot was very confusing. I'm not versed in code much at all so the shift has been very hard. As for the textures, I ended up not giving myself enough time to work on them. To add onto that, I struggled with the UVs a LOT. I could not figure out how to do them well with all the other stuff that I tacked on.

What could I do differently next time? -     
I would definitely work on the textures, and I do plan to later after submitting. I would also try to figure out the UVs and see why I was having such a hard time.
