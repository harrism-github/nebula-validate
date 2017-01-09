[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/arsnebula/nebula-validate)
# \<nebula-validate\>

Web component (built with Polymer) to support data validation.

## Installation

```
$ bower install --save arsnebula/nebula-validate
```

## Usage

Import the element:

```html
<link rel="import" href="bower_components/nebula-validate/nebula-validate.html">
```

Add the element and set properties:

```html
<nebula-validate
  id="validator"
  auto-validate
  delay=300
  constraints="[[constraints]]"
  data="[[data]]"
  errors="{{errors}}">
</nebula-validate>
```

If using auto validation, then valdiation will be performed whenever the data changes. Validation can also be done manually:

```js
  this.$.validator.validate()
```

*For more information on element properties and methods see the element API documentation.*

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Change Log

See [CHANGELOG](/CHANGELOG.md)

## License

See [LICENSE](/LICENSE.md)