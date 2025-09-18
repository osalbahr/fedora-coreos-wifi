# fedora-coreos-wifi

Creating a Fedora CoreOS ISO with WiFi enabled

## Creating the ISO

Follow https://github.com/coreos/custom-coreos-disk-images but use the `Containerfile` from this repo.

The list of packages was obtained from [Enabling WiFi](https://docs.fedoraproject.org/en-US/fedora-coreos/sysconfig-enabling-wifi).

If you also use the demo ignition file from this repo, the user is `core` and the password is also `core` in the console. No `ssh` authentication. See [Producing an Ignition Config](https://docs.fedoraproject.org/en-US/fedora-coreos/producing-ign).

Note: took about 15 minutes to create the ISO on my laptop
