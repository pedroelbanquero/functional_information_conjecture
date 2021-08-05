# Functional information conjecture

Information analisis from point of view of encodig data without lose with function who generates the data instead of precise representation of the reality in bits.

As Kurt Gödel demonstrates many decades ago for different porpouses, information , or mathemathical expressions can be transformated as a unique nummber who represents the information. Godel develops a method to describe a mathematical expresion (function) in a number. Assuming this method is the first functional encoding method Godel is the father of functional encoding.

![image](https://user-images.githubusercontent.com/60758685/127950816-c8e399c9-a6b6-4f2b-a75e-10971622196b.png)


## The information theory

The traditional information theory assumes for encoding information is mandatory repesented as a minimal expresion of information, the Bit . Like any infomration as the theory demonstrates have a limitation to be represented in bits by  the frequency of the simbols and the order who composes a chunk of information, this theory is limited just to represent information with no loses exactly as you observe. The best way ro encode the information is always in a bits , chosing as a bit simbol 2^e where that is at least equal to the symbol numers. Another compression techniques can improve the way to save data with no loses , like LZ + hufman encoding, defalte , br, etc ...

![image](https://user-images.githubusercontent.com/60758685/127951514-25b754dd-2a59-4cd0-b655-d23a56e96db5.png)

In the traditional information theory, the Entropy of the data defines the limits of the encoding .
In traditional information theory, you encode the information as you observe.

## A functional point of view of the information

In a functional information conjecture the information is not the result of a event who generates the information. We can consider from a functional point of view than the information is the function who generates the data and not viceversa.

Of course in a observable information is easy observe and save the information as the same way you observe, but in a a point of view of a funciontal encoding we have the challange to know the function, or group of functions who composes a dataset of information.

Gödel in his exercise to develop a system to represent mathematical expresions (functions) in numbers, choosed a semiprimes for his properties, they are uniques and just can be decomposed in unique symbols , the Prime numbers.

Gödel specifically used this scheme at two levels: first, to encode sequences of symbols representing formulas, and second, to encode sequences of formulas representing proofs. This allowed him to show a correspondence between statements about natural numbers and statements about the provability of theorems about natural numbers, the key observation of the proof

Another big genius , Christian Goldbach wrote a letter to Leonhard Euler as a result of GoldBach conjecture, discovering any pair number can be represented at least by sum of 2 primes.

Then any semiprime can be represated as a sum of 2 primes and the goldbach permutation order.

If we take as a example 377, 13+29 = 42 in consecuence we can encode asume 377 = (42,2) , the sum of factors of the product and the glodbach permutation order, in this case 12 29 is the thir glodbach combination who can get 42 as a result. (sum of 2 primes) .

As we can see this information transoformation can reduce the number of bits, (symbol/frequency) needed to represent information. Any time anybody try to encode information based on the observability of the informatoin is not posible reduce the number of necesary bits by the traditional information theory demonstration, because when you win in some case a bits, in others you lose.

Information is like the energy in the model of traditional information theory, the information based on the observability.

As no way is know more than check all know funcions to define datasets from data bases like oeis.org or wolframalpha.com . Is not posible in a practice do this task in a efficient computation cost, finding the better functions to represent information in the computation time. By other part, the most of the data in the entropy of the reallity, the known functions are a really small percentage of the uncertain. This makes imposible base a system to encode data in functions ?

## Artificial intelligence

Artificial intelligence based on linear regresions aproximates results of funciontions generating functions from models.

A model can be used in the AI network to apply the "learned" function.

Any AI have two main properties.

- Can generate information from input data source aplying the model (the function learned)
- Can filter information from a input parsing the criteria who aomplish the model (the funcion learned)

For now all known "AI" methods are based in train models to aproximate the functions who composees a information dataset.

Artificial intelligence methods can't be used to encode data because the output of the data is not accurated to the reallity. This make imposible use for encodin with no information loses .

## How should be a functional encoding method

- A functional encoding method have be unique anotation for each different message of information, otherwise the same data can't be distingued one from other.

- The starting moment of a function (SM)

- The length of the dataset (LD)

- A unique representation of the function (A B C D)

- A computational advantages in bit size of the encoded information

f LD (A=SM) B C D..) = Next Out Sequence | Back Out Sequence

In the sequence [1,2,3,4], we can observe we have:
  
### f n = n+1

If the time space between each element of the data set is the same, we can assume f = n+1 function information is inside the dataset, just no way to extract the information is known more the know extrapolations methods. https://en.wikipedia.org/wiki/Extrapolation

### f 1 [1,2,3,4] = 5

## A real way to encode functions 

In 2021 was published in wikipedia and haskell official repositories and operating system NIX, the Probnet.

Probnet description and code source can be found here. https://hackage.haskell.org/package/Probnet


## The role of time in functional encoding

When we would to encode the function (f n =n+1) from the information of a dataset, we can assume that the "time" of the result is the next element or the back element of the dataset, in a 1 dimension object just past present and future are posible, and the time can just walk around 2 directions, "left or right" , past or future, because the information represents the present,

When the time or space is geometric we can predict the result with 100 % accuracy, making posible encoding system based on the function information int the dataset.

As V.Nos and E. Santos demontrates with Probnet. Around 1/3 of the know functions from oeis.org database (the known functions) .

The probability of solve just with a funcional encoding a dataset is 1 / 3, this means what around 1 / 3 of the known universe is perfectlly probnet, you can define the funcion with 3 fraction parameters, the starting point, and the numer of function time, or function space, defined by the math expresion function.

By this way we can encode 

### [n .. n + x]

with 3 consecutive fractions of the present, the starting time, and numer of loops in the space.

for example to encode 100 numbers of fibonachi secuence , we can encode :

```
100,1,2,3,5
```

is better than :

```Haskell

*Probnet> probnet 100 [1,2,3,5]

[1,2,3,5,8,13,21,34,55,89,144,233,377,610,987,1597,2584,4181,6765,10946,17711,28657,46368,75025,121393,196418,317811,514229,832040,1346269,2178309,3524578,5702887,9227465,14930352,24157817,39088169,63245986,102334155,165580141,267914296,433494437,701408733,1134903170,1836311903,2971215073,4807526976,7778742049,12586269025,20365011074,32951280099,53316291173,86267571272,139583862445,225851433717,365435296162,591286729879,956722026041,1548008755920,2504730781961,4052739537881,6557470319842,10610209857723,17167680177565,27777890035288,44945570212853,72723460248141,117669030460994,190392490709135,308061521170129,498454011879264,806515533049393,1304969544928657,2111485077978050,3416454622906707,5527939700884757,8944394323791464,14472334024676222,23416728348467688,37889062373143912,61305790721611600,99194853094755520,160500643816367136,259695496911122656,420196140727489792,679891637638612480,1100087778366102272,1779979416004714752,2880067194370817024,4660046610375531520,7540113804746347520,12200160415121876992,19740274219868221440,31940434634990092288,51680708854858301440,83621143489848360960,135301852344706596864,218922995834554843136,354224848179261276160,573147844013815824384,927372692193076576256,1500520536206891548672,2427893228399967076352,3928413764606857052160]

```
## Conclusions

### Where :

sequence = [a,b,c,d,x,x1,x2,x3,x4,x5....]

### And:

f1(x,y) =  (x) / y

### Get

d1 = f1 (c,b)

d2 = f1 (d,c)

md = divisor (if is not modular == 1 )

r = radiant (arc longitude)


### x = fnos (c,d,d1,d2) =  cos OR sin ( r  ( round ( ( ( c * d1 ) - d ) + ( d * d2  ) ) (DivMod) md ) )

### If x  == next out sequence, then :

### H (t, (a b c d) ) <  H (N) 


- It is possible that the entropy of the functional coding is much smaller than the entropy of the observable information. From the point of view of traditional information theory. o Shannon's entropy, in an observable encoding  .

- At least to describe around the 30 % of the know function universe, and a big percentage of the geometric uncertain can be defined by a probnet funcion, and can be encoded with 5 parameters.

- Encode saving number of executions of a function and 4 elements of dataset is the minimum information needed in geometric extrapolation with error prediction, to calculate pasts and futures n times.

- The information theory based on the observability of the data and on the faithful reproduction of the data does not contemplate the information, geometric, polynomial or arithmetic where the time of each element of the dataset is constant. In this case the entropy of the data of the function is less thant the entropy of the dataset. 

- Two kind of encoding types are posible :

  - Encoding based on observable data.
  
  - Encoding based on functions and time, who generate the observable data set.

- Observable data in functional sequences can be converted and encoded as a NOS function when is defined by combitanions of:
  
  - Exponents (Logarithmic)
  - Sumatory / Rest (Arithmetic)
  - Product / Divisions (Geometric)
  - Polinomy x degree
  - Modular (Modular Arithmetic) (Not implementet in probnet yet)
  

## Functional encoding layers

Where a dataset is:

```

*Probnet> probnet 100 [2,4,6,8]
[2,4,6,8,10,12,14,16,18,20,22,24,26,28,30,32,34,36,38,40,42,44,46,48,50,52,54,56,58,60,62,64,66,68,70,72,74,76,78,80,82,84,86,88,90,92,94,96,98,100,102,104,106,108,110,112,114,116,118,120,122,124,126,128,130,132,134,136,138,140,142,144,146,148,150,152,154,156,158,160,162,164,166,168,170,172,174,176,178,180,182,184,186,188,190,192,194,196,198,200,202,204,206,208]


[*Probnet> probnet 100 [1,2,3,4]
1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27,28,29,30,31,32,33,34,35,36,37,38,39,40,41,42,43,44,45,46,47,48,49,50,51,52,53,54,55,56,57,58,59,60,61,62,63,64,65,66,67,68,69,70,71,72,73,74,75,76,77,78,79,80,81,82,83,84,85,86,87,88,89,90,91,92,93,94,95,96,97,98,99,100,101,102,103,104]


-- Both zipped

[1,2,2,4,3,6,4,8,5,10,6,12,7,14,8,16,9,18,10,20,11,22,12,24,13,26,14,28,15,30,16,32,17,34,18,36,19,38,20,40,21,42,22,44,23,46,24,48,25,50,26,52,27,54,28,56,29,58,30,60,31,62,32,64,33,66,34,68,35,70,36,72,37,74,38,76,39,78,40,80,41,82,42,84,43,86,44,88,45,90,46,92,47,94,48,96,49,98,50,100,51,102,52,104,53,106,54,108,55,110,56,112,57,114,58,116,59,118,60,120,61,122,62,124,63,126,64,128,65,130,66,132,67,134,68,136,69,138,70,140,71,142,72,144,73,146,74,148,75,150,76,152,77,154,78,156,79,158,80,160,81,162,82,164,83,166,84,168,85,170,86,172,87,174,88,176,89,178,90,180,91,182,92,184,93,186,94,188,95,190,96,192,97,194,98,196,99,198,100,200,101,202,102,204,103,206,104,208]



```

We can encode merged funcional datasets as two function symbols

```

A,100,1,2,3,4

B,100,2,4,6,8

100,A,B


```

## Functional encoding and dimensions, vector processing

With a n dimensions vector , extract n element to grup them by order

Process each 1 dimision vector with probnet

Join in a viceversa process the data to the original state.

```

[(1,2),(2,2),(3,3),(4,4)]

-- convert  to 

[[1,2,3,4],[1,2,3,4]]

-- predict next of each one

probnet 1 [1,2,3,4]

5

probnet 1 [1,2,3,4]

5

-- add to the result

[(1,2),(2,2),(3,3),(4,4),(5,5)]



```

## Classes of functional encoding

- When the encoding represents a function with his operators (Godel Encoding)

- Whe the encoding represents a function with part of information with engouth operators information to generate de information from the funcion by mathematical operations, can be extrapolated (Nos)

## Data as a final point of a sequence

- If all numbers can be generated as a mathematical expresion. 

- Any information can be represented as a number

- Any number can be represented by the distance to a nos function , loops param1 param2 param3

- When the distance of the information to a nearest probnet function the information can be encoded outside entrooy of shannon.

### if (bit loops+bit p1+bit p2+bit p3) operator distance < (bit N) : H (fnos,op,distance) < H (N)

   
## Data as a result of 2 probnet functions operations


## information = ( probnet l1 [a,b,c] )

## Geometric mnemonic time regression, Back to the Future Algorithm

### Encode

- Search de low degree nearest Polinomy .

- Turn x back n until near number the square of information.

- Get the difference from the point to information

- Use as the last point x less the calculated diference

- Compute time of the information, until 1

- encode loop times , last 3 points until 1

- Do the same with the next information

### Decode

- Parse each element as a probnet inputs.

## Conclusion

- Any information can be represented as a polinomy, any polinomy is a function that can be taken to the past .

- When the numer of times to arrive to the first past 1 of any posible serie in the infinite solutions is less than the information, then the information can be encoded with encoding benefits than traditional information theory ways.

- When extract the information of the funcion of a polinomy is posible, the geometric regresion to the past will be probnet calculable. In consecuence the first expresion of the function with the first information posible to generate the funcion will have less entropy than the original information, in traditional information point of view.

- For each type of function who can extract the information about the funcion from observable will be have a funcional encoding method

- As more functioncs can solve the generator function , better performance is posible to obtain depending .

- The information have a functional estructure, when you observe as a the function who generates the observable information

- The minimum functional representation of any information is the reprsentation as a funcion composet by time and 3 conseecutive parameters of the dataset.

- The minimum entropy to encode information is :

### H (probnet n+..)

- Entropy is not a valid mesure to define how encodeable is the information. 

- Any information can be represented as a function of :
  - times
  - 3 time/space , past, present and future

  ## Functional Information = fns times past present future
  
- As the number field, informations is made by unique "symbols" who expands them in N consecutivie replies in the time expansion over complex plane.

- Any number can be encoded in a time space function , 1 parameter for time and 3 parameters for the "space", past, present, future

  
## Usage

```

ns_encode (C.pack "sentense data")

ns_decode data

```


## Computacion Costs

...

## Authors

V.Nos

E.Santos

All rights are reserved. Any use of this documentation for commercial porpouses is forbidden. Pleas contact with vnos@blackhole.consulting



