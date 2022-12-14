# Ironhack/Wilco Quest

## Quest Details

#### title: Ironcomponents

#### level: Begginer

#### skills:

- frontend
- setup

#### dependencies:

- docker_localsetup

## Overview

The objective of this quest is for the user to learn how to setup the styled-components library for future use

## Outline

Describe each step in the quest.

- Ironcomponents Setup [ironcomponents_setup]: The user will install the styled-components package and setup the ThemeProvider and theme vriable
- Ironcomponents Global [ironcomponents_global]: The user will create the GlobalStyle component and add some of the already existing css styles to it

## Textbook solution

For this quest the user needs to install the styled-components package and create the folders and files on the correct places and import the newly created files into index.js.

### Instructions for completing the quest:

#### Ironcomponents Setup [ironcomponents_setup]:

- Install the styled-components package in the frontend folder
- Create a styled folder inside frontend/src
- Create a theme.js inside the styled folder
- Create an object with two properties, dark (#170539) and light (#af93f2)
- Import the theme object created previously and the ThemeProvider from styled-components into index.js
- Setup the ThemeProvider in the React tree using the theme variable

#### Ironcomponents Global [ironcomponents_global]:

- Inside the styled folder create a GlobalStyle.js file
- In the GlobalStyle file setup the component according to the [docs](https://styled-components.com/docs/api#createglobalstyle)
- In the GlobalStyle component, setup the body's background-image, background-position and background-repeat properties available already in the custom.scss file
