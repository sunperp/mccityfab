README.txt

NOTE: This is unfinished code with incomplete documentation.  Use at your own risk. 


McCityFab - proof-of-concept for perl-based city generator utilizing schematic
            building blocks.  This requires codewarrior0's pymclevel to build
            a city in a Minecraft map.
------------------------------------------------------------------------------

usage: ../mccityfab [-[no]flag-option | -string-option="string" | -numeric-option=number ]...

  options:

     flag options:

      diagout		write out diagnostics file
      rawout		write out raw file
      txtout		write out ascii and ansi files
      debug		specify one or more times for increased verbose output

     string options:

      prefix="name"
			override default "maze" file prefix for output files
      mc_schemroot="path"
			set the path to the schematic sets

     integer numeric options:

      seed		specify a random seed
      xgridsize		size of grid array X dimension
      ygridsize		size of grid array Y dimension
      zgridsize		size of grid array Z dimension

     floating numeric options:

      [option]		[floating number]

      see variable section in ../mccityfab for more detailed information

  examples: [not yet implemented]

