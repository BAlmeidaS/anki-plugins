# Notes

**3.2** | 23/02/2021

* Add support for blockquote (starting line with `>`)
* Make preview resizable
* Make it compatible with upcoming changes on fill-the-blanks add-on
* Fix bug to use its css styles on review

**3.1** | 28/04/2020

* Fix bug on editor
* Add support for bold and italic shortcuts 

**3.0** | 18/03/2020

* Make the addon work with >= Anki 2.1.20
* Big change on the editor, improving plain text edition
* Disable purple indicator
  * Related issue: #24

**2.4** | 09/07/2019

* Handle issue on timer for previewer
  * Related issue: #21
  
**2.3** | 09/05/2019

* Add feature: Preview
* Improve how to handle pasting (on editor)
* Other small adjustments

**2.2** | 25/04/2019

* Better handling of chars: `< > &`
* Added handling for pasting data, when editing 
  * Now, if the Markdown is On, the data will pasted as plain text
* Refactor for using it along with other addons

> More precisely, make it works with my new Addon: *Fill the blanks*

**2.1** | 16/03/2019

* Fix: Formating area was around everything, must be around <amd> parts only
* Pre processing HTML escaped chars

**2.0** | 26/02/2019

* Large refactor
* Added conversion from HTML to MD
* Added options to execute the conversions immediately (in-place) (Either HTML to MD or MD to HTML)
* Handles notes edition, preventing Anki from formatting the inputs as HTML
* Added options to invoke the conversions as a batch operation (on Browser view)
* Added visual demarcation to parts handled by this add on (left border)
* Dropped the configurations *trim* and *replace-spaces* as they aren't necessary anymore

**1.1** | 24/10/2018

* Support for trim and replace-spaces configuration, both globally and locally
* Config renamed: showMdButton -> show-md-button  
* There is no longer the limitation for code block, as trimmimg may is customizable 

**1.0**

* Initial version
  * Interprets text surrounded by <amd> as Markdown and converts it to HTML
