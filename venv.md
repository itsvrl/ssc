# 1st - Make universal access to python

```sh
bash $ echo "alias python=\"python3\"" >> $HOME/.bashrc
fish $ echo "alias python=\"python3\"" >> $HOME/.config/fish/config.fish
```

# 2nd - Enable your Python Virtual Env

```sh
python -m venv venv
```

# 3rd - Make em executable

```sh
chmod +x ./venv/bin/activate
chmod +x ./venv/bin/activate.csh
chmod +x ./venv/bin/activate.fish
chmod +x ./venv/bin/Activate.ps1
```

# 4th - Enable your venv for stating using it

```sh
bash $ ./venv/bin/activate
csh  $ ./venv/bin/activate.csh
fish $ ./venv/bin/activate.fish
PS   $ ./venv/bin/Activate.ps1
```

# 5th - Install needed packages

```sh
python -m pip install -r requirements.txt
```