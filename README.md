PhotoFX
===============

> Note that this code has not been updated to reflect the most recent changes in MontageJS. Although you will be able to run the application, it may not look or behave as intended.

[Live Demo](http://montagejs.org/apps/photofx/)

This application is an example of how a Montage application can be structured and implemented.

##Installation

This application depends on the Montage framework which isn't included in the repository. To run the PhotoFX demo locally, you must have Node.js and npm installed. MontageJS application development depends on npm, the Node package manager, which is distributed with Node.js. If you haven't done so already, be sure to [download](http://nodejs.org/download/) and run the prebuilt Node.js installer for your platform from the Node.js website. Then follow these steps:

1. Clone the photofx [GitHub repo](https://github.com/montagejs/photofx) in your desktop.

2. Use your command line tool to navigate to the cloned directory and install the modules required to run the demo:
        
   ```
   cd photofx
   npm update
   ```
    
3. Spin up your preferred HTTP server and point your browser to the associated port.

    > During development MontageJS applications rely on XHR to load their various components and modules, which is why you will need a web server to serve the demo.

    > If you happen to have [minit](https://github.com/montagejs/minit), the Montage Initializer, installed (`npm install minit -g`) you can run `minit serve` from within the demo directory to set up a server on demand.

## Contact Us

Got questions? Join us on [irc.freenode.net#montage](http://webchat.freenode.net/?channels=montage).

Got feedback or want to report a bug? Let us know by creating a new [GitHub issue](https://github.com/montagejs/photofx).

## Credit

This demo application was created by [MontageJS](http://montagejs.org).

