```uml
@startuml
start
:体力=10;

if(体力<=20)then(ture)
:「宿屋に泊まる」と表示;
elseif(体力>=20)then(ture)
:「頑張ってレベルを上げる」と表示;
else
:「無料です」と表示;
endif

end
@enduml

```
