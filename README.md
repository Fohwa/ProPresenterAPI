# Proxplat Extended

This is a website that uses the offical ProPresenter API by RenewedVision to make ProPresenter usable remotely in a webbrowser
Some of its functionality maybe will be replaced by the official Propresenter control (check out renewedvision.com/propresenter/control when it comes out), but propaly not all of it.

## Use
In order to use this you need to be in the same network as the Computer running ProPresenter and have its IP and Port (can be seen in the Preferences under Networking)

## Development
This is currently work in progress and things might change at any moment.

## Differences to Proxplat
Proxplat was designed to work on Github pages. Due to their limitations on using http requests for secrurity purposes it was hard to implement more advanced features (entire API works with http what kinda sucks). From a ressouce perspective it was definetly enough. Therefore Github Pages is no longer an option for advancement. Basic version will still be available, but not updated.

### Hosting
Without Github Pages there are really no good options for me to host this. We could just put it all in one html file and send it to people. That would limit the options we have for structure and design (no custom images, no seperate css, hard to manage code), but would make it easy to open on a device. There comes another problem: While opening html files in a browser is no problem for any computer or android device, it is for some reason for IOS. Our only option is to host it on my Laptop/RasPi during an event to use it.
So We will use a Node Server. That way it is easy to host to other devices and does not limit our options for more complex structure (login, computation on Server, database).
There are downsides, like having to host it on my device, but should not be used to often so should be fine.
