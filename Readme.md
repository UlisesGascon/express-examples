# Express examples

This repository contains several examples using Express.

- [auth](./examples/auth) - Authentication with login and password
- [content-negotiation](./examples/content-negotiation) - HTTP content negotiation
- [cookie-sessions](./examples/cookie-sessions) - Working with cookie-based sessions
- [cookies](./examples/cookies) - Working with cookies
- [downloads](./examples/downloads) - Transferring files to client
- [ejs](./examples/ejs) - Working with Embedded JavaScript templating (ejs)
- [error-pages](./examples/error-pages) - Creating error pages
- [error](./examples/error) - Working with error middleware
- [hello-world](./examples/hello-world) - Simple request handler
- [markdown](./examples/markdown) - Markdown as template engine
- [multi-router](./examples/multi-router) - Working with multiple Express routers
- [multipart](./examples/multipart) - Accepting multipart-encoded forms
- [mvc](./examples/mvc) - MVC-style controllers
- [online](./examples/online) - Tracking online user activity with `online` and `redis` packages
- [params](./examples/params) - Working with route parameters
- [resource](./examples/resource) - Multiple HTTP operations on the same resource
- [route-map](./examples/route-map) - Organizing routes using a map
- [route-middleware](./examples/route-middleware) - Working with route middleware
- [route-separation](./examples/route-separation) - Organizing routes per each resource
- [search](./examples/search) - Search API
- [session](./examples/session) - User sessions
- [static-files](./examples/static-files) - Serving static files
- [vhost](./examples/vhost) - Working with virtual hosts
- [view-constructor](./examples/view-constructor) - Rendering views dynamically
- [view-locals](./examples/view-locals) - Saving data in request object between middleware calls
- [web-service](./examples/web-service) - Simple API service


## Clone

You can clone this repository using:

```console
$ git clone https://github.com/expressjs/examples
$ cd examples
```

## Installation

:warning: Node.js 18.0 or higher is recommended.

[NVM](https://github.com/nvm-sh/nvm) is supported, so you can do:

```console
$ nvm install
```

Installation is done using the
[`npm install` command](https://docs.npmjs.com/getting-started/installing-npm-packages-locally):

```console
$ npm install
```

### Running examples

Whichever example you want:

```console
$ node examples/content-negotiation
```

## Contributing

The Express.js project welcomes all constructive contributions. Contributions take many forms,
from code for bug fixes and enhancements, to additions and fixes to documentation, additional
tests, triaging incoming pull requests and issues, and more!

See the [Contributing Guide](https://github.com/expressjs/express/blob/master/Contributing.md) for more technical details on contributing.

See the [Code of Conduct](https://github.com/expressjs/express/blob/master/Code-Of-Conduct.md) for a description of the standards we adhere to.

### Security Issues

If you discover a security vulnerability in Express, please see [Security Policies and Procedures](https://github.com/expressjs/express/blob/master/Security.md).

### Running Tests

To run the test suite, first install the dependencies, then run `npm test`:

```console
$ npm install
$ npm test
```

## People

The original author of Express is [TJ Holowaychuk](https://github.com/tj)

The current lead maintainer is [Douglas Christopher Wilson](https://github.com/dougwilson)

[List of all contributors](https://github.com/expressjs/examples/graphs/contributors)

## License

[MIT](LICENSE)
