# jq.sisense.plugin
# example usage - add a panel using sisense's interface and then do whatever you want with it. 

$('div[wtitle=sub_now]').sisenseClearPanel({
    css: {
        'background-color': '#e75025',
        'border-radius': '3px',
        'color': '#fff',
        'font-weight': 'bold',
        'text-align': 'center',
        'padding-top': '.8em',
        'cursor': 'pointer',
        'padding-top': '10px',
        'height': '23px'
    }
});
