[<img src="https://cdn.rawgit.com/lutsen/lagan/master/lagan-logo.svg" width="100" alt="Lagan">](https://github.com/lutsen/lagan)

Lagan Properties Optionselect Template
======================================

Admin template to use a fixed array of options with the Lagan String property.
You define options in the properties of a model like this:
```php
'options' => [
	'option_a' => [ 'name' => 'Option A' ],
	'option_b' => [ 'name' => 'Option B' ]
]
```

You can set the validation rule in the String property like this:
```php
'validate' => 'inlist({"list": {"0":"option_a", "1":"option_b"}})'
```

To be used with [Lagan](https://github.com/lutsen/lagan). Lagan lets you create flexible content objects with a simple class, and manage them with a web interface.

Lagan is a project of [Lútsen Stellingwerff](http://lutsen.net/).