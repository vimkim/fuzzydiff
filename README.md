# 🔍 fuzzydiff

![fuzzydiff demo](https://github.com/user-attachments/assets/4c87cb3c-390a-41c1-a899-d5e782409754)

Use it just like delta or diffnav!

```sh
$ git diff branchA branchB | fuzzydiff.py

$ diff -ur a.txt b.txt | fuzzydiff.py
```

Then, just use `Up` or `Down` arrow keys and press `<Enter>` to open it in your favorite text editor!


## What is fuzzydiff?

fuzzydiff is a lightning-fast tool that combines the power of `fzf` and `delta` to supercharge your diff viewing workflow. It opens piped diff files in a fuzzy finder interface, with beautiful syntax highlighting via delta, and lets you quickly open selected files in your preferred editor.

## ✨ Key Features

- ~**Blazing Fast**: Navigate through diffs with the speed and flexibility of fzf~ Not yet. I'll port it to Rust one day so please wait.
- **Beautiful Visualization**: See your changes with delta's beautiful syntax highlighting
- **Seamless Editing**: Press Enter to instantly open the selected file in your `$EDITOR`
- **Maximum Productivity**: Save precious development time with intuitive keyboard navigation

## 🤔 Why fuzzydiff?

As someone deeply invested in optimizing my development workflow, I created fuzzydiff to fill a specific gap:

- **For git power users**: Even as a heavy lazygit user, I found myself wanting something faster for certain diff scenarios
- **For vim/neovim enthusiasts**: Works perfectly alongside your existing telescope/fzf-lua workflows
- **For everyone**: Much faster than traditional methods when comparing branches or exploring diff patches

While you can achieve similar results with lazygit's `<shift-w>` or plugins like diff.nvim, fuzzydiff provides a streamlined, focused experience that's often much quicker for day-to-day use.

## 🚀 Getting Started

Unfortunately, since this being too nightly, pip or nix things are not yet supported.
You can just clone the repo, put the fuzzydiff.py into /usr/local/bin or any path you like and use it!

## 💡 Pro Tips

[Any additional tips for power users would go here]

---

Give it a try and watch your productivity soar! Questions or suggestions? Feel free to open an issue or PR.
