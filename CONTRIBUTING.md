# Contributing

## Add configuration settings
uShip.Logging uses a custom configuration section to read settings from the web/app configs. The code to read these settings is autogenerated. To make an update, follow the below steps:

1. Download and run [.NET Configuration Code Generator](https://nconfiggen.codeplex.com/)
1. Paste in a sample of your desired configuration in the "Step : Sample XML" window
1. Go over to the newly created "Step 3: Output" window
1. In the "Namespace" box, add uShip.Logging
1. Replace the existing uShipLoggingConfigurationSection class with what was autogenerated
1. Rename the classes to start with "uShip" instead of "UShip"
1. Rename the uShipLoggingSection class to be uShipLoggingConfigurationSection
