# Vue-hmr-test-parcel-and-webpack

**Vue CLI v3.0.0-beta.9** was used with TypeScript to create the file structure. 

I deleted the HelloWorld component.

This simple project shows that parcel does not preserve the state currently while hot reloading.


#### Running the project with webpack

```
npm run serve
```
using webpack preserves the state while hot reloading:

[Short video using webpack](https://screencast-o-matic.com/watch/cFhVDhbquR)

#### Running the project with parcel


```
parcel index.html
```

using parcel shows that currently the state is not preserved.

[Short video using parcel](https://screencast-o-matic.com/watch/cFhVDnbqu4)

