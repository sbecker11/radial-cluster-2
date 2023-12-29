# Radial cluster tree

https://observablehq.com/@d3/radial-cluster/2@245

View this notebook in your browser by running a web server in this folder. For
example:

~~~sh
npx http-server
~~~

Then, import your notebook and the runtime as:

~~~js
import {Runtime, Inspector} from "@observablehq/runtime";
import define from "@d3/radial-cluster/2";
~~~

To log the value of the cell named “foo”:

~~~js
const runtime = new Runtime();
const main = runtime.module(define);
main.value("foo").then(value => console.log(value));
~~~
