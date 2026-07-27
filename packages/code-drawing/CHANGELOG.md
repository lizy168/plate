# @platejs/code-drawing

## 54.0.0-beta.2

### Major Changes

- [#5036](https://github.com/udecode/plate/pull/5036) by [@zbeyens](https://github.com/zbeyens) – Insert code drawings through `editor.update.codeDrawing.insert(props, options)`,
  append when no block target is available, and register code-drawing properties
  with versioned inline validation in compiled schemas. The plugin and command
  identity is `codeDrawing`; persisted elements remain `code_drawing`. Use
  `KEYS.codeDrawing` instead of `CODE_DRAWING_KEY`.

  **Migration:** Replace direct `insertCodeDrawing` calls with the installed plugin command. Pass `at` to target the block after which the drawing is inserted.

## 53.0.0

## 52.3.10

### Patch Changes

- [#4897](https://github.com/udecode/plate/pull/4897) by [@zbeyens](https://github.com/zbeyens) – Fix declaration bundling by restoring the workspace `platejs` build edge during package builds

## 52.3.0

### Minor Changes

- [#4811](https://github.com/udecode/plate/pull/4811) by [@electroluxcode](https://github.com/electroluxcode) – Add code drawing plugin with inline editing support for PlantUML, Graphviz, Flowchart, and Mermaid diagrams
