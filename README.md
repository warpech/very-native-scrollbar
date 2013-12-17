Very Native Scrollbar
=====================

This small library gives you a tiny API to create and interact with a native browser scrollbar.

Live example: http://warpech.github.io/very-native-scrollbar

### API

#### VeryNativeScrollbar ()

Constructor

#### setScrollCallback ( `function` )

Sets a callback function that will be called (without any arguments) on scrollbar `scroll` events.

#### setTop ( `number` )

Sets the top scrollbar position in pixels, relative to the viewport (`position: fixed`)

#### setLeft ( `number` )

Sets the left scrollbar position in pixels, relative to the viewport (`position: fixed`)

#### setWidth ( `number` )

Sets the width of the scrollbar in pixels. Changes scrollbar dimension to horizontal

#### setHeight ( `number` )

Sets the height of the scrollbar in pixels. Changes scrollbar dimension to vertical

#### setScrolledWidth ( `number` )

Sets the width in pixels of the internal scrolled area (usually it is greater than the scrollbar width; otherwise scrollbar handle won't show up). Use only after `setWidth` (horizontal scrollbar)

#### setScrolledHeight ( `number` )

Sets the height in pixels of the internal scrolled area (usually it is greater than the scrollbar height; otherwise scrollbar handle won't show up). Use only after `setHeight` (vertical scrollbar)

#### setPositionPx ( `number` )

Sets the scrollbar handle position in pixels

#### getPositionPx ( ) : `number`

Returns the current scrollbar handle position in pixels

#### setPositionFactor ( `number` )

Sets the scrollbar handle position in relative value from 0 to 1.

#### getPositionFactor ( ) : `number`

Returns the current scrollbar handle position in relative value from 0 to 1.

## Changelog

#### v0.0.20131217

Change class name to be `very-native-scrollbar`.

#### v0.0.20131216

Initial release

## License

MIT (see the LICENSE file)
