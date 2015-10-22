# BikersField

![RunnersField Screenshot](/doc/BikersField1.png)

This is free a Data Field for the Fenix 3 that shows multiple values on a single field. 
BikersField is open source and its code resides at github: https://github.com/kopa/BikersField

Release versions are published in the [Garmin App Store](https://apps.garmin.com)

## Feedback
https://forums.garmin.com/showthread.php?327411-DataFields-RunnersField

## Features
* TIME: 12/24h mode based on system settings.
* SPEED: speed in km/h or mi/h based on system settings (as average of the last 10 values)
* AVG SPEED: average speed over the whole activity
* DISTANCE: elapsed distance in km or miles based on system settings
* DURATION: duration of the activity in [hh:]mm:ss
* GPS: green bars for poor/acceptable/good signal, gray if no signal
* battery: visualization of battery percentage as indicator bar. 
  If battery value < 30 the indicator bar gets orange. If value < 10% the exact value will be shown and the indicator bar turns red 
* unit system in use: "(km)" will be shown when metric system is set in the settings, "(mi)" if statute (imperial) units are configured.


## Install Instructions
A Data Field needs to be set up within the settings for a given activity (like Run)

* Long Press UP
* Settings
* Apps
* Run
* Data Screens
* Screen N
* Layout
* Select single field
* Field 1
* Select ConnectIQ Fields
* Select RunnersField
* Long Press Down to go back to watch face

## Usage
Start Run activity.
Hopefully you see the RunnersField datafield.

## Changelog 1.1.0
* Redesign
* Improved memory footprint

## Changelog 1.0.3
* Fix app id so that it doesn't interfere with RunnersField

## Changelog 1.0.2
* Based on RunnersField 1.0.2 and changed pace for speed
* Fix when black background is configured in device settings.
* Add battery percentage if < 10% left and make visualization red.
* Fix irrelevant slow pace values
* Change string TIMER to DURATION
* Change string metric to km and statute to miles

## Changelog 1.0.1
* Time mode is now dependent on device settings (12/24 hours mode)
* Distance and pace will be presented dependent on device settings (metric [km, km/min] or statute [miles, miles/min]), "metric" or "statute" will be shown below battery/gps
* HR is now dark red to visually decipher the different values faster

## Changelog 1.0.0
* Time of day
* Current Pace (average over 10 seconds)
* Average Pace
* Heart Rate
* Distance
* Timer
* Battery Status
* GPS Status (green = gps lock, red = no gps lock)
