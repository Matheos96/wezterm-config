# My Wezterm Config

**Heavily** based on [Kevin Silvester's wezterm config](http://github.com/Kevinsilvester/wezterm-config)

## Getting Started

- ##### Requirements:

  - <details>
      <summary><b>WezTerm</b></summary>

    Minimum Version: `20240127-113634-bbcac864`<br>
    Recommended Version: [`Nightly`](https://github.com/wez/wezterm/releases/nightly)

    [Official Installation Page](https://wezfurlong.org/wezterm/installation.html)

    **Windows**

    - <details>
      <summary>Install Stable</summary>

      - Install with Scoop (non-portable)

        ```sh
        scoop bucket add extras
        scoop install wezterm
        ```

      - Install with Scoop (portable)

        ```sh
        scoop bucket add k https://github.com/KevinSilvester/scoop-bucket
        scoop install k/wezterm
        ```

      - Install with winget

        ```sh
        winget install wez.wezterm
        ```

      - Install with choco

        ```sh
        choco install wezterm -y
        ```
      </details>

    - <details>
      <summary>Install Nightly</summary>

      - Install with Scoop (non-portable)

        ```sh
        scoop bucket add versions
        scoop install wezterm-nightly
        ```

      - Install with Scoop (portable)

        ```sh
        scoop bucket add k https://github.com/KevinSilvester/scoop-bucket
        scoop install k/wezterm-nightly
        ```
      </details>

    > :bulb:<br>
    > Toast notifications don't work in non-portable installations.<br>
    > See issue <https://github.com/wez/wezterm/issues/5166> for more details
  
    ---

    **MacOS**

    - <details>
      <summary>Install Stable</summary>

      - Install with Homebrew

        ```sh
        brew install --cask wezterm
        ```

      - Install with MacPort

        ```sh
        sudo port selfupdate
        sudo port install wezterm
        ```
      </details>

    - <details>
      <summary>Install Nighlty</summary>

      - Install with Homebrew

        ```sh
        brew install --cask wezterm@nightly
        ```

      - Upgrade with Homebrew

        ```sh
        brew install --cask wezterm@nightly --no-quarantine --greedy-latest
        ```
      </details>

    ---

    **Linux**

    Refer to the Linux installation page.<br>
    <https://wezfurlong.org/wezterm/install/linux.html>

    </details>

  - <details>
    <summary>JetBrainsMono Nerd Font</summary>

    Install with Homebrew (Macos)

    ```sh
    brew tap homebrew/cask-fonts
    brew install font-jetbrains-mono-nerd-font
    ```

    Install with Scoop (Windows)

    ```sh
    scoop bucket add nerd-fonts
    scoop install JetBrainsMono-NF
    ```

    > More Info:
    >
    > - <https://www.nerdfonts.com/#home>
    > - <https://github.com/ryanoasis/nerd-fonts?#font-installation>
    </details/>


- ##### Steps:

  1.  ```sh
      # On Windows and Unix systems
      git clone https://github.com/matheos96/wezterm-config.git ~/.config/wezterm
      ```
  2.  And Done!!! 🎉🎉
