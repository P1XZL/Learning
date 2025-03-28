## What is YAML?
"YAML is a data serialisation language designed to be directly writable and readable by humans."

In my own words, YAML is a coding language for other coding languages to communicate with each other.

Other examples like YAML include .json and .xml (.xml is used in excel for example).

YAML files are very easy to read but it can be quite complicated to use it yourself.

Sources I recommend: https://learnxinyminutes.com/yaml/

## Basics
Just like any other language, YAML also has variables.
Things like lists, booleans, strings and more.

### Booleans
A boolean is essentially a vallue that can either be on or off. In this case true or false. You can change the value of a boolean by

```yaml
# Basic Booleans

boolean: false
boolean: true

# Other examples

booleanName: yes # The boolean is true
booleanName: "yes" # The boolean is true
booleanName: no # The boolean is false

# Common mistakes

yes: no # The boolean is false

no: yes # The boolean is true
```

#### Strings:
