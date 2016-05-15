# check-print: Print Checks From Your Web Browser

This is an HTML file that formats check properties for printing on [QuickBooks-compliant standard business checks](https://duckduckgo.com/?q=quickbooks+standard+business+checks) - directly from a web browser. I've written an [article](http://blog.michaelscepaniak.com/how-to-print-checks-without-quickbooks) on my [blog](http://blog.michaelscepaniak.com) explaining why you would want [a template for printing checks outside of QuickBooks](http://blog.michaelscepaniak.com/how-to-print-checks-without-quickbooks), so I'm not going to re-state it here.

**Please be aware**, you need to purchase and supply your own QuickBooks-compliant checks onto which your check **properties** will be printed.

## Directions

1. Pull down the project (or just copy and paste the contents of check-template-standard-business.html into a text editor).
1. In this HTML file, search for every occurrence of "REPLACE-ME". These are the values for check \#1 that you can (and should) replace/customize:

 - **date** - The date when the check is first eligible to be cashed/deposited.
 - **payTo** - To whom the check should be made out.
 - **amountNbr** - The amount of the check, as a number.
 - **amountTxt** - The amount of the check, written out long-form.
 - **payToAddress** - Lines 1 through 5 of the recipient's address.
 - **memo** - A short note to include on the check.

1. The same values can be set/customized for checks \#2 and \#3. If you only need to print one check, leave the values for these two blank. If you only need to print two checks, leave the values for the third check blank.
1. Save the file and open it in your web browser.
1. Use your web browser's print function to print your checks. (Be sure to feed your pre-printed checks into your printer first, of course.)

## Caveats

I've tested this on the following browsers:

* Firefox on Mac OS X
* (that's it :)

In addition, I've only tested this on my own printers, with one set of checks. So, your mileage may vary. When printing, I take the default margin settings. On Firefox, that means setting "Paper Size" to "US Letter", which I believe equates to the following margins:
* Top: 0.20 inches
* Bottom: 0.20 inches
* Left: 0.20 inches
* Right: 0.20 inches

## Possible Future Enhancements

* Support for other check formats. (e.g., wallet checks, etc.)
* Ability to supply check properties from a form instead of editing HTML.
* Suggestions?


Mike....
