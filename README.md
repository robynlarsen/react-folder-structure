# react-folder-structure
Creates a `_boilerplate` folder that contains a set of tested folder structures to maintain order in projects.

NOTE: This is highjly opionionated and should be viewed as such. 

# JSLINT
As we needed mandatory JSLINT configuration to keep the world in order, this is also bolted in here, you may need to roll your jslint back if required. 

## Using it

1. Install

`npm install react-folder-structure --save-dev`

2. Run it!

`react-folder-structure`

3. Remove it, once copied not much point in leaving it active. 

`npm remove react-folder-structure --save`

## Folder Structure: 

```
_boilerplate
--| assets // Stylesheets, etc etc.
--| blueprints // Mock data or blueprint files
--| components // Where the react components live
--| config // Config files? possibly sensitive
--| constants // shared constants?
--| containers // Often these are views? or loaders for views.
--| helpers // We all know we need them some times.
--| routes  // router stuffs.
--| seed // Does your app seed some data? this is a good place for it.
--| store // Potential location for store and logical points.

.jslintrc.js => Added to root. 
```
