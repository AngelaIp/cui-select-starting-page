# Change Starting Page option for every user

## Description

This package adds an additional CUI Menu Button that give users the ability to choose the **Starting Page** by themselves.

## Project Details

#### Built Using:
Aras 11.0 SP9

#### Versions Tested:
Aras 11.0 SP9

#### Browsers Tested:
Internet Explorer 11, Chrome 61.0, Firefox ESR 52.4.0

## Installation

#### Important!
**Always back up your code tree and database before applying an import package or code tree patch!**

### Prerequisites

1. Aras Innovator installed (version 11.0 SPx preferred)
2. Aras Package Import tool
3. Import package of this project

### Install Steps

#### Database Installation
1. Backup your database and store the BAK file in a safe place.
2. Open up the Aras Package Import tool.
3. Enter your login credentials and click **Login**
    * _Note: You must login as root for the package import to succeed!_
4. Enter the package name in the TargetRelease field.
    * Optional: Enter a description in the Description field.
5. Enter the path to your local `..\SelectStartingPage\Import\imports.mf` file in the Manifest File field.
6. Select **bpl.app.SelectStartingPage** in the Available for Import field.
7. Select Type = **Merge** and Mode = **Thorough Mode**.
8. Click **Import** in the top left corner.
9. Close the Aras Package Import tool.

You are now ready to login to Aras and try out the image importer.

## Usage

1. Login to Aras.
2. Navigate to **Tools > Preferences > Select Starting Page** in the main menu.
3. Choose the new Starting Page from the drop down list.
4. Click **Ok** to save the new Starting Page.

![cui-select-starting-page](./Screenshots/ChangeStartingPage.png)

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Credits

Created by @AngelaIp


## License

This project is published to Github under the Microsoft Public License (MS-PL). See the [LICENSE file](./LICENSE.md) for license rights and limitations.
