# babel-plugin-import-graphql-files
This babel plugin lets you import GraphQL files into your Javascript application as compiled schema definitions. Which uses [graphql-tag](https://www.npmjs.com/package/graphql-tag) package to compile them into their compiled equivalent.

##Installation
####npm
```bash
npm install --save-dev babel-plugin-import-graphql-files
```

####yarn
```bash
yarn add --dev babel-plugin-import-graphql-files
```

##Usage
In your babel configuration file, just add the package name into your plugins array.
```javascript
{
    plugins: [
        'babel-plugin-import-graphql-files'
    ]
}
```
or
```javascript
{
    plugins: [
        'import-graphql-files'
    ]
}
```