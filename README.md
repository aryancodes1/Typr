<img src="https://github.com/DriftingOtter/Typr/blob/main/assets/Typr_Astro.png" alt="Typr logo of an astronaut using a keyboard">

# Typr: Your Personal Typing Tutor :keyboard:.
## Description 📜 
> typr is a Python-based applicatio

1. Clone typr Repository:

Clone typr repository to your desired location.

```
git clone https://github.com/DriftingOtter/Typr.git

cd TyprCLI
```

2. Run install script:

```
chmod +x install.sh

./install.sh
```

### Manual Install // Manual Build

1. Install rich Python module:

If you have not already done so, install the [rich](https://pypi.org/project/rich/) Python module, as it's a *critical* library for typr.

```
pip install rich
```

2. Clone typr Repository:

Clone typr repository to your desired location using Git

```
git clone https://github.com/DriftingOtter/Typr.git

cd TyprCLI
```

3. Locate main.py:

Make sure you know the correct path to your main.py file within the __TyprCLI/src/__ directory you just cloned.

4. Set up Aliases ___(Optional)*___

Please check with your shell's documentation on how to add aliases to your rc files.

Here are some commonly used shell alias commands you can copy.

#### Bash
Add the following line to your __~/.bashrc__ file:

```
alias typr="python3 /path/to/TyprCLI/src/main.py"
```

#### Zsh
Add the following line to your __~/.bashrc__ file:

```
alias typr="python3 /path/to/TyprCLI/src/main.py"
```

#### Fish
Add the following line to your __~/.config/fish/config.fish__ file:

```
alias typr="python3 /path/to/TyprCLI/src/main.py"
```

#### Xonsh
Add the following line to your __~/.xonshrc__ file:

```
aliases['typr'] = 'python3 /path/to/TyprCLI/src/main.py'
```

5. Test The Alias

Open a new terminal window and type typr. It should execute your typr application.

___You can also run ```typr -h``` to output the manual page for the application to see all the addional run-time flags you can utilize.___

## Contributing

If you want to contribute to this project, please feel free to read the [CONTRIBUTING.md](./CONTRIBUTING.md) document to gain a better understanding of how to make changes, and improve this application.

## Acknowledgements
- [Freepik.com](https://www.freepik.com/free-vector/cute-astronaut-working-with-laptop-space-cartoon-vector-icon-illustration-science-technology_42161336.htm#query=keyboard&position=13&from_view=search&track=sph) for astronaut logo

___(Image by catalyststuff on Freepik)___

- [katto-studios](https://github.com/katto-studios/loki) for the default word list

- [monkeytype](https://github.com/monkeytypegame/monkeytype) for the inspiration for the [CONTRIBUTING.md](./CONTRIBUTING.md) document

