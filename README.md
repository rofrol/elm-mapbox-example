# elm mapbox example

## Run

Install node and elm and also some http server like `npm i -g serve`.

```bash
$ npm i
$ cp .env.example .env
# set your env variables in .env
$ bash prepare.sh
$ elm make src/Main.elm --output elm.js
$ serve 
```

Open http://localhost:5000/.
