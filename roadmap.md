# PUniSport_Scheduler Roadmap

## Overview
We want to create a tool that assists students of the Uni Bern in the process of finding a suited sport activity.
The tool is gathering the needed information from the UniBe sports website and provides activities based on the students input.
The following aspects shall be taken into account (for further detail see Milestone 2): Available timeslots, level of expertise needed, preferences (e.g. team sport, etc.)

## Milestones
- [ ] **Milestone 1**:  Setting up the Github page (Target Date: 2024-04-25)
  - A welcome page, README file and a roadmap are available.
- [ ] **Milestone 2**: Data collection and integration (Target Date: 2024-05-02)
  - The data from the UniBe sport website can be scraped, stored and read.
  - Ths includes schedules, registration requirements, difficulty, locations, descriptions.
  - The information is collected in a proper format like a pandas dataframe (to be determined)
  - Optional (at latest within milestone 3 it gets obligatory): get a first mask that takes user preferences that can be used to check the collected data
- [ ] **Milestone 3**: Data visualization (Target Date: 2024-05-16)
  - Based on the user input a selection of suited sport activities gets presented.
  - Give the data output not only as a list, but also as a timetable, so the students can more easily decide

## Upcoming Features
- **Feature A**: All UniBe sport activities are implemented with one software solution.
- **Feature B**: Sport selection based on preferences. Be it your schedule, your sport category, or that the training is nearby.
- **Feature C**: You get an overview over all possible sport activities within a proper timetable, so you can manually chose to your likings.

## Known Issues
- To be updated

## Future Enhancements
- Data scraping from Unisport
- Information storage
- Match with user preferences
- personalized recommendations

## Release Plan
- **Version 1.0**: Basic functionality (Release Date: 2024-05-16)
