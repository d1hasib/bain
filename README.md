# bain - the battery indicator

![Arch Example](example/Arch.png)

## How to use?

* Make sure you're in `$HOME` directory

```bash
cd
```

* Clone the repository, and `cd` into it

```bash
git clone https://github.com/amirashabani/bain
cd bain
```

* Make the script executable
```bash
chmod +x bain.sh
```

* Run the code from your startup file (e.g. `.xinitrc`). Make sure to use `&` at the end of the file as it is a blocking script.
```bash
$HOME/bain/bain.sh $HOME/bain/Nord.png &
```

* Restart your X session (log out and log back in).
