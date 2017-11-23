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
`org.springframework.web.bind.annotation`

* @GetMapping
* @PostMapping
* @PutMapping
* @DeleteMapping
* @PatchMapping

RequestMapping的属性：
* name
* value 指定请求的实际地址，指定的地址可以是URI Template模式;
* path
* method 指定请求的method类型， GET、POST、PUT、DELETE等;
* params 指定request中必须包含某些参数值是，才让该方法处理;
* headers  指定request中必须包含某些指定的header值，才能让该方法处理请求;
* consumes 指定处理请求的提交内容类型（Content-Type），例如application/json, text/html;
* produces 指定返回的内容类型，仅当request请求头中的(Accept)类型中包含该指定类型才返回;
