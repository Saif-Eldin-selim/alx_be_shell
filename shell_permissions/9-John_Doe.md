#!/bin/bash
chmod 731 hello

touch 7-set_permissions
echo '#!/bin/bash' > 7-set_permissions
echo 'chmod 731 hello' >> 7-set_permissions
chmod +x 7-set_permissions
./7-set_permissions
