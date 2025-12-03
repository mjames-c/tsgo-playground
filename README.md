Used for sharing bug repros with TSGO team

## Find refs re-export bug

Find refs doesn't seem to be able to follow re-exports.

working example (no re-export):

<img src="./find-refs-working.png" width="600" >

bug example (symbol re-exported in barrel file):

<img src="./find-refs-fail.png" width="600" >