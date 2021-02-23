# Test
## Testing my setup
<a href="http://stackoverflow.com" target="_blank">http://stackoverflow.com</a>
Visit https://github.com

showdown.extension('targetlink', function() {
  return [{
    type: 'html',
    regex: /(<a [^>]+?)(>.*<\/a>)/g,
    replace: '$1 target="_blank"$2'
  }];
});
