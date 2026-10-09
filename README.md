# go-text-edit

The text editor screen for [bubblestack](https://github.com/brohd11/bubblestack) apps, and the
editor behind [gote](https://github.com/brohd11/gote). Package `editor` offers syntax highlighting,
undo, block indent, comment toggling, search, LSP-shaped completion and edits, and host sign
columns, built from bubblestack's shared components (MenuScreen, LineEditScreen,
DialogScreen, Frame).

```go
import editor "github.com/brohd11/go-text-edit"
```

Start at `editor.New` and `editor.Opts`.

Split out of `bubblestack/components/editor` on 2026-10-09; the API is unchanged, only the import
path moved.
