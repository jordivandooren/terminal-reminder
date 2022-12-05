# Terminal reminder

Get a random reminder when your terminal opens. 

Manage reminders in a file (`~/.reminders`) and make your shell
print a random line on initialisation, using GNU core utility [`shuf`](https://www.gnu.org/savannah-checkouts/gnu/coreutils/manual/coreutils.html#shuf-invocation).

## Install (bash)

```sh
echo 'shuf -n 1 ~/.reminders' >> ~/.bashrc
```