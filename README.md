# sheep_realms

## Config
### All
```
{
  "sprp_id": "SPR-NET-API-001";
  "sprp_version": "1.0.0";
  "name": "绵羊领域";
  "id": "sheep_realms";
  "uid": 1;
  "uuid": "a000-0000-0000-0001";
  "info": "绵羊领域工作室";
  "user-group-main": "admin";
  "user-group-add": ["authen","debuger"];
  "tag": [];
  "link": [
    {
      "name": "spr-bbs";
      "user": "2"
    };
    {
      "name": "mcbbs";
      "user": "2153967"
    }
  ];
  "display": false
}
```

### Request (Standard)
```
{
  "cmd": "request userinfo";
  "sprp_id": "SPR-NET-API-001";
  "sprp_version": "1.0.0";
  "uuid": "a000-0000-0000-0001";
  "request-type": "basic";
}
```

### Request (Logged-in user)
```
{
  "cmd": "request userinfo";
  "sprp_id": "SPR-NET-API-001";
  "sprp_version": "1.0.0";
  "uuid": "a000-0000-0000-0001";
  "request-from": "a000-0000-0000-0013";
  "request-type": "display";
  "request-list": []
}
```
