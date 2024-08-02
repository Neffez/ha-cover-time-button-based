# Time Based Cover

Converts 2 `button` for each up and down into a `cover`. Only works if each button stops the movement if pressed a second time in succession.

## Install

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=Neffez&repository=ha-cover-time-button-based&category=integration)

Add this GitHub repository as custom repository in HACS and search for "Time-based Cover (with Buttons)". Install the integration and restart HA.

## Usage

After install and restart you can find the integration looking for integrations with the name "Time-based Cover (with Buttons)". 
Add a helper using the config flow, which creates a time based cover entity.

## Credits

Forked from https://github.com/duhow/hass-cover-time-based.
* [@davidramosweb](https://github.com/davidramosweb) for its original code base.
* [@kotborealis](https://github.com/kotborealis/home-assistant-custom-components-cover-time-based-synced) for another fork implementing synced status.
* [xknx](https://xknx.io/) Python library for the `TravelCalculator` control class.
