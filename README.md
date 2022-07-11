# Moodle

Moodle.org

Moodle is a free and open-source learning management system written in PHP and distributed under the GNU General Public License. Moodle is used for blended learning, distance education, flipped classroom and other online learning schemes in schools, universities, workplaces and other sectors. It can be used to create custom websites with online courses and allows for community-sourced plugins.

## Setup and configuration

Running this project is as simple as deploying it to a balena Cloud application. You can do it in just one click by using the button below:

[![deploy button](https://balena.io/deploy.svg)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://github.com/maggie0002/balena-moodle&defaultDeviceType=raspberry-pi)

Set the `DEVICE_HOSTNAME` environment variable in the docker-compose file to the hostname of the device this will run on. To test locally, set to `0.0.0.0` and access from `0.0.0.0:8442`.
