## document_base_url

This option specifies the base URL for all relative URLs in the document. The default value is the directory of the current document. If a value is provided, it must specify a directory (not a document) and must end with a `/`.

This option also interacts with the [relative_urls](#relative_urls), [remove_script_host](#remove_script_host), and [convert_urls](#convert_urls) options to determine whether TinyMCE returns relative or absolute URLs. The [FAQ]({{ site.baseurl }}/get-started/get-support/) contains a thorough description and examples of working with relative and absolute URLs.

**Type:** `String`

##### Example

```js
tinymce.init({
  selector: 'textarea',  // change this value according to your HTML
  document_base_url: 'http://www.example.com/path1/'
});
```
