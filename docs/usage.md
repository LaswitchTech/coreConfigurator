# Usage
## Initiate Configurator
To use `coreConfigurator`, simply include the coreConfigurator.php file and create a new instance of the `Configurator` class.

```php

// Import Configurator class into the global namespace
// These must be at the top of your script, not inside a function
use LaswitchTech\coreConfigurator\Configurator;

// Load Composer's autoloader
require 'vendor/autoload.php';

// Initiate coreConfigurator
$Configurator = new Configurator();
```

## Methods
`coreConfigurator` provides the following methods to manage configuration files:

- [add()](methods/add.md)
- [get()](methods/get.md)
- [set()](methods/set.md)
- [delete()](methods/delete.md)
- [root()](methods/root.md)
