# Command Line Tools

[cheat.sh](http://cheat.sh/) & [eg](https://github.com/srsudar/eg) are useful tools. [Command Line Interface Guidelines](https://clig.dev/) are great.

[nap](https://github.com/maaslalani/nap) & [circumflex](https://github.com/bensadeh/circumflex) are nicely made CLIs written in [Go](../programming-languages/go/go.md) & [Bubble Tea](https://github.com/charmbracelet/bubbletea) (my preferred CLI stack).

There is also a [nice curated CLI list](https://github.com/learn-anything/command-line-tools)

[fzf](https://github.com/junegunn/fzf) is [great tool](https://news.ycombinator.com/item?id=35248098).

## Use

- [ripgrep](https://github.com/BurntSushi/ripgrep) to search for text.
- [fzf](https://github.com/junegunn/fzf) to fuzzy search through inputs.
- [watchexec](https://github.com/watchexec/watchexec) to rerun command when files of certain type change. Essential for fast feedback workflows. I usually have code on the left and terminal on right in [VSCode](../text-editors/vs-code/vs-code.md). Use some [fish functions](https://github.com/nikitavoloboev/dotfiles/blob/master/fish/functions.fish#L20) for common commands.
- [exa](https://github.com/ogham/exa) to replace ls as it has prettier output.
- [bat](https://github.com/sharkdp/bat) to show contents of the file.
- [jq](https://github.com/stedolan/jq) to process/modify JSON.
- [git](../programming/version-control/git.md) for all version control.
- [curl](https://curl.haxx.se/docs/manpage.html) to do HTTP requests in terminal.
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) to download videos.

## Interesting

- [rga](https://github.com/phiresky/ripgrep-all) - Ripgrep, but also search in PDFs, E-Books, Office documents, zip, tar.gz, etc. ([Article](https://phiresky.github.io/blog/2019/rga--ripgrep-for-zip-targz-docx-odt-epub-jpg/)) ([HN](https://news.ycombinator.com/item?id=25277280))
- [fd](https://github.com/sharkdp/fd) - Simple, fast and user-friendly alternative to 'find'.
- [up](https://github.com/apex/up) - Deploy infinitely scalable serverless apps, APIs, and sites in seconds to AWS.
- [tmux](https://github.com/tmux/tmux) - Terminal multiplexer.
- [direnv](https://direnv.net/) - Environment switcher for the shell.
- [htop](https://github.com/hishamhm/htop) - Interactive text-mode process viewer for Unix systems.
- [httpie](https://github.com/jakubroztocil/httpie) - HTTP client.
- [rq](https://github.com/dflemstr/rq) - Tool for doing record analysis and transformation.
- [pandoc](https://github.com/jgm/pandoc) - Universal markup converter.
- [trash](https://github.com/sindresorhus/trash) - Move files and folders to the trash.
- [vtop](https://github.com/MrRio/vtop) - Graphical activity monitor.
- [gotop](https://github.com/cjbassi/gotop) - Terminal based graphical activity monitor inspired by gtop and vtop.
- [howdoi](https://github.com/gleitz/howdoi) - Instant coding answers.
- [asciinema](https://github.com/asciinema/asciinema) - Terminal session recorder.
- [tldr](https://github.com/tldr-pages/tldr) - Simplified and community-driven man pages.
- [imgcat](https://github.com/eddieantonio/imgcat) - Like [cat](http://www.linfo.org/cat.html) but for images.
- [screenfetch](https://github.com/KittyKatt/screenFetch) - Fetches system/theme information in terminal.
- [hugo](https://github.com/gohugoio/hugo) - Fast and flexible static site generator.
- [reflex](https://github.com/cespare/reflex) - Run a command when files change.
- [modd](https://github.com/cortesi/modd) - Flexible tool for responding to file system changes.
- [now](https://github.com/zeit/now-cli) - Real time global deployments served over HTTP/2.
- [yarn](https://github.com/yarnpkg/yarn) - Fast, reliable, and secure dependency management.
- [hub](https://github.com/github/hub) - GitHub wrapper.
- [xsv](https://github.com/BurntSushi/xsv) - Fast CSV command line toolkit written in Rust.
- [pv](https://ivarch.com/programs/pv.shtml) - Pipe Viewer.
- [m-cli](https://github.com/rgcr/m-cli) - Useful utils for macOS.
- [pgcli](https://github.com/dbcli/pgcli) - Postgres CLI with autocompletion and syntax highlighting.
- [mas](https://github.com/mas-cli/mas) - CLI for mac app store.
- [loc](https://github.com/cgag/loc) - Count lines of code quickly.
- [alfred](https://godoc.org/github.com/jason0x43/go-alfred/alfred) - Manage Go-based Alfred workflows.
- [neofetch](https://github.com/dylanaraps/neofetch) - System information tool.
- [license-up](https://github.com/nikitavoloboev/license-up) - Create a license quickly for your project.
- [piknik](https://github.com/jedisct1/piknik) - Copy/paste anything over the network.
- [bench](https://github.com/Gabriel439/bench) - Command-line benchmark tool.
- [ghq](https://github.com/motemen/ghq) - Manage remote repository clones.
- [npx](https://github.com/zkat/npx) - Execute npm package binaries.
- [devd](https://github.com/cortesi/devd) - Local webserver for developers.
- [wifi-password](https://github.com/rauchg/wifi-password) - Get the password of the WiFi you're on.
- [fkill](https://github.com/sindresorhus/fkill-cli) - Fabulously kill processes.
- [ran](https://github.com/m3ng9i/ran) - Simple static web server written in Go.
- [mcfly](https://github.com/cantino/mcfly) - Fast visual command history search.
- [hyperfine](https://github.com/sharkdp/hyperfine) - Excellent command-line benchmarking tool.

## Notes

- Look into [gh cli](https://github.com/cli/cli) for example of a well designed CLI. The `-h` is amazing.

## Links

- [Awesome command line tools](https://github.com/learn-anything/command-line-tools)
- [Ask HN: What are your favorite terminal programs?](https://news.ycombinator.com/item?id=17011227)
- [What's an awesome Linux/Unix command that you wish someone had told you about earlier?](https://twitter.com/b0rk/status/993165679833567233)
- [Awesome Console Services](https://github.com/chubin/awesome-console-services)
- [tldr](https://github.com/tldr-pages/tldr) - Collection of simplified and community-driven man pages. ([Web](https://tldr.sh/))
- [Awesome jq](https://github.com/fiatjaf/awesome-jq) - Curated list of awesome things built with the JSON processor and turing-complete functional language jq.
- [cli.fan blog](https://cli.fan/posts/introduction/) - [Introduction](https://cli.fan/posts/introduction/).
- [One Things Well blog](https://onethingwell.org/) - Weblog about simple, useful software.
- [Terminals Are Sexy](https://terminalsare.sexy/) - Curated list of Terminal frameworks, plugins & resources for CLI lovers.
- [Inconsolation](https://inconsolation.wordpress.com/) - Adventures with lightweight and minimalist software for Linux.
- [Arabesque](https://sanctum.geek.nz/arabesque/) - Systems, Tools, and Terminal Science.
- [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line) ([HN](https://news.ycombinator.com/item?id=33726831))
- [cheat](https://github.com/cheat/cheat) - Allows you to create and view interactive cheatsheets on the command-line. ([HN](https://news.ycombinator.com/item?id=24195122))
- [hyperfine](https://github.com/sharkdp/hyperfine) - Command-line benchmarking tool.
- [An Illustrated Guide to Useful Command Line Tools (2019)](https://www.wezm.net/technical/2019/10/useful-command-line-tools/) ([Lobsters](https://lobste.rs/s/pven1z/illustrated_guide_some_useful_command)) ([HN](https://news.ycombinator.com/item?id=21363121))
- [uutils coreutils](https://github.com/uutils/coreutils) - Coreutils Rewritten in Rust. ([HN](https://news.ycombinator.com/item?id=29456115))
- [The Language Agnostic, All-Purpose, Incredible, Makefile (2019)](https://blog.mindlessness.life/makefile/2019/11/17/the-language-agnostic-all-purpose-incredible-makefile.html) ([Lobsters](https://lobste.rs/s/ots6gm/language_agnostic_all_purpose)) ([HN](https://news.ycombinator.com/item?id=21566530))
- [CLI: improved (2018)](https://remysharp.com/2018/08/23/cli-improved)
- [Awesome CLI apps](https://github.com/agarrharr/awesome-cli-apps)
- [Fast Searching with ripgrep (2020)](https://mariusschulz.com/blog/fast-searching-with-ripgrep)
- [Awk in 20 Minutes](https://ferd.ca/awk-in-20-minutes.html) ([HN](https://news.ycombinator.com/item?id=23048054))
- [Grep for System Admins: Using Grep to Automate Daily Tasks (2020)](https://developer.okta.com/blog/2020/05/06/grep-for-system-admins)
- [Command line interfaces are reified UIs (2017)](https://www.expressionsofchange.org/reification-of-interaction/) ([HN](https://news.ycombinator.com/item?id=15619796)) ([Lobsters](https://lobste.rs/s/sjtxdi/clis_are_reified_uis))
- [My Favorite CLI Tools (2020)](https://switowski.com/blog/favorite-cli-tools) ([HN](https://news.ycombinator.com/item?id=23603906))
- [wttr.in](https://github.com/chubin/wttr.in) - Console-oriented weather forecast service. ([HN](https://news.ycombinator.com/item?id=23646953))
- [Structured text tools](https://github.com/dbohdan/structured-text-tools) - List of text-based file formats and command line tools for manipulating each.
- [Conventions for Command Line Options (2020)](https://nullprogram.com/blog/2020/08/01/) ([HN](https://news.ycombinator.com/item?id=24020952))
- [Rewritten in Rust: Modern Alternatives of Command-Line Tools (2020)](https://zaiste.net/posts/shell-commands-rust/) ([Lobsters](https://lobste.rs/s/2mxwdm/rewritten_rust_modern_alternatives))
- [Search and replace tricks with ripgrep (2020)](https://learnbyexample.github.io/substitution-with-ripgrep/) ([Lobsters](https://lobste.rs/s/tn4olb/search_replace_tricks_with_ripgrep))
- [What are your favorite non-standard CLI utils/applications (2020)](https://lobste.rs/s/eprvjp/what_are_your_favorite_non_standard_cli)
- [cheat.sh](https://github.com/chubin/cheat.sh) - Unified access to the best community driven cheat sheets. Available via CLI. ([Web](https://cheat.sh/))
- [My growing list of Rust programs to use](https://gist.github.com/Phate6660/76779693f654d48c5c410be658c53f02) ([Lobsters](https://lobste.rs/s/ltd2be/my_growing_list_rust_programs_use))
- [dasel](https://github.com/TomWright/dasel) - Allows you to query and modify data structures using selector strings.
- [You Don't Need GUI](https://github.com/you-dont-need/You-Dont-Need-GUI) - CLI commands as alternatives to GUI. ([HN](https://news.ycombinator.com/item?id=26743704))
- [CLI Guidelines](https://clig.dev/) - Guide to help you write better command-line programs, taking traditional UNIX principles and updating them for the modern day. ([Code](https://github.com/cli-guidelines/cli-guidelines)) ([HN](https://news.ycombinator.com/item?id=25304257)) ([Lobsters](https://lobste.rs/s/bsgtju/cli_guidelines))
- [nq](https://github.com/leahneukirchen/nq) - Utils for creating lightweight job queue systems. ([HN](https://news.ycombinator.com/item?id=25920517))
- [Building Rich Terminal Dashboards (2021)](https://www.willmcgugan.com/blog/tech/post/building-rich-terminal-dashboards/) ([HN](https://news.ycombinator.com/item?id=26149488))
- [frawk](https://github.com/ezrosent/frawk) - JITted and SIMD-optimized AWK written in Rust. ([Lobsters](https://lobste.rs/s/bdzlsu/frawk_jitted_simd_optimized_awk_written)) ([HN](https://news.ycombinator.com/item?id=30343373))
- [How to Handle Secrets on the Command Line (2021)](https://smallstep.com/blog/command-line-secrets/) ([HN](https://news.ycombinator.com/item?id=27490885))
- [Modern Unix](https://github.com/ibraheemdev/modern-unix) - Collection of modern/faster/saner alternatives to common unix commands.
- [Awesome TUIs](https://github.com/rothgar/awesome-tuis) - List of projects that provide terminal user interfaces.
- [Lobsters: What interesting command line tools do you use? (2021)](https://lobste.rs/s/yfgwjr/what_interesting_command_line_tools_do)
- [binenv](https://github.com/devops-works/binenv) - One binary to rule them all. Manage all those pesky binaries (kubectl, helm, terraform, ...) easily.
- [Command line tools for productive programmers (2021)](https://earthly.dev/blog/command-line-tools/) ([HN](https://news.ycombinator.com/item?id=27992073))
- [Writing Programs with Ncurses](https://invisible-island.net/ncurses/ncurses-intro.html) ([HN](https://news.ycombinator.com/item?id=28354194))
- [Awk: The Power and Promise of a 40-Year-Old Language (2021)](https://www.fosslife.org/awk-power-and-promise-40-year-old-language) ([HN](https://news.ycombinator.com/item?id=28441887))
- [buke](https://github.com/epilys/buke) - Full text search man pages.
- [Renamer](https://github.com/75lb/renamer) - Rename files in bulk.
- [CLI Testing Tool](https://github.com/saurabhdaware/cli-testing-tool) - Testing library that allows you to test input and outputs of your CLI command.
- [bvm](https://github.com/bvm/bvm) - Binary Version Manager.
- [command-not-found.com](https://command-not-found.com/) - Install any command on any operating system.
- [mdbook-man](https://github.com/vv9k/mdbook-man) - Generate man pages from mdBooks.
- [Powerful Terminal And Command-Line (CLI) Tools For Modern Web Development (2021)](https://www.smashingmagazine.com/2021/11/powerful-terminal-commandline-tools-modern-web-development/)
- [GoAWK](https://github.com/benhoyt/goawk) - AWK interpreter written in Go. ([Article](https://benhoyt.com/writings/goawk/))
- [htop](https://github.com/htop-dev/htop) - Cross-platform interactive process viewer. ([Web](https://htop.dev/))
- [hgrep](https://github.com/rhysd/hgrep) - Grep with human-friendly search results.
- [Ask HN: What are the best and worst command-line interfaces you have used? (2021)](https://news.ycombinator.com/item?id=29329607)
- [Command Line Magic Twitter](https://twitter.com/climagic) ([Web](http://www.climagic.org/))
- [Tips on adding JSON output to your CLI app (2021)](https://blog.kellybrazil.com/2021/12/03/tips-on-adding-json-output-to-your-cli-app/) ([HN](https://news.ycombinator.com/item?id=29435786))
- [Why and How to add changelog in your next CLI (2021)](https://bhupesh-v.github.io/why-how-add-changelog-in-your-next-cli/)
- [A practical overview of most useful Unix tools (2021)](https://medium.com/fundbox-engineering/cheating-at-a-company-group-activity-using-unix-tools-5c1d706f3d58) ([HN](https://news.ycombinator.com/item?id=29528439))
- [fq](https://github.com/wader/fq) - jq for binary formats. ([HN](https://news.ycombinator.com/item?id=29657094))
- [termshot](https://github.com/homeport/termshot) - Creates screenshots based on terminal command output.
- [aqua](https://github.com/aquaproj/aqua) - CLI tool to install CLI tools with declarative YAML configuration. ([Docs](https://aquaproj.github.io/docs/tutorial-basics/quick-start/))
- [Supreme](https://github.com/opendevtools/supreme) - Add configurations, GitHub actions and get started quickly with new projects.
- [Bina](https://bina.egoist.sh/) - Installer for self-contained, single-file binaries, no additional CLI needed. ([Code](https://github.com/egoist/bina))
- [Nice CLIs](https://twitter.com/amilajack/status/1479328649820000256)
- [Charm](https://charm.sh/) - Tools to make the command line glamorous. ([HN](https://news.ycombinator.com/item?id=30048332))
- [Quick reference on command line tools and techniques](https://github.com/vastutsav/command-line-quick-reference)
- [Grep flags – the good stuff](https://zwischenzugs.com/2022/02/02/grep-flags-the-good-stuff/) ([HN](https://news.ycombinator.com/item?id=30179533))
- [SnipKit](https://github.com/lemoony/snipkit) - Snippet CLI manager for quickly accessing code snippets without leaving the terminal.
- [pz](https://github.com/CZ-NIC/pz) - Easily handle CLI operation via Python instead of regular Bash programs. ([HN](https://news.ycombinator.com/item?id=30302955))
- [Scaffolder](https://github.com/galElmalah/scaffolder) - Increasing dev velocity and standardizing file conventions.
- [crispr](https://github.com/yoav-lavi/crispr) - CLI tool allowing to scaffold a project from a template with a .crispr.{toml,json} configuration file.
- [envy](https://github.com/mre/envy) - Sets environment variables when you enter a directory.
- [timer](https://github.com/caarlos0/timer) - sleep with progress.
- [hwatch](https://github.com/blacknon/hwatch) - Modern alternative to the watch command, records the differences in execution results and can check this differences at after.
- [lets-run](https://github.com/egoist/lets-run) - Run a command when a certain file exists, and/or watch files to rerun on changes.
- [eg](https://github.com/srsudar/eg) - Useful examples at the command line.
- [zf](https://github.com/natecraddock/zf) - Command line fuzzy finder that prioritizes matches on filenames.
- [NO_COLOR](https://no-color.org/) - Disabling ANSI color output in various Unix commands. ([HN](https://news.ycombinator.com/item?id=30483417))
- [igrep](https://github.com/konradsz/igrep) - Interactive Grep.
- [Argc](https://github.com/sigoden/argc) - Handy way to handle sh/bash cli parameters.
- [qsv](https://github.com/jqnatividad/qsv) - Ultra-fast CSV data-wrangling CLI toolkit.
- [More Than a Dozen Command Line Tools I've Written—and So Can You (2018)](https://blog.carlmjohnson.net/post/2018/go-cli-tools/)
- [Track changes to CLI tools by recording their help output](https://simonwillison.net/2022/Feb/2/help-scraping/) ([HN](https://news.ycombinator.com/item?id=30658310))
- [Scout](https://github.com/jhbabon/scout) - Friendly fuzzy finder made in rust.
- [fzf](https://github.com/junegunn/fzf) - Fommand-line fuzzy finder. ([HN](https://news.ycombinator.com/item?id=30736518))
- [Making the command line glamorous with Toby Padilla (2022)](https://changelog.com/gotime/222)
- [septum](https://github.com/pyjarrett/septum) - Context-based code search tool.
- [has](https://github.com/kdabir/has) - Checks presence of various command line tools and their versions on the path.
- [Fig Manual Pages](https://fig.io/manual) - Beautiful, community-driven documentation for 300+ CLI tools.
- [csvlens](https://github.com/YS-L/csvlens) - CSV file viewer in the command line.
- [Difftastic](https://github.com/Wilfred/difftastic) - Diff tool that compares files based on their syntax. ([HN](https://news.ycombinator.com/item?id=30841244)) ([Article](https://www.wilfred.me.uk/blog/2022/09/06/difftastic-the-fantastic-diff/)) ([HN](https://news.ycombinator.com/item?id=32746258)) ([Lobsters](https://lobste.rs/s/mvzrr8/difftastic_fantastic_diff))
- [Goreman](https://github.com/mattn/goreman) - Manage Procfile-based applications.
- [Testing your CLI](https://github.com/google/go-cmdtest) - Go package simplifies testing of command-line interfaces.
- [Periscope](https://github.com/anishathalye/periscope) - Gives you "duplicate vision" to help you organize and de-duplicate your files without losing data.
- [Wiki CLI](https://github.com/BetaPictoris/wiki) - View Wikipedia articles through the CLI.
- [tush](https://github.com/darius/tush) - Literate testing for command-line programs.
- [-h --help -help help --? -? ???? (2022)](https://blog.craftyguy.net/cmdline-help/) ([Lobsters](https://lobste.rs/s/9e7yoy/h_help_help_help)) ([HN](https://news.ycombinator.com/item?id=30991834))
- [New(ish) command line tools (2022)](https://jvns.ca/blog/2022/04/12/a-list-of-new-ish--command-line-tools/) ([HN](https://news.ycombinator.com/item?id=31009313))
- [ff](https://github.com/vishaltelangre/ff) - Find files by name, fast.
- [cexec](https://github.com/mrusme/cexec) - Run commands and cache their output for a specific amount of time.
- [Hoard](https://github.com/Hyde46/hoard) - CLI command organizer written in rust.
- [A Simple Ejectable CLI Pattern (2022)](https://hire.jonasgalvez.com.br/2022/mar/13/a-simple-ejectable-cli-pattern/)
- [rush](https://github.com/thesephist/rush) - Command-line utility that lets you run one command on many files using a simple command template syntax.
- [mprocs](https://github.com/pvolok/mprocs) - Runs multiple commands in parallel and shows output of each command separately.
- [CLET](https://github.com/node-modules/clet) - Command Line E2E Testing.
- [climod](https://github.com/nixosbrasil/climod) - Modular generated command line interfaces using the same technology as the NixOS module system.
- [The sort --key Trick](https://www.gwern.net/Sort)
- [UX patterns for CLI tools (2022)](https://lucasfcosta.com/2022/06/01/ux-patterns-cli-tools.html) ([Lobsters](https://lobste.rs/s/av7f4o/ux_patterns_for_cli_tools))
- [forever](https://github.com/foreversd/forever) - Simple CLI tool for ensuring that a given script runs continuously (i.e. forever).
- [Best practices for inclusive CLIs (2022)](https://seirdy.one/posts/2022/06/10/cli-best-practices/) ([Lobsters](https://lobste.rs/s/zsazbu/best_practices_for_inclusive_clis)) ([HN](https://news.ycombinator.com/item?id=31709317))
- [tuc](https://github.com/riquito/tuc) - When cut doesn’t cut it. ([HN](https://news.ycombinator.com/item?id=31726472))
- [linebyline](https://github.com/pylover/linebyline) - Command line text processor.
- [Viddy](https://github.com/sachaos/viddy) - Modern watch command. Time machine and pager etc. ([HN](https://news.ycombinator.com/item?id=31829343))
- [cronlocker](https://github.com/viafintech/cronlocker) - Command line tool to allow running cronjobs on multiple hosts while ensuring that it only runs once at a time.
- [pipe-rename](https://github.com/marcusbuffett/pipe-rename) - Rename your files using your favorite text editor.
- [Backpack](https://github.com/rusty-ferris-club/backpack) - Use template and starter projects easily.
- [tere](https://github.com/mgunyho/tere) - Faster Alternative to cd+ls. ([HN](https://news.ycombinator.com/item?id=32106126))
- [bin](https://github.com/marcosnils/bin) - Manages binary files downloaded from different sources.
- [catp](https://github.com/rapiz1/catp) - Print the output of a running process.
- [lurk](https://github.com/JakWai01/lurk) - Simple and pretty alternative to strace. Allows the user to trace system calls of a process or of a command.
- [wrappe](https://github.com/Systemcluster/wrappe) - Packer to create self-contained single-binary applications from executables and directory trees.
- [Gum](https://github.com/charmbracelet/gum) - Tool for glamorous shell scripts. Leverage the power of Bubbles and Lip Gloss in your scripts and aliases without writing any Go code. ([Lobsters](https://lobste.rs/s/zpl3xn/gum_tool_for_glamorous_shell_scripts)) ([HN](https://news.ycombinator.com/item?id=32263827))
- [Things I've learned building a modern TUI framework (2022)](https://www.textualize.io/blog/posts/7-things-about-terminals) ([HN](https://news.ycombinator.com/item?id=32331367))
- [trashy](https://github.com/oberblastmeister/trashy) - Simple, fast, and featureful alternative to rm and trash-cli written in rust.
- [procmon](https://github.com/sebdah/procmon) - Simple utility for checking if processes are running.
- [Marian Montagnino - Reinventing the CLI with Go (2022)](https://www.youtube.com/watch?v=5oVvX08r6RE)
- [Awesome list of CLI/TUI programs](https://github.com/toolleeo/cli-apps)
- [goldplate](https://github.com/fugue/goldplate) - Cute and simple golden test runner for CLI applications.
- [CLI Testing Library](https://github.com/crutchcorn/cli-testing-library) - Simple and complete CLI testing utilities that encourage good testing practices.
- [run-pty](https://github.com/lydell/run-pty) - Run several commands concurrently. Show output for one command at a time. Kill all at once.
- [headtail](https://github.com/CleanCut/headtail) - Head and tail simultaneously.
- [enquirer](https://github.com/termapps/enquirer) - Command Line Utility for Stylish Interactive Prompts.
- [Your favorite Rust CLI utilities this year (2022)](https://www.reddit.com/r/rust/comments/xgwe4u/your_favourite_rust_cli_utilities_this_year/)
- [pipebuffer](https://github.com/tfenne/pipebuffer) - Simple command line program for buffering stdin/stdout between piped processes.
- [zig-dwarfdump](https://github.com/kubkon/zig-dwarfdump) - dwarfdump utility but in Zig.
- [Bevel](https://github.com/NorfairKing/bevel) - Command line history in an SQLite database for effective re-use.
- [alt](https://github.com/dotboris/alt) - Simple version manager. Tool for switching between different versions of commands.
- [Charm VHS](https://github.com/charmbracelet/vhs) - Write terminal GIFs as code for integration testing and demoing your CLI tools.
- [JC](https://github.com/kellyjonbrazil/jc) - JSONifies the output of many CLI tools. ([HN](https://news.ycombinator.com/item?id=33448204))
- [Command-line data analytics made easy (2022)](https://danielcmoura.com/blog/2022/spyql-cell-towers/)
- [CLI Tools Are Not Inherently User-Hostile - Mindy Preston (2022)](https://www.youtube.com/watch?v=IcV9TVb-vF4)
- [How stdbuf works (2022)](https://hmarr.com/blog/how-stdbuf-works/) ([HN](https://news.ycombinator.com/item?id=33561319))
- [keyb](https://github.com/kencx/keyb) - Create and view your custom hotkey cheat sheet with TUI.
- [GPT3 Powered CLI](https://github.com/abhagsain/ai-cli) - Get answers for CLI commands from GPT3 right from your terminal.
- [Nap](https://github.com/maaslalani/nap) - Code snippets in your terminal.
- [chimp](https://github.com/xolvio/chimp) - Tooling that helps you do quality, faster.
- [llama](https://github.com/antonmedv/llama) - Terminal file manager.
- [moar](https://github.com/walles/moar) - Pager. It reads and displays UTF-8 encoded text from files or pipelines.
- [Terminal CoPilot](https://github.com/Methexis-Inc/terminal-copilot) - Smart terminal assistant that helps you find the right command.
- [Copilot, for your terminal](https://github.com/m1guelpf/plz-cli) - CLI tool that generates shell scripts from a human readable description.
- [How we improved productivity with an internal CLI (2022)](https://medium.com/qonto-way/how-we-improved-productivity-with-an-internal-cli-7466f3bf5fee)
- [Awesome CLI](https://github.com/Kikobeats/awesome-cli) - Curated list of things related with Command Line Interfaces.
- [DidYouMean](https://github.com/hisbaan/didyoumean) - CLI spelling corrector for when you're unsure.
- [fre](https://github.com/camdencheek/fre) - Command line frecency tracking.
- [rsms-utils](https://github.com/rsms/rsms-utils) - Collection of CLI programs to help with everyday computer life. ([HN](https://news.ycombinator.com/item?id=34242275))
- [shelltestrunner](https://github.com/simonmichael/shelltestrunner) - Easy, repeatable testing of CLI programs/commands.
- [Catimg](https://github.com/posva/catimg) - Renders images in the terminal.
- [Just](https://github.com/casey/just) - Command Runner. ([HN](https://news.ycombinator.com/item?id=34315779))
- [felix](https://github.com/kyoheiu/felix) - TUI file manager with Vim-like key mapping, written in Rust.
- [Rmt](https://github.com/AmineZouitine/rmt.rs) - Similar to the rm command but saves the deleted elements in the trash and restores them.
- [Commands.dev](https://www.commands.dev/) - Find commands at the speed of thought. ([Code](https://github.com/warpdotdev/commands.dev))
- [sudo at home](https://github.com/Xe/xn--ts9h) ([HN](https://news.ycombinator.com/item?id=34454165))
- [CSView](https://github.com/hymkor/csview) - Simple CSV viewer/editor.
- [Flagon](https://github.com/Pondidum/Flagon) - Feature Flags from your CLI.
- [Solitaire TUI](https://github.com/brianstrauch/solitaire-tui) - Klondike solitaire for the terminal. Built with Bubble Tea Go.
- [gotop](https://github.com/xxxserxxx/gotop) - Terminal based graphical activity monitor inspired by gtop and vtop.
- [Erdtree](https://github.com/solidiquis/erdtree) - Multi-threaded file-tree visualizer and disk usage analyzer.
- [clipboard](https://github.com/amilajack/clipboard) - Better command line clipboard.
- [xdg-ninja](https://github.com/b3nj5m1n/xdg-ninja) - Shell script which checks your $HOME for unwanted files and directories.
- [greple](https://github.com/kaz-utashiro/greple) - Extensible grep with lexical expression and region handling.
- [WIKI-TUI](https://github.com/Builditluc/wiki-tui) - Simple and easy to use Wikipedia Text User Interface.
- [GTop](https://github.com/mJehanno/gtop) - Alternative to top or htop made in Go.
- [Teleport](https://github.com/bollu/teleport) - Lightning-fast tool to quickly switch between repositories.
- [Building CLI with Bubble Tea and Lip Gloss](https://github.com/charmbracelet/wizard-tutorial)
- [halp](https://github.com/orhun/halp) - CLI tool to get help with CLI tools.
- [WIK](https://github.com/yashsinghcodes/wik) - Terminal Based Wikipedia. ([HN](https://news.ycombinator.com/item?id=35119681))
- [teip](https://github.com/greymd/teip) - Masking tape to help commands "do one thing well".
- [gotrash](https://github.com/koki-develop/gotrash) - rm alternative written in Go.
- [JSCodemod](https://github.com/NickHeiner/jscodemod) - Codemod runner.
- [textra](https://github.com/freedmand/textra) - Command-line application to convert images, PDFs, and audio files to text using Apple's APIs.
- [Curated list of command-line utilities written in Rust](https://github.com/sts10/rust-command-line-utilities)
- [gat](https://github.com/koki-develop/gat) - cat alternative written in Go.
- [sttr](https://github.com/abhimanyu003/sttr) - Cross-platform, cli app to perform various operations on string.
- [demo](https://github.com/saschagrunert/demo) - Framework for performing live pre-recorded command line demos.
- [killport](https://github.com/jkfran/killport) - Command-line tool to easily kill processes running on a specified port. ([HN](https://news.ycombinator.com/item?id=35698282))
- [sudo-rs](https://github.com/memorysafety/sudo-rs) - Memory safe implementation of sudo and su. ([Article](https://www.memorysafety.org/blog/sudo-and-su/)) ([HN](https://news.ycombinator.com/item?id=35714347))
- [hunt](https://github.com/LyonSyonII/hunt-rs) - Simplified Find command made with Rust.
