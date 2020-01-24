## Serverless GO Template

Template created from following instructions [here](https://serverless.com/blog/framework-example-golang-lambda-support/) and added serverless-offline to show local development possibilities

## Notes*
* Since GO is a compiled language it may take a few seconds since we have to leverage Docker for `serverless-offline`
There is also [LocalStack](https://github.com/localstack/localstack) but your mileage may vary.
* This is a very simplified example and you may need additional offline plugins to get your local development to work appropriately. 
There be dragons!

```shell
brew install dep # for GO

yarn install # first time
yarn start # for local serverless-offline
yarn deploy # to remove it
```
