# json dot js (`.json.js`)

This is a JSON parser for human-readable JSON to solve this
problem once and for all. It does so by following these constraints:

- the contents of `.json.js` must:
  - Always be a superset of JSON
  - Always be a subset of javascript
  - Always be a valid expression in javascript
    when wrapped in `(` and `)`.
  - Always be guarenteed to halt

This implementation is allowed to be a superset of the latest
version of the `.json.js` spec, and the `.json.js` spec will
get updated versions to keep it in sync with the implementation.
This has the advantage of allowing new conveniences to be added
to `.json.js` rather than strictly adhere to a spec that prevents
supporting future EMCAScript syntax additions.

Right now this is version `0`, so there is _no spec_ to speak of.
