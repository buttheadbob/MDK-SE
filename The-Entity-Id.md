The entity ID is a value which uniquely identifies individual grids and blocks. You can access it through the item's `EntityId` property. This value is guaranteed to remain the same during the entire lifetime of the item in question, even if you reload your world.

### Know when an entity is recreated
There are caveats. Blocks are pretty clear cut, as long as they exist they will have the same ID. Grids are a bit harder to deal with though.

The **Merge Block** is very popular to use as a docking clamp, and people are often not aware of the fact that this isn't really what this block was designed to do. It's original purpose was to _permanently_ merge grids together - hence its name. 
When you lock your grids together with a merge block, all the blocks in one of the grids are moved to the other grid, and then the first grid is _destroyed_. When you unlock again, the game creates a _new_ grid, and moves blocks from the merged grid over to this new grid. This means that the entity ID of the grid your programmable block is placed on _might change_ whenever you use a merge block. This is something you need to be aware of as a scripter if you intend to make use of this value.

### Blueprints and Copy Paste
This one should be rather obvious. When you paste in new grids from either blueprints or a copy/paste in creative, all grids and blocks will get new IDs compared to the original copy or blueprint.