# CanvasTodoList: TodoMVC with PixiJS

This is an Canvas-only implementation of [TodoMVC][] using Typescript and Pixi.js as a
learning exercise.

## Getting Started

- Requires Linux/OSX, python 3, [invoke][], and [docker-compose][].
- Add `export UID=$UID 2> /dev/null` to your `.bashrc`, or `.bash_profile`, or other shell startup file.
- In the root of the project, run `invoke start`.
  - invoke and docker-compose take care of setting up ALL requirements for you!
- Visit `localhost:8000`. Replace localhost with the ip of the host running docker if
different.


[TodoMVC]: https://github.com/tastejs/todomvc
[invoke]: http://www.pyinvoke.org/
[docker-compose]: https://docs.docker.com/compose/overview/
