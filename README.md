# jhipster-jdl

Some examples of JDL schema for use with JHipster.

JDL is the JHipster Domain Language, the specification can be found [here](http://www.jhipster.tech/jdl/).

You can edit JDL files in VS Code or Eclipse using the JHipster plugin or they can be uploaded to [JDL-Studio](https://start.jhipster.tech/jdl-studio/)
where you can edit and view the schema diagram.

Also see notes on the use of DTOs [here](https://www.jhipster.tech/using-dtos/).

*Note:* The ".jh" file extension is used as a default by JDL-Studio but the plugin likes ".jdl".

## Usage

Assuming you have JHipster installed globally then first create an empty directory and go into it:
```
mkdir myapp
cd myapp
```
Run JHipster and follow the instructions on screen to generate your flavour of application:
```
jhipster
```
Once completed import the required JDL schema which will regenerate the application to include the new entities:
```
jhipster import-jdl jhipster-example.jdl
```

## Examples

- jhipster-blog - A blog, as used in Matt Raible's [Getting Started with JHipster 6](https://www.youtube.com/watch?v=uQqlO3IGpTU) video.

- jhipster-developer-portfolio - A *work in progress* example to go with my [Developer Portfolio](https://github.com/RatJuggler/developer-portfolio) site.

- jhipster-example - The default Oracle "Human Resources" example from the JDL-Studio editor.

- jhipster-pet-clinic - An implementation of the Petclinic entities used in numerous other project examples.

- jhipster-monolith-dinosaurs - Used to create my own [JHipster Monolith Dinosaurs](https://github.com/RatJuggler/jhipster-monolith-dinosaurs) example application. It includes the application options used to make (re)generation easier. See that project for more details.

- jhipster-microservices-dinosaurs - Used to create my own [JHipster Microservices Dinosaurs](https://github.com/RatJuggler/jhipster-microservices-dinosaurs) example application.  It includes the application options used to make (re)generation easier See that project for more details.
