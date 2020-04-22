# Fastly Edge Modules - Datadome integration 

This module will enable Datadome integration. Datadome is a security provider providing services such 
as bot detection, etc. You have to have an account with Datadome before proceeding. This module only provides
integration with Datadome service. It's available in module version 1.2.127+. 

Before you can use Fastly Edge Modules you need to [make sure they are enabled](https://github.com/fastly/fastly-magento2/blob/master/Documentation/Guides/Edge-Modules/EDGE-MODULES.md) and that you have selected the Datadome integration module.

After you have enabled the module it's time to configure. You will be prompted with a screen like this

![Fastly Edge Module Datadome configuration](../../images/guides/edge-modules/edge-module-datadome.jpg "Fastly Edge Module Datadome configuration")

## Configurable options

### Datadome API Key

This is the API key provided to you by Datadome.

## Enabling

After any change to the settings you need to click *Upload* as that will upload require VCL code to Fastly.
