# Simple sample config files for using Force.com Migration Tool

## Setup

Follow the instructions here:
https://developer.salesforce.com/docs/atlas.en-us.daas.meta/daas/meta_development.htm

You will need to install ANT (if not already installed), and put the ant-salesforce.jar in the correct location (depending on OS).

Following that, enter your options in the `build.properties` folder. Which include your username, password, URL and other options.

## Commands

### Deploy

Put your package.xml and deployment contents into the `deploy` folder, and type `ant deploy` from the command line (from this root directory).

### Retrieve

Put your package.xml of what you want to retrieve, and type `ant get` in your command line. This will retrieve all contents of your package.xml into the retireved folder.

### Retrieve Changeset

Used to retrieve all contents of a changeset. Put your changeset name in the `build.properties` file and run `ant getChangeset` from the command line.