# docs

Documentation files are placed in the `public` directory.

Use the following command to generate the documentation:

```bash
./gradlew dokkaGenerateHtml
```

Then you can open the `index.html` file in the `public/dokka` directory.

Use `yarn dev` to preview the documentation locally.

> [!INFO]
> Put /docker-kotlin in the URL to be able to access the documentation.