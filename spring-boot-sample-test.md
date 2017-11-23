#### spring-boot-sample-test

##### 1. MediaType
返回HTML格式：
```
    @GetMapping(path = "/test",produces = MediaType.TEXT_HTML_VALUE)
    public String test(){
      return "<html><body><h1>Hello world</h1></body></html>";
    }
```
|MediaType|Value|ContentType|
|---|---|---|
|APPLICATION_ATOM_XML|APPLICATION_ATOM_XML_VALUE|application/atom+xml|
|APPLICATION_FORM_URLENCODED|APPLICATION_FORM_URLENCODED_VALUE|application/x-www-form-urlencoded|
|APPLICATION_JSON|APPLICATION_JSON_VALUE|application/json|
|APPLICATION_JSON_UTF8|APPLICATION_JSON_UTF8_VALUE|application/json;charset=UTF-8|
|APPLICATION_OCTET_STREAM|APPLICATION_OCTET_STREAM_VALUE|application/octet-stream|
|APPLICATION_PDF|APPLICATION_PDF_VALUE|application/pdf|
|APPLICATION_RSS_XML|APPLICATION_RSS_XML_VALUE|application/rss+xml|
|APPLICATION_XHTML_XML|APPLICATION_XHTML_XML_VALUE|application/xhtml+xml|
|APPLICATION_XML|APPLICATION_XML_VALUE|application/xml|
|IMAGE_GIF|IMAGE_GIF_VALUE|image/gif|
|IMAGE_JPEG|IMAGE_JPEG_VALUE|image/jpeg|
|IMAGE_PNG|IMAGE_PNG_VALUE|image/png|
|MULTIPART_FORM_DATA|MULTIPART_FORM_DATA_VALUE|multipart/form-data|
|TEXT_EVENT_STREAM|TEXT_EVENT_STREAM_VALUE|text/event-stream|
|TEXT_HTML|TEXT_HTML_VALUE|text/html|
|TEXT_MARKDOWN|TEXT_MARKDOWN_VALUE|text/markdown|
|TEXT_PLAIN|TEXT_PLAIN_VALUE|text/plain|
|TEXT_XML|TEXT_XML_VALUE|text/xml|

##### 2. RequestMapping
* @GetMapping
* @PostMapping
* @PutMapping
* @DeleteMapping
* @PatchMapping
