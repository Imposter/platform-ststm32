# ST STM32: development platform for [PlatformIO](http://platformio.org)
[![Build Status](https://travis-ci.org/platformio/platform-ststm32.svg?branch=develop)](https://travis-ci.org/platformio/platform-ststm32)
[![Build status](https://ci.appveyor.com/api/projects/status/y5dayom6bltenoeh/branch/develop?svg=true)](https://ci.appveyor.com/project/ivankravets/platform-ststm32/branch/develop)

The STM32 family of 32-bit Flash MCUs based on the ARM Cortex-M processor is designed to offer new degrees of freedom to MCU users. It offers a 32-bit product range that combines very high performance, real-time capabilities, digital signal processing, and low-power, low-voltage operation, while maintaining full integration and ease of development.

* [Home](http://platformio.org/platforms/ststm32) (home page in PlatformIO Platform Registry)
* [Documentation](http://docs.platformio.org/page/platforms/ststm32.html) (advanced usage, packages, boards, frameworks, etc.)

# Usage

1. [Install PlatformIO](http://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](http://docs.platformio.org/page/projectconf.html) file:

## Stable version

```ini
[env:stable]
platform = https://github.com/Imposter/platform-ststm32.git#master
board = ...
...
```

## Development version

```ini
[env:develop]
platform = https://github.com/Imposter/platform-ststm32.git#develop
board = ...
...
```

# TODO
- Update CI information
- Update fork with latest versions.
- Delete other branches (make new develop branch)

# Configuration

Please navigate to [documentation](http://docs.platformio.org/page/platforms/ststm32.html).
