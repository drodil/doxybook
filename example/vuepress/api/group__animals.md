
# Group animals


[**Modules**](modules.md)
 **>** [**animals**](group__animals.md)



_This is a brief description to the animals group._ [More...](#detailed-description)







## Files

| Type | Name |
| ---: | :--- |
| file | [**config.h**](config_8h.md) <br>_This is a config file._  |




## Classes

| Type | Name |
| ---: | :--- |
| class | [**example::Animal**](classexample_1_1_animal.md) <br>_Base class for all animals from which_ [_**Bird**_](classexample_1_1_bird.md) _derives._ |
| interface | [**example::AnimalInterface**](classexample_1_1_animal_interface.md) <br> |
| class | [**example::Bird**](classexample_1_1_bird.md) <br> |
| class | [**example::CustomException**](classexample_1_1_custom_exception.md) <br> |
| class | [**example::NumericException**](classexample_1_1_numeric_exception.md) <br> |
| class | [**example::SpecialBird**](classexample_1_1_special_bird.md) <br> |

## Public Types

| Type | Name |
| ---: | :--- |
| enum  | [**example::Animal::Type**](classexample_1_1_animal.md#enum-type)  <br>_The 6 classes of animal kingdom._  |




## Public Functions

| Type | Name |
| ---: | :--- |
|  void | [**some\_global\_function**](animal_8h.md#function-some-global-function) ([**example::Animal**](classexample_1_1_animal.md) \* animal) <br>_Some random global function that modifies Animal._  |
|  void | [**example::some\_namespace\_function**](namespaceexample.md#function-some-namespace-function) ([**Animal**](classexample_1_1_animal.md) \* animal) <br>_Some random namespace function that modifies_ [_**Animal**_](classexample_1_1_animal.md) _._ |







## Macros

| Type | Name |
| ---: | :--- |
| define  | [**CONFIG\_HELLO**](config_8h.md#define-config-hello)  () (123)<br> |
| define  | [**CONFIG\_WORLD**](config_8h.md#define-config-world)  () ("abx")<br> |
| define  | [**PI**](config_8h.md#define-pi)  () (3.14159265358979323846)<br> |

## Public Types Documentation


### enum Type 


```cpp
enum example::Animal::Type {
    **NONE** = 0,
    **INSECT** = 1,
    **AMPHIBIAN** = 2,
    **BIRD** = 3,
    **FISH** = 4,
    **REPTILE** = 5,
    **MAMMAL** = 6
};
```


Lorem Ipsum Donor. 


        
## Public Functions Documentation


### function some\_global\_function 


```cpp
void some_global_function (
    example::Animal * animal
) 
```




**See also:** Animal 


**Parameters:**


* **animal** The pointer to the animal instance 




        

### function some\_namespace\_function 


```cpp
void example::some_namespace_function (
    Animal * animal
) 
```




**See also:** [**Animal**](classexample_1_1_animal.md) 


**Parameters:**


* **animal** The pointer to the animal instance 




        ## Macro Definition Documentation



### define CONFIG\_HELLO 


```cpp
#define CONFIG_HELLO () 
```



### define CONFIG\_WORLD 


```cpp
#define CONFIG_WORLD () 
```



### define PI 


```cpp
#define PI () 
```



------------------------------