# digikeyboard_ch-de
Digikeyboard for the Swiss German Keyboard Layout (QWERTZ)

Characters that don't work yet:

```bash
#'<>@\^`"~
```

Sample Code for testing

```bash
#include <DigiKeyboard.h>

void setup() {
  // don't need to set anything up to use DigiKeyboard
}


void loop() {
  DigiKeyboard.delay(2000);
  DigiKeyboard.sendKeyStroke(0);
  DigiKeyboard.delay(500);
  DigiKeyboard.println("abcdefghijklmnopqrstuvwxyz ABCDEFGHIJKLMNOPQRSTUVWXYZ 1234567890 !"#$%&'()*+,-./:;<=>?@[\]^_`{|}~");
  delay(10000);
}
```
