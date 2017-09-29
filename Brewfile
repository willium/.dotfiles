cask_args appdir: '/Applications'

#----------------------------------------------------------------------------------------#
# Brews
#----------------------------------------------------------------------------------------#

brew 'mas'

brew 'bash'
brew 'bash-completion'
brew 'git'
brew 'git-lfs'
brew 'wget'
brew 'pkg-config'
brew 'cairo'
brew 'libpng'
brew 'jpeg'
brew 'giflib'

# Install more recent versions of some OS X tools.
tap 'homebrew/dupes'
brew 'grep'
brew 'openssh'
brew 'screen'
brew 'vim', args: ['with-override-system-vi']
brew 'emacs'
brew 'tmux'
brew 'z'
brew 'hub'
brew 'parallel'
brew 'postgresql'
brew 'sqlite'
brew 'youtube-dl'
brew 'python3'
brew 'yarn' # also install Node.js
brew 'go'
brew 'rbenv'
brew 'ruby-build'

tap 'thoughtbot/formulae'
brew 'rcm'

#----------------------------------------------------------------------------------------#
# Casks
#----------------------------------------------------------------------------------------#

cask 'google-chrome'
cask 'firefox'

cask 'java' unless system '/usr/libexec/java_home --failfast'
cask 'eclipse-java'

cask 'postgres'
cask 'rstudio'
cask 'sketch'
cask 'spectacle'
cask 'skim'
cask 'spotify'
cask 'vlc'

cask 'xquartz'

cask 'iterm2'

cask 'visual-studio-code'
cask 'dashlane'

cask 'dropbox'
cask 'google-drive'

cask 'adobe-creative-cloud' # installer dl

#----------------------------------------------------------------------------------------#
# Mac App Store
#----------------------------------------------------------------------------------------#

mas 'Sip', id: 507257563
mas 'Airmail 3', id: 918858936
mas 'Twitter', id: 409789998
mas 'Slack', id: 803453959
mas 'The Unarchiver', id: 425424353
mas 'Daisy Disk', id: 411643860
mas 'iA Writer', id: 775737590
