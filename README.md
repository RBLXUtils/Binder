# Binder
Binder is a class which handles callbacks which need to be called in a certain order, which one with a custom priority. It shaped as a ScriptSignal class, except one with custom ordering.

# Warning

### Binder is a preview, Binder is still in beta! Anything might change, method names, behaviour, consistency, and things like going from deferred to immediate behaviour instead.
### As binder is using currently an array, as using a linked list was proven to be complex to introduce, this might change at any time, allowing for safe immediate firing instead, and faster / less expensive `:Bind` and `:Unbind` calls.
