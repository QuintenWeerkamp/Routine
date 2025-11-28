# Chapter 1 - Runnning 
```plantuml
@startuml
start
Group Preperation
:Check weather;
if (Is it dry?) then (no)
stop
Else (yes)
endif
:Change clothes;
:Put on watch;
:Connect earbuds;
:Play music;
:Search GPS;
:Check 3D-Print;
:Put on running shoes;
end group
Group Warm-up
:Go outside;
repeat
repeat while (GPS connected) is (no) not (yes)
:Start Warm-up;
End group
Group Running
:Start Running;
:Ran 1km\nCheck time;
:Ran 2km\nCheck time;
:Ran 10km;
:Stop running;
end group
Group End run
:Cool down;
:Go home;
:Rest;
:Take off shoes;
:Drink water;
:Check Print;
:Shower;
end group



Stop
@enduml
```