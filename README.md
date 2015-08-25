flot-state-plugin
=================

A plugin for Flot showing states along the x-axis of the graph

Fork includes option to disable text, and an example in example.html.

Usage (see example.html)
````
var data = [
    {
        // Regular series here
    },
    }
    {
        data: [
            [timestamp1, 'On'],
            [timestamp2, 'Off'],
            // Etc.
        ],
        xaxis: 2,
        yaxis: 2,
        label: false,
        state: {
            show: true,
            showText: true,
            label: "On/Off",
            states: {
                "On": "rgba(0,255,0,1)", "Off": "rgba(255,0,0,1)"
            }
        }
    }
]
````