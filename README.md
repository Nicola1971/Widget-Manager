# Widget Manager
dashboard widget manager for EVO 1.3.3

A small EVO plugin to hide, resize and sort default dashboard widgets

- Show/Hide widgets: show/hide/AdminOnly
- Widget size: 12/6/4/3
- Menu index: sort widget order by number

![screenshot](https://user-images.githubusercontent.com/7342798/30176337-5b2127c8-9402-11e7-8333-af40ed22604c.png)

# Troubleshooting

#### Q: Cant hide widgets 

R: 
- Go to **Elements > Plugins > Edit Plugin Execution Order > OnManagerWelcomeHome** 
- Drag **Widget Manager** Plugin BELOW all other plugins (at the bottom of the list)
- Save
