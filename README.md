# meals

A new Flutter project.



format = """
$all
"""
add_newline = true
[character]
format="\n└ $symbol "
[username]
format = "┌ 🤖 [$user]($style) "
show_always = true
[directory]
format = "\n| 📁 [$path]($style)[$read_only]($read_only_style) "
[git_branch]
format=" [$symbol$branch]($style) "
[git_commit]
commit_hash_length = 7
only_detached = false
tag_disabled = false
disabled = false
[git_status]
format = "([ $all_status$ahead_behind  ]($style) )"
conflicted = "😱"
ahead = "☝️"
behind = "👇"
diverged = "👀☝️👇"
untracked = "🤷"
stashed = "🗃"
modified = "✏️"
staged = "📎"
renamed = "📝"
deleted = "🗑"
[docker_context]
symbol = "🐋"
disabled = false
[env_var]
variable = "SHELL"
disabled = true
[kubernetes]
format = "\n| [$symbol$context( ($namespace))]($style) "
symbol = "⛵ "
disabled = false
[package]
format="\n| is [$symbol$version]($style) "
[memory_usage]
format="\n| via $symbol [${ram}( | ${swap})]($style) "
[gcloud]
format= "\n| [$symbol $account (($project / $region))]($style)  "
style = "bold italic green"
[line_break]
disabled = true
