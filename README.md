
###### This documentation is provided in English only, feel free to translate it into French, German, Spanish or other languages.

# FPHT Drive - Documentation

## What is FPHT Drive?

FPHT Drive is a service offered by [FPHT](https://fpht.eu/) to store your large files and folders on a Sovereign French Cloud.

The entire project is developed in France, by a French developer. The aim is to secure company and customer data in France, so that it never leaves French territory.

The Drive is GDPR-compliant.

## What is the purpose of this repository?

This repository allows me to give free access to my research, my resources, and everything that enabled me to develop the FPHT drive from A to Z.

You'll find detailed documentation of all the features available on the project, as well as some documents containing information on the management of the functional and technical features I've implemented.

Would you like to make your own Drive? Read the documentation, learn, then practice! You'll find plenty of documents here to get you started on creating your own Drive, or to help you understand how FPHT's works.

## Why is the Drive code private?

The code is not public, simply because for the moment I wish to keep the code as my property, and I still wish to finance my studies and my business with this additional service.

Later on, I'm not closed to the possibility of making the code open-source, but I have no worries about making progress on the code, and then I'm quietly going at my own pace on it, I don't want to see people adding 2-3 features every day, while I can take a little more time on my side.

What's more, you'll find functions or lines of code directly in the documentation, so you can sometimes understand how a feature works with a snippet of the associated code.

## What programming language do you use?

I use Rust to do all the Drive logic. The aim is to get the code as close to the machine as possible, using as few external libraries as possible to avoid unintentional data breaches unrelated to my development.

In addition, I preferred to develop the Drive in Rust to enable me to learn another machine-oriented language other than C, which I already know and which would have made the project too simple.

The final objective would be to make a Bootloader in Assembly as well as a Kernel, which I could link to my code in Rust, and thus have my own little OS, which would once again greatly reduce all possible and involuntary backdoors, like the one for [XZ](https://en.wikipedia.org/wiki/XZ_Utils_backdoor) for example.