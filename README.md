# jQuery File Upload for Rails 3.1 Asset Pipeline

[jQuery-File-Plugin](https://github.com/blueimp/jQuery-File-Upload) is a file upload plugin written by [Sebastian Tschan](https://github.com/blueimp). jQuery File Upload features multiple file selection, drag&drop support, progress bars and preview images for jQuery. Supports cross-domain, chunked and resumable file uploads and client-side image resizing.

jquery-fileupload-rails is a library that integrates jQuery File Upload for Rails 3.1 Asset Pipeline (Rails 3.2 supported).

## Plugin versions

* jQuery File Upload User Interface Plugin 6.9.4
* jQuery File Upload Plugin 5.16.3
* jQuery UI Widget 1.8.23+amd

## Installing Gem

    gem "jquery-fileupload-rails"

## Using the javascripts

Require jquery-fileupload in your app/assets/application.js file.

    //= require jquery-fileupload

The snippet above will add the following js files to the mainfest file.

    //=require jquery-fileupload/vendor/jquery.ui.widget
    //=require jquery-fileupload/vendor/load-image
    //=require jquery-fileupload/vendor/canvas-to-blob
    //=require jquery-fileupload/vendor/tmpl
    //=require jquery-fileupload/jquery.iframe-transport
    //=require jquery-fileupload/jquery.fileupload
    //=require jquery-fileupload/jquery.fileupload-fp
    //=require jquery-fileupload/jquery.fileupload-ui
    //=require jquery-fileupload/locale

If you only need the basic files, just add the code below to your application.js file. [Basic setup guide](https://github.com/blueimp/jQuery-File-Upload/wiki/Basic-plugin)

    //=require jquery-fileupload/basic

The basic setup only includes the following files:

    //=require jquery-fileupload/vendor/jquery.ui.widget
    //=require jquery-fileupload/jquery.iframe-transport
    //=require jquery-fileupload/jquery.fileupload

## Using the stylesheet

Require the stylesheet file to app/assets/stylesheets/application.css

    *= require jquery.fileupload-ui

## [Example app](https://github.com/tors/jquery-fileupload-rails-paperclip-example)
This app uses paperclip and twitter-bootstrap-rails


## Thanks
Thanks to [Sebastian Tschan](https://github.com/blueimp) for writing an awesome file upload plugin.

## License
Copyright (c) 2012 Tors Dalid

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
