## 0.0.0 - First Release
* Experimental language support for Terraform.io configurations

## 0.1.0 - Second Release
* Add support for nested provisioning statements

## 0.2.0 - Third Release
* Better names for capture groups

## 0.3.0 - Fourth Release
* Fix for comments (thanks frntn)

## 0.4.0 - Fifth Release
* Fix for "${a.b}" style strings. (thanks sbward)

## 0.5.0
* Fix for nested interpolated strings not parsing correctly
* Fix for comments not parsing correctly inside blocks

## 0.6.0 - Thanks Ryan Graham (rmg)
* multi-line comments
* booleans
* number literals, including supported suffixes
* syntax highlighting inside string interpolations
* functions
* variables
* literals
* support for heredoc strings
* embedded syntax hightlighting based on token suffix (<<CONFIG_JSON, <<CONFIG_YAML, ...)
* string interpolation highlighting inside the embedded language (this one is kind of magical)

## 0.7.0 - Thanks John Engelman (johnrengelman) and Bo Tranberg (tranberg)
* Fix for nested interpolations.
* New snippets

## 0.7.1 - Thanks Bo Tranberg
* Small fix for correct resource highlighting

## 0.7.2
* Small fix adding `//` as line comment

## 0.7.3
* Adds Indent Rules (thanks itiut)

## 0.7.4 - Thanks Bo Tranberg
* Allow dashes in resource names and handle curly braces in regex

## 0.7.5 - Thanks Jamie Lennox and Roberto Barbosa
* Adding ignore_changes. Ref: https://www.terraform.io/docs/configuration/resources.html#ignore_changes
* Added all types of variable and module, and provider/provider-aws and provisioner

## 0.8.0 - Thanks Ipswitch
* Adds new keyword snippets for better autocompletion

## 0.8.1 - Thanks Seth Chisamore
* Adds quick toggle line comments to bring more in line with Atom's other grammars.

## 0.9.0
* Use (temporarily?) new package name language-terraform-12 to allow usage
* Support most common Terraform 0.12 features and functions

## 0.9.1
* Add package keywords

## 0.9.2
* Add `null` as primitive literal like `true` and `false`

## 0.9.3
* Add support for [indented heredoc strings](https://www.terraform.io/docs/configuration/expressions.html#string-literals) (thanks privatwolke)

## 0.9.4 - Deprecate package
* Deprecate this package and archive repository as development on the official [language-terraform](https://github.com/cmur2/language-terraform) has [resumed](https://github.com/cmur2/language-terraform/issues/46) and all features are upstreamed
