<h1 align="center">
	<img
	width="150"
	src="/images/max-terminal.gif"></br>
	Maven Files<br>     
</h1>

<h4 align="center">
	<a href="#overview">Overview</a> |
	<a href="#installation-instructions">Install Me</a> |
	<a href="#faqs">FAQs</a> |
	<a href="#contributing">Contribute</a>
</h4>
	
<h3 align="center">
	In this repository, you can find some maven files examples that will help you for other tutorials.<br><br>
</h3>

## Overview

Take these files as example or to use as your own for other tutorials that may require you to use Maven.

- If you're following the [Custom Policy Tutorial](https://developer.mulesoft.com), you can find the example file and the instructions [here](/CustomPolicyTutorial).
- For a general example with comments and instructions, go to [this file](/FullSettingsFile/settings.xml).

## Installation Instructions

1. Go to the example file you need to follow your tutorial
2. Download the file or copy its contents
3. Put the file inside the `.m2` folder or create a new one and paste its contents
4. Don't forget to add your own credentials!

## FAQs

#### Where do I find my .m2 folder?

- For Windows: `C:\Users\<user>\.m2`
- For Mac: `${user.home}/.m2`

#### What if I don't have an .m2 folder?

- Make sure you have installed [Maven](https://maven.apache.org/install.html).

## Contributing

Contributions are what make the MuleSoft community such an amazing place. Any contributions you make are **greatly appreciated**.
	
See [contributing.md](/contributing.md) for the MuleSoft Developer principles.

## Utilities and Dependencies

#### Dependencies

-   [Maven](https://maven.apache.org/install.html)

#### Code formatting

[Prettier](https://prettier.io/) is a code formatter used to ensure consistent formatting across your code base. To use Prettier with Visual Studio Code, install [this extension](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) from the Visual Studio Code Marketplace. The [.prettierignore](/.prettierignore) and [.prettierrc](/.prettierrc) files are provided as part of this repository to control the behavior of the Prettier formatter.
