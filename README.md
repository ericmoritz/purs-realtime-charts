# purs-chart

This is an example of an isomorphic PureScript applicaton.  The goal is to create
a backend and a frontend using both PureScript for both

The goal is to create an application that reads values off a MQTT topic and
chart it in the browser in real time

This project should demostrate how to do the following in PureScript:

1. Interface with existing battle tested React libraries (Material UI)
2. Demostrate data streams and transformations of those streams
3. JSON parsing of messages
4. small and medium tests of functionality

## Components

### backend

The backend will be a HTTP server that streams MQTT messages to the frontend

### frontend

The frontend will be a [Material-UI](https://material-ui.com/) frontend that
will chart the data as a D3 line graph in real time
