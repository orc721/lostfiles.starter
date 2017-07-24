[Office.TXT @ GitHub](https://github.com/officetxt)

# Office.TXT - The Free Writer's Command Line Tool Suite

Works w/ any text editor - future-proof text formats - write notes, articles, journals, presentations, websites, blogs, manuscripts, books & more


All-in-one installation:

```
$ gem install officetxt
```

Command line tools include:

- `officetxt` (`txt`)
- `journaltxt` (`jo`)
- `jekyll`
- `drjekyll` (`drj`)
- `mrhyde` (`mrh`)
- `octopod`
- `slideshow`
- `pluto`
- `rougify`   
- `kramdown`
- `w2m`   
- `quik` (`qk`)


Use

``` text
$ officetxt   
   -or-
$ txt
```

to list all command line tools and versions:

``` text
Welcome to officetxt/0.1.1

Tool versions installed:
  journaltxt/1.0.1
  jekyll/3.5.0
    jekyll-import/0.12.0
    jekyll-avatar/0.4.2
    jekyll-planet/0.2.1
  mrhyde/0.1.1
  drjekyll/1.0.1
  octopod/0.9.0
  slideshow/3.1.0
  pluto/1.2.3
  rouge/1.11.1
  kramdown/1.13.2
  word-to-markdown/1.1.7
  quik/0.3.0
```


### What's Journal.TXT?

Reads Journal.TXT and writes out (auto-builds) a blog (w/ Jekyll posts etc.);
learn more [journaltxt/journaltxt »](https://github.com/journaltxt/journaltxt)

Try on the command line:

```
$ journaltxt --help
  -or-
$ jo --help
```

resulting in:

```
Usage: journaltxt [OPTS]
    -v, --[no-]verbose               Show debug messages
    -o, --output=PATH                Output path (default: .)
    -n, --name=NAME                  Journal name (default: Journal)
        --[no-]date                  Add date to page title (default: true)
    -h, --help                       Prints this help
```


### What's Slide Show (S9)?

Write your slides / talks / presentations in (plain) text with markdown formatting conventions;
free web alternative to PowerPoint and Keynote; learn more [slideshow-s9 »](http://slideshow-s9.github.io)

Try on the command line:

```
$ slideshow help
```

resulting in:

```
slideshow/3.1.0

NAME
    slideshow - Slide Show (S9) - a free web alternative to PowerPoint and Keynote in Ruby

SYNOPSIS
    slideshow [global options] command [command options] [arguments...]

GLOBAL OPTIONS
    -c, --config=PATH - Configuration Path (default: Z:/.slideshow)
    --help            - Show this message
    -q, --quiet       - Only show warnings, errors and fatal messages
    --version         - Display the program version

COMMANDS
    about, a           - (Debug) Show more version info
    build, b           - Build slideshow
    help               - Shows a list of commands or help for one command
    install, i         - Install template pack
    list, ls, l        - List installed template packs
    new, n             - Generate quick starter sample
    plugins, plugin, p - (Debug) List plugin scripts in load path
    update, u          - Update shortcut index for template packs 'n' plugins
```

### What's Dr Jekyll?

Lets you manage static website theme packages; 
learn more [drjekyllthemes/drjekyll »](https://github.com/drjekyllthemes/drjekyll)

Try on the command line:

```
$ drjekyll help
  -or-
$ drj help
```

resulting in:

```
drjekyll/1.0.1

NAME
    drjekyll - jekyll command line tool .:. the missing static site package manager

SYNOPSIS
    drjekyll [global options] command [command options] [arguments...]

GLOBAL OPTIONS
    --help    - Show this message
    --version - Display the program version

COMMANDS
    download, dl, d, get, g - (Debug) Step 1: Download theme; .zip archive saved
                              in working folder (./)
    help                    - Shows a list of commands or help for one command
    list, ls, l             - List themes
    new, n                  - Download 'n' setup (unzip/unpack) theme
    unpack, pk, p, setup, s - (Debug) Step 2: Setup (unzip/unpack) theme; uses
                              saved .zip archive in working folder (./)
```

## What's Mr Hyde?

Lets you run a static website quick starter wizard script 
to download and install (unzip/unpack) a theme archive and configure a static website ready-to-use;
learn more [mrhydescripts/mrhyde »](https://github.com/mrhydescripts/mrhyde)


Try on the command line:

```
$ mrhyde help
  -or-
$ mrh help
```

resulting in:

```
mrhyde/0.1.1

NAME
    mrhyde - jekyll command line tool .:. the static site quick starter script wizard

SYNOPSIS
    mrhyde [global options] command [command options] [arguments...]

GLOBAL OPTIONS
    --help            - Show this message
    --test, --dry_run - (Debug) Dry run; run script in simulation for testing
    --version         - Display the program version

COMMANDS
    help   - Shows a list of commands or help for one command
    new, n - Run static site quick starter script
```


### What's Octopod?

Write your show notes in (plain) text and publish (and sync)
your podcasts / radio talk shows; learn more [jekyll-octopod »](https://jekyll-octopod.github.io)

Try on the command line:

```
$ octopod --help
```

result in:

```
Octopod - podcast publishing for geeks

Basic Command Line Usage:
  Standard Jekyll commands:
    octopod b[uild]                                                # . -> ./_site
    octopod build <path to write generated site>                   # . -> <path>
    octopod build <path to source> <path to write generated site>  # <path> -> <path>
    octopod import <importer name> <options>                       # imports posts using named import script
    octopod setup                                                  # Setup blog to become podcast-aware, copy assets and default config
    octopod s[erver]                                               # Starts the server

  Additional Octopod commands:
    octopod episode                                           # adds a template for a new episode
    octopod deploy                                            # deploys your site

  See 'octopod <command> --help' for more information on a specific command.
```


## Questions? Comments?

Send them along to the [wwwmake mailing list/forum](http://groups.google.com/group/wwwmake). Thanks.
