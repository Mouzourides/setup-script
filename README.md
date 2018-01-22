# setup-script

A quick script I wrote, designed for Ubuntu based distros, to hook me up with packages because I'm lazy.

Credit to [Sam Warner](https://github.com/sjwarner) for the idea.

## How to run

- Clone this repo
- Edit the `apt-stuff` and `snap-stuff` files in the Data directory to install your desired packages via `apt-get` and `snap`
- Edit the `projects-stuff` file in the Data directory using the following format: `repo author,repo title` e.g. `Nik-Mouz,setup-script` 
- Replace the image in the Data directory to your desired wallpaper image and title your desired image: `wallpaper`
- Run: `./setup-script.sh`

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
