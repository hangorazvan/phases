# Moon phase

[![Platform](https://img.shields.io/badge/platform-MagicMirror2-informational)](https://github.com/hangorazvan/MagicMirror2)
[![CC-0 license](https://img.shields.io/badge/License-CC--4.0-blue.svg)](https://creativecommons.org/licenses/by-nd/4.0)
[![GitHub branches](https://badgen.net/github/branches/hangorazvan/phases)](https://github.com/hangorazvan/phases)
[![GitHub forks](https://badgen.net/github/forks/hangorazvan/phases)](https://github.com/hangorazvan/phases)
[![GitHub stars](https://badgen.net/github/stars/hangorazvan/phases)](https://github.com/hangorazvan/phases)

https://github.com/hangorazvan/phases

Magic Mirror Module that displays the current moon phase with compliments

Based on Sven1603 / mmm-moon-phase-display and mykle1 / MMM-Lunartic images.

<img src=https://github.com/hangorazvan/phases/blob/master/phases.png>

## Using the module

Configure the module in your `config.js` file.


        modules: [
                {
                        module: 'phase',
                        position: 'top_center',
                        config: {
                                updateInterval: 60 * 60 * 1000,
                                animationSpeed: 1000,
                                moonPhasesNightOnly: true,
                                nightStart: "20:00:00",
                                nightEnd: "07:00:00",
                                width: "70",
                                height: "70"
                        }
                },
        ]

## Compliments

You need to use my compliments_plus to work with phases compliments https://github.com/hangorazvan/compliments_plus

        compliments: {
                new_moon : [
                        "<i class=\"pix wi wi-moon-new\"></i><span class=\"txt\"> New Moon</span>",
                ],
                waxing_crescent : [
                        "<i class=\"pix wi-moon-waxing-crescent-4\"></i> <span class=\"txt\"> Waxing Crescent</span>",
                ],
                first_quarter : [
                        "<i class=\"pix wi-moon-first-quarter\"></i> <span class=\"txt\"> First Quarter</span>",
                ],
                waxing_gibbous : [
                        "<i class=\"pix wi-moon-waxing-gibbous-4\"></i> <span class=\"txt\"> Waxing Gibbous</span>",
                ],
                full_moon : [
                        "<i class=\"pix wi wi-moon-full\"></i> <span class=\"txt\"> Full Monn</span>",
                ],
                waning_gibbous : [
                        "<i class=\"pix wi-moon-waning-gibbous-4\"></i> <span class=\"txt\"> Waning Gibbous</span>",
                ],
                third_quarter : [
                        "<i class=\"pix wi-moon-third-quarter\"></i> <span class=\"txt\"> Third Quarter</span>",
                ],
                waning_crescent : [
                        "<i class=\"pix wi-moon-waning-crescent-4\"></i> <span class=\"txt\"> Waning Crescent</span>",
                ],
        }

Redesigned by Răzvan Cristea https://github.com/hangorazvan Creative Commons BY-NC-SA 4.0, Romania.