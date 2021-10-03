# Binder
Binder is a class which handles callbacks which need to be called in a certain order, which one with a custom priority. It shaped as a ScriptSignal class, except one with custom ordering.

# Warning

### Binder is a preview, Binder is still in beta! Anything might change, method names, behaviour, consistency, and things like going from deferred to immediate behaviour instead.
### As binder is currently using an array for its bindings, as doing the same with a linked-list was proven to be hard, this might change at any time, allowing for safe immediate firing instead, and faster / less expensive `:Bind` and `:Unbind` calls, by not needing array elements to be shifted.

### Contributions helping to achieve these goals are very welcome!
