# Linux

## Installation using Snap

> Snaps are app packages for desktop, cloud and IoT that are easy to install, secure, cross‐platform and dependency‐free. Snaps are discoverable and installable from the Snap Store, the app store for Linux with an audience of millions.
>
> Source: [https://snapcraft.io/about](https://snapcraft.io/about)

We provide AuthPass on the [Snap Store](https://snapcraft.io/authpass). You can use the Snap Store or the Terminal.

Refer to the following steps if using the Snap Store.

* Search for AuthPass on the Snap Store or open the above link.
* Install AuthPass by clicking the install button.

Refer to the following steps if using the Terminal.

* Install AuthPass using the `snap` package manager.

```text
sudo snap install authpass
```

{% hint style="warning" %}
Make sure `snapd` is running on your Linux distribution. The instructions to do so are documented [here](https://snapcraft.io/docs/installing-snapd).
{% endhint %}

## Installation using PPA

We provide AuthPass in a Personal Package Archive \(**PPA**\) for Ubuntu and other Debian-based distributions.

Refer to the following steps if using the PPA.

* Add our PPA to your system and update the package manager cache.
* Install AuthPass using the `apt` package manager.

```text
sudo add-apt-repository ppa:codeux.design/authpass
sudo apt-get update
sudo apt-get install authpass
```

## Installation using source tarball

{% hint style="warning" %}
Using this method for installation is not recommended for a normal user because AuthPass updates such a security updates, bug fixes and new features will not be available easily.
{% endhint %}

We provide AuthPass as source tarballs on [GitHub](https://github.com/authpass/authpass/releases).

Refer to the following steps if using the source tarballs.

* Download the latest release for Linux from the above GitHub releases page \(e.g. `authpass-linux-1.7.8_1552.tar.gz`\).
* Extract the downloaded file and launch AuthPass.

```text
wget https://github.com/authpass/authpass/releases/download/v1.7.8/authpass-linux-1.7.8_1552.tar.gz
tar xzf authpass-linux-1.7.8_1552.tar.gz
authpass/authpass
```



## F.A.Q.

