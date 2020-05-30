# Gedit SPICE Syntax Highlighting

SPICE (Simulation Program with Integrated Circuit Emphasis) syntax highlighting for Gedit (GtkSourceView).

![Screenshot](https://i.imgur.com/57BizGY.png)


## Installation

To install a new language syntax file you must copy the `spice.lang` file to the appropriate directory and restart any applications that uses GtkSourceView, then you should automatically get the SPICE highlighting when opening a supported file.

The appropriate directory to copy the `spice.lang` file depends on the version of GTK+ used by the application.

  * For Pluma, older versions of Gedit and Geany: `/usr/share/gtksourceview-2.0/language-specs/` or `~/.local/share/gtksourceview-2.0/language-specs/`
  * For Xed and newer versions of Gedit: `/usr/share/gtksourceview-3.0/language-specs/` or `~/.local/share/gtksourceview-3.0/language-specs/`


## Compatibility

This language definition file uses version 2.0 of the format specification, so it should be compatible with both GTK+ 2 and GTK+ 3 GtkSourceView, but all the testing was done in Pluma 1.12.2 (GTK+ 2).


## Supported Extensions

The following extensions are supported by this syntax definition file, which includes definitions for SPICE, HSpice, Spectre, SpiceOpus, ngspice, gnucap and others.

  * Models: `mdl`, `mod`
  * Circuits: `sp`, `net`, `cir`, `ckt`, `cdl`, `scs`, `spi`
  * Sub-circuits: `sub`

