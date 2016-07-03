This project is most useful if your Maven web project:
* Has only static content
* Is fed dynamic data from a seperate API (REST, perhaps?)
  * Don't forget to add a [proxy middleware](https://github.com/drewzboto/grunt-connect-proxy) if your API doesn't support [CORS](https://en.wikipedia.org/wiki/Cross-origin_resource_sharing)

# Usage
Use `mvn compile frontend:grunt` to develop with auto [JSHint](http://jshint.com), [Jasmine](https://jasmine.github.io), [Karma](https://karma-runner.github.io), and [LiveReload](https://github.com/napcs/node-livereload).

 Use `mvn jetty:run-war` to test in a more "production" setting where WAR is built and deployed.

## Thanks
Major inspiration courtesy of: https://github.com/eirslett/frontend-maven-plugin/tree/master/frontend-maven-plugin/src/it/example%20project

## License
MIT
