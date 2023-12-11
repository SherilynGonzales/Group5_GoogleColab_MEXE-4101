<div align="center">
  
# Group5_GoogleColab_MEXE-4101

</div>

## Lists, Tuples, Sets and Dictionaries

### 1) List
> Example 1
>
    #List - ordered sequence of elements, always uses [] to represent the list. Each item is seperated by ,.

    food = ["pizza","burger","rice", "noodles"]
    print(food)
>
    ['pizza', 'burger', 'rice', 'noodles']
> Example 2
>
    print(food[0])
>
    pizza
>
> Example 3
>
    #to add element in list
    food.append("cake")
    print(food)
>
    ['pizza', 'burger', 'rice', 'noodles', 'cake']
> Example 4
    food.append("sandwhich")
    print(food)
>
    ['pizza', 'burger', 'rice', 'noodles', 'cake', 'sandwhich']
> Example 5
> 
    food.extend(["sandwhich","pasta"])
    print(food)
>
    ['pizza', 'burger', 'rice', 'noodles', 'cake', 'sandwhich', 'sandwhich', 'pasta']
> Example 6
>
    food.extend(["sandwhich","pasta"])
    food
>
    ['pizza',
     'burger',
     'rice',
     'noodles',
     'cake',
     'sandwhich',
     'sandwhich',
     'pasta',
     'sandwhich',
     'pasta']
> Example 7
>
    print(food*2)
>
    ['pizza', 'burger', 'rice', 'noodles', 'cake', 'sandwhich', 'sandwhich', 'pasta', 'sandwhich', 'pasta', 'pizza', 'burger', 'rice', 'noodles', 'cake', 'sandwhich', 'sandwhich', 'pasta', 'sandwhich', 'pasta']
>Example 8
>
    food + ["coffee","tea"]
    food
>
    ['pizza',
     'burger',
     'rice',
     'noodles',
     'cake',
     'sandwhich',
     'sandwhich',
     'pasta',
     'sandwhich',
     'pasta']
