# NodeJS shebang

Add `#!/usr/bin/env node` shebang to your generated js files when targetting
nodejs.

## Usage

Install the lib:
```
haxelib install node-shebang
```

Add the lib to your hxml file:
```hxml
# ...
-lib node-shebang
```

And compile. Your compiled js should now begin with `#!/usr/bin/env node`. You
still need to make it executable yourself, though.

