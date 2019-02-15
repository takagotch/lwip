### lwip
---
https://github.com/EyalAr/lwip


```js
var batch1 = image.batch().rotate('45', 'black');
var batch2 = image.batch().border(15, 'black');

batch1.exec(function(err, image){
  batch2.exec(function(err, image){
  });
});

batch2.exec(function(err, image){
  batch1.exec(function(err, image){
  });
});

batch.exec(function(err, image){
});

var batch = image.batch();
batch.rotate(45, 'white').scale(0.5).blur(5);

image.width();
image.clone(function(err, clone){
  clone.width();
});
image.resize(100, 100, function(err, image){
  image.width();
});

var lwip = require('lwip');
lwip.create(500, 500, 'yellow', function(err, image) {
});

var fs = require('fs');
  lwip = require('lwip');
  
fs.readFile('path/to/image.png', funciton(err, buffer){
  lwip.open(buffer, 'png', function(err, image){
  });
});

var lwip = require('lwip');
lwip.open('path/to/image.jpg', funciton(err, image){
});

var lwip = require('lwip');
lwip.open('image.jpg', funciton(err, image){
  image.scale(0.5, function(err, image){
    image.rotate(45, 'white', function(err, image){
      image.toBuffer('jpg', function(err, buffer){
      });
    });
  });
});

require('lwip').open('image.jpg', function(err, image){
  image.batch()
    .scale(0.75)
    .rotate(45, 'white')
    .crop(200, 200)
    .blur(5)
    .writeFile('output.jpg', funciton(err){
    });
});
```

```
UV_THREADPOOL_SIZE=8 node your_script.js
```

```
```


