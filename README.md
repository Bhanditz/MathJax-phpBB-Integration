# MathJax phpBB Integration #

[![Powered by phpBB][1]][2]  
[![Powered by MathJax][3]][4]

phpBB modification that enables users to post beautiful math in LaTeX and MathML, rendered in all major browsers using the MathJax JavaScript Library.

## Features: ##
* Uses the phpBB BBCode system.
* Multiple BBCodes can be used with static preview texts.
* Dynamic loading, saving users time and bandwidth.
* MathJax CDN can be used with a local installed copy for fallback purposes.
* Processing is done client side, by the JavaScript library. No complicated setups!
* Works on all major browsers.
* Renders in native MathML, Web fonts and Image fonts depending on the browser capabilities.

### Requirements: ###
* phpBB3, v3.0.9 is recommend.
* The [MathJax library][5] accessible from your forum's path or the ability to accept the [CDN TOS][6].

### Instalation: ###
* Use [AutoMOD][7] or open `install_mod.xml` in your browser and follow the instructions
 * Note: `contrib/modx.prosilver.en.xsl` is needed to render properly all xml files.
* Complete the installation by running the php file mentioned, if any.
* Links to additional languages, themes, optional modifications and update instructions can be found in the mentioned xml file.
* You may check the [Wiki][8] for optimization tricks and special use-cases.

### Notes: ###
* All git branches *are intended for development purposes only* and may be incomplete and/or broken between releases.
 * Please download a [tagged version][9] instead.

*****************

![Screenshot][10]

 [1]: https://github.com/sergio91pt/MathJax-phpBB-Integration/raw/master/contrib/images/phpbb.png
 [2]: http://www.phpbb.com
 [3]: https://github.com/sergio91pt/MathJax-phpBB-Integration/raw/master/contrib/images/mathjax.gif
 [4]: http://www.mathjax.org/
 [5]: http://www.mathjax.org/download/
 [6]: http://www.mathjax.org/download/mathjax-cdn-terms-of-service/
 [7]: http://www.phpbb.com/mods/automod/
 [8]: https://github.com/sergio91pt/MathJax-phpBB-Integration/wiki
 [9]: https://github.com/sergio91pt/MathJax-phpBB-Integration/archives/master
 [10]: https://github.com/sergio91pt/MathJax-phpBB-Integration/raw/master/contrib/images/screenshot2.png