# lockwright-utils-pattern-search

A simple utility to search for patterns in a list

Site: [lockwright.dexterity.works](https://lockwright.dexterity.works)

Community fork of PearPass (Apache 2.0). Not affiliated with or endorsed by Tether Data or the Pears project.

## Table of Contents

- [Features](#features)
- [Security Notice](#security-notice)
- [Installation](#installation)
- [Usage Examples](#usage-examples)
- [Dependencies](#dependencies)
- [Related Projects](#related-projects)

## Features

- Case-insensitive pattern searching
- Handles null and undefined values safely
- Simple API with boolean return values
- Zero dependencies
- Lightweight and optimized for performance
- ESM module support

## Security Notice

Imports stay `@tetherto/pear-apps-utils-pattern-search`. That npm name is not this fork if you install it from the npm registry.

## Installation

```bash
npm install git+https://github.com/Dexterity-Works/lockwright-utils-pattern-search.git
```

## Usage Examples

```javascript
import { matchPatternToValue } from '@tetherto/pear-apps-utils-pattern-search';

const pattern = 'hello';
const value = 'Hello, World!';

if (matchPatternToValue(pattern, value)) {
  console.log('Pattern found in value');
} else {
  console.log('Pattern not found in value');
}
```

## Dependencies

This package has no external dependencies.

## Related Projects

- [lockwright-app-mobile](https://github.com/Dexterity-Works/lockwright-app-mobile) - Lockwright for mobile
- [lockwright-app-desktop](https://github.com/Dexterity-Works/lockwright-app-desktop) - Lockwright for desktop
- [tether-dev-docs](https://github.com/Dexterity-Works/tether-dev-docs) - Documentations and guides for developers

## License

This project is licensed under the Apache License, Version 2.0. See the [LICENSE](./LICENSE) file for details.