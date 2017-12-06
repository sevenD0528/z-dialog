# z-dialog

## A Zepto Plugin

During the development of a H5 activity of the company, I found out that we always built the dialog by ourselves everytime. So I think it's necessary to build a plugin for the common confirm dialog.


The plugin is written built on the great Zepto.js and flexble.js which is a common lib used for our mobile development solution.
It can be used as below, which u can also find out in the demo index.html:

```
    $.dialog({
        content : 'Content',
        title : 'ok',
        width : '5rem',
        height : '4rem',
        confirm : function() {
            alert('Confirmed');
            return true;
        },
        confirmText: 'Confirm'
    });
```

Thanks.
