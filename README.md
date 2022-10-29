a=gg.getRangesList("il2cpp.so")[1].start

gg.setValues({{address=a+0xb868bc,flags=4,value="~A MOV	 R0, #66, 8"}})

gg.setValues({{address=a+0xB868C0,flags=16,value="~A bx lr"}})

b=gg.getRangesList("il2cpp.so")[1].start

gg.setValues({{address=b+0xd8099c,flags=16,value="~A MOV	 R0, #1157627904"}})

gg.setValues({{address=b+0xD809A0,flags=16,value="~A bx lr"}})

c=gg.getRangesList("il2cpp.so")[1].start

gg.setValues({{address=c+0xd9deb8,flags=16,value="~A MOV R0, #0"}})

gg.setValues({{address=c+0xD9DEBC,flags=16,value="~A bx lr"}})

d=gg.getRangesList("il2cpp.so")[1].start

gg.setValues({{address=d+0xda0f10,flags=16,value="~A mov r0, #8"}})

gg.setValues({{address=d+0xDA0F14,flags=16,value="~A bx lr"}})

e=gg.getRangesList("il2cpp.so")[1].start

gg.setValues({{address=e+0x1c84a9c,flags=16,value="~A mov r0, #1"}})

gg.setValues({{address=e+0x1C84AA0,flags=16,value="~A bx lr"}})
