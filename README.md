# Thymeleaf Snippets

## Features

Thymeleaf snippets for vscode

Snippets for the most common thymeleaf features. Works with .html files.


| Trigger | Context | Description |
|---------|---------|-------------|
|`thtext`|th:text="${variable}"|Display dynamic text in a template.|
|`thutext`|th:utext="${variable}"|Display dynamic text in a template, while escaping special characters to prevent XSS attacks.|
|`thvalue`|th:value="${variable}"|Set the value of an input field, select element, or textarea.|
|`thif`|th:if="${variable}"|Conditionally include or exclude content based on a Boolean expression.|
|`thunless`|th:unless="${variable}"|Conditionally exclude content based on a Boolean expression.|
|`theach`|th:each="item : ${item}"|Iterate over a collection of objects and display the data for each one.|
|`thobject`|th:object="${variable}"|Bind form data to a specific object in the model|
|`thhref`|th:href="@{url}"|Dynamically set the destination URL for a hyperlink.|
|`thsrc`|th:src="@{url}"|Dynamically set the source URL for an image or other media resource.|
|`thstyle`|th:style="${variable} == 'conditional'} ? 'true' : 'false'"|Set the inline style for an element.|
|`thfield`|th:field="*{name}"|Bind form field values to a specific property of a model object.|
|`thaction`|th:action="@{variable}"|Specify the URL for form submissions.|
|`thclassappend`|th:classappend="${variable} == 'conditional'} ? 'true' : 'false'"|Specify the URL for form submissions.|
|`thattr`|th:attr="data-attribute=${variable}"|Set arbitrary attributes for an element.|
|`thfragment`|th:fragment="${content}"|Define a reusable fragment of HTML that can be included in multiple templates.|
|`threplace`|th:replace="fragment :: content"|Replace the contents of an element with the contents of a named fragment.|
|`thinclude`|th:include="common-header :: header"|Include the contents of another template in the current template.|
|`thblock`|th:block="title"|Define a block of content that can be overridden by templates that extend the current template.|
|`thswitch`|th:switch="${data}"|Conditionally include content based on the value of a variable.|
|`thcase`|th:case="anything"|Conjunction with th:switch to define a case in a switch statement.|
|`thwith`|th:with="anything"|Expose a specific object in the model as a local variable, making it easier to access in the template.|
|`thinsert`|th:insert="anything :: anything"|Include the contents of another template in the current template, replacing the contents of an element with an ID that matches the name of the included template.|
|`thremove`|th:remove="all"|Remove an element from the template, including its contents.|

## Release Notes

### 1.0.0

- Initial release

