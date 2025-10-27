# ZED EDITOR PPA
This is an unofficial ppa hosted on github pages for Ubuntu/Debian and their derivatives.

> [!IMPORTANT]
> This is a unofficial repo, not maintained by the authors of the software.

> [!WARNING]
> This ppa only provides a package for 64bit (amd64) systems.
> Since it is only maintained by me, the packages might not be very latest, and things might break.
> But that will be hopefully rare.

## How to use:
> [!TIP]
> Paste every command one by one.

```
curl -s --compressed "https://sinfulbobcat.github.io/zed-editor-ppa/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/zed-editor-ppa.gpg >/dev/null
```
```
sudo curl -s --compressed -o /etc/apt/sources.list.d/my_list_file.list "https://sinfulbobcat.github.io/zed-editor-ppa/my_list_file.list"
```
```
sudo apt update
```
```
sudo apt install zed-editor
```
