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

resulting in:

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

### What's Pluto?

Lets you auto-build web pages from published web feeds; learn more [feedreader »](http://feedreader.github.io)

```
$ pluto help
```

resulting in:

```
NAME
    pluto - another planet generator (lets you build web pages from published web feeds)

SYNOPSIS
    pluto [global options] command [command options] [arguments...]

GLOBAL OPTIONS
    -c, --config=PATH - Configuration Path (default: Z:/.pluto)
    --help            - Show this message
    -q, --quiet       - Only show warnings, errors and fatal messages
    --version         - Display the program version

COMMANDS
    about, a      - (Debug) Show more version info
    build, b      - Build planet
    fetch, f      - Fetch feeds
    help          - Shows a list of commands or help for one command
    install, i    - Install template pack
    list, ls, l   - List installed template packs
    merge, m      - Merge planet template pack
    update, up, u - Update planet feeds
```


### What's Rouge?



```
$ rougify help
```

resulting in:

```
usage: rougify [command] [args...]

where <command> is one of:
        highlight       highlight code
        help            print help info
        style           print CSS styles
        list            list available lexers
        version         print the rouge version number

See `rougify help <command>` for more info.
```


### What's Kramdown?

```
$ kramdown -help
```

resulting in (shortened):

```
Command line options:

    -i, --input ARG
          Specify the input format: kramdown (default), html, GFM or markdown
    -o, --output ARG
          Specify one or more output formats separated by commas: html (default),
          kramdown, latex, pdf, man or remove_html_tags
    -v, --version
          Show the version of kramdown
    -h, --help
          Show the help

kramdown options:

        --auto-id-prefix ARG
          Prefix used for automatically generated header IDs

          This option can be used to set a prefix for the automatically generated
          header IDs so that there is no conflict when rendering multiple kramdown
          documents into one output file separately. The prefix should only
          contain characters that are valid in an ID!

          Default: ''
          Used by: HTML/Latex converter


        --[no-]auto-ids
          Use automatic header ID generation

          If this option is `true`, ID values for all headers are automatically
          generated if no ID is explicitly specified.

          Default: true
          Used by: HTML/Latex converter


        --entity-output ARG
          Defines how entities are output

          The possible values are :as_input (entities are output in the same
          form as found in the input), :numeric (entities are output in numeric
          form), :symbolic (entities are output in symbolic form if possible) or
          :as_char (entities are output as characters if possible, only available
          on Ruby 1.9).

          Default: :as_char
          Used by: HTML converter, kramdown converter

        --footnote-backlink ARG
          Defines the text that should be used for the footnote backlinks

          The footnote backlink is just text, so any special HTML characters will
          be escaped.

          If the footnote backlint text is an empty string, no footnote backlinks
          will be generated.

          Default: '&8617;'
          Used by: HTML converter

        --footnote-nr ARG
          The number of the first footnote

          This option can be used to specify the number that is used for the first
          footnote.

          Default: 1
          Used by: HTML converter

        --gfm-quirks ARG
          Enables a set of GFM specific quirks

          The way how GFM is transformed on Github often differs from the way
          kramdown does things. Many of these differences are negligible but
          others are not.

          This option allows one to enable/disable certain GFM quirks, i.e. ways
          in which GFM parsing differs from kramdown parsing.

          The value has to be a list of quirk names that should be enabled,
          separated by commas. Possible names are:

          * paragraph_end

            Disables the kramdown restriction that at least one blank line has to
            be used after a paragraph before a new block element can be started.

            Note that if this quirk is used, lazy line wrapping does not fully
            work anymore!

          Default: paragraph_end
          Used by: GFM parser


        --header-offset ARG
          Sets the output offset for headers

          If this option is c (may also be negative) then a header with level n
          will be output as a header with level c+n. If c+n is lower than 1,
          level 1 will be used. If c+n is greater than 6, level 6 will be used.

          Default: 0
          Used by: HTML converter, Kramdown converter, Latex converter


        --latex-headers ARG
          Defines the LaTeX commands for different header levels

          The commands for the header levels one to six can be specified by
          separating them with commas.

          Default: section,subsection,subsubsection,paragraph,subparagraph,subparagraph
          Used by: Latex converter

        --line-width ARG
          Defines the line width to be used when outputting a document

          Default: 72
          Used by: kramdown converter

        --link-defs ARG
          Pre-defines link definitions

          This option can be used to pre-define link definitions. The value needs
          to be a Hash where the keys are the link identifiers and the values are
          two element Arrays with the link URL and the link title.

          If the value is a String, it has to contain a valid YAML hash and the
          hash has to follow the above guidelines.

          Default: {}
          Used by: kramdown parser

        --math-engine ARG
          Set the math engine

          Specifies the math engine that should be used for converting math
          blocks/spans. If this option is set to +nil+, no math engine is used and
          the math blocks/spans are output as is.

          Options for the selected math engine can be set with the
          math_engine_opts configuration option.

          Default: mathjax
          Used by: HTML converter

        --math-engine-opts ARG
          Set the math engine options

          Specifies options for the math engine set via the math_engine
          configuration option.

          The value needs to be a hash with key-value pairs that are understood by
          the used math engine.

          Default: {}
          Used by: HTML converter


        --smart-quotes ARG
          Defines the HTML entity names or code points for smart quote output

          The entities identified by entity name or code point that should be
          used for, in order, a left single quote, a right single quote, a left
          double and a right double quote are specified by separating them with
          commas.

          Default: lsquo,rsquo,ldquo,rdquo
          Used by: HTML/Latex converter

        --syntax-highlighter ARG
          Set the syntax highlighter

          Specifies the syntax highlighter that should be used for highlighting
          code blocks and spans. If this option is set to +nil+, no syntax
          highlighting is done.

          Options for the syntax highlighter can be set with the
          syntax_highlighter_opts configuration option.

          Default: coderay
          Used by: HTML/Latex converter

        --syntax-highlighter-opts ARG
          Set the syntax highlighter options

          Specifies options for the syntax highlighter set via the
          syntax_highlighter configuration option.

          The value needs to be a hash with key-value pairs that are understood by
          the used syntax highlighter.

          Default: {}
          Used by: HTML/Latex converter


        --toc-levels ARG
          Defines the levels that are used for the table of contents

          The individual levels can be specified by separating them with commas
          (e.g. 1,2,3) or by using the range syntax (e.g. 1..3). Only the
          specified levels are used for the table of contents.

          Default: 1..6
          Used by: HTML/Latex converter

        --[no-]transliterated-header-ids
          Transliterate the header text before generating the ID

          Only ASCII characters are used in headers IDs. This is not good for
          languages with many non-ASCII characters. By enabling this option
          the header text is transliterated to ASCII as good as possible so that
          the resulting header ID is more useful.

          The stringex library needs to be installed for this feature to work!

          Default: false
          Used by: HTML/Latex converter
```



## Questions? Comments?

Send them along to the [wwwmake mailing list/forum](http://groups.google.com/group/wwwmake). Thanks.
