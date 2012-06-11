MooView
=======

This is a small and simple image viewer for large images.  It uses HTML5 canvas with no fallback.  I haven't needed one, but it should be pretty easy to extend.

You can:
* Pan
* Zoom
* Use keyboard to navigate
* Load large images, i.e. 5120x5120+

How to use
----------

    var viewer = new MooView();
    viewer.setImages([
        {
            "image": "/static/i/winter.jpg",
            "thumbnail": "/static/i/__winter.jpg"
        }
    ]);
    viewer.show();