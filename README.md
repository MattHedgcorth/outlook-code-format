# outlook-code-format
```function loadDropDown() {
    $.ajax({
        url: 'webservices/AcctNumber.asmx/GetSeriesData',
        type: "POST",
        data: '{}',
        dataType: 'xml',
        success: parse,
        error: loadfail
    });
}```
