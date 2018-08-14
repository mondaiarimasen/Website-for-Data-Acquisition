%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%% Website for Data Acquisition %%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

mondaiarimasen
Created August 8, 2018

*****************************************************************************
I. Motivation

  - have a place to monitor:
        > temperature of the channels of the dilution refrigerator (DR)
        > flow rate of the cooling water of the He compressor outside building
        > temperature of the He compressor
        > temperature and humidity of the lab room

  - can monitor instruments from the office room while the DR is operating,
    without having to go to the lab room

*****************************************************************************
II. Program Descriptions

  - test_website.html
        ->  draft website for placement of things on website
        ->  current version can read from tempData.dat and display the most 
            recent data on the webpage, and constantly refreshes the page 
            every 5 seconds
        ->  temp readings displayed are colored red or green depending on
            if the reading is out of or within the limits, respectively
        ->  displays cooling water flow rate, temp of He compressor, and 
            temp and humidity of lab, but values are hard-coded, and are
            for demo purposes (not exactly real values)

*****************************************************************************
III. Comments

  - will most likely not be on a domain or server, as that is a bit
    complicated for current purposes

  - starting August 14, 2018, new directory "Cryo-Monitor" will contain the 
    programs to read the LS372 in real time, to display the website, and
    obtain data from the environment (e.g. cooling water flow rate, 
    temperature of the He compressor, and the temperature and humidity of 
    the lab

*****************************************************************************
