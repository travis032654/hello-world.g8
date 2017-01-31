# Hello world Scala project with sbt

First download sbt http://www.scala-sbt.org/

Then run `sbt` to open the sbt console.

* To run the program, execute `run`.
* To compile the program, execute `compile`.
* To run tests, execute `test`.
* To continuously `run` when you save a file, execute `~run`.
  `~` works the same for `~compile` and `~test`.
* If you update build.sbt, execute `reload` to pick up your new build settings
  (takes a few seconds).

Sbt weirdness:

* `reload` is slow. The bright side is that the sbt console is really fast once loaded.
* `Ctrl+c` will exit the sbt console. To remove a command you're editing, use backspace or `Ctrl+u`.

