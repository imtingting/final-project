# Final Project

**This is only a draft of the final project writeup. It is not finalized yet.**

The final project will be the culmination of all of the skills learned in the class. Students will build an application that has a custom backend (e.g., PostGIS database) hosted on the cloud that can be publicly accessed and returns custom responses based on user feedback. Expectations are that API responses will be communicated in multiple ways: a static chart or map, interactive map, and formatted statistics.

## Requirements

* Data
  * Data is hosted on your own AWS RDS PostgreSQL/PostGIS database that you manage
  * Does one or more third-party API calls (e.g., Google Maps APIs, Census API, Twitter)
* Application
  * Contents
    * Option to download response
    * Image
    * Bad requests lead to good errors letting user know that their input was not valid
    * 404 page
* Python script
  * Python application functions all have full docstrings
  * Architecture diagram of your application
  * Credentials for any third-party APIs are stored in accompanying JSON files instead of being hard-coded into the Python script
  * Contains one or more templated queries to your DB, using
* Web pages
  * Must have full HTML tags (html, title, body, header, etc)
  * Use static CSS for styling the page
  * Include one at least one partial HTML template to include in the full HTML page
  * Give option on page to run another query (e.g., gives user the option to explore areas adjacent to region of interest)
  * Works with backend to ensure that inputs are valid. Gives feedback if not. E.g., Flask message flashing
* Application Development
  * All code is to be committed to GitHub
  * No API credentials, DB credenitals, or otherwise should be committed to the repo. Instead, commit files that are in the same structure but do not contain the API keys, passwords, hosts, etc. A good practice is to have files like `pg-credentials.json.sample` committed but in the `.gitignore` file `pg-credentials.json` is added to avoid accidentally committing.
  * Each person in the group must contribute roughly equal contributions of code to the repository
