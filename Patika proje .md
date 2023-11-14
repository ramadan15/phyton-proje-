# Patika phyton projesi 

## Bu projede fonksiyonlarla alakalı ödevimi yükledim 

- herhangi bir listeyi flatten listeye çevirmek için aşağıdaki adımlarla gidilir
``` def flat(liste):
    flatten=[]
    for l in liste:
    if type(l)!= list:
          flatten.append(l)
          
    else:
         flatten.extend(flat(l))
         return flatten
````
- verilen listedeki elemanları tersine çevirebilen fonksiyonu şu şekilde yazabiliriz 

````
   def reverse(l):
       l.reverse()
       for i in l:
           if type(i)==list:
               i.reverse()
       return(l)
  ````
  
  
       


```python

```

    [[56, 129, 23], 125, 345, 125, 224, 109, 10, 6, 2]



```python

```
