# My Fish Prompt
This is a repo to track my personal [fish shell](https://fishshell.com/) prompt. It is based on the default [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) prompt by [Robby Russell](https://github.com/robbyrussell). Specifically, it is based on the [fish port of that prompt](https://github.com/fish-shell/fish-shell/blob/85cd372a4ecdc95e68139e87892437f7ecc66809/share/tools/web_config/sample_prompts/robbyrussell.fish).

# Installation
To install, run the following command in your terminal:

```curl -o ~/.config/fish/functions/fish_prompt.fish https://raw.githubusercontent.com/DeanPDX/fish-prompt/master/fish_prompt.fish```

From the [fish documentation](https://fishshell.com/docs/current/faq.html#faq-prompt):

> The prompt is the output of the fish_prompt function. Put it in ~/.config/fish/functions/fish_prompt.fish.

If you want to uninstall, set a new prompt using the `fish_config prompt` command. That will replace your `fish_prompt.fish` file with whatever prompt you select in the web UI.
