## - Monday
1. https://www.codewars.com/kata/5266876b8f4bf2da9b000362
2. https://www.codewars.com/kata/526571aae218b8ee490006f4
3. https://www.codewars.com/kata/54b724efac3d5402db00065e

## - Tuesday
1. https://www.codewars.com/kata/55c45be3b2079eccff00010f
2. https://www.codewars.com/kata/54bf1c2cd5b56cc47f0007a1 
3. https://www.codewars.com/kata/520b9d2ad5c005041100000f

## - Wednesday
1. https://www.codewars.com/kata/52774a314c2333f0a7000688
2. https://www.codewars.com/kata/517abf86da9663f1d2000003
3. https://www.codewars.com/kata/54e6533c92449cc251001667

## - Thursday
1. https://www.codewars.com/kata/57ea70aa5500adfe8a000110
2. https://www.codewars.com/kata/5848565e273af816fb000449
3. https://www.codewars.com/kata/53368a47e38700bd8300030d

```sh
function list(names){
  var result;
  if (names.length === 0) { result= ''; }
  else if(names.length === 1) { result = names.map(p=>p.name).join(); }
  else {
    result = names.map(p=>p.name);
    result = result.slice (0, names.length-1).join(', ')+' & '+names[names.length-1].name;
  }
  return result;
}
```

4. www.linkedin.com/in/ekaterinagbondareva
