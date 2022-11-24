##Data Format##

This document specifies how data is formatted in data.json. This is subject to change.


Number codes (replace "NUMBER"):
-3 - Does not result in a crash, but nonetheless very incompatible
-2 - Some features are lost, see description if any
-1 - Completely incompatible under all circumstances, results in a crash
0 - No data
1 - Completely compatible
2 - Mostly compatible, see description


```json
{
    "MODNAME" : {
        "MODNAME": {"compatible": NUMBER, "description": "Lorem Ipsum"},
        "MODNAME": {"compatible": NUMBER, "description": "Lorem Ipsum"}
    },
    "MODNAME" : {
        "MODNAME": {"compatible": NUMBER, "description": "Lorem Ipsum"},
        "MODNAME": {"compatible": NUMBER, "description": "Lorem Ipsum"}
    }
}```