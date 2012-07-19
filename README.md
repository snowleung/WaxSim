# WaxSim
While Apple doesn’t provide an “official” way to launch an app in the iOS Simulator from the command line, there’s a way to do it with WaxSim.

## Installation
Installation process is straight forward, all you need is to:

- Clone repo
  
  `git clone git@github.com:Taptera/WaxSim.git`
- Go to project directory
  
  `cd WaxSim`
- Build and install
  
  `xcodebuild install DSTROOT=/`

Last command will build and copy `waxsim` executable file in yours `/usr/local/bin/`.

## Usage
In order to run simulator using waxsim you need to call:

  `waxsim [application path]`