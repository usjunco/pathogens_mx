# node-pathogens-portal-theme

Hugo theme for [node pathogens portal](https://github.com/ScilifelabDataCentre/node-pathogens-portal) inspired by [Swedish pathogen portal](https://www.pathogens.se/) and [Swiss pathogen portal](https://pathogensportal.ch/), while following the visual identity of [central pathogens portal](https://www.pathogensportal.org/).

## How to use

If you desire to use this theme in your `hugo` project, follow the steps mentioned.

1) Open a terminal and go to the root of your hugo project

    ```
    cd <path to hugo project>
    ```

    where `<path to hugo project>` should be an absolute or relative path to the hugo project

2) Create a `themes` directory if it did not exist already and change to it

    ```
    mkdir themes && cd themes
    ```

3) Clone (download) this theme to in the `themes` directory

    ```
    git clone https://github.com/ScilifelabDataCentre/node-pathogens-portal-theme.git
    ```

4) Add the following to your `hugo.yaml` config file

    ```yaml
    theme: "node-pathogens-portal-theme"
    ```

    **Note:** `hugo` config file can also be in `toml` and `json` format, so change the above according to your config format

That is all, after this you can run `hugo` as usual and it will use this themes to display the content.

## Credits

This project is supported by the National Institute Of Allergy And Infectious Diseases of the National Institutes of Health under Award Number U24AI183840. The content is solely the responsibility of the authors and does not necessarily represent the official views of the National Institutes of Health.

This theme was developed by [Scilifelab Data Centre](https://www.scilifelab.se/data/) as part of [PDN project](https://pathogendatanetwork.org/) and is based on [central pathogens portal](https://www.pathogensportal.org/), [Swedish pathogen portal](https://www.pathogens.se/) and [Swiss pathogen portal](https://pathogensportal.ch/).

We thank [Swiss Institute of Bioinformatics](https://www.sib.swiss/), [EMBL-EBI](https://www.ebi.ac.uk/) and all collaborators.
