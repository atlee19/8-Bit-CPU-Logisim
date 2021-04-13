# 8-Bit-CPU-Logisim
8 bit cpu built in logisim.

## Instructions for loading test program:
Right click on RAM > Load Image > testprogram.obj

* Make sure to enable 'Load Data'

Test program translation
```
Machine code         Assembly
f118                 mov 24, r1
2600                 add r1, r2
0400                 inc r1 
a3fd                 add -3, r3
3700                 sub r1, r3
1c00                 dec r3
f00f                 mov 15, r0
e000                 halt (not included in our ISA)
```

### ⛔️ Broken Instructions
```
2600                 add r1, r2     Not producing correct 6 bit ALU opcode
0400                 inc r1         Not producing correct 6 bit ALU opcode
```

## Links
Link to control matrix sheet: https://docs.google.com/spreadsheets/d/1q5ler1lktvx4j2TuqqX3yOqUN5U9RWflokVJhNfCc8M/edit?usp=sharing

<br>
Link to project instructions: https://learn-us-east-1-prod-fleet01-xythos.content.blackboardcdn.com/blackboard.learn.xythos.prod/5a6a00cf15ab4/6005745?X-Blackboard-Expiration=1618185600000&X-Blackboard-Signature=ioQo5w2rVK3jZ9PA%2Fp1NrNCRDZP9DC5jlSmeqWg9xHQ%3D&X-Blackboard-Client-Id=914479&response-cache-control=private%2C%20max-age%3D21600&response-content-disposition=inline%3B%20filename%2A%3DUTF-8%27%27ALU_S2021%25282%2529.pdf&response-content-type=application%2Fpdf&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20210411T180000Z&X-Amz-SignedHeaders=host&X-Amz-Expires=21600&X-Amz-Credential=AKIAYDKQORRYTKBSBE4S%2F20210411%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=49c713a315a2ac065178210e8e96fad74710fa71860e6aa848e8bc486f2f5370 
