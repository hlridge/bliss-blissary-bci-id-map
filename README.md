# bliss-blissary-bci-id-map

## Description
A JSON mapping of Blissary IDs and BCI-AV IDs for Bliss language.

## License
This data is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. For more details, see the [LICENSE](LICENSE) file in this repository or visit [Creative Commons BY 4.0](https://creativecommons.org/licenses/by/4.0/).

## Attribution
### Blissary
- **Author**: Hannes Ljusås
- **Source**: [Blissary](https://blissary.com)

### BCI-AV
- **Author**: Blissymbolics Communication International
- **Source**: [BCI-AV 2026](https://www.blissymbolics.org/index.php/bci-av-2026)

## Usage
To use this data, you can import the JSON file into your project.

### ES Modules
```javascript
import mapping from './path-to-json-file.json';
```

### CommonJS

```javascript
const mapping = require('./path-to-json-file.json');
```

### Dynamically

```javascript
fetch('https://raw.githubusercontent.com/hlridge/Bliss-Blissary-BCI-ID-Map/main/path-to-json-file.json')
  .then(response => response.json())
  .then(data => {
    // Do something with your data here
  });
```

## Advanced Usage: Git Submodule (Optional)
For those who are comfortable with Git, this repository can be included as a submodule in your project. This allows you to keep the mapping easily up-to-date. To add this repository as a submodule, run:

```bash
git submodule add https://github.com/hlridge/Bliss-Blissary-BCI-ID-Map.git folder-name
git submodule update --init --recursive
```

To update the submodule to the latest version:

```bash
git submodule update --remote folder-name
```
