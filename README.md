# dotfiles
Minimal defaults and tools for a dev machine on macOS

## Software Installation

The following suggestions form a base for ergonomic software development. The tools under the "required" header are either so widely used (Homebrew) that you can't avoid them, or necessary for day-to-day collaboration.

Tools under the "recommended" header are highly encouraged -- especially if you're not familiar with what they do. They're all easy to learn, require little configuration, and immediately increase your productivity. 

If you know of better tools (please feel free to share if so!) or have spent lots of time customizing your own tooling, you're welcome to use your own day-to-day or customize our suggestions. However, the expectation is all engineers are comfortable with the following defaults.

For example, you're welcome to use a JetBrains IDE (we're happy to pay for it too), but because VSCode is our default editor, you should know basic shortcuts (e.g. `cmd+p` quick open or `cmd+shift+f` global search) so that you can collaborate with others.

### Required

- Homebrew (https://brew.sh/)
- Slack (https://slack.com/downloads/osx) 
  - Mobile app as well on your phone
- VSCode (https://code.visualstudio.com/)
  - For Rotabull development: ElixirLS, Prettier
  - For Python development: Python
  - For remote pairing: VS Live Share
  
### (Highly) Recommended

- Fish Shell (https://fishshell.com/)
  - Oh My Fish plugin manager (https://github.com/oh-my-fish/oh-my-fish)
  - bobthefish theme (https://github.com/oh-my-fish/theme-bobthefish)
  - Nerd Fonts (https://github.com/ryanoasis/nerd-fonts#option-4-homebrew-fonts)
- iTerm2 (https://www.iterm2.com/index.html)
  - Go to Preferences > Profiles > General > Command and set the command to `/usr/local/bin/fish`
  - Go to Preferences > Profiles > General > Working Directory and select "Reuse previous session's directory"
  - Go to Preferences > Profiles > Text and choose a Powerline-enabled font
  - [Optional] Go to Preferences > Profiles > Keys and set up a Hotkey Window as Option-Space
- ShiftIt (https://github.com/fikovnik/ShiftIt) OR Spectacle (https://www.spectacleapp.com)
- FlyCut (https://github.com/TermiT/Flycut)

## Config files

- .gitconfig
- .tmux.conf
