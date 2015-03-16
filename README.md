# angular-busyclick
Easily add busy state to buttons or other components in your Angular app without manually wiring anything up.

## Details
This package provides the 'busy-click' directive, which is used exactly the same as the built in Angular ng-click.
The busy-click directive adds one extra feature: if the expression in the attribute evaluates to a promise then the
element will get class 'busy' applied to it until the promise resolves.

## Examples

