onboardapis, was, what I was looking for: [documentation](https://felix-zenk.github.io/onboardapis/onboardapis.html), [repository](https://github.com/felix-zenk/onboardapis), [pypi](https://pypi.org/project/onboardapis/)

# Zug Book
Jupyter Notebook for the iceportal.de in the trains of the Deutsche Bahn.

Depends on python 3.12 and poetry.

Currently doesn't do a lot, just calls the API. Probably [onboardapis](https://github.com/felix-zenk/onboardapis) is the way to go.

My idea was that I would like to have a GNOME extension that show some information just like the [onboard-plasmoid (for KDE)](https://github.com/timschneeb/onboard-plasmoid) in my task bar, and also the the steam deck something like that would be useful.

## Install and Run

```
$ poetry install
$ peotry run jupyter notebook
```

## Other Projects

- [onboardapis](https://github.com/felix-zenk/onboardapis) - in python. onboardapis allows you to interact with different on-board APIs. You can connect to the Wi-Fi of a supported transportation provider and access information about your journey, the vehicle you are travelling in and much more [Documentation](https://felix-zenk.github.io/onboardapis/onboardapis.html).
- [iceportal_rs](https://github.com/adridevelopsthings/iceportal_rs) - in rust [Installation](https://lib.rs/crates/iceportal) [API Reference](https://docs.rs/iceportal/latest/iceportal/)
- [iceportal-api](https://github.com/craftamap/iceportal-api) - in golang
- [onboard-plasmoid](https://github.com/timschneeb/onboard-plasmoid) - A KDE plasmoid that displays live local telemetry data about the train you're sitting in
- [ice-portal-speed-logger](https://github.com/rurseekatze/ice-portal-speed-logger) - A shellscript for logging the speed of German ICE trains
- [Some further APIs by the Deutsche Bahn](https://developer-docs.deutschebahn.com/doku/apis/)

## Screenshot

![2024-04-27-205420_002](https://github.com/white-gecko/zugbook/assets/1018168/4b7e033c-134b-40ca-8c95-a4976a750f6e)
