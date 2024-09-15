#!/bin/bash
whoami


touch 1-who_am_i

echo '#!/bin/bash' > 1-who_am_i
echo 'whoami' >> 1-who_am_i

chmod +x 1-who_am_i

./1-who_am_i
