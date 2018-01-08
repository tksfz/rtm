Routes-Types-Models
===================

`rtm` is an experimental Web framework. It's premised on a correspondence between:

  route <=> type <=> route-model

It's natural to associate a type with every route; and for that type to capture the
"route-model": the data submitted to the route. In rtm this association is mandatory
and essential.

Why?

In addition to being a somewhat natural convention, associating a type with every route
potentially allows us to take advantage of *type-driven routes*. For example:

- generic routes (e.g. CRUD routes)
- generic derivation of functionality backing routes? (views and controllers)
- type-based compsition of routes?

rtm is meant to explore this design space.
