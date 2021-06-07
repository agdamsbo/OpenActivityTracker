_Please see this document as a working document or brainstorm._

# OpenActivityTracker (OpenATrack?)
More focus is put on physical activity (PA) as a way of preventning diseases and improving mental health.
For several years pedometers has been widely available and witing the last decade more dedicated fitness and healthtrackers or wearables have gained traction. Most recently heart rate monitoring (photoplethysmopgraph, PPG) has been made available to consumers. Multiple commercial trackers are available with different degrees of closed data and software.

In clinical vascular neuroscience physical activity is gaining increased focus. In this group of patients (like many others) it is difficult to get a reliable measure from questionaires alone. And the meassure of physical activity is concerned with everyday activities, and not VO2-max on a treadmill. For reasearch, a reliable non-intrusive tracker of PA would improve the insights as to the possible beneficial effect of PA, and also what kind and degree of PA.

## Goal
An open activity tracker as in open software, open design and open process..

## Wish list

### Must haves
- Accelerometer
- Heart rate (PPG) - preferably
- +7 days (preferably longer) battery life
- Local data storage

### Additional possible features
- Low cost
- Non-disturbing device (possible for upper arm placement?)
- Nudging function (vibration?) to remind of activity (standing or walking)- 

## Other options and inspiration

### Commercial trackers
Not a pefectly complete list, however a list of candidates living up to most of the pointers on the wish list.

Name | Comments | Data export
------------ | ------------- | -------------
Moov |Tracking is split in two devices. One for activity, and one for heart rate (placed around head or chest, likely to get better readings than on the wrist). Advertised six months battery. | Unknown
Fitbit Inspire 2 | 10 days battery. Small. Activity and heart rate. | Export through Fitabase.
Mi Band 6 | Tracker. Simple look. | Unknown
Withings Steel HR | Regular watch look. Tracks activity and heart rate. 25 days batterylife advertised (less with continous heartrate) | CSV export from cloud
Withings ScanWatch | Regular watch look. Tracks activity, heart rate and SpO2. 30 days batterylife advertised (less with continous heartrate) | CSV export from cloud
Withings Pulse HR | Tracker. Simple. | CSV export from cloud

### Open projects
I have tried 

Name and link | Comments
------------ | -------------
Openmovement (https://github.com/digitalinteraction/openmovement) | Open trackers developed for research at Newcastle University. Project seems stalled. Maybe related to Brexit? No PPG. Sample data available, dated 2013.
OpenHAK (https://www.openhak.com) | Tracker with optional screen. Simple. Simblee chip has been terminated. All schematics available.
Emotibit (https://www.emotibit.com) | Tracker. Based on arduino feather. Open software. A lot of sensors. Bulky when wearing for extended period. No hardware schematics available.
PineTime (https://www.pine64.org/pinetime/) | Smartwatch. Open software, data export and hardware scematics. 3-5 days batterylife.
Bangle.js (https://banglejs.com) | Smartwatch. No schematics available.
Open SmartWatch (https://open-smartwatch.github.io) | Smartwatch. Schematics available. DIY-kit. No consumer product.

## Other projects of interest

- GNU Health (https://gnuhealth.org/index.html)
  - A full open source health suite for institutions and individuals. Support for the PineTime watch is pending and other open hardware and open source health trackers.

# Open issues with open projects
- CE certification for usage
- more..

# Possible roads
The following are just loose thoughts in an attempt to get a grip on the options available.

- Start with a new project from scratch.
- Fork the PineTime project and develop an essential version with only sensors and no display for optimised battery.
- Convert the OpenHAK project to a new chip technology.
- Forget about the open hardware and by a commercial project and export the data available.
