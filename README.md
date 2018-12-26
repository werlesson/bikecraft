# [Bikecraft](https://werlesson.github.io/bikecraft/)

Website created during the _"Web Design Completo"_ course and improved with the _"CSS with SASS"_ course. The courses were created by [Origamid](https://www.origamid.com).

## INSTALLATION

Tools used in website creation:

### SASS (node/npm)

  The following commands were used to convert the _.scss_ files to _.css_.

 `npm install -g sass`

 `npm install -g sass-globbing`

## COMMANDS

The installation command that has _sass-globing_ helps to convert the entire directory, not just a file.

### Converting a file

`sass INPUT_FILE OUTPUT_FILE`

### Converting a directory

`sass INPUT_DIR:OUTPUT_DIR`

### Parameters

+ --no-source-map: prevents generation of _source-map_ files;
+ --style=compressed: compress output files;
+ --watch: monitors changes and converts files;

### Examples

#### Development

`sass --no-source-map --watch INPUT_DIR:OUTPUT_DIR`

#### Production

`sass --no-source-map --style=compressed --watch INPUT_DIR:OUTPUT_DIR`

## WEBSITE

[https://werlesson.github.io/bikecraft/](https://werlesson.github.io/bikecraft/)
