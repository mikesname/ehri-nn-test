This is an example site for EHRI National Nodes

To build the Sass continuously on Linux, install the NPM dependenies:

    npm install

Then run a watch command to generate CSS:

    while inotifywait scss/styles.scss; do
        npm run sass scss/styles.scss css/styles.css
    done

