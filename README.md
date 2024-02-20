## Project description...


## Instructions ... 


---------

**About this template**

This template is designed to be used with the [Quarto](https://quarto.org) reproducible document system. It harnesses the functionality of Quarto websites to create a reproducible project template. 

The main file used to configure the project is `_quarto.yml`. It includes the key-value pairs that define the project. Important keys include:

- `title`: The title of the project
- `repo-url`: The URL of the project repository
- `site-url`: The URL of the project website

The process and report files are stored in the `process` and report directories, respectively. Adding a Quarto document to these directories will automatically add it to the website.

Each file in the `process` directory should be a Quarto document that conducts and documents a specific step in the project workflow. The files in the `report` directory should be Quarto documents that describe the project and its results.

All Quarto documents should be modular. That is, the input and output of each document should be read from and written to the `data` directory and no variables should be defined outside of the document. This ensures that the project is reproducible and that the documents can be run in any order.

You can execute and build this project using the [Quarto command line interface](https://quarto.org/docs/cmd.html). For example, to build the project website, run:

```bash
quarto render
```

To build the project website and open it in a web browser, run:

```bash
quarto render --serve
```

Alternatively, you can open the project in [RStudio](https://rstudio.com) and use the Render command in the Build pane to build the project website.