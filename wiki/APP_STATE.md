# App State
## database collections:
#### users
```
{
  _id: "598296cd172824a3e8d0d5e4",
  userName: "Santa",
  email: "santa@noggish.com",
  iconUrl: "../src/img/Santa_profile.jpg"
}
```

#### nogtypes
```
{
  _id: "598254b7172824a3e8d0d5d7",
  name: "snowflake",
  version: "1.0",
  description: "the original snowflake",
  numLights: 30,
  iconUrl: "src/img/nogTypes/snowflake_1.0.png"
}
```

#### userpatterns
```
{
  _id: "59e38df1fc6b720012a49e41",
  name : "Rudolph's revenge",
  description: "Inspired by Rudolph's nose, this bright pattern will guide your sled through any foggy Christmas eve.",
  userId: "598296cd172824a3e8d0d5e4",
  defaultSpeed: 50,
  defaultColor: "",
  nogTypeId: "598254b7172824a3e8d0d5d7",
  published: true,
  singleColor: false,
  instances: [
    {
      instanceNum: 0,
      _id: "59e42af7fbc43500121b96bb",
      lightsColor" : [ 0, 0, 0, 0, ... , 0 ] // # of entries = nogtype.numLights
    },
    {
      instanceNum: 1,
      _id: "59e42af7fbc43500121b96ba",
      lightsColor: [ 7, 7, ... , 7 ]
    },
    { ... }
  ],
  customColors: [
    "empty",
    "#a6ff00",
    "empty",
    "empty",
    "empty",
    "empty",
    "empty",
    "empty"
  ]
}
```

## redux state

