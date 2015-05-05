# Manifest for Qt

This is a repo manifest for use with developing on Qt. You can use repo to
submit to gerrit, update repositories, manage projects across repositories, etc.
It's pretty useful.

# How to do changes

Make the change on the dev branch, and then merge it down into the version
branch of your choice.

# How to track a new version

    git checkout dev
    git checkout -b <version>

Change the default revision in default.xml to match the branch version of
your choice.
