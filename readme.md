# Javascript Track Assessment

## Instructions

This repo contains the accessment exercise for the Javascript Track
Please perform the following instructions.

* Fork this repository.
* Clone the repository to your local computer.
* Add your solution to the specificied position.
* Commit your solution.
* Push your update to your repository.
* Submit your repository URL on the provided google form.

## Example

```js
// src/index.js

// complete the function
function prime(num){
    if (num === 1){
        return false;
    } else if (num === 2){
        return true;
    } else {
        for (let x = 2; x < num; x++){
            if(num % x === 0){
                return false;
            }
        }
        return true;
    }
}


function solution(arg) {
  return prime(arg);
}
```

## Running

``` shell
# run the solution
$: npm start <input>
```

## Testing
``` shell
$: npm test
```


## Need Help?
contact: engineering@shecodeafrica.org
