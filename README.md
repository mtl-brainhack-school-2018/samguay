# mtl_brainhack_school_project
---
### This is my repo for the projects I've been working on during the [MONTREAL BRAINHACK SCHOOL](https://brainhackmtl.github.io/school2018/) from May 14th to June 1st 2018.
***
####  :dizzy::boxing_glove::woman_cartwheeling::rugby_football::baseball::basketball::soccer::football::zap: I'm working with sports-related concussion MRI data :zap::football::soccer::basketball::baseball::rugby_football::men_wrestling::boxing_glove::dizzy:

This BrainHack School is an amazing opportunity for me to finally try and learn how to use different tools I have heard for a while. As a newcomer to the field, my aim are __1-__ to set up a proper neuroimaging-friendly environment and __2-__ familiarize myself with a reproducible framework while analyzing some quantite MRI data. By that I mean:

:pushpin: = What I am currently working on <br>
:interrobang: = Where I'm curently stuck / struggling / have questions
:arrow_right: = Some comments I added as reminder

# 1- Setting up a multi-modality database (__[LORIS](http://loris.ca/)__):

 With more than 150 people who will undergo several MRI and PET scans as well as multiple cognitive and behavioral assessments for my project, developping data handling skills is more than a must for me. This is where __[LORIS](http://loris.ca/)__ comes in handy by standardizing data entry.

 > If you don't know  what LORIS is (taken from LORIS [website](http://loris.ca/)):
 > - _What is LORIS?_ <br>
  LORIS is a flexible web-based platform that facilitates and centralizes data collection and data management in multi-site, multi-modal integrative neuroimaging and behavioral studies.


> - _Why use LORIS?_ <br>
 LORIS is designed to simplify integration, management, and dissemination of cohort studies that involve various neuroimaging modalities, behavioral tests, and genetic and neurophysiological data. It provides secure web-based access to data validation and quality control modules, as well as visualization and basic statistical tools.

#### As a first step, I'd like to properly set it up locally on my machine so I can start customizing it for my project!

- [x] __Installing Loris__ (basic functionality)
  - [x] Assumptions
  - [x] Getting Prerequisites
  - [x] Creating a user for LORIS
  - [x] Downloading LORIS
  - [x] Running the Install Script
  - [x] Configuring Apache2
  - [x] Installing the Database - 1 of 2
  - [x] Installing the Database - 2 of 2 <br>
- [x] __Project Customization__
  - [x] Database Configuration settings
  - [x] Create front-end Users
  - [x] Create back-end accounts
  - [x] Define study Sites
  - [x] Configure study Variables :arrow_right: still need to define some more
  - [x] Useful Apache configuration options <br>
- [x] __Behavioral Database__ :arrow_right: installed but not fully customized yet
  - [x] Instrument Builder
  - [ ] Scoring algorithms :arrow_right: Looked at it, will play with it later.
  - [ ] Populate test_names and test_subgroups tables
  - [ ] Populate test_battery table
  - [ ] Populate Examiners table
  - [ ] Testing and Troubleshooting Instruments
  - [x] Double Data Entry
  - [ ] Excluding Instruments
  - [ ] Instrument Permissions
  - [ ] Instrument Manager
- [ ]:pushpin: __Imaging Database__<br>
  - [x] Install the imaging pipeline codebase
  - [ ] Set up imaging insertion scripts :interrobang: :arrow_right: Think I am done with the step
  - [ ] Loading a scan into LORIS :interrobang: :arrow_right: still need to figure out the naming convention to convert DCM --> Niftii
    - [ ] 3a. Imaging Uploader
    - [ ] 3b. Running the insertion Pipeline
  - [ ] Verify loaded images and Troubleshooting
  - [ ] Queue Manager
  - [ ] Email Notifications [is it possible if local installation?]
  - [ ] Visualization: BrainBrowser
  - [ ] Quality Control within the Imaging Browser
  - [ ] Anonymization
  - [ ] Post-processing (CBRAIN)
<br>
- [ ] __LORIS Modules__

- [ ] __Data Querying Tool__

- [ ] __Backups__

- [ ] __Security: Enabling SSL__ :interrobang: Even if locally installed ?

- [ ] __Enable Mail Server__ :interrobang: Even if locally installed ?

:bomb: Shout out to __Cecil__ and __Liza__ who consistently helped me out ! :bomb:

# 2- Setting up my reproducible environment and try analyzing some prelimenary data:

If I have some more __free__ times (~~which I doubt~~)
* I have some data that I'd like to quantitatively analyze using __[QMRLab](https://github.com/neuropoly/qMRLab)__ that __[Agah](https://github.com/agahkarakuzu)__ (also a 2018 participant :arrow_right: [his school repo here](https://github.com/mtl-brainhack-school-2018/agahkarakuzu)) is developing.

Final word: Free your schedule to make sure you actually have time to work on the project you had in mind and not spend your whole time elsewhere :weary:
