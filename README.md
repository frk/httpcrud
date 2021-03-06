[`godoc`](http://godoc.org/github.com/frk/httpcrud)
[`pkg.go.dev`](https://pkg.go.dev/github.com/frk/httpcrud)

# httpcrud

The `httpcrud` package defines a number of interfaces and types that provide
an alternative, idiosyncratic approach to writing HTTP handlers in Go.

What the package tries to achieve is to make it *easier* to adhere to SRP without
having to introduce a large number of disjointed units that, while easy to comprehend
individually, in combination are difficult to reason about. This can become increasingly
more challenging as the complexity of an app's CRUD operations starts to rapidly grow
in an attempt to meet the app's shape-shifting requirements.

The package willfuly ignores some of the common recommendations on how to
write HTTP handlers in Go and as such, it fails to be a good option for anyone
who wants to follow said recommendations.
