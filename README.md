Test how github renders "sponsor this project" section.

Generated with `rg "github-sponsors ?= ?true" --files-with-matches ./people/ | gawk 'match($0, /.*\/([-a-zA-Z0-9]+).toml/, m) { print "- \""m[1]"\"" }'` in [github.com/rust-lang/team](https://github.com/rust-lang/team).
