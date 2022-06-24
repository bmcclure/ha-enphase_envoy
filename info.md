[![GitHub Release][releases-shield]][releases]
[![GitHub Activity][commits-shield]][commits]
[![License][license-shield]][license]

[![hacs][hacsbadge]][hacs]
[![Project Maintenance][maintenance-shield]][user_profile]
[![BuyMeCoffee][buymecoffeebadge]][buymecoffee]

[![Discord][discord-shield]][discord]
[![Community Forum][forum-shield]][forum]

An updated Enphase Envoy integration that supports the v7 firmware with token-based authentication.

Credit goes to @DanBeard for the original code in this updated repository.

**This component will set up the following platforms.**

| Platform        | Description                         |
| --------------- | ----------------------------------- |
| `sensor `       | Solar sensors.                      |

{% if not installed %}
## Installation

1. Click install.
2. Restart Home Assistant.
{% endif %}

## Configuration

All configuration is done in the UI.

In the HA UI go to "Configuration" -> "Integrations" click "+" and search for "Enphase Envoy".

***

[integration_blueprint]: https://github.com/custom-components/integration_blueprint
[buymecoffee]: https://www.buymeacoffee.com/benmcclure
[buymecoffeebadge]: https://img.shields.io/badge/buy%20me%20a%20coffee-donate-yellow.svg?style=for-the-badge
[commits-shield]: https://img.shields.io/github/commit-activity/y/bmcclure/ha-enphase_envoy.svg?style=for-the-badge
[commits]: https://github.com/bmcclure/ha-enphase_envoy/commits/master
[hacs]: https://github.com/custom-components/hacs
[hacsbadge]: https://img.shields.io/badge/HACS-Custom-orange.svg?style=for-the-badge
[discord]: https://discord.gg/Qa5fW2R
[discord-shield]: https://img.shields.io/discord/330944238910963714.svg?style=for-the-badge
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg?style=for-the-badge
[forum]: https://community.home-assistant.io/
[license-shield]: https://img.shields.io/github/license/custom-components/blueprint.svg?style=for-the-badge
[maintenance-shield]: https://img.shields.io/badge/maintainer-Ben%20McClure%20%40bmcclure-blue.svg?style=for-the-badge
[releases-shield]: https://img.shields.io/github/release/bmcclure/ha-enphase_envoy.svg?style=for-the-badge
[releases]: https://github.com/bmcclure/ha-enphase_envoy/releases
[user_profile]: https://github.com/bmcclure
