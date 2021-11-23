---
testspace:
foo: bar
bar:
  baz: foo
---
# Partials with variables :octocat:

## Example scenario :octocat:

Check if partials with variables are working correctly: 

{% include context-variables-partial.md %}
{% include custom-defined-variables.md %}
{% include partial-with-local-variables.md myLocalVar="testing service" otherLocalVar=313 %}
