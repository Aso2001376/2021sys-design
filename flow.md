```uml
@startuml
start
:age=10;

if(age>=16)then(ture)
:「大人運賃です」と表示;
elseif(age>=6)then(ture)
:「小児運賃です」と表示;
else
:「無料です」と表示;
endif

end
@enduml

```
