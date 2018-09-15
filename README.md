# Arduino snippets for VS Code

This extension for Visual Studio Code adds snippets for Arduino.  
Adds arduino snippets for both `*.ino` files and `cpp` language. So, if you didn't install [Microsoft's Arduino extension](https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.vscode-arduino), the snippets would still work.

![Use Extension](assets/gif/demo.gif)


## Usage

Type part of a snippet, press `enter`, and the snippet unfolds.

### Snippets

| Snippet              | Purpose                       |
| -------------------- | ------------------------------|
| `abs`                | [abs()](https://www.arduino.cc/reference/en/language/functions/math/abs/)                     |
| `analogRead`         | [analogRead](https://www.arduino.cc/reference/en/language/functions/analog-io/analogread/)                |
| `analogWrite`        | [analogWrite](https://www.arduino.cc/reference/en/language/functions/analog-io/analogwrite/)               |
| `arduino`            | [skelet]( )                    |
| `attachInterrupt`    | [attachInterrupt()](https://www.arduino.cc/reference/en/language/functions/external-interrupts/attachinterrupt/)         |
| `byte`               | [byte()](https://www.arduino.cc/reference/en/language/variables/conversion/bytecast/)                    |
| `char`               | [char()](https://www.arduino.cc/reference/en/language/variables/conversion/charcast/)                    |
| `constrain`          | [constrain()](https://www.arduino.cc/reference/en/language/functions/math/constrain/)               |
| `define`             | [Macro define]( )              |
| `delay`              | [delay()](https://www.arduino.cc/reference/en/language/functions/time/delay/)                   |
| `delayMicroseconds`  | [delayMicroseconds()](https://www.arduino.cc/reference/en/language/functions/time/delaymicroseconds/)       |
| `detachInterrupt`    | [detachInterrupt()](https://www.arduino.cc/reference/en/language/functions/external-interrupts/detachinterrupt/)         |
| `digitalRead`        | [digitalRead](https://www.arduino.cc/reference/en/language/functions/digital-io/digitalread/)               |
| `digitalWrite`       | [digitalWrite](https://www.arduino.cc/reference/en/language/functions/digital-io/digitalwrite/)              |
| `dowhile`            | [do-while](https://www.arduino.cc/reference/en/language/structure/control-structure/dowhile/)                  |
| `float`              | [float()](https://www.arduino.cc/reference/en/language/variables/conversion/floatcast/)                   |
| `for`                | [for](https://www.arduino.cc/reference/en/language/structure/control-structure/for/)                       |
| `if`                 | [if](https://www.arduino.cc/reference/en/language/structure/control-structure/if/)                        |
| `ifdef`              | [Macro ifdef]( )               |
| `ifndef`             | [Macro ifndef]( )              |
| `include`            | [include userlib]( )           |
| `include`            | [include syslib]( )            |
| `int`                | [int()](https://www.arduino.cc/reference/en/language/variables/conversion/intcast/)                     |
| `long`               | [long()](https://www.arduino.cc/reference/en/language/variables/conversion/longcast/)                    |
| `loop`               | [loop](https://www.arduino.cc/reference/en/language/structure/sketch/loop/)                      |
| `map`                | [map()](https://www.arduino.cc/reference/en/language/functions/math/map/)                     |
| `max`                | [max()](https://www.arduino.cc/reference/en/language/functions/math/max/)                     |
| `elif`               | [Macro elif]( )                |
| `micros`             | [micros()](https://www.arduino.cc/reference/en/language/functions/time/micros/)                  |
| `if`                 | [Macro if](https://www.arduino.cc/reference/en/language/structure/control-structure/if/)                  |
| `millis`             | [millis()](https://www.arduino.cc/reference/en/language/functions/time/millis/)                  |
| `min`                | [min()](https://www.arduino.cc/reference/en/language/functions/math/min/)                     |
| `noTone`             | [noTone()](https://www.arduino.cc/reference/en/language/functions/advanced-io/notone/)                  |
| `pinMode`            | [pinMode](https://www.arduino.cc/reference/en/language/functions/digital-io/pinmode/)                   |
| `pow`                | [pow()](https://www.arduino.cc/reference/en/language/functions/math/pow/)                     |
| `pulseIn`            | [pulseIn()](https://www.arduino.cc/reference/en/language/functions/advanced-io/pulsein/)                 |
| `random`             | [random()](https://www.arduino.cc/reference/en/language/functions/random-numbers/random/)                  |
| `randomSeed`         | [randomSeed()](https://www.arduino.cc/reference/en/language/functions/random-numbers/randomseed/)              |
| `savailable`         | [Serial.available()]( )        |
| `sbegin`             | [Serial.begin()]( )            |
| `send`               | [Serial.end()]( )              |
| `sevent`             | [serialEvent()]( )             |
| `sfind`              | [Serial.find()]( )             |
| `sfindUntil`         | [Serial.findUntil()]( )        |
| `sflush`             | [Serial.flush()]( )            |
| `spfloat`            | [Serial.parseFloat()]( )       |
| `spint`              | [Serial.parseInt()]( )         |
| `speek`              | [Serial.peek()]( )             |
| `sprint`             | [Serial.print()]( )            |
| `sprint`             | [Serial.println()]( )          |
| `sread`              | [Serial.read()]( )             |
| `sreadBytes`         | [Serial.readBytes()]( )        |
| `sreadBytesUntil`    | [Serial.readBytesUntil()]( )   |
| `stimeout`           | [Serial.setTimeout()]( )       |
| `swrite`             | [Serial.write()]( )            |
| `setup`              | [setup](https://www.arduino.cc/reference/en/language/structure/sketch/setup/)                     |
| `shiftIn`            | [shiftIn()](https://www.arduino.cc/reference/en/language/functions/advanced-io/shiftin/)                 |
| `shiftOut`           | [shiftOut()](https://www.arduino.cc/reference/en/language/functions/advanced-io/shiftout/)                |
| `sizeof`             | [sizeof()](https://www.arduino.cc/reference/en/language/variables/utilities/sizeof/)                  |
| `sqrt`               | [sqrt()](https://www.arduino.cc/reference/en/language/functions/math/sqrt/)                    |
| `switch`             | [switch](https://www.arduino.cc/reference/en/language/structure/control-structure/switchcase/)                    |
| `tone`               | [tone()](https://www.arduino.cc/reference/en/language/functions/advanced-io/tone/)                    |
| `undef`              | [Macro undef]( )               |
| `while`              | [while](https://www.arduino.cc/reference/en/language/structure/control-structure/while/)                     |
