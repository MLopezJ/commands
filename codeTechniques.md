# Code Techniques

- ## Avoid nested conditionals 

    ### Example

    - Use:
    ``` javascript
    const fruitColor = {
        red: ['apple', 'strawberry'],
        yellow: ['banana', 'pineapple'],
        purple: ['grape', 'plum']
    };

    return fruitColor[color] || [];
    ```
    - Or:
    
    ``` javascript
    const fruitColor = new Map()
        .set('red', ['apple', 'strawberry'])
        .set('yellow', ['banana', 'pineapple'])
        .set('purple', ['grape', 'plum'])

    return fruitColor.get(color) || [];
    ```

    - Instean of:
    ``` javascript
    if (color === 'red'){
        return ['apple', 'strawberry'];
    }
    else{
        if (color === 'yellow'){
            return ['banana', 'pineapple'];
        }
        else{
            if (color === 'purple'){
                return ['grape', 'plum'];
            }
            else{
                return [];
            }
        }
    }
    ```

    ref: https://scotch.io/bar-talk/5-tips-to-write-better-conditionals-in-javascript