# 🚀 Update 🚀
# Nuebase v=2.0.1-stable
- NueBase is a spiffy project manager for your groovy nue programs. 💻
- Current Stable Version: `2.0.1`
  - Last Stable Version: `1.0.1` (a bit dated, if you ask me) 🕰️
  - Last Stable Version: `0.0.1` (a bit dated, if you ask me) 🕰️
    
**Features:**
- You can easily create and run nue programs with the help of our trusty `.\nb.exe` sidekick. 🔧

*Note:*
- Hey, don't forget to put that `NueStuff` directory in your system programs folder, like `C:\Program Files\NueStuff`. It's where the magic happens! 🎩

*Example Usage:*
  ```shell
  .\nb.exe
  ```
  *Output:*
  ```shell              
  Usage:
    nb new <projectname>                      :: Create a new project with the given name.
    nb run                                    :: Run the default main file specified in nue-conf.json.
    nb run -s <scriptname>                    :: Run a specific script specified in nue-conf.json.
    nb run --ignore-dev                        :: Run the program without showing errors for missing dependencies.      
    nb run -s <scriptname> --ignore-dev        :: Run a specific script without showing errors for missing dependencies.
    nb del <projectname>                      :: Delete the project directory.
    nb conf init <projectname>                :: Initialize a new nue-conf.json file for the project.
    nb conf <name> <value>                    :: Update nue-conf.json with the specified name and value.
    nb conf -s <scriptname> <scriptlocation>  :: Add a script to nue-conf.json.
    nb conf -s -cc                            :: Check if all script files are present in their registered directories. 
    nb conf dev                               :: Update dependencies with files in nuepkgs directory.
    nb conf dev -cc                           :: Check if all libraries are present in their correct paths.
  ```

*Updates:*
- Added `conf dev` and `conf dev -cc` commands to make managing your `.pkg` files a breeze. 🛠️
- Added `run --ignore-dev` and `run <scriptname> --ignore-dev` commands to let you `Continue Anyway` when a `.pkg` is missing, use this instead of commenting it in nue-conf.json. No need to fuss with that file! 🚀
