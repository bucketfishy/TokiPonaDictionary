# uwulang dictionary

a simple uwulang - english dictionary with search function.

this dictionary is forked by bucketfish from [jprogr's simple toki pona dictionary](https://github.com/jProgr/TokiPonaDictionary). it has been updated to use uwulang data.

the data used in this dictionary is from the [official uwulang document](https://docs.google.com/document/d/1ZV1U0S8qC6yJEi6grFO_Vq5A15lRVCLYeq_udWsC-9Y/edit).

all content below are unedited from the original project.

## Development

The project uses NPM and its ecosystem. So to run it you need at least:

- Node 14.

To begin install depencies using NPM:

```
npm i
```

Now you can start up a server for development:

```
npm start
```

This will lint the code and make the page available at `http://localhost:9000/`.

### Build

To build everything for release or deployment use:

```
npm run build
```

### Utilities

The project includes other commands to aid development.

To see the page in any other device in your local network you can use the following command:

```
npm run start:open
```

This will make the page available under `<IP of the device running the dev server>:9000`. Good for testing in mobile devices.

The command `npm run start:prod` does the same but uses production mode (more optimizations).

#### Linting

To project uses ESLint, to run it use:

```
npm run lint
```
