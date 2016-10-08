# Tutorial button click

## Purpose
Tutorial: show how simle to program a button click 

2016.10.02 by Szőke Sándor
Android Studio version: 2.2 (September 15, 2016)

## Steps needed:

* create application
* drag button onto layout
* add code to: class MainActivity 
* attach code to button onClick: buttonOnClick

```java
    public void buttonOnClick(View v)
    {
        Button button = (Button) v;
        ((Button) v).setText("Clicked");

    }
```
* place cursor after "(View v)" and press ALT+ENTER
* place cursor after "(Button)" and press ALT+ENTER
* exetute and click
