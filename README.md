# Typewave for Linux

Download the files from the Releases page.

## Install

Arch Linux or CachyOS:

    sudo pacman -U typewave-<ver>-1-x86_64.pkg.tar.zst

Ubuntu 24.04:

    sudo apt install ./typewave_<ver>_amd64.deb

Replace `<ver>` with the version you downloaded, for example `0.1.22`.

## Check the download

Each release has a `SHA256SUMS` file. Put it in the same folder as the
package you downloaded, then run:

    sha256sum --check --ignore-missing SHA256SUMS

You should see `OK` next to the file name. If you don't, download it again.
