# EjerciciosComplejidad

## 1.
    repeatedChars(srt1, str2)
     word = ''
     for each c1 in str1
     for each c2 in str2
      if c1 == c2
        Adicionar c1 a word
        break(the cicle)
     return word

Este algoritmo actualmente tiene una complejidad temporal de **O(n*m)**y una complejidad espacial de **O(n)**

## 2.
    findLongestWordLength(str)
     longestWordSize = 0
     arr = split str (get each word)
     for each word in arr
      if word.length > longestWordSize
       longestWordSize = word.length
    
    return longestWordSize

Este algoritmo actualmente tiene una complejidad temporal de **O(n+m)**y una complejidad espacial de **O(n)**

## 3.
    sort(arr)
     arrSort = arr
     i = 1
     while i < arrSort.length
      num = arrSort[i]
      j = i - 1
      while j >= 0 and arrSort[j] > num
       arrSort[j+1] = arrSort[j]
        j = j - 1
    
     arrSort[j+1] = num
     i = i + 1
    
    return arrSort 

Este algoritmo actualmente tiene una complejidad temporal de **O(n^2)**y una complejidad espacial de **O(n)**

## 4.
    Anagram (str1, str2)
     If str1.length != str2.length
      Return false
     word = ''
     for each c1 in str1
      for each c2 in str2
       if c1 == c2
        Adicionar c1 a word 
        Remove c2
        break(the cicle)
    
    return word == str1

Este algoritmo actualmente tiene una complejidad de **O(n*m)**y una complejidad espacial de **O(n)**

## 5.
    tictactoe (matrix)
     if element in row1 are equal || element in row2 are equal || element in row3 are equal
      return true
    
     else if element in column1 are equal || element in column2 are equal || element in column3 are equal 
      return true
    
     else if element in pos\[0\][0], pos\[1\][1], pos\[2\][2] are equal || if element in pos\[0\][2], pos\[1\][1], pos\[2\][0] are equal
      return true
    
     else
      return false

Este algoritmo actualmente tiene una complejidad de **O(n)**y una complejidad espacial de **O(n)**

