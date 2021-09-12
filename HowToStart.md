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

### 1.4.1	Data types supported by Rezonator

Rezonator supports TXT and CSV. There are seven different Import functions, each of which has been set up to deal with data organized in different ways that reflect a variety of data that linguists might be working with. What follows is a description of the data types that are supported so that you can select the most convenient schema for your data.

### 1.4.2	Song & Verse

![unnamed-2](https://user-images.githubusercontent.com/77072787/130712131-fde4cec2-e73c-4e27-ae4e-68e3e959ae09.png)

Song & verse data consists of short lines of text in which line breaks are meaningful. Within this schema, there is no word wrap and words are split on whitespace. The accepted file type is plain text (.TXT). Examples include songs and poems. 

### 1.4.3	Prose

![unnamed-4](https://user-images.githubusercontent.com/77072787/130712316-fc06a8f8-e85c-44cd-9fe2-697827c68490.png)

Prose data consists of long paragraphs of text. Within this schema, data is organized with a hard return at the end of the paragraph and the words wrap to fit on the page or screen. Words are also split on whitespace. The accepted file type is plain text (.TXT). Examples include news articles, blogs, Wikipedia pages, and novels.  

### 1.4.4	One Word Per Line (OWPL)

![unnamed-7](https://user-images.githubusercontent.com/77072787/130719148-524753d8-7b30-4605-bef0-40037ddd254f.png)


One Word Per Line (OWPL) data consists of columns and rows of text in which the text columns read vertically. Each row represents 1 word (token), while each column displays a word feature. The accepted file type is a spreadsheet (.CSV). An example shown above is the Santa Barbara Corpus .CSV file. 

### 1.4.5	CoNLL-U

![unnamed](https://user-images.githubusercontent.com/77072787/130718707-2333da8a-e2ef-4acc-8b21-39d5d1511422.png)

CoNLL-U data consists of columns and rows of text in which the text columns read vertically. Each row represents 1 word (token) while each column displays a word feature. Hashtag lines mark unit features. The accepted file type is a spreadsheet (.CSV). An example shown above is the Universal Dependencies corpus. 

### 1.4.6	Transcription

![unnamed-1](https://user-images.githubusercontent.com/77072787/130718798-359f7bc2-df70-4465-b31f-df3965f49951.png)

Transcription data consists of one unit per line in which the text reads normally. There is a tab for speaker labels and an optional tab for timestamps. Within this schema, words are split on whitespace. The accepted file type is tab-delimited text (.TXT, .CSV). An example shown above is the Santa Barbara Corpus .TXT file. 

### 1.4.7	Elan (tab-delimited export)

![unnamed-3](https://user-images.githubusercontent.com/77072787/130718878-9cec3f2c-193c-445b-9ac2-68585e83ec5d.png)

Elan data consists of one unit per block in which each block has 1 or more lines. Within this schema, the text reads normally. There is a tab for speaker labels and a tab for timestamps with words split on whitespace. Once imported the file is sorted based on timestamps. The accepted file type is tab-delimited text (.TXT). An example shown above is the Santa Barbara Corpus .TXT file.

### 1.4.8	Interlinear Glossed Text (IGT)

![unnamed-6](https://user-images.githubusercontent.com/77072787/130719027-f0b041b8-1816-4cc0-81a2-d46b7787c0cf.png)

 Interlinear Glossed Text (IGT) consists of one unit per block in which each block has 2 or more lines. The blocks are separated by a blank line and the schema hyphenates split morphs on whitespace. The accepted file type is plain text (.TXT). An example shown above is Nuu-chah-nulth. 

