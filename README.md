# Welcome to the repository for TECH UP: LINUX

## Contents:

- meetupCom/TemplateEvent.md - The template used for the announcement of the Linux Tech Up event on meetup.com
- meetupCom/TemplateInstallNight.md - The template used for the install night announcement on meetup.com
- meetupCom/AnnoucementInstallNight.md - The formal announcement to be published on meetup.com.
- meetupCom/AnnouncementEvent.md - The formal announcement to be published on meetup.com.
- Instructions for the following:
	- WSL2 installation (installInstructions/WSL2.md)
	- VirtualBox installation (installInstructions/virtualBox.md)

## Repository Rules

We follow **Scaled Trunk Based Development** in the repository. For more information on how to do this, please see https://trunkbaseddevelopment.com.

1. **Create your branch from the trunk.** This must be a short-lived branch. For example, something that can be done over the weekend. Please don't branch out from a release branch.
1. **Make your changes.**
1. **Commit your branch.** Do not commit to the release branches.
1. **Squash your commits.** If you have made many changes, combine your commits into one before pushing back to the repository.
1. **Open a pull request.** So your co-maintainer can review your changes before it merges back into the trunk.

### Releases

**Releases are made when they are ready to be published to the Meetup page.** Releases are always created using the format `YYYYMMDD` (e.g., 20210417) signifying the date of the main event (not *Install Night*. Minor releases have a dot number in `09` format (e.g., 20210417.01).

Again, please **do not create branches from the release branch**.
