Cyfer is a Chrome extension that provides a fully-responsive web interface to the Gliph service available at http://gli.ph/m/

All this extension does is add additional styling to the code that is served by Gliph's servers after it has been downloaded on your own computer - this cannot interfere with the privacy or security of your messages or transactions in any way.

Feel free to fork this extension and use this as a base for your own custom Gliph interface, there is a file called 'custom.css' that currently has no active code. Put all custom theme development in 'custom.css' to keep it separate from the code that breaks Gliph out of the frame on the website.

INSTALLATION

  You can install the extension via the Chrome Web Store from https://chrome.google.com/webstore/detail/cyfer-custom-responsive-s/bdgabfibghdpfpjbhmcppkggpppeelnf

  Or to hack on it, start by installing Cyfer in Chrome locally:

  - Download Cyfer via git clone, or from https://github.com/tomhodgins/cyfer/archive/master.zip
  - Visit chrome://extensions in your browser, and expand "Development mode" (top right).
  - Choose "Load unpacked extension ..." and point to the directory where you downloaded Cyfer.
  - It's installed! The next time you visit http://gli.ph/m/ you should be greeted by a responsive interface

WHO MADE THIS?

  Tom Hodgins (http://tomhodgins.com) built this extension. I am a freelance UI/UX
  developer and am not affiliated with Gliph in any way. This extension has been 
  developed with their blessing, but without any direct input or oversight from Gliph.

  Michael Mahemoff (http://mahemoff.com) laid the foundation for this extension
  by creating a wonderful Chrome Extension template to build from. Thank you!
