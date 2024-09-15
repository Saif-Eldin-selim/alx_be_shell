#!/bin/bash
chmod u+x hello

touch 5-execute

echo '#!/bin/bash' > 5-execute
echo 'chmod u+x hello' >> 5-execute

chmod +x 5-execute


./5-execute
