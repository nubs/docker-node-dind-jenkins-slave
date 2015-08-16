# docker-node-dind-jenkins-slave
This is a jenkins slave image for building [node.js][node.js] [npm][npm]
repositories based on
[tehranian/dind-jenkins-slave][tehranian/dind-jenkins-slave].

## Purpose
This jenkins slave image allows for building docker containers and executing
node.js code directly.

## Usage
This container can be used with the [Jenkins Docker Plugin][Jenkins Docker Plugin]
and is a derivative of the example slave container described there.

It can also be run more permanently and used with Jenkins standard "dumb
slave" configuration over ssh.

## License
docker-node-dind-jenkins-slave is licensed under the MIT license.  See
[LICENSE](LICENSE) for the full license text.

[node.js]: http://nodejs.org/
[npm]: https://www.npmjs.org/
[tehranian/dind-jenkins-slave]: https://github.com/tehranian/dind-jenkins-slave
[Jenkins Docker Plugin]: https://wiki.jenkins-ci.org/display/JENKINS/Docker+Plugin
