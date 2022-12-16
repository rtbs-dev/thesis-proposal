# MD Presentation Template

Nice-looking, NIST-compliant separation of form and content. 

> work smarter, not harder. 


## Notes

- Requires: 
    - matze/mtheme to be installed (`make sty`) (may come with TexLive already) 
    - and the Fira fonts (also in TexLive, but make sure system can access)
    - `pandoc-beamer-block` python package for beamer-style callouts in pandoc.
- Optional:
    - edit `settings.yaml` to include a `csl:` citation style file e.g. `asme.csl`. 

## Output Options: 


### Reveal.js 

`pandoc -t revealjs -s -o example.html example.md -V theme=serif`

If you don't have a local reveal installed/accessible: 

`-V revealjs-url=https://revealjs.com`

### LaTeX/Beamer
see `settings.yaml`


## TODO
settings config hierarchy for different outputs. 
