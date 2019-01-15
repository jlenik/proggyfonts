# Proggy Fonts
Monospaced fonts for programming. This Github page is now the official home of the Proggy fonts.

The fonts are a cset of fixed-width screen fonts that are designed for programming. They were optimized while coding in C or C++. For this reason, characters like the `*` are vertically centered as `*` usually means dereference or multiply, but never 'to the power of' like in Fortran.

The {}s are centered horizontally (in case you align braces vertically), the zero looks different from the capital oh, and there is never any confusion between ells, ones, and eyes.

Additionally, the arithmetic operators (+ - * < >) are all axis aligned... unlike the last ones you just saw.


# Proggy Vector
New for 2019 is a vector (scalable) version of Proggy Clean Slashed-Zero. Proggy Vector comes in woff, svg, eot, ttf (with Mac variants), and otf (with Mac variants). Here is a sample.

![Proggy Vector](https://raw.githubusercontent.com/bluescan/proggyfonts/master/ProggyVector/ProggyVector_Sample.png)

There are also two variants of Proggy Vector. The first is Proggy Dotted. It is a conversion of Proggy Clean with the dotted zero. The second is Proggy Crossed with crossed sevens and zeds. Here is a screenshot:

![Proggy Crossed](https://raw.githubusercontent.com/bluescan/proggyfonts/master/ProggyCrossed/ProggyCrossed_Sample.png)

Proggy Vector Regular is a modified version of the Hack Font. The modifications were made using the Bird Font editor. Both the modifications made by SourceFoundry for Hack and my subsequent modifications are licensed under MIT. However, Hack started life out elsewhere, so please read the licensing information in ProggyVector_Readme_And_Licensing.txt. There's nothing arduous.

The web format woff file was generated by importing the otf into FontForge and exporting. I have also included the BirdFont (.birdfont) project file in case anyone would like to make further edits.

Windows appears to do a better job rendering ttf fonts over otf versions (even though otf supports cubic beziers which should not be approximations of the authored curves). Point size 10 of the ttf works well for me in Visual Studio. Here's a sample.

![Proggy Vector](https://raw.githubusercontent.com/bluescan/proggyfonts/master/ProggyVector/ProggyVector_SampleVS.png)

Note the 100% at the lower left. If magnification is not set to 100% the text will be blurry.


# Proggy Original

The original bitmap fonts are distributed as ttf, fon, pcf, and dfont files. The fon format works well with Visual Studio, a command prompt, Photoshop, etc. Some editors do not recognize fon fonts in which case you should use the ttf version (12pt PC, 16pt Mac). Not all fonts are available in all formats.

The original fonts are pixel-based and only look good at a particular point size. The ttf fonts should be used at their intended point size as they are basically conversions of the pixel based bitmap versions. 
These fonts will not benefit form having ClearType turned on. You're better off using some other ttf font that is curve-based and not pixel-based if you want sub-pixel anti-aliasing.

Most fonts contain the Latin-1 character set (ISO 8859-1) except ProggyCleanCE.ttf which can be used for the Czech language (Latin-2). You can try it if the characters you want are missing and you were able to read English enough to understand this paragraph.

Lastly, the two Webby fonts are not monospaced, but may be useful for other purposes like websites.

![Proggy Clean](https://raw.githubusercontent.com/bluescan/proggyfonts/master/ProggyOriginal/images/example_proggy_clean.gif)

![Proggy Clean CP](https://raw.githubusercontent.com/bluescan/proggyfonts/master/ProggyOriginal/images/example_proggy_clean_cp.gif)

![Proggy Clean SZ](https://raw.githubusercontent.com/bluescan/proggyfonts/master/ProggyOriginal/images/example_proggy_clean_sz.gif)

![Proggy Clean SZ BP](https://raw.githubusercontent.com/bluescan/proggyfonts/master/ProggyOriginal/images/example_proggy_clean_sz_bp.gif)

![Proggy Small](https://raw.githubusercontent.com/bluescan/proggyfonts/master/ProggyOriginal/images/example_proggy_small.gif)

![Proggy Square](https://raw.githubusercontent.com/bluescan/proggyfonts/master/ProggyOriginal/images/example_proggy_square.gif)

![Proggy Square BP](https://raw.githubusercontent.com/bluescan/proggyfonts/master/ProggyOriginal/images/example_proggy_square_bp.gif)

![Proggy Square SZ](https://raw.githubusercontent.com/bluescan/proggyfonts/master/ProggyOriginal/images/example_proggy_square_sz.gif)

![Proggy Tiny](https://raw.githubusercontent.com/bluescan/proggyfonts/master/ProggyOriginal/images/example_proggy_tiny.gif)

![Proggy Tiny BP](https://raw.githubusercontent.com/bluescan/proggyfonts/master/ProggyOriginal/images/example_proggy_tiny_bp.gif)

![Proggy Tiny SZ](https://raw.githubusercontent.com/bluescan/proggyfonts/master/ProggyOriginal/images/example_proggy_tiny_sz.gif)

![Proggy Webby Caps](https://raw.githubusercontent.com/bluescan/proggyfonts/master/ProggyOriginal/images/example_webby_caps.gif)

![Proggy Webby Small](https://raw.githubusercontent.com/bluescan/proggyfonts/master/ProggyOriginal/images/example_webby_small.gif)
