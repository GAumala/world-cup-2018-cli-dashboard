![screenshot](https://raw.githubusercontent.com/cedricblondeau/world-cup-2018-cli-dashboard/master/screenshot.jpg)

# World Cup 2018 CLI Dashboard [![Build Status](https://travis-ci.org/cedricblondeau/world-cup-2018-cli-dashboard.svg?branch=master)](https://travis-ci.org/cedricblondeau/world-cup-2018-cli-dashboard)

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/kinda-sfw.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/uses-js.svg)](https://forthebadge.com)

## Install

**Using `docker` 🐳**:

```bash
docker run -ti cedricbl/world-cup-2018-cli-dashboard
```

**Using `yarn`**:

```bash
yarn global add world-cup-cli-dashboard
```

Requires NodeJS 6+.

**Using `npm`**:

```bash
npm install -g world-cup-cli-dashboard
```

Requires NodeJS 6+.

## Usage

```bash
wc2018
```

## How does it work?

Data is sourced from the awesome [worldcup.sfg.io](http://worldcup.sfg.io/).

Today matches get updated each 5 minutes. Current game score gets updated each 60 seconds.

Terminal interface built with [react-blessed](https://github.com/Yomguithereal/react-blessed).

## LICENSE

MIT
