# Oh My Posh

First `cd $env:POSH_THEMES_PATH\`<br>
Copy `rosepine-russell.omp.json` into the folder<br>

Run `notepad $PROFILE`<br>
If file doesn't exist, allow notepad to create it<br>

Paste `oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH\rosepine-russell.omp.json" | Invoke-Expression` into the file
