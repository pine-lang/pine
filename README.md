# Pine CLI

Run the server:

```
pine run serve
```

or with a specific configuration:

```
CONFIG=default pine run serve
```

or use encrypted configuration:

```
CONFIG=prod.nc pine run serve
```

# Dev Setup

Clone with submodules:

```
git clone --recurse-submodules git@github.com:pine-lang/pine-cli.git
```

One time setup:

- Install dependencies `cd pine-app && npm install`

```
pine run dev-server
pine run app
```
