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
* __Proxy__ : 교체 스크립트에서 정의하지만, 바디를 스왑하지 않고 프록시 콜을 수행합니다.
* __Inject__ : 주입 대상 어셈블리에는 존재하지 않는 메소드를 삽입합니다.

roadmap
----
* [x] 정적 메소드 교체
* [ ] 런타임 메소드 교체
