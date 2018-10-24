[![Travis CI](https://travis-ci.org/opendevsecops/travis-cohesion-bench.svg?branch=master)](https://travis-ci.org/opendevsecops/travis-cohesion-bench)

# travis-cohesion-bench

The purpose of this project is to provide a practical example how to integrate SecApps [Cohesion](https://secapps.com/cohesion) into Travis CI for continues dynamic vulnerability scanning.

The following demo targets are tested once a week:

* http://demo.testfire.net
* http://php.testsparker.com
* http://testphp.vulnweb.com
* http://webscantest.com

Feel free to add more targets. See `.travis.yml` for more information.

Keep in mind that the build will not fail when vulnerabilities are identified. This can be configured using the available cohesion command-line flags. More information can be found here: https://secapps.com/docs/cohesion/.
