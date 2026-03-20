# pear-apps-utils-pattern-search

A simple utility to search for patterns in a list

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

1. To ensure the security and integrity of your projects, please note that official PearPass packages are distributed exclusively through our GitHub organization.
2. Any packages with similar names found on the npm registry or other third-party package managers are not affiliated with PearPass and should be strictly avoided. We recommend installing directly from this repository to ensure you are using the verified, open-source version.

## Installation

```bash
npm install git+https://github.com/tetherto/pear-apps-utils-pattern-search.git
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

- [@tetherto/pearpass-app-mobile](https://github.com/tetherto/pearpass-app-mobile) - A mobile app for PearPass, a password manager
- [@tetherto/pearpass-app-desktop](https://github.com/tetherto/pearpass-app-desktop) - A desktop app for PearPass, a password
- [@tetherto/tether-dev-docs](https://github.com/tetherto/tether-dev-docs) - Documentations and guides for developers

## License

This project is licensed under the Apache License, Version 2.0. See the [LICENSE](./LICENSE) file for details.