# BCF Flight Plan Sources

This repository contains the sources for the BCF flight plans. 

- Each file should contain one flight plan
- Examples of pre-sets or reusable components can be found in `common_blocks.rb`
- An example flight plan can be found in `module_3.rb`
- There is a VSCode devcontainer configuration to write flight plans.
- To build the currently open file run the Render PDF task or launch configuration.
    - Or use one of the files in the `bin/` directory with the filename as an argument.
    - `bin/render-pdf` builds once
    - `bin/render-pdf-watch` watches for changes and rebuilds but may be less reliable.
    - `bin/render-pdf-fswatch` uses fswatch to watch for changes and rebuilds, so is slower but more reliable.

## Things to do 

TODO is it safe having a "/" in the gem name

TODO License both a license file and also in GitHub

TODO Declare demo and also require it to be there (and if there's one and no demo declaration then raise an error)

TODO Consistency check that all common blocks take the same time

TODO I removed some of the highlighting in STATE_CHECKIN
TODO is state checkin always 2 mins

TODO need to add who Fx is for the common blocks
TODO we can do something with the Flipcharts
