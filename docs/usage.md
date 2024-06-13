# Usage
## Initiate Configurator
To use `Configurator`, simply include the Configurator.php file and create a new instance of the `Configurator` class.

```php

// Import Configurator class into the global namespace
// These must be at the top of your script, not inside a function
use LaswitchTech\coreConfigurator\Configurator;

// Load Composer's autoloader
require 'vendor/autoload.php';

// Initiate coreConfigurator
$Configurator = new Configurator();
```

### Methods
`Configurator` provides the following methods to manage configuration files:

- [add()](methods/Configurator/add.md)
- [get()](methods/Configurator/get.md)
- [set()](methods/Configurator/set.md)
- [delete()](methods/Configurator/delete.md)
- [root()](methods/Configurator/root.md)

## Initiate Form
To use `Form`, simply include the Form.php file and create a new instance of the `Form` class.

```php

// Import Configurator class into the global namespace
// These must be at the top of your script, not inside a function
use LaswitchTech\coreConfigurator\Configurator;

// Load Composer's autoloader
require 'vendor/autoload.php';

// Initiate coreConfigurator
$Configurator = new Configurator();
```

### Methods
`Form` provides the following methods to manage configuration files:

- [add()](methods/Form/add.md)
- [get()](methods/Form/get.md)
- [set()](methods/Form/set.md)
- [delete()](methods/Form/delete.md)
- [root()](methods/Form/root.md)

## Initiate Command for coreCLI integration
To use `Command`, simply create `Command/ConfiguratorCommand.php` file and extend a new instance of the `Command` class.

```php

// Import Configurator class into the global namespace
// These must be at the top of your script, not inside a function
use LaswitchTech\coreConfigurator\Command;

// Initiate the Command class
class ConfiguratorCommand extends Command {}
```

### Methods
`Command` provides the following methods to manage configuration files:

- [setAction()](methods/Command/setAction.md)
- [getAction()](methods/Command/getAction.md)

## Initiate Controller for coreAPI and/or coreRouter integration
To use `Controller`, simply create `Controller/ConfiguratorController.php` file and extend a new instance of the `Controller` class.

```php

// Import Configurator class into the global namespace
// These must be at the top of your script, not inside a function
use LaswitchTech\coreConfigurator\Controller;

// Initiate the Controller class
class ConfiguratorController extends Controller {}
```

### Methods
`Controller` provides the following methods to manage configuration files:

- [setAction()](methods/Controller/setAction.md)
- [getAction()](methods/Controller/getAction.md)

## Adding the Configurator View
To use the included view file, simply add a route pointing to the view file (`vendor/laswitchtech/core-configurator/View/configurator.php`).
