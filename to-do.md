# To Do

- [x] Add a home page component
- [x] Add a basic R3f Canvas
- [x] add left side hud
- [x] Use JSON as parent-child recipe for all components in DOM
  - [x] In-progress
  - [x] setup data-template to later generate basic canvas content
  - [x] setup recursice loop to render children ( renderChildren() in TemplateToComponents.tsx )
    - [x] in-progress
- [x] Use recipe to add canvas
- [x] Add basic Cube
- [x] Add directory stucture component to left-side for component tree
- [x] In order to select and update deeply nested primitives, and their references. I'll need to have loops leave trail of breadcrumbs on children, to indicate which child they are, and in what position
- [x] Selected Sidebar components
- [x] Modularize code for updating nodes to separate utils file
- [x] Move actual trigger of node update to secondary-sidebar prop-listing
- [x] Make props manually editable, instead of just changing color onClick
- [x] Add basic menus to update props
- [ ] Add/Refine, convert to AST, and export...
  - [ ] Test exporting to string, then file, from existing "basicCanvas1" import
  - [ ] Get "basicCanvas1" from global stores json object
- [ ] Next, Revisit scene-exporting. Refine, cleanup, make univeral to more prop types.
  - [ ] File names, project shell wrapper, etc
- [ ] Add ability/menu to add more props to a primitive
- [ ] Add menu to Add more primitives to the tree
- [ ] Non-primitive components
  - [ ] Test a simple box-based dynamic-lazy-import
  - [ ] Add ability to parse TS files, using FS Access API and AST lib, into json format that JS can more easily understand.
  - [ ] Add component templates, for example a pre-made box, or a slope/ramp. That can be dropped in and configured similar to individual primitives. Using dynamic, lazy imports
- [ ] Slope/ramp
- [ ] Add/edit cameras and canvases...
