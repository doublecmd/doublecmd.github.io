General instructions and conventions about HTML help file of DC
==============================================================

- When using a link to something external to Double Commander help, set the target to be a new window using target="_blank" like in this example:
  <a title="Double Commander Home Page" href="https://doublecmd.sourceforge.io/" target="_blank">Homepage</a>

- To be more friendly with the user, to make us as the same level as the user, let's talk using "WE" instead of "YOU".
The user will feel that we're working together.
(By tradition, for all sections except "2.1. Basic Help", "2.2. Configuration" and "2.3. Keyboard layout".)

- DO NOT USE POINT NUMBER IN HTML FILENAME.
Just name the file based on what it describes and assume we will not rename it.
Even if today "findfiles.html" has point 2.5, it does not mean it will always be 2.5.
But it will always be talking about finding files.
Keeping reference pointing "findfiles.html" will always be true...
...which would not be the case if we would have point to something like "sec2_5_findfiles.html" for example.
Keep the section numbers for the text inside page and NEVER INSIDE A LINK.

- If you want to add a link to the FAQ, do not use the question number, because it may be changed in the future.

- If you want to add a description of a feature that is currently only available in the alpha version (development version) or in the beta version (usually the first versions of the new major release), then add a special label:
  <span class="versionref"><sup>(Alpha version)</sup></span>
or
  <span class="versionref"><sup>(Beta version)</sup></span>
Don't forget to delete after release.


Contributors
============

  Alexander Koblov aka Alexx2000 (alexx2000@mail.ru)
  Denis Bisson (denis.bisson@denisbisson.org)
  Dmitry Kolomiets aka B4rr4cuda (B4rr4cuda@rambler.ru)
  Przemysław Nagay aka cobines (cobines@gmail.com)
  RedSkotina
  Rod J (rodmac_shiels@hotmail.com)
  Rustem Rakhimov (dok_rust@bk.ru)
  Sash0k
  Максим aka Ma$terok
