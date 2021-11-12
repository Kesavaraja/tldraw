## 0.1.14

- Fixes "shifting" bug with drawing tool. Finally!

## 0.1.13

- Fixes bugs related to `readOnly` mode.

## 0.1.12

- Fixes behavior of context menu.

## 0.1.11

- Fixes appearance of keyboard shortcuts in tooltips.

## 0.1.10

- Fixes spacing in text and sticky shapes.

## 0.1.7

- Fixes text and sticky shapes on iOS.

## 0.1.4

- UI bug fixes.

## 0.1.3

- Update dependencies.

## 0.1.2

- Improve migrations.

## 0.1.1

- Update dependencies.

## 0.1.0

- Mark dependencies as external.
- Revamp UI

## 0.0.133

- Removed libraries (vec, svg, and intersect) to their own repositories.

## 0.0.133

- Migration for bindings.

## 0.0.132

- Fix bug with bounds handles.

## 0.0.131

### TLCore

- Extracted into its own repository (`tldraw/core`) and open sourced! :clap:

### TLDraw

- Updated with latest `@tldraw/core`, updated ShapeUtils API.

## 0.0.130

### TLCore

- Major change to ShapeUtils API.

### TLDraw

- Rewrite utils with new API.

## 0.0.126

### TLDraw

- Swap behavior of command and alt keys in arrow shapes.

## 0.0.125

### TLDraw

- Bug fixes.

## 0.0.124

### TLDraw

- Fix typings.

## 0.0.123

### TLDraw

- Adds bound shape controls.
- Drag a bound shape control to translate shapes in that direction.
- Double click bound shape controls to select shapes in that direction.
- Fix bug in arrow decorations toggle.

## 0.0.122

### TLDraw

- Adds snapping for transforming shapes.

## 0.0.121

### Core

- Adds `snapLines`.

### TLDraw

- Adds shape snapping while translating. Hold Command/Control to disable while dragging.

## 0.0.120

### TLDraw

- Improves rectangle rendering.
- Improves zoom to fit and zoom to selection.

## 0.0.119

### TLDraw

- Fixes bug with bound arrows after undo.

## 0.0.118

### Core

- Improves multiplayer features.

### TLDraw

- Fixes bugs in text, arrows, stickies.
- Adds start binding for new arrows.
- Adds copy painting (alt + shift + drag).
- Adds side clonig.
- Adds clone dragging.

## 0.0.116

### Core

- Improves rendering on Safari.

### TLDraw

- Improves rendering on Safari.
- Minor bug fixes around selection.
- Fixes bug when undoing a newly created shape.

## 0.0.115

### Core

- Adds [side cloning](https://github.com/tldraw/tldraw/pull/149).
- Improves rendering.

### TLDraw

- Adds sticky note [side cloning](https://github.com/tldraw/tldraw/pull/149).

## 0.0.114

### TLDraw

- Improves fills for filled shapes.

## 0.0.113

### TLDraw

- Improves grouping and ungrouping.

## 0.0.112

### TLDraw

- Fixes centering on embedded TLDraw components.
- Removes expensive calls to window.

## 0.0.111

### TLDraw

- Adjust stroke widths and sizes.
- Fixes a bug on very small dashed shapes.

## 0.0.110

### Core

- Adds `user` and `users` props (optional) for multiplayer cursors. This feature is very lightly implemented.

### TLDraw

- Adds multiplayer support.
- Adds `showMenu` and `showPages` props.
- Adds `mergeState`, `updateUsers`, and `removeUser` methods.

## 0.0.109

### TLDraw

- Bumps perfect-freehand
- Fixes dots for small sized draw shapes

## 0.0.108

- Adds CHANGELOG. Only 108 releases late!

### TLDraw

- Fixes a bug with bounding boxes on arrows.