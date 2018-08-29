# Automating Tasks with the Redcap API
#### CAPS Presentation, Aug 29, 2018


 This repo contains:
 - A <a href='https://github.com/billsanto/caps_redcap_api/blob/master/caps_redcap_api_presentation.pdf'>pdf export</a> of the presentation
 - Three Jupyter notebooks. The notebooks progress from the basics to fully functional code that can be adapted for a project:
     - <a href='https://github.com/billsanto/CAPS-Redcap-API-Presentation-20180829/blob/master/caps_python_intro.ipynb'>Intro to Python 3</a>
        - Basic data structures
        - Comprehensions
        - Map, filter
        - Lambda expressions
        - Functions
        - Loops
        - Exception handling
     - <a href='https://github.com/billsanto/CAPS-Redcap-API-Presentation-20180829/blob/master/caps_pandas_redcapy.ipynb'>Data Wrangling with Redcap</a>
        - Import test data into a simple longitudinal project
            - Consists of baseline, 6, and 12 Month events
            - Repeating instrument
            - Randomized participants
        - Exporting data records from the API
            - Caching data locally
        - Exporting the data dictionary from the API
            - Using the dictionary with raw and labeled data
        - Importing and deleting files using the API
        - Demonstration of import overwrite behavior
        - Data wrangling Redcap data using lists, dicts, series, and DataFrames
            - Missing data
            - Filtering DataFrames
            - Transforming data
     - <a href=''>Messaging with Email and the Twilio API</a>
        - Sending email notifications with the SMTP protocol
        - Using Python logging to record events
        - Sending SMS to study participants using Twilio
        - Checking SMS delivery status
        - Twilio datetime localization
        - Importing Twilio status data into a Redcap instrument
- An <a href='https://github.com/billsanto/caps_redcap_api/blob/master/CAPSDemoProject_2018-08-28_2111.REDCap.xml'>XML copy</a> of the Redcap demo project that is paired with this code is also available. This file can be imported into Redcap by selecting <a href='https://redcap.ucsf.edu/index.php?action=create'>'New Project'</a> and choosing the option 'Upload a REDCap project XML file (CDISC ODM format)'.




