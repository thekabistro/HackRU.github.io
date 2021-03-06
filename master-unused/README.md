# HackRU Splash Page
[![Build Status](https://travis-ci.org/HackRU/splash-page.svg?branch=master)](https://travis-ci.org/HackRU/splash-page)
[![GitHub license](https://img.shields.io/badge/license-ISC-blue.svg)](https://raw.githubusercontent.com/HackRU/splash-page/master/License.md)

This repository is used to store the splash page (landing page, squeeze page, whatever) for HackRU every semester. The splash page is designed to collect potential registrants' emails so that we can send out newsletters and important dates to them. It serves as the temporary landing page of [the HackRU website](http://www.hackru.org/) before the official pages (with signups, application, decisions, dashboard, etc.) are released. The splash page also hosts the sponsorship website (http://sponsorship.hackru.org), which gives potential sponsors an overview of the costs and perks that come with each sponsorship package, along with a form to communicate with the finance team about custom packages. Typically, the splash page is created and put up one month before the main website is finished.

# Running the App
Use the following commands to clone the repo and start the Node.js web app on your local machine (you'll need to [download Node.js first](https://nodejs.org/en/)). 

1. `git clone git@github.com:HackRU/splash-page.git`
1. `cd splash-page`
1. `npm install`
1. `npm start`

Visit `localhost:8080` (or whatever port the app started on) to view the app.

# Archival Branches
Every semester, before starting a new splash page for the semester's hackathon, please be sure to clone the current master branch, as that serves to preserve the previous semester's splash page for archival purposes. In order to do so, make sure you have contributor rights to this repository. Open up your favorite CLI (Bash, Cmder, or even Windows Command Prompt if you like to be made fun of) with Git installed.

1. `git clone git@github.com:HackRU/splash-page.git`
1. `git checkout -b HackRU-{Semester}-{Year}` (for example: `git checkout -b HackRU-Spring-2017`)
1. `git push origin HackRU-{Semester}-{Year}`

Refresh GitHub, and you should now see your archived branch under the branches. Work on the current semester's splash page using the master branch. Make it nice and pretty for all the hackers to see.
