# Hosts

A small script to manage your `/private/etc/hosts` file on Mac.

## Usage

The following command backs up `/private/etc/hosts`, and then replaces it with the blocklist hosted [here](http://winhelp2002.mvps.org/hosts.htm).

```sh
$ sudo ./hosts --update
```

Restore `/private/etc/hosts` to its original state with the following command.

```sh
$ sudo ./hosts --restore
```

## Disclaimer

Read `hosts` before you run it. Understand what it is doing before you run it. This goes for every command you run as `sudo`.
