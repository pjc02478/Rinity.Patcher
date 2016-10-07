# Rinity.Patcher
Rinity.Patcher
<br>
<br>
__Rini.csx__
```cs
int Def {get;set;}

int CalcDamage(int incomingDamage) {
  return incomingDamage - Def;
}
```

Attributes
----
* __Proxy__

roadmap
----
* [x] 정적 메소드 교체
* [ ] 런타임 메소드 교체
