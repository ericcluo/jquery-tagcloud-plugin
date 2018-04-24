# jquery-tagcloud-plugin
This is a simple jquery tagcloud plugin to use in your blog.
## How to use
    <div id="youridname">
      <a href="/path" rel="1">front end</a>
      <a href="/path" rel="2">deep learning</a>
      <a href="/path" rel="3">life</a>
      <a href="/path" rel="4">having fun</a>
    </div>
    
then generate the tagcloud with different sizes and colors:

    $.fn.tagcloud.defaults = {
      size: {start: 20, end: 30, unit: 'px'},
      color: {start: '#1c5866', end: '#661c49'}
    };

    $(function () {
      $('#youridname a').tagcloud();
    });

## Demo
[Click here to view](https://ericcluo.github.io/jquery-tagcloud-plugin/).
    
