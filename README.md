
# modal

  A simple modal UI component

## Installation

  Install with [component(1)](http://component.io):

    $ component install heatroom/modal

## API

```html
<div class="overlay modal-overlay"></div>
<div class="modal-wrapper">
  <div class="modal">
    <a class="modal-close-button"></a>
    { Your element gets injected here. }
  </div>
</div>
```
### Modal(el)
  Create a new `Modal` instance with the given `el`.

### #show(fn)
  Show the modal, emitting `show`, optionally calling `fn`.

### #hide(fn)
  Hide the modal, emitting `hide`, optionally calling `fn`.

### #remove(fn)
  Remove the modal from the DOM, optionally calling `fn`.

### #closeable()
  Make the modal closeable.

### #temporary()
  Make the modal one-time-use, so that it removes itself on hiding.

### #addClass(name)
  Add a class `name` to the `.modal` and `.modal-overlay`.

### #removeClass(name)
  Remove a class `name` from the `.modal` and `.modal-overlay`.

## License

  The MIT License (MIT)

  Copyright (c) 2014 <copyright holders>

  Permission is hereby granted, free of charge, to any person obtaining a copy
  of this software and associated documentation files (the "Software"), to deal
  in the Software without restriction, including without limitation the rights
  to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
  copies of the Software, and to permit persons to whom the Software is
  furnished to do so, subject to the following conditions:

  The above copyright notice and this permission notice shall be included in
  all copies or substantial portions of the Software.

  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
  IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
  FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
  AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
  LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
  OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
  THE SOFTWARE.