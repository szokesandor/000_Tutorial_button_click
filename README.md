# 000_Tutorial_button_click

## Purpose 
Tutorial: adding button to an activity
2016.10.02 by Szőke Sándor

## Steps needed:
* create application
* drag button onto layout
* add code to: class MainActivity 
* attach code to button onClick: buttonOnClick

    public void buttonOnClick(View v)
    {
        Button button = (Button) v;
        ((Button) v).setText("Kattintas");

    }

* place cursor after "(View v)" and press ALT+ENTER
* place cursor after "(Button)" and press ALT+ENTER
* exetute and click
