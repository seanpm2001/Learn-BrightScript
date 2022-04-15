
***

![/BrightScript_1.png](/BrightScript_1.png)

### Learning BrightScript

I am not too experienced with BrightScript at the moment. This document will go over my knowledge of the BrightScript language so far.

This document used version ? of the BrightScript programming language.

#### Comments in BrightScript

Comments in BrightScript are the same as comments in languages like VB.NET, etc.

```BrightScript
' This is a single line comment
' BrightScript does not support multi-line comments (as far as I know)
```

_/!\ This example has not been tested yet, and may not work_

#### Break keyword in BrightScript

BrightScript does NOT support the `break` keyword.

To this day, I am still not entirely sure what the `break` keyword does, but most languages support it.

_/!\ This example has not been tested yet, and may not work_

#### Hello World in BrightScript

A hello world program in BrightScript is a bit complicated It is not similar to any language I am currently familiar with.

```BrightScript
Function helloWorld(msgPort As Object, userVariables As Object, bsp as Object)
	print "Hello World"
End Function
```

_/!\ This example has not been tested yet, and may not work_

#### Functions in BrightScript

Functions work like so in BrightScript

```brightscript
function myFunction1(msgPort As Object, userVariables As Object, bsp as Object)
	print "My function has functioned"
End Function
```

I am not sure what the `msgPort As Object, userVariables As Object, bsp as Object` does, I don't have any way of testing these programs, and this is the piece I took with me.

_/!\ This example has not been tested yet, and may not work_

#### Booleans in BrightScript

Booleans are defined like so in BrightScript:

```brightscript
boolean isTrue = true;
boolean isFalse = false;
```

_/!\ This example has not been tested yet, and may not work_

#### Return a function in BrightScript

Returning a function in BrightScript is simple:

```brightscript
function myFunction2(msgPort As Object, userVariables As Object, bsp as Object)
	print "My function has functioned"
End Function
return myFunction2()
```

_/!\ This example has not been tested yet, and may not work_

#### Source

The majority of my BrightScript knowledge comes from self-experimentation, VB.NET syntax comparisons, and these reposories:

[BrightSign/BrightScript-Samples](https://github.com/brightsign/brightscript-samples/)

[BrightSign/BrightAuthor-Plugins](https://github.com/brightsign/BrightAuthor-Plugins/)

[BrigthSign/BrigtSign BLE-Commands](https://github.com/brightsign/brightsign-ble-commands/)

#### Other knowledge of BrightScript

1. BrightScript is not curly bracket and semicolon language

2. I began learning BrightScript with a new Roku TV I got for Christmas in 2020. Most of my knowledge comes from experimenting with Visual Basic DOT NET syntax, as they both have similar syntax

3. BrightScript is the language Roku uses for their TV monitors.

4. BrightScript uses the `.brs` file extension

5. BrightScript is a language recognized by GitHub

6. I don't know if BrightScript is an open source language or not

7. No other knowledge of BrightScript at the moment.

***

**File version:** `1 (2022, Thursday, April 14th at 10:00 pm PST)`

***
