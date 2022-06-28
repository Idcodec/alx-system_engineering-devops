0. #!/bin/bash
    alias ls="rm *"

1. #!/bin/bash
echo "hello" $USER

2.#!/bin/bash
export PATH="$PATH:/action"

3. #!/bin/bash
echo $PATH | tr -s ":" "\n" | wc -l

4. #!/bin/bash
printenv

5. #!/bin/bash
set

6. #!/bin/bash
BEST="School"

7.#!/bin/bash
export BEST='School'

8. #!/bin/bash
echo -e $((128 + TRUEKNOWLEDGE))

9. #!/bin/bash
echo $((POWER / DIVIDE))

10. #!/bin/bash
echo $((BREATH ** LOVE))

11. #!/bin/bash
echo $((2#$BINARY))

12. #!/bin/bash
printf "%s\n" {a..z}{a..z} | grep -v "oo"

13. #!/bin/bash
printf "%0.2f\n" $NUM

14. #!/bin/bash
printf '%x\n' $DECIMAL

15. #!/bin/bash
tr '[A-Za-z]' '[N-ZA-Mn-za-m]'

16. #!/bin/bash
paste - - | cut -f 1

17. #!/bin/bash
printf "%o\n" $((5#$(echo $WATER | tr 'water' '01234') + 5#$(echo $STIR | tr 'stir.' '01234'))) | tr '01234567' 'bestchol'
