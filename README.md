# Polymer Darksky

Polymer web components for Dark Sky API

## Installation

```
bower install --save polymer-darksky
```

## Usage

```
<darksky-forecast
  auto
  api-key="0c91dff60f9a0f4f2628d39ee828341a"
  latitude="-37.817348"
  longitude="144.965108"
  exclude='["minutely","hourly","daily","flags"]'
  extend-hourly
  lang="en"
  units="ca"
  response="{{_fcResponse}}">
</darksky-forecast>
```

and

```
<darksky-time-machine
  auto
  api-key="0c91dff60f9a0f4f2628d39ee828341a"
  latitude="-37.817348"
  longitude="144.965108"
  time="409467600"
  exclude='["minutely","hourly","daily","flags"]'
  lang="en"
  units="ca"
  response="{{_tmResponse}}">
</darksky-time-machine>
```
