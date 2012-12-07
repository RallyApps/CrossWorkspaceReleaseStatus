Rally Cross Workspace Release Status
======================

![Title](https://raw.github.com/RallyApps/CrossWorkspaceReleaseStatus/master/screenshots/title-screenshot.png)

## Overview

The Cross Workspace Release Status app is a management view of work across workspaces that share the same release schedule.

## How to Use

### Running the App

If you want to start using the app immediately, create an Custom HTML app on your Rally dashboard. Then copy App.html from the deploy folder into the HTML text area. That's it, it should be ready to use. See [this](http://www.rallydev.com/help/use_apps#create) help link if you don't know how to create a dashboard page for Custom HTML apps.

Or you can just click [here](https://raw.github.com/RallyApps/CrossWorkspaceReleaseStatus/master/deploy/App.html) to find the file and copy it into the custom HTML app.

### Using the App

A shared release schedule is determined by a release with the same name, start and end date. If a release with the same name and different dates exists, the release drop-down will show the unique dates. Otherwise, the release drop-down will only display the release name.

Releases across all workspaces that a user has permission to view are populated in the Release drop-down. The user can then select a given release to see a tabular view of scheduled stories, defects, and defect suites for a particular release. The tabular view includes the formatted ID, workspace name, project name, schedule state, plan estimate, task estimate and to do for the given artifact.

## Customize this App

You're free to customize this app to your liking (see the License section for details). Since this app uses a very old version of Rally's SDK, the app is only presented in its deployed form.

## License

CrossWorkspaceReleaseStatus is released under the MIT license.  See the file [LICENSE](https://raw.github.com/RallyApps/CrossWorkspaceReleaseStatus/master/LICENSE) for the full text.
