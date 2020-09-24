# Linux

## Installation using Snap

{% hint style="warning" %}
Make sure `snapd`\(the daemon behind snaps\) is running on your Linux distribution. The instructions to do so are documented [here](https://snapcraft.io/docs/installing-snapd).
{% endhint %}

Installing AuthPass on Linux is usually a 1-step process thanks to snap packages. You can install AuthPass using the Snap Store or run the following command in the terminal.

```text
sudo snap install authpass
```

> Snaps are app packages for desktop, cloud and IoT that are easy to install, secure, cross‐platform and dependency‐free. Snaps are discoverable and installable from the Snap Store, the app store for Linux with an audience of millions.
>
> Source: [https://snapcraft.io/about](https://snapcraft.io/about)

## Installation using PPA

We provide a Personal Package Archive \(**PPA**\) for Ubuntu and other Debian-based distributions. Installing AuthPass is just a matter of adding the PPA and installing the package using `apt`.

```text
sudo add-apt-repository ppa:codeux.design/authpass
sudo apt-get update
sudo apt-get install authpass
```

## Installation using source tarball

{% hint style="danger" %}
Using this method for installation is not recommended for a normal user. AuthPass updates such a security updates, bugfixes and new features will not be available easily.
{% endhint %}

We also provide releases as source tarballs on [GitHub](https://github.com/authpass/authpass/releases). Refer to the following steps to use AuthPass from the source tarballs.

* Download the latest release for Linux \(e.g., `authpass-linux-1.6.3_1201.tar.gz` \).
* Extract the downloaded file and launch AuthPass.

```text
wget https://github.com/authpass/authpass/releases/download/v1.7.8/authpass-linux-1.7.8_1552.tar.gz
tar xzf authpass-linux-1.7.8_1552.tar.gz
authpass/authpass
```



## F.A.Q.

{% hint style="info" %}
Installing Authpass on Linux will also create `/usr/bin/authpass` if you need to run Authpass from the CLI.
{% endhint %}

