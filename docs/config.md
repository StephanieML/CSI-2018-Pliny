# Configuring Atom #

1. Download and install atom from https://atom.io/. If on OS X, open atom and choose from the Atom menu, “Install Shell Commands”. (This step should not be necessary on Windows or Linux operating systems.)

2. Open a Terminal window (Mac users) or a GitBash window (Windows users)

3. enter these commands (you can copy and paste the whole list)

`apm install intentions`

`apm install busy-signal`

`apm install linter`

`apm install linter-ui-default`

`apm install linter-autocomplete-jing`

`apm install atom-xsltransform`

`apm install tablr`

`apm install xml-formatter`

4. Download the file [atom-tablr-conf.cson](http://hcmid.github.io/tech/atom-tablr-conf.cson), change directories to your Downloads folder, and copy it to atom’s default location for config files. You can do that with the `cd` and `cp` commands in your terminal.

`cd Downloads` 

`cp atom-tablr-conf.cson $HOME/.atom/config.cson`

(Gotcha: if your browser renames your file for you when you download – e.g., if it calls it atom-tablr-conf.txt – it, you’ll have to use the name it chose instead of atom-tablr-conf.cson.)

(Sidenote: this step is not essential for today's workshop, but is helpful if you want to get involved in the full editing process in the future)

5. Add the [linter-autocomplete-jing plugin](https://github.com/aerhard/linter-autocomplete-jing). You can choose to download it as a zip file by clicking the green button.

6. Install [this package](https://github.com/neelsmith/atomic-tei) for automatic validation of documents following the Text Encoding Initiative (TEI) schema. Again, just download the zip file and keep it somewhere on your computer. 
