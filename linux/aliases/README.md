Create a script in /etc/profile.d/ to make aliases for all users:

Create a file called `00-aliases.sh` (or any other fancy name) in `/etc/profile.d`:

Put you aliases in this file. Example:

```sh
alias foo='bar --baz'
alias baz='foo --bar'
```

Save the file

Restart any open terminals to apply the changes.
