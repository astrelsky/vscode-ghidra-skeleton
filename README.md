# VSCode Ghidra Plugin/Script Skeletons

The following are pre setup directory structures to simplify working with Ghidra plugins and scripts in vscode.

## Dependencies

* Ghidra
* Java 11
* Gradle
* VSCode
* VSCode Java Extension Pack

### Usage

* Copy the skeleton directory of your choice to another destination.
* Rename directory accordingly.
  * For Extensions/Plugins set the project name in `.project` and in `.vscode/launch.json`. If the names do not match the debugger will fail to launch.
  * For Scripts the `ghidra_script` directory must still be added via Ghidra's Script Manager.
* Open VSCode in the directory containing the `.project` and `build.gradle` files.
* Let the Java Language Server finish initializing and get to work.

#### Supports

- [x] Java Plugins/Extensions
- [x] Java Ghidra Scripts
- [ ] Python Ghidra Scripts
- [ ] Ghidra Processor Projects
