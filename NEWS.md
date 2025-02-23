dads v0.1.11 (2023-03-27) 
=========================

### BUG FIXES

 * Corrected the `BM.process` to now be to `rnorm(n = 1, mean = x0, sd = sqrt(sd^2 * edge.length))` (thanks to Rachel Warnock for spotting that one).
 * Fixed `bd.params` print display when inputs are numeric.

### NEW FEATURES
 
 * Full polished version of the manual!
 * `dads` has now a `save.steps` option to create internal nodes at regular intervals or specified ones.
 * Added a `make.bd.parms` utility function for sampling from distributions (jointly or not).
 * Trees can now be generated with birth-death parameters sampled from functions.
 * added a list of pre-made `modification` and `condition` for events.
 * `traits` can now have a background component that triggers trait generation in the background each time traits are generated.
 * `events` are now fully handled and modular.
 * `make.events` function for helping to make events.
 * `make.modifiers` now has a `select.taxa` argument.
 * `make.dads` to create `"dads"` objects from a tree and a dataset (e.g. matrix). This can be useful for using the the `plot.dads` function on non `"dads"` objects. 
 * `"events"` class objects are now implemented and fully functional with the `make.events` function and the pre-made `mass.extinction` and `founding.event` events.
 * `drop.things` to drop fossils or livings species or internal nodes from `"dads"` objects.

### MINOR IMPROVEMENTS

 * Many clarifications and rewording to the manual.

dads v0.1.0 (2020-11-13) *first release*
=========================

### NEW FEATURES
 
 * `dads` function first release.
 * `make.traits` function first release.
 * `make.modifiers` function first release.
 * `print` and `plot` functions for `"dads"` objects.
 * `parent.traits` utility function first release.
 * Manual first release

<!-- ### MINOR IMPROVEMENTS

 * INIT

### BUG FIXES

 * INIT
 -->