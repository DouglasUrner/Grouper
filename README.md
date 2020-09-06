# Grouper
Create import CSV file for Zoom to pre-assign breakout rooms. Optionally generate a second file to populate a slide table of room and role assignments.

## Options:
* Breakout Room Basename, a sequential number is added to it, starting with 1.
* Randomize the order of the input CSV file before generating rooms.
* Generate a Markdown table or CSV file to populate a table with group and role assignments for your slides.
* Input CSV fields holding the participants:
  - e-mail address
  - first name
  - last name
  - display name (used as is)
  - sortable name (last, first [mi]) parsed into last and first
  - role (overrides automatic role assignment)
* Desired group size
* Maximum group size (defaults to desired size)
* Minimum group size (defaults to desired size - 1)
* Role names in order to be assigned (defaults to "Manager, Presenter, Recorder, Reflector")
