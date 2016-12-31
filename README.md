# <%= siteName %>

> <%= siteDescription %>

## Usage

Watch for SCSS and JS changes:

    $ gulp

Preferably use MAMP or any other Apache server.

## Deployment & synchronization

#### grav-sync

Sync remote/local environment by pulling the `/user` folder from your server.
Make sure you fill in `.grav-sync.yml`.

    $ rake

#### phploy

Incremental Git (S)FTP deployment tool. Having [PHPloy](https://github.com/banago/PHPloy) installed locally is necessary.

    $ phploy -s [name]

## GPM

#### Update Grav

    $ bin/gpm selfupgrade

#### Update plugins and themes

    $ bin/gpm update

## License

(c) <%= siteName %>
