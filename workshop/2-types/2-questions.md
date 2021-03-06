# Types

## Question 1: Which of the following strings are valid? Add an 'x' between the ( ) to indicate that it's valid.

1. ( ) "I am a "Horse""
2. ( ) "I 'prefer' ducks'
3. (X) 'Yes, duck is nice'
4. (X) "Ah, but I\'m vegan!"
5. ( ) 'You'll eat salad then'
6. (X) 'Yes I\'ll eat salad'
7. (X) "I'm happy to hear that!"
8. (X) "\"Happy to hear " + 'that" ' + "he says!"
9. ( ) “Hello world!”


## Question 2: Rewrite below all of the strings that are not valid, and correct them to make them valid. 
"I am a \"Horse\""
"I 'prefer' ducks"
'You\'ll eat salad then'
'Hello world!'


## Question 3: Which of the following expressions are true? Add an 'x' between the ( ) to indicate that it's true.

1. ( ) 7 == 2
2. (X) 7 == 7
3. (X) 7 == '7'
4. (X) 7 != 0
5. (X) 7 !== '7'
6. ( ) 7 != '7'
7. ( ) 7 != 7


## Question 4: Which of the following expressions is/are truthy?

1. (X) !0
2. ( ) !1
3. (X) -1
4. ( ) !"hello!"
5. ( ) null
6. (X) !undefined
7. (X) !NaN


## Question 5: Which of the following are valid objects?

1. (X) {}
2. (X) { 'hello' }
3. (X) { name: 'I am fruit' }
4. (X) {'brand-name': 'Dior' }
5. ( ) { brand-name: 'Channel' }
6. (X) { cool_name: 'bob' + ' Dylan', age: 25 }


## Question 6: For each array, specify the number of elements and the type of each element.

1. ['cat', 'dog', 'bird']
    - number of elements: 3
    - type of _each_ element:
        - 'cat': string
        - 'dog': string
        - 'bird': string

2. [[], 24, 'hello', true]
- number of elements: 4
    - type of _each_ element:
    []:array
    24: number
    'hello': string
    true: boolean

3. []
- number of elements: 0
    - type of _each_ element:

4. [['romeo', 'juliet'], false]
- number of elements: 2
    - type of _each_ element:
    []:array
    false: boolean

5. [{name: 'bob', age: 23}, {name: 'paul', age: 33}]
- number of elements: 3
    - type of _each_ element:2
    {}:object
    {}:object


## Question 7: What is the type and value for each of the following variables?

1. let  name = 'bob';
    - type: string
    - value: 'bob'

2. let age = 45;
    - type: number
    - value: 45

3. let isMarried = false;
    - type: boolean
    - value: false

4. let person = { name: name, age: age, isMarried: isMarried }
    - type: object
    - value: name: name, age: age, isMarried: isMarried 

5. let kids = [{name: 'Morty', age: 3}, {name: 'Summer', age: 7}]
    -type: array
    value: {name: 'Morty', age: 3}, {name: 'Summer', age: 7}
