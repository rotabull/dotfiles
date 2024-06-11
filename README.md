# dotfiles
Minimal defaults and tools for a dev machine on macOS

## Software Installation

The following suggestions form a base for productive development. The tools under the "Default" header are used for day-to-day collaboration, even if there are other tools you typically prefer. Tools under the "recommended" header are highly encouraged, especially if you're not familiar with what they do. They're all easy to learn and a few days later, you'll forget what it's like to use a computer without them!

If you know of better tools (please feel free to share if so!) or have spent lots of time customizing your own tooling, you're welcome to use those. However, the expectation is engineers are comfortable with the following defaults.

For example, you're welcome to request a JetBrains IDE, but because VSCode is our default editor, you should know basic shortcuts (e.g. `cmd+p` quick open or `cmd+shift+f` global search) so that you can collaborate with others.

### Default

- **Editor**: VSCode (https://code.visualstudio.com/)
  - For Rotabull development: ElixirLS, Prettier
- **Database GUI**: TablePlus (https://tableplus.com/)
  - Ask your manager for a License Key
- **Package Manager**: Homebrew (https://brew.sh/)
  
### (Highly) Recommended

- **Shell**: Fish Shell (https://fishshell.com/ -- install via Homebrew)
  - To set up Fish to work with Homebrew, run `fish_add_path /opt/homebrew/bin`
  - Oh My Fish plugin manager (https://github.com/oh-my-fish/oh-my-fish)
  - bobthefish theme (https://github.com/oh-my-fish/theme-bobthefish)
  - Nerd Fonts (https://github.com/ryanoasis/nerd-fonts#option-4-homebrew-fonts)
- **Terminal Emulator**: iTerm2 (https://www.iterm2.com/index.html)
  - Go to Preferences > Profiles > General > Command and set the command to `/opt/homebrew/bin/fish`
  - Go to Preferences > Profiles > General > Working Directory and select "Reuse previous session's directory"
  - Go to Preferences > Profiles > Text and choose a Powerline-enabled font
  - [Optional] Go to Preferences > Profiles > Keys and set up a Hotkey Window as Option-Space
- **Window Manager**: Rectangle (https://rectangleapp.com/)
- **Clipboard Manager**: Maccy (https://maccy.app/)

## Config files

- .gitconfig
- .tmux.conf
