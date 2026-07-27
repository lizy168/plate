# @platejs/footnote

## 54.0.0-beta.2

### Major Changes

- [#5036](https://github.com/udecode/plate/pull/5036) by [@zbeyens](https://github.com/zbeyens) – Use `BaseFootnotePlugin` / `FootnotePlugin` for footnote references and
  document-level footnote behavior. Read footnotes through `editor.read.footnote`
  and mutate them through `editor.update.footnote`, including
  `editor.update.footnote.insert()`.

  The plugin requires the matching footnote-input descriptor. Footnote queries,
  navigation, insertion, definition creation, and duplicate normalization are
  owned by the plugin instead of exported editor/transaction helper functions.

## 53.0.0

### Minor Changes

- [#4941](https://github.com/udecode/plate/pull/4941) by [@zbeyens](https://github.com/zbeyens) – Add `FootnoteReferencePlugin`, `FootnoteDefinitionPlugin`, and
  `FootnoteInputPlugin` for real footnote nodes and inline `[^` combobox
  insertion in Plate editors.
