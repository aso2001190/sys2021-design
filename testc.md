```uml
@startuml
start;
:weather;
if(weather = 0) then (sunny☀);
:快晴です;
elseif(weather = 1) then (cloudy☁);
:曇りです;
elseif(weather = 2) then (rainy☂);
:雨です;
else(????);
:不明です;
endif;
end;
```
