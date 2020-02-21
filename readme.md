# ng-redundancy
> This package, when required, aggressively makes your app redundant by terminating the node process with exit code 0

## Install
```bash
npm install ng-redundancy
```

## Usage
```javascript
require('ng-redundancy') // smooth, right?
```

## Why exit code 0?
This package doesn't discriminate or assume your app is good/bad/buggy. Every app shall be dealt with the same way (eventually).

## Do I need this?
No! Every app should be given a chance to prove itself (in th real world) no matter what. Don't require if you don't wanna be made redundant.
