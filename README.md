#About
LESS Mixin to give css arrows (with given properties) on elements. (based on http://cssarrowplease.com/)

#Usage

To create a black box with an 10px high upwards pointing arrow:

    .block {
        #arrow > .top(10px, black);
    }

To create a white box with a black border and a downwards arrow:

    .block {
        #arrow > .bottom(20px, #ffffff, 10px, #000);
    }
