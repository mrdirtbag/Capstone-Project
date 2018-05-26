[//]: # (Image References)

[image1]: ./images/LifeguardApp_today.png "Today screenshot"
[image2]: ./images/LifeguardApp_calendar.png "Calendar screenshot"
[image3]: ./images/LifeguardApp_makeavailable.png "Make Available screenshot"

# Capstone-Project
## Screenshots

![image1][Today screenshot]

![image2][Calendar Screenshot]

![image3][Make Available Screenshot]


## Lifeguard App

- [x] Screens
  - [x] Today
  - [x] Tomorrow
  - [x] Calendar
    - [ ] Reload calendar data when user is hired.

  - [ ] Settings Screen
    - [x] cleanup order and format of settings screen
    - [ ] check each notification reacts to settings filters

- [x] Monitor place on list
  - [x] notify user when within 5 people of being hired
  - [x] notify user when assigned a shift
- [x] Review previous shifts worked or assigned - Calendar View

- [x] Make available
  - [x] Notification when made available
  - [x] Reload calendar data when made available
  - [x] set date buttons to today in onCreate 
  - [x] Reload picklist data if affected 

- [x] Make unavailable
  - [x] Notification when made unavailable
  - [x] Reload calendar data when made unavailable
  - [x] Reload picklist data if affected

- [x] Google Play Services
  - [x] Firebase Job Scheduler
    - [x] turn on and off scheduler from settings screen
  - [x] Itentity - show current user icon
    - [ ] invalidate picklist data after icon is activated 
  - [x] Analytics - to get usage stats

- [ ] Auto update widget provider

- [ ] material design
  - [ ] transition to Make Available and back
  - [ ] transition to Settings and back
- [x] rebuild both ListViews as RecyclerViews
- [ ] Change AppCompat Activities to modern Activities.
- [x] add TestFairy user tracking
