ewucsthesis
===========

This document class is intended to fulfill the thesis style requirements for EWU graduate thesis. The Thesis Style Guidelines are available in PDF form [here](http://www.ewu.edu/Documents/Grad/Graduate%20Thesis%20Submission%20Form.pdf).

# Setup
To use this document class, simply include the ewucsthesis.cls file alongside your LaTeX file and set the document class to ewuthesis.cls in your preamble:

    \documentclass[]{ewucsthesis}

This document class is based off of the article document class. Any options supplied to this document class will be passed on to the article document class. For example, using 12pt font would look like this:

    \documentclass[12pt]{ewucsthesis}

The following variables should be set for using this document class:
 * title -- the title of the thesis
 * author -- the author of the thesis
 * date -- the term you are graduating (e.g., Winter 2014)
 * primaryadvisor -- the name of your primary advisor as you wish it to appear on the comittee signature page
 * secondaryadvisor -- the name of your secondary advisor as you wish it to appear on the committe signature page

After the variables are set, \maketitle can be used to generate the title, committee signature, authorization/copyright, and table of contents pages.

# What this document class does
 * Set the page margins
 * Create the title, committee signature, authorization/copyright, and table of contents pages
 * Setup the appropriate pagination

# What this document does not do
 * Create a vita page
 * Set the bibliography style
 * Handle abstract or acknowledgements pages even though they are allowed as per the style guideline (they're optional)

# Other considerations
 * This document class was designed around a 10pt font. It should still work with a 12pt font, but it may require some tweaking.
 * Check with your advisor about further style guidelines (e.g., bibliography style, caption placement, line spacing, font size, etc.)
 * Do not use the fullpage package! This will change the margins set by document class. If you are starting with this document class, this should not be a problem, but users adding this document class to an existing thesis might already be using the fullpage package.
 * If your advisor does not specify a bibliography style, IEEEtran is recommended.
