# phantom-mocha

Mocha-like tests in phantomjs script

This attempt is abandoned.

The newest mocha version really struggles inside phantom 2.0.

Using [node-phantom-simple](https://www.npmjs.com/package/node-phantom-simple) bridge inside mocha tests that run in node produces good results and a low performance cost (less than 20% including spawning phantomjs for a single test that runs for approx 2 sec.)