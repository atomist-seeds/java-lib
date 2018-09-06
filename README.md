# java-lib

A Java library for creating other Java libraries.

This project is an example progenitor project that can be used to
create other projects.  Once created, these new projects remain
connected to their progenitor, with changes in the progenitor and
progeny selectively propagated between all related projects.  See
the [Atomist documentation][docs] for more information.

[docs]: http://docs.atomist.com/ (Atomist Documentation)

## Development

This project is driven using [Maven][mvn].  You will need to install
Maven locally to build, run, and test this project.

[mvn]: https://maven.apache.org/

### Run tests

This service comes with some rudimentary tests as a good starting
point for writing your own.  Use the following command to execute the
tests using Maven:

```
$ mvn test
```

---

Created by [Atomist][atomist].
Need Help?  [Join our Slack team][slack].

[atomist]: https://www.atomist.com/ (Atomist - How Teams Deliver Software)
[slack]: https://join.atomist.com/ (Atomist Community Slack Workspace)
