###### ***Readme last reviewed at ThinBasic v1.11.4.0***

**This tool should not be necessary anymore. Kept as reference.**

# GitPrepare

## Why GitPrepare ?
This script eases the removing of the $NUL character that thinAir puts at the end of scripts when saving. 

## Effect
After processing, scripts are no more shown as _binary_ by Github, thus scripts content is displayed whithin Github.

## Setup 
Setup is almost the same as for [thinternational](https://github.com/DirectuX/thinternational/blob/master/README.md "Setup")

Note: append the following section to _thinAir_Tools.ini_

<pre>
[GitPrepare]
Menu=GitPrepare
CommandLine=%thinbasicinstallpath%\thinbasicc.exe "%thinAirinstallpath%\Tools\GitPrepare\GitPrepare.tbasic " %sourcecodefullpathnameext%
SaveScriptBefore=true
</pre>
