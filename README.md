# watch-plantuml

A tiny script to generate plantuml diagram every time the source file changes, using `ìnotifywait` on Linux.

## Prerequisites

The script assumes that a `plantuml.jar` file is located in *$HOME/apps/* and that the appropiate Java runtime is installed.

## Usage

Add */path/to/watch-plantuml/bin/* to your path and run:

`watch-plantuml mydiagram.plantuml ./out`

The 2nd argument, *output directory*, is optional, defaults to current working directory.
