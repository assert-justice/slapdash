# SlapDash Productivity Suite

SlapDash is a one stop shop for automating build processes and managing artifacts across several different related projects in any language you like. It empowers you to write simple and maintainable automation tools to make building and distributing your projects as painless as possible.

## Features 
- Write automation scripts in pure Python, no half baked languages or config files here.
- Streamline common tasks like working with compilers, build systems, version control, and deployment with built in scripts.
- Build high level interfaces that generate both cli and gui controls.
- Language agnostic, if it's got a cli you can use it.
- Good, honest GPL3 code. It'll be Free Software forever.

## Motivation
Across various projects over the years I've had a common irritation. Suppose I'm working on a game as well as that game's engine. The game and its engine are two projects but they are obviously closely linked. There are countless different ways to organize this relationship. 

```
project
    | engine
    | binaries
    | game
    | launcher
```

## Libraries Used
- toml
- PyInstaller
- mypy
- rich
- watchdog