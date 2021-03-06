<a id="extractmatchedpath-java"></a>
# extractMatchedPath

## Description

Extracts the matched path from the request context.

The `extractMatchedPath` directive extracts the path that was already matched by any of the @ref[PathDirectives](../path-directives/index.md#pathdirectives-java)
(or any custom ones that change the unmatched path field of the request context). You can use it for building directives
that use already matched part in their logic.

See also @ref[extractUnmatchedPath](extractUnmatchedPath.md#extractunmatchedpath-java) to see similar directive for unmatched path.

## Example

@@snip [BasicDirectivesExamplesTest.java](../../../../../../../test/java/docs/http/javadsl/server/directives/BasicDirectivesExamplesTest.java) { #extractMatchedPath }