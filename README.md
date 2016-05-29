View Exif
===========
viewexif display some exif data for attached images

[![Build Status](https://travis-ci.org/BoardTools/cronstatus.svg?branch=master)](https://travis-ci.org/BoardTools/cronstatus)

## Requirements
* phpBB 3.1.0 or higher
* PHP 5.3.3 or higher


## Quick Installation
You can quickly install this extension on the latest version of [phpBB 3.1](https://www.phpbb.com/downloads/) or on the latest development version of [phpBB 3.1-dev](https://github.com/phpbb/phpbb3) by doing the following:

1. Upload the extension with "[Upload Extensions](https://github.com/BoardTools/upload)".
2. Check that you have uploaded the correct files.
3. Click `Enable`.

## Standard Installation
You can install this extension on the latest version of [phpBB 3.1](https://www.phpbb.com/downloads/) or on the latest development version of [phpBB 3.1-dev](https://github.com/phpbb/phpbb3) by doing the following:

1. Download the extension. You can do it [directly from phpbb.com](https://www.phpbb.com/customise/db/extension/cronstatus/) or by downloading the [latest ZIP-archive of `master` branch of its GitHub repository](https://github.com/BoardTools/cronstatus/archive/master.zip).
2. Check out the existence of the folder `/ext/boardtools/cronstatus/` in the root of your board folder. Create folders if necessary.
3. Copy the contents of the downloaded `cronstatus-master` folder to `/ext/boardtools/cronstatus/`.
4. Navigate in the ACP to `Customise -> Extension Management -> Manage extensions -> Cron Status`.
5. Click `Enable`.

## Usage
### Cron Status page
To check the Cron Status navigate in the ACP to `Maintenance -> Cron Status -> Check Cron Status`.

### Cron Status Notice
Cron Status Notice is displayed on the main page of ACP when Cron is locked. This notice provides some information about the last Cron task that made Cron locked.
If you want to remove Cron Status Notice from the main page of ACP (to use only Cron Status page), navigate in the ACP to `General -> Board configuration -> Board settings -> Cron Status -> Notice on ACP index page` and set it to "No".

### Cron Status settings
You can change the date format for Cron Status or remove Cron Status Notice that is displayed on ACP index.
Navigate in the ACP to `General -> Board configuration -> Board settings -> Cron Status`.

## Update
1. Download the updated extension. You can do it [directly from phpbb.com](https://www.phpbb.com/customise/db/extension/cronstatus/) or by downloading the [latest ZIP-archive of `master` branch of its GitHub repository](https://github.com/BoardTools/cronstatus/archive/master.zip).
2. Navigate in the ACP to `Customise -> Extension Management -> Manage extensions -> Cron Status` and click `Disable`.
3. Copy the contents of the downloaded `cronstatus-master` folder to `/ext/boardtools/cronstatus/`.
4. Navigate in the ACP to `Customise -> Extension Management -> Manage extensions -> Cron Status` and click `Enable`.
5. Click `Details` or `Re-Check all versions` link to follow updates.

## Uninstallation
Navigate in the ACP to `Customise -> Extension Management -> Manage extensions -> Cron Status` and click `Disable`.

For permanent uninstallation click `Delete Data` and then you can safely delete the `/ext/boardtools/cronstatus/` folder.

## License
[GNU General Public License v2](http://opensource.org/licenses/GPL-2.0)

© 2014 - John Peskens (http://ForumHulp.com) and Igor Lavrov (https://github.com/LavIgor)