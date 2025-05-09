## Privacy Policy

CSS Exfil Protection Privacy Policy
Current revision: October 15, 2019

CSS Exfil Protection (the "Plugin") is a security extension designed to 
sanitize website content loaded by a web browser.  As such, the Plugin has 
access to read and manipulate web page data, specifically the Cascading Style 
Sheet (CSS) styles loaded by web pages viewed by the web browser.  To function, 
the Plugin must read and access the HTML body of the web page being viewed.  
The Plugin does not - and will never - gather statistics or send data to any 
party for inspection.  Stylesheet sanitization is processed locally in the web 
browser by the Plugin.

To sanitize "cross-domain" CSS stylesheets, HTTP(S) requests must be made to 
retrieve the stylesheet for inspection.  No stylesheets are ever retrieved that 
have not already been designated for load by the visited web page.

No user data is requested by the Plugin.  As such, no user data is sent to
any party by the Plugin.

The CSS Exfil Protection project will remain open-source offered as-is through 
the MIT license.  Verification of this privacy policy can be performed though 
source code inspection.

