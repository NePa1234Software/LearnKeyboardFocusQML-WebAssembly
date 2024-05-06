# LearnKeyboardFocusQML-WebAssembly
This is a small project for learning QML keyboard focus and navigation. States and transitions are used for fun. 
The WebAssembly (WASM) build is a drop-in compiler selected using QtCreator. The build output is provided here to host the assembly using github pages.
FocusScope and KeyNavigation are important concepts to master. The first row uses just KeyNavigation attached properties, the second row only uses the activeFocusOnTab. FocusScope is used to "direct" the focus request to the desired component item. 
One detail is the return path that KeyNavigation provides, without configuration you can navigated to another item - and back again.

## Live Online

URL: https://nepa1234software.github.io/LearnKeyboardFocusQML-WebAssembly/appLearnKeyboardFocusQML.html

## Code

Repo URL: https://github.com/NePa1234Software/LearnKeyboardFocusQML

## Licensing

See the license file and License Folder for details
- The app is build using the Qt Framework opensource version (https://www.qt.io/licensing/)
- WebAssembly build powered by emscription SDK (https://emscripten.org/docs/introducing_emscripten/emscripten_license.html)
