HunSpell Venetan Spellchecker
-----------------------------

1. Copyright
2. Compatibility
3. Installation and Setup
4. Contributing


1. Copyright
============

This Venetan Dictionary for Spell-checking is maintained by
Mauro Trevisan <mauro.trevisan@gmail.com>.

Copyright © 2019 Mauro Trevisan <mauro.trevisan@gmail.com>.


The HunSpell Venetan dictionary is based on various dictionaries (starting from
the end of the 18th century), all in public domain.


You should have received a copy of the GNU Lesser General Public License
along with this dictionary.  If not, see <http://www.gnu.org/licenses/>.


2. Compatibility
================

This extension is compatible with:
- LibreOffice (Version 5.1+)
- OpenOffice (Version 4.1.3+)


3. Installation and Setup
=========================

Automated
---------
Newer versions of OpenOffice.org have a built in macro to step you through an 
automatic install process.

  File -> Autopilot -> Install new dictionaries...

If this is unavailable then download 'DicOOo.sxw' from:
http://ftp.services.openoffice.org/pub/OpenOffice.org/contrib/dictionaries/dicooo/DicOOo.sxw

Run the macro and follow the steps outlined.  If you would like the dictionary
to be available to all users then run the installation as the administrative or
root user.  It is best to restart OpenOffice.org after the installation.

The macro operates in two modes:

1) Online - the latest dictionaries are retrieved from the OpenOffice.org
   website.

2) Offline - an offline dictionary pack, which you have already downloaded, is
   installed from the hard-drive.  Offline dictionaries can be downloaded from:
   http://lingucomponent.openoffice.org/dictpack.html 
    OR
   http://sourceforge.net/project/showfiles.php?group_id=91920&package_id=103504

For more detailed instructions see:
  http://lingucomponent.openoffice.org/auto_instal.html


Non-automated
-------------
For instructions on how to install the Venetan dictionary manually please visit 
the following URL:
http://lingucomponent.openoffice.org/manual_instal.html


Spellchecker Selection
----------------------
Once the spellchecker is installed you need to configure a few settings and
perform some checks.

1) Check that the Venetan Spellchecker is enabled.

  Tools -> Options -> Language Settings -> Writing Aids

In the section marked 'Available language modules' select 'Edit...'.  Under
the languages drop-down select Venetan and ensure that the 'OpenOffice.org
MySpell SpellChecker' is enabled.

2) Set your default document language to Venetan

If most of your writing is in Venetan then this step will ensure that
documents you compose from now on are treated as Venetan documents.  If much
of your writing is in a language other than Venetan you might want to skip this
step.

  Tools -> Options -> Language Settings -> Languages

In the section marked 'Default languages for documents' is a drop-down labelled
'Western'.  Venetan has a tick next to it to indicate that a spellchecker is 
installed.  Set your default language to Venetan.

3) Changing existing documents or paragraphs to Venetan

Some old document might be written in Venetan but the document was stored
indicating that the text was in another language.  You can indicate that this
is a Venetan text by:

    a) Select the relevant text (Ctrl-A selects the whole document)
    b) Format -> Character...
       Change the 'Language' drop-down to Venetan.


4. Contributing
===============

You can help to make this software better by:

a) Contributing corrections and missing words
b) Contributing your wordlists

Email your contributions to Mauro Trevisan <mauro.trevisan@gmail.com>.
