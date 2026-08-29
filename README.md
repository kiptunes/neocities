# miyufen.neocities.org

A personal site hosted on neocities to separate my personal things from my dev work and to have a place to organize all my art. Also functions as a html/css sandbox. Javscript-free mostly for fun : &#41;

- [Project structure](#project-structure)
- [Unfinished work](#unfinished-work)
- [Credits](#credits)
- [Licensing](#licensing)

## Project Structure

**src/**
: the folder that the github action deploys to neocities.

```
src/                  # deploy folder
├‒ _assets/           # local assets
|  ├‒ fonts/
|  |  ├‒ body/
|  |  ├‒ header/
|  |  └‒ title/
|  └‒ img/
|  |  ├‒ art/
|  |  ├‒ bg/
|  |  ├‒ graphics/
|  |  ├‒ icons/
|  |  └‒ media/
├‒ _css/              # stylesheets
|  ├‒ bulma/
|  ├‒ components/     # css snippets
|  ├‒ mod/            # modifies parent style.css
|  |  ├‒ art/
|  |  ├‒ info/
|  |  ├‒ links/
|  |  └‒ media/
|  ├‒ components.css
|  └‒ style.css
|                     # site folders
├‒ art/
├‒ links/
├‒ media/
|
├‒ credits.html       # attributions page
└‒ index.html         # landing page

```

## Unfinished Work

This project is unfortunately still unfinished and has many incomplete sections. Namely:<br>

- Many images are placeholders and do not yet have assets
  - Buttons
  - Art
  - Media (e.g. book and album covers)
- The entirety of the art folder
- JS functionality in the media folder
  - i.e. changing description based on selected book/album
- The /src/music/songs.html and /src/music/articles.html pages

I intend to keep working on this page as my main personal site, so these functionalities will eventually be implemented. In the meantime, I'm very sorry for the mess.

## Credits

- [**Bulma**](https://bulma.io) - CSS Framework by [jgthms](https://github.com/jgthms)<br>
- [**deploy-to-neocities**](https://github.com/marketplace/actions/deploy-to-neocities) - Github action by [bcomnes](https://github.com/bcomnes)
- [**Hack Club**](https://hackclub.com) - Global nonprofit dedicated to high school hackers

## Licensing

All code in this project is dedicated to the public domain under [The Unlicense](https://unlicense.org/) excluding the Bulma CSS framework, which is under the [MIT License](https://github.com/jgthms/bulma/blob/main/LICENSE).
