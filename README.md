# osu-world-maps

Map bundling system for [osu! World](https://osuworld.octo.moe)

### Features

* [Joining regions](/src/modifiers/join.ts)
* [Removing parts of regions](/src/modifiers/erase.ts)
* [Defining custom IDs](/src/modifiers/customId.ts)

### Contributing

You are welcome to help us by contributing new countries. Just keep in mind that, since we only use [Nominatim IDs](https://nominatim.openstreetmap.org/ui/search.html), they all require comments.

##### Testing

> ⚠ Don't forget to add the country [to the list](/src/countries/index.ts)

1. Bundle the country with `npm run bundle <code>`
2. Start the server with `npm run serve`
3. Open `http://localhost:7891/?<code>`

You can hover over a region to check its ID
