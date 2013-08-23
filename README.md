ngsvgdemo
=========

Short demo about using angular and svg's together

Key points
==========

- Angular is a great tool for svg manipulation
- ng-attr-<attribute-name> is your friend, as browser panics with the unprocessed values
- Only works with inline svg, as Angular can't modify the contents of an image
  - You can use ng-include to keep source code clean ( http://docs.angularjs.org/api/ng.directive:ngInclude )
