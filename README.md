oh-mainline-installability
==========================

This repo exists merely to trigger travis-ci to test if oh-mainline's latest code commits have broken our install instructions.

The install instructions officially live here:

* http://openhatch.readthedocs.org/en/latest/getting_started/installation.html

We've carefully hand-copied them into .travis.yml, so this will detect if it

To make sure that this runs periodically, there should be a cron job on e.g. linode.openhatch.org
that triggers Travis-CI to do a build.

In effect, this git repo exists merely to get Travis-CI to run a periodic task for us.
