# currencyrate
JavaScript library for currencyrate.today
# main
```js
async function main(){
    const {currencyrate} = require('./currencyrate');
    const rates= new currencyrate();
    let req=await rates.latest_rates()
    console.log(req)
}
main()
```
