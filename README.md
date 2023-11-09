# RLS
### Rust Logic Simulator

Logisim-inspired logic circuits simulator

### Global TODOs

- [Done] Place circuit boards as circuits
- [Working] Circuit designer for circuit boards
- [In progress] Circuit controls 
> special circuit interfaces that can be exposed on containing circuit design and can receive user input

- Rename the project

- Proper keybinds, some mobile support

- More components (LEDs, 7-segments...)

- Embed as `iframe`s
- Some sort of plugin api
- Separate into backend and frontend crates
- Figure out themes
- Proper mobile support
- Proper errors

- UI descriptions, tooltips, hints, etc

## Local TODOs

- Rotate selection
- Remove wire with Wire tool
- Warning to replace circuits that don't match latest pin layout
- Make pins use random ID and store it in board data
- When copying pins, preserve their ID and design data
- Maybe show circuit pin labels in paste

![](progress_preview.png)

### Web version

Web version is available [here](https://ved-s.github.io/rls).
It's less precise due to browser limitations.