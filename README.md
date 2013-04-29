Param.js
=======

Validation system, that expects from you some rules (JSON-like-described) and if you want some custom data-type of input-param(s), a validation function for it and/or custom viewer function.
If you need custom previewer for your form, you can create a custom template, but usually you can use theme-templates from us. Param.js:

- already supports a lot of data-types, and it's truly rare situation, when you need to add your own; 
- works both at the client and at the server-side (node.js);
- was written in pure JavaScript, that makes it compatible with all libraries whatever you want;
- supports params dependencies;
- supports custom data-types;
- supports custom data-properties;
- supports custom validation functions;
- supports theming.

Supported data-types
=======
- integer
- float
- enum
- string
- custom (whatever you want)

All data-types support such limit-properties:

Supported data-properties
=======
- maxlength
- minvalue
- maxvalue
- visibility
- regexp
- default
- dependencies
- required
- readonly
- type
- visibility
- alone
- etc (whatever you want)

Data-dependencies
=======
(coming soon)

PS
=======
Documentation and code coming soon (in the next episode =) :)

License
=======
MIT
Param.js originally developed for Omnicomm (http://www.omnicomm.ru/).
