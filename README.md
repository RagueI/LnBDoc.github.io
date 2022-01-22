# Hierarchy 

> An awesome project.

---


# Manager
## `static` GameRuleManager
> ### Description
> This is description
> > `singleton`

> ### Properties

> ### Functions
---



## MonoBehaviour
> ### Description

> ### Properties

> ### Functions
---



## `abstract` Card 

> ### Description
> This is an abstract class

<br>

> ### Properties

> #### public 
> **string**
>> ##### [CARD_NAME](Card.Properties/CARD_NAME.md)
>> ##### [CARD_DESCRIPTION](Card.Properties/CARD_DESCRIPTION.md)
>> ##### [CARD_ROLE](Card.Properties/CARD_ROLE.md)
>> ##### [CARD_TAG](Card.Properties/CARD_TAG.md)
>> ##### [CARD_IMAGE](Card.Properties/CARD_IMAGE.md)
>
> **bool**
>> ##### [IN_SET](Card.Properties/IN_SET.md)
>> ##### [IN_HAND](Card.Properties/IN_HAND.md)
>> ##### [CARD_USAGE_LIMIT](Card.Properties/CARD_USAGE_LIMIT.md)
>
> **int**
>> ##### [CARD_INDEX_IN_SET](Card.Properties/CARD_INDEX_IN_SET.md)
>
> **enum**
>> ##### [CARD_CONDITION](Card.Properties/CARD_CONDITION.md)
>> ##### [CARD_CATEGORY](Card.Properties/CARD_CATEGORY.md)
>> ##### [CARD_SUBCATEGORY](Card.Properties/CARD_SUBCATEGORY.md)



> #### private
<br>


> ### Functions
>> #### Virtual Functions
>>
>>> ##### [DebugThis()](Card.Properties/VirtualFuntion.md)



> ### SubClasses
  - #### [CardInHand](Card.Properties/CardInHand.md)
  - #### [CardNotInHand](Card.Properties/CardNotInHand.md)
  - #### [CounterCard](Card.Properties/CounterCard.md)
  - #### [FieldCard](Card.Properties/FieldCard.md)
  - #### [ItemCard](Card.Properties/ItemCard.md)
  - #### [RegularCard](Card.Properties/RegularCard.md)
  - #### [WeaponCard](Card.Properties/WeaponCard.md)
---





## `abstract` Character

> ### Description
> This is an abstract class

<br>

> ### Properties
> #### public
> **string**
>> ##### [CHARACTER_NAME](Character.Properties/CHARACTER_NAME.md)

>
> **int**
> >> ##### [CHARACTER_HP](Character.Properties/CHARACTER_HP.md)
>> ##### [CHARACTER_DRAW_COUNT](Character.Properties/CHARACTER_DRAW_COUNT.md)
>> ##### [CURRENT_CARD_COUNT](Character.Properties/CURRENT_CARD_COUNT.md)
>> ##### [CARD_SAVE_COUNT](Character.Properties/CARD_SAVE_COUNT.md)
>> ##### [CURRENT_POSITION](Character.Properties/CURRENT_POSITION.md)

>
>**Skill**
>> ##### [skill]()
>
>**enum**
>> ##### [status](Character.Properties/status.md)





> ### Functions
>> #### Virtual Function
>>
>>> ##### [DebugThis()]()
---



## Deck

> ### Description

> ### Properties

> ### Functions

---


## Set

> ### Description

> ### Properties

> ### Functions

---


## Skill

> ### Description

> ### Properties

> ### Functions

---