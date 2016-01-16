# React and Flux from Scratch - Fluent 2016

##Please complete the following machine setup in advance:
1. **Install the latest version of [Node](https://nodejs.org)**.  
2. **Install [Git](https://git-scm.com/downloads)**. 
3. **Download an [Editor that supports JSX and install the appropriate plugin**
4. **Clone my React Starter Kit** Open the command line and run this in the directory where you plan to work: `git clone https://github.com/coryhouse/react-flux-starter-kit.git`
5. **Install the dependencies** `cd react-flux-starter-kit` and then run this: `npm install`
6. On a Mac? You're all set. If you're on Linux or Windows, complete the steps for your OS below.  
 
**On Linux:**  
Run this to [increase the limit](http://stackoverflow.com/questions/16748737/grunt-watch-error-waiting-fatal-error-watch-enospc) on the number of files Linux will watch. [Here's why](https://github.com/coryhouse/react-slingshot/issues/6).    
`echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p` 

**On Windows:**  
1. **Install [Python 2.7](https://www.python.org/downloads/)**. Browser-sync (and various other Node modules) rely on node-gyp, which requires Python on Windows.  
2. **Install C++ Compiler**. [Visual Studio Express](https://www.visualstudio.com/en-US/products/visual-studio-express-vs) comes bundled with a free C++ compiler. Or, if you already have Visual Studio installed: Open Visual Studio and go to File -> New -> Project -> Visual C++ -> Install Visual C++ Tools for Windows Desktop. The C++ compiler is used to compile browser-sync (and perhaps other Node modules).

