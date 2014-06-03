ASP.NET 2.0 CSS Friendly Control Adapters 1.0 (Precompiled Edition)

Based on the ASP.NET 2.0 CSS Friendly Control Adapters (http://www.asp.net/cssadapters)

Originally released by Brian DeMarzo (http://www.demarzo.net)
Migrated to CodePlex on Feb 26 2007

    
Goals----------------------

The CSSFriendly project includes all code for compiling your own stand-alone version
of the CSS Friendly Control Adapters. The code within is taken directly from the
source code of the original CSS Friendly Control Adapters, with small modifications
to support the distribution of JavaScript and CSS files.


Getting Started------------

Download the source code and compile. Find the CSSFriendly.dll and use it in your
web projects.


Implementation-------------

First, let's review the manual instalation steps for the standard (non-compiled)
CSS Friendly Control Adapters.

   1. Add a file to the App_Browsers directory.
   2. Add a folder of JavaScript files.
   3. Add a folder of CSS files.
   4. Add a bunch of files to the App_Code directory
   5. Add some <link> tags to the <head> section of your web pages (to import the stylesheets and handle some conditional imports for IE6).

By using the precompiled edition of the CSS adapters, implementation becomes this.
Note that only the first step is the same as those listed above; 
steps #2 through #5 are eliminated by the "new" step #2 below.

   1. Add the appropriate file to your App_Browsers directory.
   2. Add the compiled CSSFriendly.dll to your web site's bin directory.

Note that this implementation wasn't heavily tested, but did work without any issue
against the CSSFriendly demo app (which is included in the source code distribution).


If you have any problems or suggestions, please contact brian@demarzo.net.
