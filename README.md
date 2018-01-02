This is a data project for efficient changing between lines in Berlin.
Take a look at the
[generated](https://github.com/OpenMetroMaps/berlin-change/tree/generated)-branch
for a auto-generated Markdown-view on the data in this repository.

Previously, data has been manually collected in a hand-crafted Markdown files.
Although these files are considered deprecated,
[they are still here](manual/README.md).

The data is stored in the [data.xml](data.xml) file.

# File format specs
## Location attribute

The `change` and `exit` element should contain a `location` attribute.
It can have any of the following values:

* `front`
* `almost front`
* `middle/middle front`
* `middle`
* `middle/middle back`
* `almost back`
* `back`
