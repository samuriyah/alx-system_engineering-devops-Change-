0. My name is Betty
  Script:   #!/bin/bash
    su betty

1. Who am I
Script:   #!/bin/bash
    whoami

2. Groups
Script:   #!/bin/bash
    groups

3. New owner
Script:   #!/bin/bash
    sudo chown betty hello

4. Empty!
Script:   #!/bin/bash
    touch hello

5. Execute
  Script:   #!/bin/bash
    chmod u+x hello

6. Multiple permissions
  Script:   #!/bin/bash
    chmod +114 hello

7. Everybody!
  Script:   #!/bin/bash
    chmod +111 hello

8. James Bond
  Script:   #!/bin/bash
    chmod 007 hello

9. John Doe
  Script:   #!/bin/bash
    chmod 753 hello

10. Look in the mirror
  Script:   #!/bin/bash
    chmod --reference olleh hello

11. Directories
  Script:   #!/bin/bash
    chmod a+x */

12. More directories
  Script:   #!/bin/bash
    mkdir –m 751 my_dir

13. Change group
  Script:   #!/bin/bash
    chgrp school hello

14. Owner and group
  Script:   #!/bin/bash
    chown vincent:staff *

15. Symbolic links
  Script:   #!/bin/bash
    chown –h vincent:staff  _hello

16. If only
  Script:   #!/bin/bash
    chown –from=guillaume betty hello

17. Star Wars
  Script:   #!/bin/bash
