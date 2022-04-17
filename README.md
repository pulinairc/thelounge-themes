## Modern The Lounge themes for Modern IRC

#### Used by the popular Finnish channel [#pulina @ QuakeNet](https://www.pulina.fi)

[![GitHub release](https://img.shields.io/github/tag/pulinairc/thelounge-themes.svg?style=flat-square)](https://github.com/pulinairc/thelounge-themes/releases) [![The Lounge](https://img.shields.io/badge/tested%20with%20thelounge-4.2.0-ff9e18.svg?style=flat-square)](https://github.com/thelounge/thelounge)

Aiming to be the **perfect** The Lounge theme out there.

**Please note:** This repository does NOT include the main midnight theme. It should be used from its own repository: [thelounge-theme-midnight](https://github.com/ronilaukkarinen/thelounge-theme-midnight) or via npm. Other themes here are mainly for experimental reasons.

## Requirements

- [thelounge](https://github.com/thelounge/thelounge)
- [thelounge-theme-midnight](https://github.com/ronilaukkarinen/thelounge-theme-midnight)

## Features

- Minimal UI
- Easy on the eyes
- Conversation layout, see [#2591](https://github.com/thelounge/thelounge/pull/2591#issuecomment-785429158)
- Automatic theme that has both day/light and night/dark versions based on your operating system setting
- Fixed preview images with correct dimensions
- Fixed most of The Lounge style bugs
- The most readable modern fonts on Retina and 60hz mobile screens

| Desktop view  | Mobile conversation layout |
| ------------- | ------------- |
| <img src="https://i.imgur.com/fOVc5Gt.png" width="800px" height="auto"> | <img src="https://i.imgur.com/MjMWZkz.png" width="390px" height="auto"> |

## Installation

1. Download
2. Move files under dist/ folder to your thelounge/public/themes/ directory

### Development

#### I want to change something!

Please fork this repository and make your changes.<br>
If the changes are good we might even accept pull requests.

#### I want a bigger font to mobile

Change your theme to "Midnight-accessible" from Settings.

## Development

1. Clone this repo and [thelounge-theme-midnight](https://github.com/ronilaukkarinen/thelounge-theme-midnight)
1. `cd /path/to/thelounge-themes`
2. `npm install`
3. Start coding by running in separate Terminal: `code .` or just use any editor you wish
4. Run watchers:

For <b>day</b>:

``` bash
scss --watch src/day.scss:dist/day.css --style compressed
```

For <b>auto-day-midnight</b>:

``` bash
scss --watch src/auto-day-midnight.scss:dist/auto-day-midnight.css --style compressed
```

For <b>midnight-classic-mobile</b>:

``` bash
scss --watch src/midnight-classic-mobile.scss:dist/midnight-classic-mobile.css --style compressed
```

For <b>midnight-accessible</b>:

``` bash
scss --watch src/midnight-accessible.scss:dist/midnight-accessible.css --style compressed
```