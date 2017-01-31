cask_args appdir: '/Applications'

#----------------------------------------------------------------------------------------#
# Brews
#----------------------------------------------------------------------------------------#

brew 'bash'
tap 'homebrew/versions'
brew 'bash-completion2'
brew 'git'
brew 'git-lfs'
brew 'wget'

# Install more recent versions of some OS X tools.
tap 'homebrew/dupes'
brew 'grep'
brew 'openssh'
brew 'screen'

# Install some other useful utilities like `sponge`.
brew 'moreutils'
# Install GNU `find`, `locate`, `updatedb`, and `xargs`, `g`-prefixed.
brew 'findutils'

# Install font tools.
tap 'bramstein/webfonttools'
brew 'sfnt2woff'
brew 'sfnt2woff-zopfli'
brew 'woff2'

brew 'bash-completion'
tap 'homebrew/completions'

brew 'colordiff'
brew 'vim', args: ['override-system-vi']
brew 'diff-so-fancy'
brew 'emacs'
brew 'ffmpeg'
brew 'fontconfig'
brew 'freetype'
brew 'hub'
brew 'git-flow'
brew 'imagemagick'
brew 'pkg-config'
brew 'cairo'
brew 'openssl'
brew 'parallel'
brew 'postgresql'
brew 'sqlite'
brew 'tmux'
brew 'tree'
brew 'doxygen'
brew 'youtube-dl'
brew 'z'

tap 'homebrew/php'
brew 'php56', args: ['with-gmp']
brew 'python3'
brew 'yarn' # also install Node.js
brew 'go'
brew 'rbenv'
brew 'ruby-build'

tap 'thoughtbot/formulae'
brew 'rcm'

tap 'caskroom/cask'
tap 'caskroom/fonts'

#----------------------------------------------------------------------------------------#
# Casks
#----------------------------------------------------------------------------------------#

cask 'google-chrome'
cask 'firefox'

cask 'java' unless system '/usr/libexec/java_home --failfast'

cask 'charles'
cask 'mactex'
cask 'cloudup'
cask 'dropbox'
cask 'eclipse-java'
cask 'github-desktop'
cask 'handbrake'
cask 'postgres'
cask 'rstudio'
cask 'sketch'
cask 'spectacle'
cask 'skim'
cask 'spotify'
cask 'steam'
cask 'vlc'
cask 'xquartz'

cask 'iterm2'
cask 'visual-studio-code'

cask 'cscreen'
cask 'Caskroom/versions/alfred2'
cask 'dashlane'

cask 'dropbox'
cask 'google-drive'

cask 'adobe-creative-cloud' # installer dl

#----------------------------------------------------------------------------------------#
# Mac App Store
#----------------------------------------------------------------------------------------#

brew 'mas'
mas 'Xcode', id: 497799835
mas 'Twitter', id: 409789998
mas 'Slack', id: 803453959
mas 'TermHere', id: 1114363220
mas 'Sip', id: 507257563
mas 'Airmail 3', id: 918858936
mas 'The Unarchiver', id: 425424353
