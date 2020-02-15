# Android SQLite support library

See the main repo for the latest README (https://github.com/requery/sqlite-android).

# Why this fork is needed

This forks bumps the maximum # of host parameters in a single SQL statement to 32768 (up from the default 999).See https://github.com/requery/sqlite-android/pull/125 PR for some background info. This fork can be deleted if that PR is merged into requery/sqlite-android.

# Deployment

1. Update the library
2. Increase the version number in sqlite-android/build.gradle
3. Run https://jenkins.planfront.net/job/Custom-Deploy-Tasks/job/DEPLOY-Android-SQLite-Requery-Fork/ to deploy a new version of the artifact.
