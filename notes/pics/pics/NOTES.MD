# 2OPTIONS FOR AJAX /NETWORK REQ:

- axios & fetch
- fetch has much lines of code and we have to do much work which is already implemented in axios

- npm i axios

- use axios.get for get req. and it takes 2 params
- 1. path or address and 2. an object

- eg: adding an object -> headers :{}
- params:{ query : term } - an object which takes different query string parameters
- all this is win the object ie. 2nd argument in axios !!

- cors error -> there will be 2 requests when 1 req is sent from code.

- axios.get() -> returns a promise.
- also make await keyword.
