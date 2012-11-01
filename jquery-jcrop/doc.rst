Jcrop API Doc
=====================

options 
-----------------------
  $.Jcrop.defaults = {

    // Basic Settings
    allowSelect: true,
    allowMove: true,
    allowResize: true,

    trackDocument: true,

    // Styling Options
    baseClass: 'jcrop',
    addClass: null,
    bgColor: 'black',
    bgOpacity: 0.6,
    bgFade: false,
    borderOpacity: 0.4,
    handleOpacity: 0.5,
    handleSize: 7,

    aspectRatio: 0,
    keySupport: true,
    createHandles: ['n','s','e','w','nw','ne','se','sw'],
    createDragbars: ['n','s','e','w'],
    createBorders: ['n','s','e','w'],
    drawBorders: true,
    dragEdges: true,
    fixedSupport: true,
    touchSupport: null,

    shade: null,

    boxWidth: 0,
    boxHeight: 0,
    boundary: 2,
    fadeTime: 400,
    animationDelay: 20,
    swingSpeed: 3,

    minSelect: [0, 0],
    maxSize: [0, 0],
    minSize: [0, 0],

    // Callbacks / Event Handlers
    onChange: function () {},
    onSelect: function () {},
    onDblClick: function () {},
    onRelease: function () {}
  };


API function
-----------------------------

- $.Jcrop.startDragMode();
- $.Jcrop.presize();
- $.Jcrop.unscale();
- $.Jcrop.doneSelect();
- $.Jcrop.newSelection();
- $.Jcrop.selectDrag();
- $.Jcrop.setClass();
- $.Jcrop.setSelect();
- $.Jcrop.tellSelect();
- $.Jcrop.tellScaled();
- $.Jcrop.setOptionsNew();
- $.Jcrop.disableCrop();
- $.Jcrop.enableCrop();
- $.Jcrop.destroy();
  
  
