# tiny-maze: Java Edition

This project is based on the great kata "tiny-maze" [from Carin
Meier](https://github.com/gigasquid/wonderland-clojure-katas/tree/master/tiny-maze).
I changed the description to match Java's syntax. The rest of the description is
taken from the [original
repository](https://github.com/gigasquid/wonderland-clojure-katas/tree/master/tiny-maze).

## Description

Alice found herself very tiny and wandering around Wonderland. Even the grass
around her seemed like a maze.

![alice](img/alicetiny.gif)

Let's write a tiny maze solver in Java. The maze is represented as a 2d-array:

```java
new String[][] {
    {"S", "0", "1"},
    {"1", "0", "1"},
    {"1", "0", "E"}
};
```

* `S`: start of the maze
* `E`: end of maze
* `1`: This is a wall that you cannot pass through
* `0`: A free space you can move through

The goal is the get to the end of the maze. A solved maze will have a "x" in the
start, the path, and the end of the maze, like this.

```java
new String[][] {
    {"x", "x", "1"},
    {"1", "x", "1"},
    {"1", "x", "x"}
};
```

## Instructions

* Clone or fork this repository
* `cd tiny-maze`
* Run the continuous tests with `gradle test -t`
* Write tests in TDD-style until you have a working solver

## License

Source code:

Copyright © 2018 Christian Meter

---

Original project-description and idea of the kata:

Copyright © 2014 Carin Meier

Distributed under the Eclipse Public License either version 1.0 or (at your
option) any later version.
