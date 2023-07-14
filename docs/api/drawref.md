<!-- Generated by document generator, changes will be lost. -->

# DrawRef

**Inherits** [RefCounted](https://docs.godotengine.org/en/4.1/classes/class_refcounted.html)

A wrapper class to easily create drawings to a [UI](#api/ui.md).

## Description

[DrawRef](#api/drawref.md) enables to quickly and easily add drawings to a node inside a [UI](#api/ui.md).

## Properties

| Type | Name | Default |
| --- | --- | --- |
| [float](https://docs.godotengine.org/en/4.1/classes/class_float.html) | [time](#property-time) | |
| [float](https://docs.godotengine.org/en/4.1/classes/class_float.html) | [delta](#property-delta) | |
| [CanvasItem](https://docs.godotengine.org/en/4.1/classes/class_canvasitem.html) | [node](#property-node) | |
## Methods

| Return | Method |
| --- | --- |
| void | [redraw](#method-redraw) ( ) |

## Property descriptions

### <a id="property-time">[float](https://docs.godotengine.org/en/4.1/classes/class_float.html) [time](#property-time) </a>

- <span style="opacity: 0.8">[float](https://docs.godotengine.org/en/4.1/classes/class_float.html) get_time ( )</span>

<blockquote>

Current time of the drawn frame in seconds.

</blockquote>

### <a id="property-delta">[float](https://docs.godotengine.org/en/4.1/classes/class_float.html) [delta](#property-delta) </a>

- <span style="opacity: 0.8">[float](https://docs.godotengine.org/en/4.1/classes/class_float.html) get_delta ( )</span>

<blockquote>

Time elapsed from the previous frame in seconds.

</blockquote>

### <a id="property-node">[CanvasItem](https://docs.godotengine.org/en/4.1/classes/class_canvasitem.html) [node](#property-node) </a>

- <span style="opacity: 0.8">[CanvasItem](https://docs.godotengine.org/en/4.1/classes/class_canvasitem.html) get_node ( )</span>

<blockquote>

The target node of the drawing as a [CanvasItem](https://docs.godotengine.org/en/4.1/classes/class_canvasitem.html).

</blockquote>

## Method descriptions

### <a id="method-redraw">void [redraw](#method-redraw) ( )</a>

<blockquote>

Requests the [UI](#api/ui.md) to redraw in the next frame.

</blockquote>
