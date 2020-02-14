# Android SQLite support library

See the main repo for the latest README (https://github.com/requery/sqlite-android).

# Why this fork is needed

See https://github.com/requery/sqlite-android/pull/125 PR for some background info. This forks bumps the maximum # of host parameters in a Single SQL statement to 32768 (up from the default 999).

# Deployment

Run https://jenkins.planfront.net/job/Custom-Deploy-Tasks/job/DEPLOY-Android-SQLite-Requery-Fork/ to deploy a new version of the artifact.
