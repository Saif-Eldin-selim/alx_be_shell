#!/bin/bash
chmod ug+x,o+r hello

touch 6-multiple_permissions

echo '#!/bin/bash' > 6-multiple_permissions
echo 'chmod ug+x,o+r hello' >> 6-multiple_permissions

chmod +x 6-multiple_permissions

./6-multiple_permissions
