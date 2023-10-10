# tui.crumb

> NOTE: this is an experimental Crumb usable. In early dev stage. It is used in [Crumbicon](https://github.com/ronilan/crumbicon).

`tui.crumb` is a [Crumb](https://github.com/liam-ilan/crumb) usable providing a rudimentary functional TUI framework.

The TUI builds up on the abstractions provided by the [event loop usable](https://github.com/ronilan/event-loop.crumb) to allow the creation and manipulation of encapsulated UI elements.

## Usage

1. Download https://raw.githubusercontent.com/ronilan/tui.crumb/main/tui.crumb
2. Download dependencies on usables: 
  - `colors.crumb` https://raw.githubusercontent.com/ronilan/colors.crumb/main/colors.crumb
  - `event-loop.crumb` https://raw.githubusercontent.com/ronilan/event-loop.crumb/main/event-loop.crumb
2. Place it in your Crumb project. (see: [Crumb Template](https://github.com/liam-ilan/crumb-template) for an easy starter.)
3. Use it.

## Basics

WIP

## Examples

WIP

## Running Examples

### With Docker:

Build: 
```
docker build -t tui.crumb.crumb git@github.com:ronilan/tui.crumb.crumb.git#main
```
Run: 
```
docker run --rm -it tui.crumb.crumb
```

Or "all in one": 
```
docker run --rm -it $(docker build -q git@github.com:ronilan/tui.crumb.crumb.git#main)
```

Then in the shell: 
```
./crumb examples/10-print.crumb
```

### Locally

Clone the repo: 
```
git clone git@github.com:ronilan/tui.crumb.crumb.git
```

CD into directory: 
```
cd tui.crumb.crumb
```

Build Crumb interpreter: 
```
chmod +x build-crumb.sh && ./build-crumb.sh
```

Run:
```
./crumb examples/demo.crumb
```

## Reference 

WIP

###### Fabriqué au Canada : Made in Canada 🇨🇦
