# **DevOps-Pre-Requisites**
This repository provides all the materials needed to get started with the fundamentals of DevOps.

## Basics to YAML
#### YAML file is used to represent data, in this case it is configuration data

#### Here are the list of Data in different formats:
**_XML_**
```
<Servers>
    <server>
        <name>Server1</name>
        <created>12345</created>
        <owner>Bhavya</owner>
        <status>active</status>
    </server>
</Servers>
```
**_JSON_**
```
{
    Servers: [
        {
        name: Server1,
        owner: Bhavya,
        created: 12345,
        status: active,
        }
    ]
}
```

**_YAML_**
```
Servers:
    -   name: Server1
        owner: Bhavya
        created: 12345
        status: active
```
1. <code>Key-Value Pair</code> 
#### YAML is represented in key-value pair. Seperated by the colon (:)
##### Below is an example of YAML syntax in key-value pair

```
name: Server1
owner: Bhavya
created: 12345
status: active
```

#### Here the keys are "Name, owner, created & status"
#### Values are "Server1, Bhavya, 12345 & active"

#### Key Notes:
- It should always be represented with Key & Value. 
- You must have space followed by the colon (:), to differentiate between the key and values.



2. <code>Array/List</code>

#### Here is an Example of How <code>Array/List</code> looks like:
```
Fruits:
-   Orange
-   Banana
-   Grapes

Vegetables:
-   Tomato
-   Carrots
-   Cauliflower
```

##### NOTE: Here in the above example the dash it is an element of an Array.

2. <code>Dictionary</code>
