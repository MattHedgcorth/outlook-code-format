# outlook-code-format

This: https://github.com/mmanela/MarkdownOutlook

and This: https://tohtml.com/

```
function loadDropDown() {
    $.ajax({
        url: 'webservices/AcctNumber.asmx/GetSeriesData',
        type: "POST",
        data: '{}',
        dataType: 'xml',
        success: parse,
        error: loadfail
    });
}
```
