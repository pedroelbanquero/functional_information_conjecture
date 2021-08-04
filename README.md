# Functional information conjecture

Information analisis from point of view of encodig data without lose with function who generates the data instead of precise representation of the reality in bits.

As Kurt Gödel demonstrates many decades ago for different porpouses, information , or mathemathical expressions can be transformated as a unique numero who represents the information. Godel develops a method to describe a mathematical expresion (function) in a numer. Assuming this method is the first functional encoding method Godel is the father of functional encoding.

![image](https://user-images.githubusercontent.com/60758685/127950816-c8e399c9-a6b6-4f2b-a75e-10971622196b.png)


## The information theory

The traditional information theory assumes for encoding information is mandatory repesented as a minimal expresion of information, the Bit . Like any infomration as the theory demonstrates have a limitation to be represented in bits by  the frequency of the simbols and the order who composes a chunk of information, this theory is limited just to represent information with no loses exactly as you observe. The best way ro encode the information is always in a bits , chosing as a bit simbol 2^e where that is at least equal to the symbol numers. Another compresion techniques can improve the way to save data with no loses , like LZ + hufman encoding, defalte , br, etc ...

![image](https://user-images.githubusercontent.com/60758685/127951514-25b754dd-2a59-4cd0-b655-d23a56e96db5.png)

In the traditional information theory, the Entropy of the data defines the limits of the encoding .
In traditional information theory, you encode the information as you observe.

## A functional point of view of the information

In a functional information conjecture the information is not the result of a event who generates the information. We can consider from a functional point of view than the information is the function who generates the data and not viceversa.

Of course in a observable information is easy observe and save the information as the same way you observe, but in a a point of view of a funciontal encoding we have the challange to know the function, or group of functions who composes a dataset of information.

Gödel in his exercise to develop a system to represent mathematical expresions (functions) in numbers, choosed a semiprimes for his properties, they are uniques and just can be decomposed in unique symbols , the Prime numbers.

Gödel specifically used this scheme at two levels: first, to encode sequences of symbols representing formulas, and second, to encode sequences of formulas representing proofs. This allowed him to show a correspondence between statements about natural numbers and statements about the provability of theorems about natural numbers, the key observation of the proof

Another big genius , Christian Goldbach wrote a letter to Leonhard Euler as a result of GoldBach conjecture, discovering any pair number can be represented at least by 2 primes.

Then any semiprime can be represated as a sum of 2 primes and the goldbach permutation order.

If we take as a example 377, 13+29 = 42 in consecuence we can encode asume 377 = (42,2) , the sum of factors of the product and the glodbach permutation order, in this case 12 29 is the thir glodbach combination who can get 42 as a result. (sum of 2 primes) .

As we can see this information transoformation can reduce the number of bits, (symbol/frequency) needed to represent information. Any time anybody try to encode information based on the observability of the informatoin is not posible reduce the number of necesary bits by the traditional information theory demonstration.

Information is like the energy in the model of traditional information theory, the information base in the observability.

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

If the time space between each element of the data set is the same, we can assume f = n+1 function information is inside the dataset, just no way to extract the information is known more the know extrapolations methods.

### f 1 [1,2,3,4] = 5

## A real way to encode functions 

In 2021 was published in wikipedia and haskell official repositories and operating system NIX, the Probnet.

Probnet description and code source can be found here. https://hackage.haskell.org/package/Probnet https://en.wikipedia.org/wiki/Extrapolation


## The role of time in functional encoding

When we would to encode the function (f n =n+1) from the information of a dataset, we can assume that the "time" of the result is the next element or the back element of the dataset, in a 1 dimension object just past present and future are posible, and the time can just walk around 2 directions, "left or right" , past or future, because the information represents the present,

When the time or space is geometric we can predict the result with 100 % accuracy, making posible encoding system based on the function information int the dataset.

As V.Nos and E. Satntos demontrates with Probnet. Around 1/3 of the know functions from oeis.org database (the known functions) .

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

m = last sequence

n = last $ last sequence 

### x = fnos (m,n,d1,d2) = round ( ( ( n * d1 ) - m ) + ( m * d2  ) )

### If x  == next out sequence, then :

### H (t, (a b c d) ) <  H (N) 


- It is possible that the entropy of the functional coding is much smaller than the entropy of the observable information. From the point of view of traditional information theory. o Shannon's entropy, in an observable encoding  .

- At least to describe around the 30 % of the know function universe, and a big percentage of the geometric uncertain can be defined by a probnet funcion, and can be encoded with 5 parameters.

- Encode saving number of executions of a function and 4 elements of dataset is the minimum information needed in geometric extrapolation with error prediction, to calculate pasts and futures n times.

- The information theory based on the observability of the data and on the faithful reproduction of the same does not contemplate the information, geometric, polynomial or arithmetic where the time of each element of the dataset is constant 

- Two kind of encoding types are posible :

  - Encoding based on observable data.
  
  - Encoding based on functions and time, who generate the observable data set.
   

## 2D and 3D spaces

In the pure information in a functional enconding just can have 1 dimension in the information vector .

In a 1 dimesion information vector the order is the second dimension.

In a 1 information vector where the order is the second dimension, the contraction of the time/space is the third dimension



