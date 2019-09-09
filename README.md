# hello-world-go-qt

[![CI Status](https://github.com/pasdam/hello-world-go-qt/workflows/Continuous%20integration/badge.svg)](https://github.com/pasdam/hello-world-go-qt/actions)

Go-Qt integration demo.

## Requirements

* Go 1.13;
* [Qt binding for Go](https://github.com/therecipe/qt).

In order to compile and deploy the app it's necessary to [install the Qt binding for Go](https://github.com/therecipe/qt#installation).

## Run

```sh
qtdeploy build desktop
```

You should find your deployed application inside the *deploy* subfolder.
