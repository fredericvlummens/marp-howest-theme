# Marp Howest Theme

## Use with Visual Studio Code

1. Install the extension `Marp for VS Code`

1. In your VS Code user settings, navigate to the setting [vscode://settings/markdown.marp.themes](vscode://settings/markdown.marp.themes)

1. Add an entry towards https://fredericvlummens.github.io/marp-howest-theme/howest.css

1. Create an MD file with the following front matter:

    ```
    ---
    marp: true
    theme: howest
    ---
    ```

1. You can now build slides using Markdown in Howest layout

1. For the title slide, use

    ```
    <!-- _class: lead -->

    # Slidedeck title

    ## Slidedeck subtitle

    ### Author, last updated date ...

    #### Copyright footer
    ```

1. Separate all following slides by `---`