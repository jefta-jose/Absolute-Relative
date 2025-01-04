# Absolute-Relative

relative: Moves the element visually but still reserves its original space in the layout. Other elements are unaffected by its movement.
absolute: Moves the element visually and physically, removing it from the flow entirely. Other elements behave as if it isn’t there.
 
 
Use position: relative if you want to move an element from its original position, but still keep its space in the layout.
Use position: relative on the parent and position: absolute on the child if you want to move an element with respect to another element (the parent). The child will be positioned relative to the parent’s edges (top, left, etc.).
 