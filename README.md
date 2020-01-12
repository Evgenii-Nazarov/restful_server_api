## A RESTful API project

#### This project was created to demonstrate basic principles of REST server API.

#### There are 4 main specific architectural principles, which are

* Addressable Resources. Every “thing” on your network should have an ID. With REST over HTTP, every object will have its own specific URI.

* A Uniform, Constrained Interface. When applying REST over HTTP, stick to the methods provided by the protocol. This means following the meaning of GET, POST, PUT, and DELETE religiously.

* Representation oriented. You interact with services using representations of that service. An object referenced by one URI can have different formats available. Different platforms need different formats. AJAX may need JSON. A Java application may need XML.

* Communicate statelessly. Stateless applications are easier to scale.

#### Here was used an _**express**_ framework set up a server as well as a _**mongoose**_ library to build a connection with mongoDB.