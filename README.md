# z-dialog

## A Zepto Plugin

During the development of a H5 activity for the company, I found out that we always built the dialog by ourselves everytime, such as the css, the callback function etc. So I think it's necessary to build a unity plugin for the best benifits and conveniency of the development.


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
If u set up the title, it will look like as below:

![img](/images/z_dialog.png)

If u don't set up the title, it will look like as below:

![img](/images/z_dialog2.png)

Thanks.
