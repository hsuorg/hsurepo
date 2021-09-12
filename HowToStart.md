---
title: How to Start and Manage Files
---
1.1	How to start
=====
**To open Rezonator, double click on the Rezonator icon on your desktop or select the icon from the Start menu. The Open screen will be displayed:**

![unnamed](https://user-images.githubusercontent.com/77072787/133002427-7aa061ac-c1ed-4c3f-8037-d204a75bd726.png)

The main options are:

Open, allows to open a REZ file

Import, different formats are supported and described in depth later on.

Help, opens the portal to our help resources

The language option lets you choose different languages supported by Rezonator. 

### 1.2	Select a user interface language

Rezonator supports multiple user interface languages. You can change the user interface language at any time. Upon opening Rezonator, you can select the box on the lower right corner and change the language.

![unnamed-1](https://user-images.githubusercontent.com/77072787/133002587-7f9a2670-6d4e-4a82-9566-9797a402347d.png)

You can also change language from the Menu bar selecting Settings > Language. At present, Rezonator supports Chinese, Hebrew, Italian, Japanese, Spanish, Vietnamese, Kazakh, Russian, Gujarati, and Armenian. New languages can be easily added: if you would like to contribute to the translation in a different language, please contact the Rezonator team.

You can also immediately incorporate a new translation on your locale. Under the directory Localization found in the directory where Rezonator has been installed, you will find a set of files named “locale_” followed by the two-letter code identifying the language of the localization (e.g. “locale_en” for English). You can use any of these files as the basis for the translation. The files are organized in a JSON dictionary, and you will need to translate only the values in order to ensure the correct functioning of the code. Modify the first value of the file to reflect the two-letter code referring to the new target language and save the file following the naming convention. Insert the new file in the Localization folder. Close and reopen Rezonator.

### 1.3	Opening a REZ File

Rezonator is distributed with a set of native REZ files which allow users to start working directly on the Santa Barbara Corpus of Spoken American English. In order to Open a REZ file, select the option Open from the Opening screen. You will be prompted to a screen and asked to select the REZ file of choice.
At any point during the working session, selecting the Exit option from the File dropdown will exit the current Rezonator session and bring the user back to the Opening Screen.

### 1.4	Importing a New File

The Import button on the Opening Screen allows users to open linguistic data and start a new Rezonator session.
At any point, you can import new data by selecting from the Menu Bar in the top left corner of Rezonator the option File > Import. You will be prompted to the import screen, which allows for selection of the type of data to be imported.
At any point during the working session, selecting the Exit option will exit the current Rezonator session and bring the user back to the Opening Screen.

### 1.4.1	Data types supported by Rezonator

Rezonator supports TXT and CSV. There are seven different Import functions, each of which has been set up to deal with data organized in different ways that reflect a variety of data that linguists might be working with. What follows is a description of the data types that are supported so that you can select the most convenient schema for your data.


