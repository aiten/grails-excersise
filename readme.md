Grails Interview Excersise
==========================

This excersise is intended to be a simple currency converter.

  - Type some Markdown text in the left window
  - See the HTML in the right
  - Magic

What is this application designed to do?

> This application purely tests programming approach. We should concern ourselves with good, clean, readable and maintainable code, useful test coverage, DRY principles, LEAN development, and path of least surprise.

The following document explains the steps to get the project running, and the work which needs to be completed on it by a candidate.

Version
----

1.0

Tech
-----------

You will need:

* gvm (http://gvmtool.net)
* grails 2.3.4 (gvm install grails)
* intellij IDEA
* Some sort of computer which doesn't run windows.
* A browser
* A working internet connection (for http://opencurrencyexchange.org)

Running
--------------

```sh
git clone git@github.com:aiten/grails-excersise.git
cd grails-excersise
./grailsw grails-excersise
```

User Stories
--------------

### As a user I would like to be able to convert an amount from GBP to USD so that I can determine how many dollars I have to take on holiday.
----------------------------------------------------------------------------------------------------------------------------------------------
> [ ] There is a box for me to enter my initial amount
>
> [ ] There is a way for me to see the converted amount
>
> [ ] If I try to convert a non-numerical amount I am shown an error message

### As a user I would like to be able to convert an amount from GBP to any other currency so that I can visit somewhere other than the USA.
-------------------------------------------------------------------------------------------------------------------------------------------
> [ ] There is a dropdown for the FROM amount where I can choose from a list of three currencies, JPY, AUD, and GBP
>
> [ ] Selecting a different currency will update the converted amount

### As a user I would like to be able to convert currencies in both directions so that I can determine how much money I have left over when I return home.
-------------------------------------------------------------------------------------------------------------------------------------------
> [ ] There is a dropdown for the TO amount where I can choose from a list of three currencies, JPY, AUD, and GBP
>
> [ ] Selecting a different currency will update the converted amount
>
> [ ] There is a way to swap the amounts in the TO and FROM boxes.

### As a product owner I would like the dropdown box of currencies to be populated from the opencurrencyexchange API.
-------------------------------------------------------------------------------------------------------------------------------------------
> [ ] I can convert to and from all the currencies supported by opencurrencyexchange








