# HelloWorld in Elm

Basic Elm code lives in `helloworld.elm` and relies on the [elm-lang/html][html] library. 

## Build Instructions

Run the following command from the root of this project:

```bash
elm-make helloworld.elm --output index.html
```

Open `index.html` in your browser or you can even start the application using python:
```
pip install SimpleHTTPServer
python -m SimpleHTTPServer

# Open in browser: http://localhost:8000
```

Type into the input field ("helloworld") to see the text appear!