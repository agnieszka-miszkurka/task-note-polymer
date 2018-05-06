# \<task-note\>

Displays a task and its details.

Example:
To show the search
```
    <body>
      <task-note title="Watch Star Wars" task-description="May the force be with you!"
                 duration="200 min" date="Fri, 4 May 2018">
      </task-note>
```
### Documentation Page
https://agnieszka-miszkurka.github.io/task-note/
### Demo Page
https://agnieszka-miszkurka.github.io/task-note/demo/
### Styling
The following custom properties and mixins are available for styling:

|Custom property | Description | Default|
|----------------------------|--------------------------------------------|----------|
|`--primary-color` | The color of the icons and checkbox | `#9a59ff`|
|`--title-background` | The color of the background for upper part of task note | `#c8d9ff`|
|`--border-color` | The color of the line between title and description | `#9a59ff`|

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.


