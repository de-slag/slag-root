# slag-root

## Principles
* KISS - Keep it simple, stupid
* SoC - Separate of concern
* FCoI - Favor Composition over Inheritance
* LoD - Daw of Demeter, "don't talk to strangers"
* YAGNI - You aint gonna neet it

## Pattern Language
|Pattern|Description|
|-------|-----------|
|Service|interface for business logic|
|ServiceImpl|implements Service, not directly referenceable|
|Utils|static business logic|
|Factory|creates a bean, may be an interface|
|FactoryImpl|implements Factory, not directly referenceable|
|Dao|interface for database persistence logic|
|DaoImpl|implements Dao, not directly referenceable|
