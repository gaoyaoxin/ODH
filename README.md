# Online Dictionary Helper (with Anki app support)

Online Dictionary Helper is a chrome extension to show online dictionary content, which also supports flash-card making compatible with Anki  (with **ankiconnect**, an Anki add-on, installed).

For the reason why comes this extension, you may check the detail [background](doc/background.md) if you are interested.

![Anki Notes](https://raw.githubusercontent.com/ninja33/ODH/master/doc/img/anki_640x400.png)

What might set this extension apart is that the users can grab online dictionary content with their own customized script. For development detail, please check the [development guide](doc/development.md)

## How to use

[[Chrome Web Store Link](https://chrome.google.com/webstore/detail/anki-online-dictionary-he/lppjdajkacanlmpbbcdkccjkdbpllajb?hl=en)]

1. Install the extension first from Chrome Web store. Setup Option and turn on the extension if you want. (Details could be found under the option page section)
2. (Optional) Setup the designated Anki deck, type and fields names to put your **word**, **definition**, **sentence**.
3. Open any given web page such as an English article (The extension has English dictionary only by its default setting).
4. Move mouse cursor to the word, double click to select or press <kbd>shift</kbd> to automatically select word in case it's a link.
5. A popup window will show up displaying the word definition.
6. (Optional) Press top/right green **(+)** icon to add Anki note.
7. (Optional) You need make sure that the Anki desktop version is opened and ankiconnect addon installed beforehand.

The extension has in it two dictionary samples for you to try out and experiment with.

1. English-Chinese dictionary: youdao.com (example for sentence captured as context)

![Youdao Dictionary](https://raw.githubusercontent.com/ninja33/ODH/master/doc/img/youdao_640x400.png)

2. English-English dictionary: collins.com (example for exact sample content from online dictionary)

![Collins Dictionary](https://raw.githubusercontent.com/ninja33/ODH/master/doc/img/collins_640x400.png)

As for dictionary collins.com, actually it is not built-in dictionary, it is here to show you how to load customized dictionary script.

## The Option Page

The extension option page is divided in three sections.

1. General Option: Turn on or turn off the extension if you want.
2. Anki Options: Setup Anki deck/type name, and which fields you are going to put **word**, **definiton**, **sentence**.

    *(Currently, the exntension can only output these three most important information. Web page url and audio can be added late.)*

3. Dictionary Options:

    - Script Repository: Input your own script location here, and click <kbd>Load</kbd> button to load it.
    - Selected Dictionary: Here will display all available dictionaries (buildin or loaded), and please select what current dictionary you want to use.

![Options Page](https://raw.githubusercontent.com/ninja33/ODH/master/doc/img/options.png)

## Use existing script or develop by yourself

1. You can use exsiting dictionary scripts contributed by others in the [dictionaries list](dicts/README.md)
2. Or develop the script by yourself based on [development guide](doc/development.md) 
3. Or raise an [issue](issues/) here if you really need help.

## Pull request

Welcome pull request if you want to enhance this extension, or put your own script here as central repository.

- the exntension source will go to [/src](https://github.com/ninja33/ODH/master/src)
- the online dictionary script will go to [/dicts](https://github.com/ninja33/ODH/master/dicts)