Change Log
==========
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/).
This project adheres to [PEP440](https://www.python.org/dev/peps/pep-0440/)
and by implication, [Semantic Versioning](http://semver.org/).

[Unreleased]
------------
- Renamed the package to ebird.scrapers. ebird-pages is used for another project.
- Updated get_checklist to return the checklist owner.
- Updated get_checklist to return a list of other participants.
- Updated get_checklist to return the number of observers.
- Updated get_checklist to use table for extracting protocol values.
- Updated get_checklist to return duration in minutes.
- Updated get_checklist to return distance in metres.
- Updated get_checklist to return area in hectares.
- Updated get_checklist to include observation comments.
- Updated get_checklist to include any media identifiers.
- Updated get_checklist to include any breeding codes.
- Updated get_checklist to include any breakdown in the count by age and sex.
- Updated get_checklist to include common and scientific names for a species.
- Split the PROALAS protocol into three - 2 point counts, 1 transect.
- Add a script that can be run via cron to check for web page changes.

[0.2.0] - 2024-10-23
--------------------
- Added get_recent_checklists to scrape the "Recent Checklists" page
- Updated get_checklist now works with the latest page layout

[0.1] - 2017-08-21
------------------
- Added get_checklist for scraping the data from the view checklist page.
- Added script so get_checklist can be called from the command line.
