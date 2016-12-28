# gource

> Renders an animated tree diagram of Git, SVN, Mercurial and Bazaar repositories.
> It shows files and folders being created, modified or removed over time.

- Run gource in a directory (if it isn't the repository's root directory, the root is seeked up from there):

`gource {{path/to/repository}}`

- Run gource in the current directory, with a custom output resolution:

`gource -{{width}}x{{height}}`

- Run gource with a custom time scale for the animation:

`gource -c {{time_scale_multiplier}}`

- Run gource specifying how long each day should be in the animation:

`gource -s {{seconds}}`

- Run gource in fullscreen mode and set the background color:

`gource -f -b {{hex_color_code}}`

- Run gource providing a title for the animation:

`gource --title {{title}}`